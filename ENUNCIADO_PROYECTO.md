# 📝 Enunciado del Ejercicio Práctico 2 (HTML - Hasta Imágenes)
## Tema: "Sitio Web de Nuestro Colegio" (6 Páginas HTML Conectadas)

**Instrucciones:**
Tomando como base la práctica realizada en clase (`E:\COLEGIO\5TO\HTML`), crea dentro de tu carpeta `practico2` un sitio web sobre **nuestro Colegio** formado por **6 archivos HTML independientes** y una carpeta llamada `imagen` para guardar las fotos.

---

### 📁 Archivos que debes crear en tu carpeta:

1. **`index.html` (Página Principal del Colegio):**
   * Título centrado con `<h1> <center> ... </center> </h1>` y línea `<hr>`.
   * Párrafo `<p>` de bienvenida usando negrita `<b>` y cursiva `<i>`.
   * Texto con `<pre>` y `<tt>`.
   * Una **lista desordenada anidada** (`<ul>` y `<li>`) con los niveles y cursos del colegio.
   * Una **lista ordenada** (`<ol>` y `<li>`) con los estudiantes destacados del curso.
   * Una **lista de definiciones** (`<dl>`, `<dt>`, `<dd>`) con 3 palabras del colegio.
   * Imagen del curso (`<img src="curso.jpeg" width="350" height="230">`).
   * **Menú de enlaces (`<a href="...">`)** separados con `<br>` para ir a las otras 5 páginas.

2. **`primaria.html` (Página de Nivel Primaria):**
   * Título centrado con `<h1> <center>`, párrafo con `<b>` e `<i>`.
   * Lista ordenada `<ol>` con los 6 grados de primaria y lista desordenada `<ul>` con los útiles escolares.
   * Imagen de las aulas (`<img src="imagen/aulas.jpg" width="320" height="220" align="middle">`) y enlaces para volver a `index.html` y a las demás páginas.

3. **`secundaria.html` (Página de Nivel Secundaria):**
   * Título centrado con `<h1> <center>`.
   * Horario de clases de 5to de Secundaria usando la etiqueta `<pre>`.
   * Lista `<ul>` de compañeros de curso y dos imágenes (`curso.jpeg` con `align="right"` e `imagen/laboratorio.jpg`).
   * Enlaces hacia las demás páginas.

4. **`materias.html` (Página de Materias y Laboratorios):**
   * Título centrado, párrafo aplicando subíndice `<sub>` ($\text{H}_2\text{O}$) y superíndice `<sup>` ($X^2$), y una cita con `<blockquote>`.
   * Lista de definiciones `<dl>` explicando las materias del colegio.
   * Dos enlaces externos (`<a href="https://...">`) a páginas educativas y el gif animado `imagen/tractor.gif`.
   * Enlaces de navegación hacia las demás páginas.

5. **`clubes.html` (Página de Clubes y Deportes):**
   * Título centrado, lista anidada `<ul>` de deportes (Fútsal, Basquetbol, Voleibol) y lista ordenada `<ol>` de ganadores del campeonato.
   * Imagen de la cancha (`<img src="imagen/deportes.jpg" width="320" height="220">`) y enlaces a las demás páginas.

6. **`galeria.html` (Galería de Fotos del Colegio):**
   * Tres imágenes probando las 3 alineaciones vistas en clase: `align="top"`, `align="middle"` y `align="bottom"`.
   * Una **imagen que funcione como enlace** para regresar al inicio (`<a href="index.html"><img src="imagen/colegio.jpg" width="320" height="220" border="0"></a>`).
   * Enlaces de texto hacia todas las páginas del proyecto.
