# joycon2cpp

Me cloné este repo y le agregué soporte para
- Botones GL y GR
- Botones Screenshot y Home
- Manejo de errores por si se toca otro botón que no sea el pairing de bluetooth
- Mapeo de botones (cambiar la palanca por la cruceta, poner un botón en otro, etc)

---

# descarga y uso

Simplemente descarguen el archivo SwitchProController2.zip, abren el exe, y presionan el botón del joycon para el pairing. Y listo a jugar.

También pueden mapear botones a su gusto.

---

# mapeo de botones

Si quieren mapear botones y cambiarlos de posición editen el archivo de texto. Usa el esquema DS4 para el caso de mapeo del mando, y para asignarle teclas usa los VK

Aquí pueden encontrar las teclas para que asignen sus propias VK: https://learn.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes

Para intercambiar la cruceta con la palanca de movimiento pueden usar este:
"DPAD_LS" "STICKL" "DS4"

Pueden comentar cualquier linea con //, --, # y ese tipo de cosas. En el archivo vienen varios ejemplos.

Si quieren pueden personalizar por juego, solo deben agregar entre paréntesis el nombre del juego. Pueden agregar varios a una misma lista. Por ejempo:

["Hollow Knight Silksong.exe", "Cronos The New Dawn.exe"]
...

También pueden agregar la ruta completa para evitar ambigüedades, por ejemplo:

["K:\Games\Hollow Knight Silksong", "Cronos The New Dawn.exe"]
