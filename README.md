# Control TV — versiones

Este repositorio solo contiene las **versiones publicadas** de Control TV (los APK y sus notas), para que la
app pueda buscar actualizaciones sola. El código y la documentación están en un repositorio privado.

**Descargar la última versión:** https://github.com/SPN177/control-tv-releases/releases/latest/download/ControlTV.apk

Cada release incluye:
- un único APK; desde la 4.3 se llama siempre `ControlTV.apk`, para que el enlace de arriba (y el código QR
  de la app) lleve siempre a la versión más nueva;
- en las notas, la línea `SHA-256: <huella>` que la app comprueba antes de instalar.

La app solo instala una actualización si la huella coincide, es la misma app (`com.casa.controltv`), es una
versión más nueva y está firmada con la misma clave que la instalada (o con su clave nueva autorizada por
rotación de clave, desde la 4.3).

Google Play Protect puede avisar al instalar porque la app no viene de la Play Store; se instala con
"Instalar de todas formas".
