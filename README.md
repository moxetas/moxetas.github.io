# moxetas.github.io

Portada de las apps de Moxetas y archivo de verificación del dominio para las apps Android de Google Play:
[`.well-known/assetlinks.json`](.well-known/assetlinks.json) (Digital Asset Links). Sin él, las apps se abrirían con la barra del navegador.

Cuando Google Play firme las apps con su propia clave (Play App Signing), hay que añadir aquí la huella SHA-256 que da Play Console
(*Prueba y lanza → Configuración → Integridad de la app → Firma de apps*), junto a la de la clave de subida.

`.nojekyll` hace que GitHub Pages publique la carpeta `.well-known`.
