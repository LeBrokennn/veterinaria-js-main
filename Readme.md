🐾 Veterinaria – Gestión de Citas en Node.js

Aplicación de línea de comandos construida con Node.js que permite registrar y listar citas veterinarias utilizando persistencia de datos en archivos JSON.

🚀 Tecnologías y Conceptos Utilizados

⚙️ Node.js ejecutado desde terminal

📁 File System (fs) para lectura/escritura de archivos

🧩 Módulos CommonJS (require / module.exports)

💾 Persistencia local en JSON

📝 Procesamiento de argumentos CLI con process.argv

📂 Estructura del Proyecto
veterinaria/
├─ index.js          # Punto de entrada CLI
├─ operaciones.js    # Lógica para registrar y leer citas
└─ citas.json        # Base de datos local

🧪 Comandos Disponibles
📌 Registrar una cita
node index.js registrar 3leches "1 año" gato blanco "tumor en el intestino"

📌 Leer todas las citas registradas
node index.js leer

🐶 Argumentos del Comando registrar
Argumento	Ejemplo	Descripción
1	registrar	Operación deseada
2	Benito	Nombre del animal
3	"2 años"	Edad del paciente
4	perro	Tipo de animal
5	blanco	Color
6	vomitos	Motivo / enfermedad
🗂️ Descripción de Archivos
Archivo	Rol
index.js	Captura argumentos y ejecuta funciones
operaciones.js	Contiene registrar() y leer() para manipular datos
citas.json	Almacena las citas de forma persistente
🔒 Validaciones Incluidas

❌ Bloquea registros incompletos

⚠️ Informa cuando la operación ingresada no existe

📤 Manejo básico de retroalimentación al usuario

✔️ Requerimientos del Desafío Cumplidos

 Ejecutar comandos con Node.js

 Utilizar process.argv

 Leer y escribir archivos JSON con fs

 Exportar e importar módulos

 Persistencia de datos sin base de datos

👩‍💻 Autor

Javiera Saavedra
Proyecto de aprendizaje inicial en JavaScript y Node.js 💛