# README.md

## ¿Qué es un lenguaje de marcas?

Un lenguaje de marcas es un sistema de codificación que utiliza etiquetas (o "marcas") para definir la estructura y el contenido de un documento. Estas etiquetas permiten organizar y presentar información de manera que pueda ser procesada por diferentes aplicaciones.

## Características generales de los lenguajes de marcas

- **Estructuración de datos**: Facilitan la organización de datos jerárquicos.
- **Legibilidad**: Se diseñan para ser legibles tanto para máquinas como para humanos.
- **Flexibilidad**: Permiten la creación de documentos complejos y personalizados.
- **Interoperabilidad**: Facilitan la comunicación entre diferentes sistemas y plataformas.

## Clasificación de los lenguajes de marcas

Los lenguajes de marcas se pueden clasificar en varias categorías, entre las que se incluyen:

1. **Lenguajes de marcas de presentación**: Como HTML, se utilizan para presentar información visualmente en navegadores web.
2. **Lenguajes de marcas de datos**: Como XML y JSON, se utilizan para almacenar y transportar datos.
3. **Lenguajes de marcas para aplicaciones específicas**: Como iCalendar y vCard, se utilizan para aplicaciones específicas como calendarios y tarjetas de contacto.

### Lenguajes de marcas más relevantes

- **HTML (HyperText Markup Language)**
- **XML (eXtensible Markup Language)**
- **JSON (JavaScript Object Notation)**
- **iCalendar**
- **vCard**
- **KML (Keyhole Markup Language)**
- **RSS (Really Simple Syndication)**

## Ámbitos de aplicación de los lenguajes de marcas

- **Desarrollo web**: HTML para crear páginas web.
- **Intercambio de datos**: XML y JSON para el intercambio de datos entre sistemas.
- **Gestión de calendarios**: iCalendar para el intercambio de eventos.
- **Contactos digitales**: vCard para compartir información de contacto.
- **Geolocalización**: KML para representar datos geoespaciales.
- **Syndication de contenidos**: RSS para compartir actualizaciones de contenido.

## Ejemplos de código

HTML

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Ejemplo de HTML</title>
</head>
<body>
    <h1>Hola, mundo!</h1>
    <p>Este es un ejemplo básico de un documento HTML.</p>
</body>
</html>
Este código define la estructura básica de una página web.

ICALENDAR


BEGIN:VCALENDAR
VERSION:2.0
CALSCALE:GREGORIAN
BEGIN:VEVENT
UID:123456@example.com
DTSTAMP:20231002T090000Z
DTSTART:20231005T120000Z
SUMMARY:Reunión de equipo
END:VEVENT
END:VCALENDAR
Resumen: Este es un archivo en formato iCalendar
VCard

BEGIN:VCARD
VERSION:3.0
FN:Juan Pérez
ORG:Empresa Ejemplo
TEL;TYPE=CELL:+1234567890
EMAIL:juan.perez@example.com
END:VCARD
Resumen: Este fragmento representa una tarjeta de contacto en formato vCard.

KML

<?xml version="1.0" encoding="UTF-8"?>
<kml xmlns="http://www.opengis.net/kml/2.2">
  <Placemark>
    <name>Ejemplo de KML</name>
    <Point>
      <coordinates>-122.0822035425683,37.42228990140251,0</coordinates>
    </Point>
  </Placemark>
</kml>
Resumen: Este código KML define un punto en un mapa.
RSS

<rss version="2.0">
  <channel>
    <title>Ejemplo de RSS</title>
    <link>http://www.ejemplo.com</link>
    <description>Este es un ejemplo de un feed RSS</description>
    <item>
      <title>Primer artículo</title>
      <link>http://www.ejemplo.com/articulo1</link>
      <description>Descripción del primer artículo.</description>
    </item>
  </channel>
</rss>
Resumen: Este código representa un feed RSS

CSS


Puedes modificar el contenido según sea necesario.


