# Exportador

**Español** · Instaladores de Exportador, la app para Mac que pasa las fotos y videos del iPhone a una carpeta por cable, sin la app Fotos ni iCloud: los originales, tal cual, y verificados uno por uno.

**English** · Installers for Exportador, the Mac app that transfers photos and videos from your iPhone to a folder over a cable, without the Photos app or iCloud: the original files, as they are, each one verified.

## Descargar · Download

### [⬇ Exportador.dmg](https://github.com/hsvchcl/exportador-releases/releases/latest/download/Exportador.dmg)

- macOS 13.3 o superior · macOS 13.3 or later
- Apple Silicon e Intel · Apple Silicon and Intel
- Gratis · Free
- Firmada con Developer ID · Signed with Developer ID

### Instalar con un comando · Install with one command

En Terminal · In Terminal:

```sh
curl -fsSL https://exportador-beta.web.app/install.sh | sh
```

Descarga la última versión, comprueba que esté firmada por su desarrollador, la copia a Aplicaciones y la abre, sin avisos. · Downloads the latest version, checks it is signed by its developer, copies it to Applications and opens it, with no warnings.

### Si usas el DMG · If you use the DMG

Esta beta aún no está notarizada por Apple: la primera vez, macOS avisa que no pudo verificarla. Ábrela una vez y ve a *Ajustes del Sistema › Privacidad y seguridad › Abrir igualmente*, o en Terminal: · This beta is not yet notarized by Apple: the first time, macOS warns it couldn’t verify it. Open it once and go to *System Settings › Privacy & Security › Open Anyway*, or in Terminal:

```sh
xattr -dr com.apple.quarantine /Applications/Exportador.app
```

Versiones anteriores y notas de cada versión en [Releases](https://github.com/hsvchcl/exportador-releases/releases). · Previous versions and release notes in [Releases](https://github.com/hsvchcl/exportador-releases/releases).

## Más · More

- Sitio · Website: https://exportador-beta.web.app
- Apoyar el proyecto · Support the project: https://buymeacoffee.com/hansvergarw

Este repositorio solo contiene los instaladores. · This repository only holds the installers.
