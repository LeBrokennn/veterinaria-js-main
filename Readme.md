🐾 Veterinaria – Gestión de Citas en Node.js

Aplicación de línea de comandos desarrollada en Node.js que permite registrar y consultar citas veterinarias, aplicando lectura/escritura de archivos y uso de módulos.

🚀 Tecnologías y conceptos aplicados

Ejecución de scripts con Node.js

Manejo de archivos mediante File System (fs)

Lectura y escritura en JSON

Modularización con require y module.exports

Uso de argumentos por consola con process.argv

📁 Estructura del proyecto
veterinaria/
├─ index.js          // Punto de entrada
├─ operaciones.js    // Lógica de registro y lectura
└─ citas.json        // Base de datos local

📌 Funcionamiento
📍 Registrar una cita
```bash
node index.js registrar 3leches "1 año" gato blanco "tumor en el intestino"
```


Argumentos en orden:

Operación (registrar)

Nombre

Edad

Tipo de animal

Color

Enfermedad

📍 Leer todas las citas
```bash
node index.js leer
```


Devuelve en consola el contenido almacenado en citas.json.

🔒 Validaciones

Evita registrar citas con datos incompletos

Informa cuando se ingresa una operación no reconocida

📝 Archivos clave
operaciones.js

registrar(): Agrega una nueva cita al JSON

leer(): Imprime todas las citas guardadas

citas.json

Archivo persistente donde se almacenan las citas (inicia como [])

✔️ Requisitos cubiertos

 Uso de Node.js en terminal

 Módulo FS para lectura y escritura

 Argumentos CLI (process.argv)

 Importación y exportación de módulos

 Persistencia en JSON

 👩‍💻 Autor

Javiera Saavedra
Proyecto de aprendizaje inicial en JavaScript y Node.js.