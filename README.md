# 📚 Leyenda.com - Visor de Manhwas

**Leyenda.com** es una página web simple y funcional para explorar manhwas y ver sus capítulos. Incluye buscador, listado dinámico y opción de mostrar u ocultar capítulos por título.

---

## 🚀 Características

- 🔍 Buscador en tiempo real para encontrar manhwas por nombre
- 📄 Lista de capítulos por cada manhwa
- 🧩 Interfaz básica, lista para personalizar
- 🌐 100% HTML, CSS y JS: sin frameworks, fácil de editar

---

## 📁 Estructura del Proyecto
---

## 💻 Cómo probarlo en Replit

1. Ve a [https://replit.com](https://replit.com) y crea una cuenta
2. Crea un nuevo proyecto con plantilla **HTML, CSS, JS**
3. Copia el contenido de este repositorio (o sube el .zip)
4. Haz clic en **Run**
5. ¡Listo! Tu página web está en funcionamiento

---

## ✏️ Personalización

Para agregar más manhwas:

```html
<div class="manhwa">
  <h2>Título: Nombre del Manhwa</h2>
  <button onclick="verCapitulos('id_unico')">Ver capítulos</button>
  <div id="id_unico" class="capitulos" style="display: none;">
    <ul>
      <li><a href="#">Capítulo 1</a></li>
      <li><a href="#">Capítulo 2</a></li>
    </ul>
  </div>
</div>
