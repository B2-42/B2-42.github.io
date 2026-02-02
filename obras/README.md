# Carpeta /obras

Añade aquí un archivo JSON por cada obra que quieras mostrar. El nombre del archivo debe ser el id que usarás en el parámetro ?id=.

Formato sugerido (obra-ejemplo.json):

{
  "id": "obra-ejemplo",
  "title": "Título de la obra",
  "author": "Autor",
  "year": "2026",
  "technique": "Técnica",
  "description": "Descripción larga (puede contener saltos de línea).",
  "rights": "© Autor"
}

Cómo crear un QR para una obra (ejemplo):
https://api.qrserver.com/v1/create-qr-code/?size=300x300&data=https://b2-42.github.io/obra.html?id=obra-ejemplo
