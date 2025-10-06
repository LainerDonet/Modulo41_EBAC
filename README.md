
# 🚀 Landing Page - MacBook Air M4  
Proyecto del **Módulo 39** del curso de Frontend en EBAC.  

Este proyecto consiste en la creación de una **Landing Page optimizada para SEO y conversión** con enfoque en la nueva **MacBook Air M4**.  
Incluye prácticas de **SEO On-Page**, optimización de **rendimiento web** y estrategias de **Call To Action (CTA)**.

---

## 📂 Estructura del proyecto
```

📦 proyecto-landing-macbook-air-m4
┣ 📜 index.html        # Página principal
┣ 📜 style.css         # Estilos CSS minificados
┣ 📜 script.js         # Scripts JS optimizados
┗ 📂 img               # Imágenes optimizadas (WebP, comprimidas)

````

---

## 🎯 Objetivos
- Crear una **Landing Page clara, atractiva y persuasiva**.  
- Optimizar **HTML, CSS y JS** aplicando técnicas de SEO y velocidad de carga.  
- Incluir un **encabezado jerárquico** con `<h1>, <h2>, <h3>` siguiendo buenas prácticas semánticas.  
- Incorporar **metadatos SEO** y **Open Graph** para mejorar la visibilidad en buscadores y redes sociales.  
- Diseñar y probar distintas versiones del **CTA** para maximizar la conversión.  
- Implementar **lazy loading** en imágenes y optimización de recursos.  

---

## 🔍 Optimización SEO

### SEO Básico
- Uso de etiquetas `<meta>` en el `<head>`:  
  ```html
  <meta name="description" content="Descubre la nueva MacBook Air M4: potencia, diseño y rendimiento en una laptop ultradelgada.">
  <meta name="keywords" content="MacBook Air M4, Apple, Laptop ligera, ultradelgada, rendimiento, diseño premium">
  <meta property="og:title" content="MacBook Air M4 - Landing Page">
  <meta property="og:description" content="Explora la potencia y diseño de la nueva MacBook Air M4. ¡Conoce más aquí!">
  <meta property="og:image" content="img/macbook-air-m4.jpg">
  <meta property="og:type" content="website">
````

* Títulos y encabezados organizados jerárquicamente (`<h1>`, `<h2>`, `<h3>`).
* Optimización de la etiqueta `<title>`.

### SEO Avanzado

* **Imágenes** con `alt` descriptivos:

  ```html
  <img src="img/macbook-air.webp" alt="MacBook Air M4 ultradelgada en color plata">
  ```
* **Enlaces internos y externos** con `rel="nofollow"`, `rel="noopener noreferrer"` según el caso.
* Contenido persuasivo orientado a beneficios:

  * En lugar de “Conoce más”, se usa “Aumenta tu productividad con la nueva MacBook Air M4”.

---

## 🎯 Call To Action (CTA)

* CTA principal optimizado:

  ```html
  <a href="#comprar" class="btn-cta">¡Compra ahora y descubre la diferencia!</a>
  ```
* Variantes propuestas para pruebas A/B:

  * Texto: **“Lleva tu MacBook hoy”** vs. **“Empieza tu nueva experiencia”**.
  * Color: **azul vs. verde**.
  * Posición: **arriba del fold vs. al final de la página**.

---

## ⚡ Optimización de Velocidad de Carga

* **CSS y JS minificados**.
* **Lazy Loading** aplicado a imágenes no críticas:

  ```html
  <img src="img/macbook-air-m4.webp" alt="Laptop Apple MacBook Air M4" loading="lazy">
  ```
* Imágenes optimizadas en formato **WebP**.
* Reducción del peso total de la página.

---

## 🖥️ Características de la Landing Page

* Diseño minimalista y responsivo.
* Secciones principales:

  * **Encabezado con logo y navegación sencilla**
  * **Hero principal con título, descripción y CTA optimizado**
  * **Beneficios o características destacadas**
  * **Imagen del producto optimizada para SEO**
  * **Botón de CTA atractivo y probado en distintas versiones**
* Interactividad básica en `script.js` (animaciones ligeras y scroll).

---

## ⚙️ Instalación y uso

1. Clona este repositorio:

   ```bash
   git clone https://github.com/LainerDonet/Modulo39_EBAC
   ```
2. Abre el archivo `index.html` en tu navegador.
3. Prueba la responsividad en distintos dispositivos.

---

## 📝 Notas

* Proyecto diseñado como **ejercicio académico** del curso de Frontend de EBAC.
* Textos y recursos gráficos simulados con fines educativos.

---

## 👨‍💻 Autor

Proyecto realizado por **Lainer F. Donet Vasconcellos** en el marco del curso de **Frontend - EBAC**.

