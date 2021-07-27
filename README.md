# Aprendiendo HTML 5
Codigo de prueba y ejercicios que escribi mientras aprendia HTML 5.

Estos son los temas de HTML que aprendi:

## 1. Sintaxis Básica:
* ```<DOCTYPE html>```
* ```<html>```
* ```<head>```
* ```<meta>```
* ```<title>```
* ```<body>```

## 2. Semantica de una Sección: ```<section>```
* Articulo: ```<article>```
* Encabezado: ```<header>```
* Titulos y Subtitulos: ```<h1> - <h6>```
* Párrafos: ```<p>```
* Abreviatura o Sigla de una Palabra o Frase: ```<abbr>```
* Mostrar Texto (Preformateado) tal cual como está Escrito en el HTML: ```<pre>```
* Escribir Código Fuente en la Página Web: ```<code>```
* Cita Larga```<blockquote>```, Cita Corta ```<q>``` y Autor o Fuente de la Cita ```<cite>```
* Contenido Principal: ```<main>```
* Contenido Lateral (Secundario): ```<aside>```
* Información Personal y de Contacto: ```<addres>```
* Pie de Página: ```<footer>```

## 3. Dar formato al Texto - Elementos de Linea:
* Emphasis: ```<em>```
* Mas Emphasis: ```<strong>```
* Menos Emphasis que el Texto Normal: ```<small>```
* Línea Horizontal ── Divisora de Contenido: ```<hr>```
* Forzar un salto de línea: ```<br>```
* Salto de línea si Hiciera Falta: ```<wbr>```
* Fecha y Hora: ```<time>```
* Cursiva (Italic): ```<i>```
* Negrita (Bold): ```<b>```
* Subrayar (Underline): ```<u>```
* Resaltar: ```<mark>```
* Superíndice ```<sup>``` y Subíndice ```<sub>```

## 4. Algunos Atributos Globales:
* Ver mensaje al pasar el cursor por una etiqueta (Tooltip): ```title```
* Asignar un valor a una etiqueta: ```data-*```
* Arrastrar Elementos: ```draggable```
* Contenido Editable: ```contenteditable```
* Ocultar Contenido: ```hidden``` ; ```<input type="hidden">``` y ```<input hidden>```
*  Especificar Ruta o Pagina Web de Donde está el Contenido Embebido, Control Interactivo o Código de JS: ```src="/ruta ó link"```

## 5. Enlaces
* Ruta Absoluta y Relativa
* Redirigirse a otra Página Web: ```<a>```
* Atributos de los Enlaces
  * Abrir Recurso en otra Pestaña: ```target=""```
  * Enlace de Descarga: ```download```
* Barra de Navegación: ```<nav>```
* Menú: ```<menu>```  

## 6. Listas
* Etiquetas de las Listas
  * Ítem: ```<li>```
  * Lista con Viñetas (Desordenada): ```<ul>```
  * Lista Enumerada (Ordenada):  ```<ol>```
  * Lista de Definición (Sin Viñetas ni Enumeración):  ```<dl>``` ; ```<dt>``` y ```<dd>```
* Listas Anidadas
  * Forma Correcta de Anidar Listas
  * Forma Incorrecta de Anidar Listas
  * Lista Enumerada (Ordenada - ```<ol>```) Dentro de Lista con Viñetas (Desordenada - ```<ul>```)
* Atributos de las Listas 
  * Cambiar Estilo de Enumeración (```<ol>```) y de Viñeta (```<ul>```): ```type```
  * Empezar a enumerar (```<ol>```) desde cualquier número: ```start```

## 7. Tabla: ```<table>```
* Estructura Básica: ```<table>``` (Contenedor de Tabla); ```<tr>``` (Fila ↔) y ```<td>``` (Casilla □ / Columna ↨)
* Estructura Completa
  * Título Principal de la table: ```<caption>```
  * Encabezado ```<thead>``` y Titulo de las Columnas ```<th>``` de la ```<table>```
  * Cuerpo (Contenido) de la ```<table>```
  * Pie de table ```<tfoot>``` y Ejemplo de ```<table>``` con Estructura Completa
* Atributos de las ```<table>```
  * Hacer que una casilla □ ocupe más de una…
    * Fila ↔: rowspan="#"
    * Columna ↨: colspan="#"
* Seleccionar Columnas ↨: ```<colgroup>``` ; ```<col>``` y ```span="#"```

## 8. Formulario: ```<form>``` 
### 8.1 Enviar Datos del ```<form>``` al Servidor (Procesar Información de una Ruta): 
  * Operaciones CRUD y Métodos HTTP
    * GET (Leer): ```<form action="/ruta" method="get">```
    * 7.1.3 POST (Guardar): ```<form action="/ruta" method="post">```
      * Formato de Datos del Formulario: ```enctype=""``` y ```formenctype=""```

### 8.2 Descripción del Campo: ```<label>```
* Asociar ```<input>``` y ```<label>```

### 8.3 Atributos de los ```<form>```
  * Pista en Campo: ```placeholder="#"```
  * Campo Obligatorio: ```required```
  * Campo de Solo Lectura: ```readonly```
  * Desactivar Campo: ```disabled```
  * Valor Mínimo y Máximo de un Campo: ```min="#"``` y ```max="#"```
  * Número Mínimo y Máximo de Caracteres de un Campo: ```minlength="#"``` y ```maxlength="#"```
  * Situar Cursor por Defecto en un Campo (Enfoque Automático): ```autofocus```

