# Kameron Sushi — Descargas

Repositorio público destinado exclusivamente a distribuir versiones instalables del sistema
Kameron Sushi. No contiene el código fuente, credenciales ni datos del restaurante.

## Aplicación de escritorio

La versión piloto actual es **0.9.1** para Windows 10/11 de 64 bits.

1. Abre la sección [Releases](https://github.com/NicolasContrerasRios/KameronSushi-Releases/releases).
2. Descarga `KameronSushi-Escritorio-0.9.1-win-x64.zip`.
3. Extrae el ZIP completo.
4. Ejecuta `Instalar-KameronSushi.cmd`.

El instalador incluye el runtime de .NET y no requiere Visual Studio. La aplicación necesita
una cuenta autorizada del personal para acceder a Caja, Cocina o Administración.

## Seguridad

- No publiques contraseñas, tokens, archivos `.jks`, configuraciones privadas ni respaldos.
- Los instaladores deben publicarse como archivos de una Release, no como archivos del repositorio.
- Cada versión debe incluir su hash SHA-256 para verificar la integridad de la descarga.

## Canal de actualización

`latest.json` es el manifiesto estable que consultará el actualizador de la aplicación. Se debe
modificar únicamente después de publicar y comprobar una Release nueva.
