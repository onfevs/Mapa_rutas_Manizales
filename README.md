# Mapa de rutas de transporte público en la ciudad de Manizales

Este es un mapa interactivo que muestra las rutas de transporte público en una ciudad de Manizales. Utiliza la API de OpenStreetMap para mostrar el mapa y la API de Datos Abiertos - Geoportal Alcaldía de Manizales  para obtener los datos de las rutas.

El código utiliza la API de geolocalización del navegador para obtener la ubicación del usuario y centrar el mapa en esa ubicación. Luego, se agrega una capa de OpenStreetMap al mapa.

A continuación, el código llama a la API de ArcGIS REST Services para obtener los datos de las rutas de transporte público y los convierte en capas de características de GeoJSON. Cada ruta se representa con una capa y se le asigna un color basado en su identificador único (FID).

Cuando el usuario hace clic en una ruta, el código resalta esa ruta cambiando su estilo y mostrando sus detalles en un cuadro emergente.

## Características

- Muestra las rutas de transporte público en un mapa interactivo.
- Permite al usuario hacer clic en una ruta para resaltarla y ver información detallada.
- Utiliza la geolocalización del usuario para centrar el mapa en su ubicación actual.

## Cómo usar

1. Abre el archivo `index.html` en un navegador web.
2. Se pedirá al usuario que permita el acceso a su ubicación. Si se concede el permiso, el mapa se centrará en su ubicación actual.
3. Las rutas se mostrarán en el mapa como líneas de diferentes colores. Haz clic en una ruta para resaltarla y ver información detallada.

## Tecnologías utilizadas

- Html
- Css
- Javascript
- Leaflet.js para crear y personalizar el mapa interactivo.
- OpenStreetMap para obtener la capa de mapa base.
- ArcGIS para obtener los datos de las rutas.
- Fetch API para obtener los datos de ArcGIS en formato GeoJSON.

## Créditos

Este mapa fue creado por [OnfeVS] como parte de un proyecto de [Personal]. La información de las rutas se obtuvo de la API de GEOSERVICIO (https://services6.arcgis.com/PtpS85InlUyG2Gqs/arcgis/rest/services/Rutas_Servicio_Publico/FeatureServer/0/query?outFields=*&where=1%3D1) y se procesó utilizando JavaScript. Los íconos utilizados en el footer son de [FonAwesome].

## Licencia

Este proyecto se encuentra bajo la Licencia MIT.```
