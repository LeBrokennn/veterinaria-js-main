¡Lo tengo Javiera!
El problema es que estás **pegándolo sin saltos**, así que aquí te lo dejo **ULTRA PLANO**, con **saltos forzados línea a línea**, sin tablas, sin listas con Markdown especial, para que NO se rompa cuando pegues 👇
(Copa, pega y te quedará tal cual)

---

🐾 Veterinaria – Gestión de Citas en Node.js
Aplicación de línea de comandos construida con Node.js que permite registrar y listar citas veterinarias utilizando persistencia de datos en archivos JSON.

---

## 🚀 Tecnologías y Conceptos Utilizados

* Node.js ejecutado desde terminal
* File System (fs) para lectura/escritura de archivos
* Módulos CommonJS (require / module.exports)
* Persistencia local en JSON
* Procesamiento de argumentos CLI con process.argv

---

## 📂 Estructura del Proyecto

veterinaria/
├─ index.js (Punto de entrada CLI)
├─ operaciones.js (Lógica para registrar y leer citas)
└─ citas.json (Base de datos local)

---

## 🧪 Comandos Disponibles

Registrar una cita:
node index.js registrar 3leches "1 año" gato blanco "tumor en el intestino"

Leer todas las citas:
node index.js leer

---

## 🐶 Argumentos del Comando "registrar"

1. Operación: registrar
2. Nombre del animal
3. Edad
4. Tipo de animal
5. Color
6. Enfermedad o motivo

---

## 🗂️ Descripción de Archivos

index.js → Captura argumentos y ejecuta funciones
operaciones.js → Contiene registrar() y leer()
citas.json → Almacena las citas de forma persistente (inicia como [])

---

## 🔒 Validaciones Incluidas

* Bloquea registros incompletos
* Informa cuando la operación ingresada no existe

---

## ✔️ Requisitos del Desafío

Uso de Node.js en terminal
Argumentos con process.argv
Lectura/escritura con File System
Importar y exportar módulos
Persistencia en JSON

---

## 👩‍💻 Autor

Javiera Saavedra
Proyecto desarrollado en el proceso de aprendizaje de JavaScript y Node.js

---

✨ Si quieres versión SIN emojis, versión con instrucciones de instalación o con imágenes, me dices y te la dejo lista 💪
