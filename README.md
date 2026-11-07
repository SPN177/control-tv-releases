# Control TV — versiones

Este repositorio solo contiene las **versiones publicadas** de Control TV (los APK y sus notas), para que la
app pueda buscar actualizaciones sola. El código y la documentación están en un repositorio privado.

Cada release incluye:
- un único `ControlTV-X.Y.apk`;
- en las notas, la línea `SHA-256: <huella>` que la app comprueba antes de instalar.

La app solo instala una actualización si la huella coincide, es la misma app (`com.casa.controltv`), es una
versión más nueva y está firmada con la misma clave que la instalada.
