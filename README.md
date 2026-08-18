<!-- PROMPT DE IA

Tu rol es programador nivel senior

Considera el siguiente codigo en markdown

# Programacion Web 2026-II

## Descripción
En este proyecto se subirán todos los ejercicios y tareas realizadas durante el periodo de quinto semestre de la materia de programación web de la carrera de Ingeniería en Desarrollo de Software. 

## Contenido
En el repositorio se encontraran diferentes ejercicios y actividades con relacion al desarrollo web, entre ellas:

- Ejercicios JavaScript
- Ejercicos HTML
- Ejercicios CSS
- Servidores
- Programación del lado del servidor

## Herramientas
- HTML
- CSS
- JavaScript

## Estado
Actualmente se encuentra en desarrollo.

## Contribuyente
- Emiliano Angulo Martínez

Revisa y agrega más contenido y ejemplos a este md para que cumpla con las buenas prácticas profesionales. Agrega negritas o italicas en caso de ser necesario. -->

💻 Programación Web 2026-II

Repositorio académico correspondiente a la materia de Programación Web, cursada durante el quinto semestre de la carrera de Ingeniería en Desarrollo de Software.

En este repositorio se almacenan los ejercicios, prácticas, actividades y proyectos desarrollados durante el periodo 2026-II, utilizando tecnologías fundamentales para el desarrollo web.

📚 Descripción

El objetivo de este repositorio es documentar y organizar el aprendizaje práctico obtenido durante la materia de Programación Web.

A lo largo del curso se desarrollarán diferentes actividades relacionadas con:

Desarrollo de páginas web.
Estructuración de documentos mediante HTML5.
Diseño y presentación mediante CSS3.
Programación del lado del cliente con JavaScript.
Desarrollo y configuración de servidores web.
Programación del lado del servidor.
Manejo de formularios y solicitudes HTTP.
Integración entre cliente y servidor.
Buenas prácticas de desarrollo y organización de proyectos.

Nota: Este repositorio tiene fines principalmente académicos y será actualizado conforme avance el periodo escolar.

🎯 Objetivos

Los principales objetivos del proyecto son:

Comprender los fundamentos del desarrollo web moderno.
Aplicar buenas prácticas de programación y organización de código.
Desarrollar páginas web utilizando HTML, CSS y JavaScript.
Comprender la comunicación entre el cliente y el servidor.
Implementar aplicaciones web sencillas utilizando programación del lado del servidor.
Mantener un repositorio organizado que permita consultar y revisar el progreso realizado durante el curso.
🛠️ Tecnologías y herramientas

Durante el desarrollo de las actividades se utilizarán principalmente las siguientes tecnologías:

Tecnología	Uso
HTML5	Estructura y semántica de las páginas web
CSS3	Diseño, estilos y presentación
JavaScript	Interactividad y lógica del lado del cliente
Node.js	Ejecución de JavaScript del lado del servidor
Git	Control de versiones
GitHub	Hospedaje y gestión del repositorio
Visual Studio Code	Editor de código

Las herramientas y tecnologías pueden ampliarse conforme avancen las actividades de la asignatura.

📂 Estructura del repositorio

La estructura puede organizarse de la siguiente manera:

Programacion-Web-2026-II/
│
├── HTML/
│   ├── ejercicio-01/
│   ├── ejercicio-02/
│   └── ...
│
├── CSS/
│   ├── ejercicio-01/
│   ├── ejercicio-02/
│   └── ...
│
├── JavaScript/
│   ├── ejercicio-01/
│   ├── ejercicio-02/
│   └── ...
│
├── Servidores/
│   ├── ejercicio-01/
│   └── ...
│
├── Servidor/
│   ├── ejercicio-01/
│   └── ...
│
├── Proyectos/
│   ├── proyecto-01/
│   └── ...
│
└── README.md


La estructura anterior es una propuesta de organización. Puede modificarse de acuerdo con los requerimientos de la materia.

🚀 Ejemplos
Ejemplo HTML

Una estructura HTML básica puede ser:

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi primera página</title>
</head>
<body>

    <h1>Hola, mundo</h1>
    <p>Este es un ejercicio de Programación Web.</p>

</body>
</html>

Ejemplo CSS
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #222;
}

h1 {
    color: #2563eb;
}

Ejemplo JavaScript
const mensaje = "Hola desde JavaScript";

console.log(mensaje);

Ejemplo de servidor con Node.js
const http = require("http");