### 8.4 Controles Interactivos ```<input>``` y Etiquetas para ```<form>```
  * Sintaxis General de ```<input>```
  * Cuadro Agrupador de Controles: ```<fieldset>``` y ```<legend>```
* Cuadro de Texto en una Sola Línea: ```<input type="text">```
   * Buscar: ```<input type="search">```
   * Teléfono: ```<input type="tel">```
   * Correo Electrónico: ```<input type="email">```
   * Contraseña: ```<input type="password">```
   * URL: ```<input type="url">```
   * Número: ```<input type="number">```
* Cuadro de Texto en Múltiples Líneas: ```<textarea>```
* Cuadro de Texto con Lista Desplegable (ComboBox): ```<datalist>``` y ```<input type="list">```
* Resultado de Eventos o Hacer Cálculos con ```<input>```: ```<output>```

### 8.5 Botón
* Diferencia Entre ```<input type="button">```, ```<input type="submit">``` y ```<button>```      
* Limpiar Campos: ```<input type="reset">```
*  Importar Archivos (Contenido Embebido, Incrustado o Externo):  ```<input type="file">```
* Insertar Imagen Dentro de un Botón: ```<input type="image">```

### 8.6 Calendario
* Fecha y Hora: ```<input type="datetime-local">```
* Fecha: ```<input type="date">```
* Hora: ```<input type="time">```
* Mes y Año: ```<input type="month">```
* Número de Semana del Año: ```<input type="week">```

### 8.7 ```<input>``` Seleccionables:
* Selección Única: ```<input type="radio">```
* Selección Múltiple: ```<input type="checkbox">```
* Cuadro de Lista Desplegable (ListBox): ```<select>``` y ```<option>```
  * ListBox con Selección Única: ```<select>```
  * ListBox con Selección Múltiple: ```<select multiple>```
  * Categorizar ListBox: ```<optgroup>```
* Cuadro de Texto o Viñeta Desplegable (Leer más) (Widget de Divulgación o Expansor): ```<details>``` y ```<summary>```

### 8.8 Barra:
* Barra de Rango Numérico Modificable: ```<input type="range">```
* Barra de Rango Numérico Inmodificable: ```<meter>```
* Barra de Progreso “Cargando…” (ProgressBar): ```<progress>```
* Color: ```<input type="color">```

## 9. Contenido Embebido o Incrustado (Externo):
* Insertar Imágenes y Media Queries CSS en HTML para Imágenes Responsive: ```srcset=""```
  * Tipos de Imágenes en Páginas Web
    * Gráficos Vectoriales Escalables: Etiqueta ```<svg>``` y formatos .svg y .svgz
    * Mapa de Bits (Bitmaps): .jpg, jpeg, png, gif y .webp
  * Forma 1 de Insertar Imagen: ```<img>```  
  * Forma 2 de Insertar Imagen: ```<picture>``` ; ```<source>``` y ```<img>``` 
  * Imagen con Enlaces (Mapa de Imagen): ```<map>```; ```<area>``` y ```<img>```
* Insertar Audio: ```<audio>```
* Insertar Video: ```<video>```
* Atributos de ```<audio>``` y ```<video>```
    * Barra de Reproducción: ```controls```
    * Silenciar ```<audio>``` y ```<video>```: ```muted```
    * Reproducción Automática al Cargar la Pagina Web: ```autoplay```
    * Volver a Reproducir Automáticamente al Terminar el ```<audio>``` o ```<video>```: ```loop```
* Insertar Contenido de una Página Web Externa (Inline Frame, Marco en Línea): ```<iframe>```
* Cargar ```<img>``` y ```<iframe>``` Conforme el Usuario se Desplaza en la Página Web (Lazy Loading, Carga Lenta o Diferida en HTML 5): ```loading="lazy"``` y ```loading="eager"```
* Lista de Formatos con Contenido Embebido para la Compatibilidad del Navegador: ```<source>```
* Descripción o Titulo ```<figcaption>``` del Contenido ```<figure>```

## 10. Atributos de Accesibilidad (ARIA):
* Seleccionar Partes de la Pagina Web con la Tecla Tabulador: ```tabindex="#"```
* Lector de Pantalla para Pagina Web: Screen Reader (ChromeVox Classic Extension)
*  Definir que Dice el Lector de Pantalla: ```aria-label=""```
* Decir al Navegador en Cual Etiqueta está Situado el Usuario (WAI-ARIA): ```role=""```

## 11. Lista de Caracteres Especiales ASCII en HTML 5

## 12. Lista de Etiquetas Obsoletas con HTML 5

## 13. Conectar HTML con CSS (```<link>``` y ```<style>```) y JS (```<script>```):
* Llamar Etiquetas HTML desde CSS y JS: ```id``` y ```class```
* Diferencia entre ```<div>``` y ```<span>```
  * Divisor de Contenido en Bloque: ```<div>```
  * Divisor de Contenido en Línea: ```<span>``` 
## 14. Ejercicios de HTML 5

[link ejercicios HTML 5](http://desarrolloweb.dlsi.ua.es/libros/html-css/ejercicios)
