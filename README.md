# Pollaland — modpack (Minecraft 1.20.1 Forge)

Modpack de Kaleth con actualización automática. Cada vez que abres el juego, se descarga solo lo que cambió.

---

## Para jugar (amigos)

1. **Instala Prism Launcher**: https://prismlauncher.org/download
   Ábrelo e inicia sesión con tu cuenta de Minecraft (Microsoft).
2. **Descarga** el archivo `Pollaland-cliente.zip` que te pasó Kaleth. **No lo descomprimas.**
3. En Prism: **Agregar instancia** → **Importar** → elige el zip → **Aceptar**.
4. Selecciona la instancia **Pollaland** y dale a **Iniciar**.

**La primera vez tarda bastante** (puede ser 10–20 minutos): descarga unos 400 mods y luego Minecraft tarda varios minutos en cargar. Es normal, no lo cierres. Las siguientes veces es mucho más rápido.

Si sale una ventanita de "packwiz-installer", déjala trabajar: es la que descarga y actualiza el pack.

### Cambiar la memoria RAM

El pack viene con **8 GB** (8192 MB). Para cambiarlo:
clic derecho en la instancia → **Editar** → **Ajustes** → **Java** → marca **Memoria** → cambia **Asignación máxima de memoria**.

- PC con 16 GB de RAM: deja 8192 MB.
- PC con 32 GB: puedes subir a 10240–12288 MB.
- PC con 8 GB: no alcanza bien para este pack.

### Tus ajustes no se pierden

Las actualizaciones **no** pisan tus controles, opciones de video, el shader que elegiste, tu lista de servidores ni la configuración del minimapa. Sí se actualizan los mods y las configuraciones del pack.

---

## Para Kaleth (mantener el pack)

Lo más fácil: **pídeselo a Claude** ("agrega el mod X", "quita el mod Y", "actualiza todo"). Si lo quieres hacer tú, necesitas [packwiz](https://packwiz.infra.link/installation/) y abrir una terminal dentro de la carpeta del repo.

### Agregar un mod

```
packwiz modrinth add <nombre-o-enlace-de-modrinth>
packwiz curseforge add <nombre-o-enlace-de-curseforge>
```

Después abre `mods/<mod>.pw.toml` y revisa la línea `side`:
`"both"` (cliente y servidor), `"client"` (solo jugadores) o `"server"` (solo servidor).
La lista con el motivo de cada mod está en `clasificacion.md`.

**Mod propio (un .jar tuyo):** cópialo en `archivos/mods/` y pídele a Claude que cree su `.pw.toml`, o copia uno existente (por ejemplo `mods/pollacoins.pw.toml`) y cambia el nombre, el archivo, el enlace y el `hash` (`sha256sum archivo.jar`). GitHub no acepta archivos de más de 100 MB.

### Actualizar o quitar mods

```
packwiz update <mod>        # un mod
packwiz update --all        # todos
packwiz remove <mod>
```

### Cambiar configuraciones

Edita los archivos en `config/` (o copia los de tu instancia encima). Luego:

```
packwiz refresh
```

Cuando cambies un `.toml` de mods o configs a mano, **siempre** corre `packwiz refresh` antes de subir.

### Subir los cambios

```
git add -A
git commit -m "Describe el cambio"
git push
```

Los amigos reciben el cambio la próxima vez que abran el juego.

### Actualizar el servidor

- **Opción A (recomendada si el host deja poner un comando de inicio):** el servidor se actualiza solo al arrancar con
  `java -jar packwiz-installer-bootstrap.jar -g -s server https://raw.githubusercontent.com/Kaleeethh/pollaland-modpack/main/pack.toml`
  (detalles en el `LEEME.txt` del zip del servidor).
- **Opción B:** pide a Claude un `Pollaland-servidor.zip` nuevo y súbelo al host (reemplaza `mods/`, `config/` y `defaultconfigs/`; **no borres la carpeta `world`**).

Los mods de cliente y servidor tienen que coincidir: cuando agregues o actualices un mod `both`, actualiza también el servidor.

### Comandos útiles del servidor (admins)

**Pregenerar el mundo con Chunky** (menos lag cuando exploran):

```
/chunky center 0 0
/chunky radius 5000
/chunky start
/chunky pause      (pausar)
/chunky continue   (seguir)
```

Hazlo cuando no haya nadie jugando; tarda horas y usa bastante CPU.

**Copias de seguridad (Simple Backups):** se hace una copia **cada 4 horas, solo si hubo jugadores conectados**, comprimida, en la carpeta `backups/` del servidor. Se guardan las **6 más recientes** (ocupan espacio del disco del host; cada copia pesa más o menos lo que pesa el mundo). Para hacer una a mano: `/simplebackups backup start`.

**Restaurar una copia:**
1. Apaga el servidor.
2. Renombra la carpeta `world` a `world_viejo` (por si acaso).
3. Descomprime el zip de `backups/` que quieras: adentro está la carpeta del mundo. Déjala como `world`.
4. Enciende el servidor. Si todo está bien, borra `world_viejo`.