const servidor = http.createServer((req, res) => {
    res.writeHead(200, {
        "Content-Type": "text/plain; charset=utf-8"
    });

    res.end("Servidor funcionando correctamente");
});

servidor.listen(3000, () => {
    console.log("Servidor ejecutándose en http://localhost:3000");
});

⚙️ Requisitos

Para trabajar con este repositorio se recomienda contar con:

Visual Studio Code o un editor de código equivalente.
Un navegador web actualizado, como Chrome, Firefox o Edge.
Git para clonar y administrar el repositorio.
Node.js, en caso de ejecutar ejercicios relacionados con servidores o JavaScript del lado del servidor.
📥 Instalación

Para obtener una copia local del repositorio:

git clone <URL_DEL_REPOSITORIO>


Posteriormente, acceder al directorio:

cd Programacion-Web-2026-II


Dependiendo de la actividad, puede ser necesario instalar dependencias adicionales o ejecutar un servidor local.

▶️ Ejecución

Los ejercicios de HTML y CSS pueden abrirse directamente desde el navegador.

Para los ejercicios que utilicen JavaScript del lado del servidor, por ejemplo con Node.js:

node app.js


Después, abrir en el navegador:

http://localhost:3000


La forma de ejecución puede variar dependiendo de cada ejercicio o proyecto.

🌿 Control de versiones

El proyecto utiliza Git para llevar un registro de los cambios realizados durante el desarrollo.

Ejemplo de flujo de trabajo:

git status

git add .

git commit -m "feat: agrega ejercicio de JavaScript"

git push

Convención de commits

Se recomienda utilizar mensajes de commit claros y descriptivos.

Algunos ejemplos:

feat: agrega ejercicio de formularios
fix: corrige validación de campos
style: mejora estilos de la página principal
docs: actualiza README
refactor: reorganiza código JavaScript


Esto facilita el seguimiento de los cambios y mantiene un historial de desarrollo más profesional.

📌 Buenas prácticas

Durante el desarrollo de las actividades se procurará seguir las siguientes prácticas:

Utilizar nombres de archivos y variables claros y descriptivos.
Mantener una estructura de carpetas organizada.
Evitar código duplicado cuando sea posible.
Utilizar HTML semántico.
Mantener separados HTML, CSS y JavaScript cuando la actividad lo permita.
Comentar únicamente el código que necesite explicación adicional.
Mantener una indentación consistente.
Evitar subir archivos innecesarios al repositorio.
Realizar commits pequeños y descriptivos.
Mantener actualizado este documento conforme evolucione el proyecto.
📝 Registro de actividades

El repositorio se actualizará progresivamente conforme se realicen nuevas actividades.

Periodo	Actividad	Estado
2026-II	Ejercicios HTML	🟡 En desarrollo
2026-II	Ejercicios CSS	🟡 En desarrollo
2026-II	Ejercicios JavaScript	🟡 En desarrollo
2026-II	Servidores	⚪ Pendiente
2026-II	Programación del lado del servidor	⚪ Pendiente
2026-II	Proyecto final	⚪ Pendiente
📈 Estado del proyecto

Estado actual: 🟡 En desarrollo

El repositorio se encuentra en construcción y será actualizado conforme avance el periodo académico.

Las actividades pueden encontrarse en diferentes estados:

🟢 Completado: actividad terminada.
🟡 En desarrollo: actividad actualmente en proceso.
🔵 En revisión: actividad terminada, pendiente de revisión o ajustes.
⚪ Pendiente: actividad aún no realizada.
🤝 Contribución

Este es un repositorio de carácter académico y personal.

Las actividades son desarrolladas principalmente por el autor del repositorio. En caso de realizarse colaboraciones, se procurará mantener una correcta organización mediante ramas y mensajes de commit descriptivos.

👨‍💻 Contribuyente

Emiliano Angulo Martínez

Estudiante de Ingeniería en Desarrollo de Software.

Quinto semestre — Programación Web 2026-II

📄 Licencia

Este repositorio se encuentra destinado principalmente a fines educativos y académicos.

El uso, modificación o distribución del contenido deberá respetar las condiciones establecidas por el autor y las políticas académicas correspondientes.

⭐ Notas finales

Este repositorio representa el progreso y aprendizaje obtenido durante la materia de Programación Web 2026-II.

El contenido será actualizado de manera progresiva para incorporar nuevos ejercicios, prácticas, proyectos y conocimientos adquiridos durante el curso.

"El código no solo debe funcionar; también debe ser comprensible, mantenible y fácil de evolucionar."
