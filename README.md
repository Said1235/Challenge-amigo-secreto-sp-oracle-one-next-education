# 🎁 Sorteo de Amigos - Oracle Next Education  

Este proyecto forma parte del programa **Oracle Next Education** y permite gestionar una lista de amigos y sortear un resultado de manera sencilla.  

## 🔨 Funcionalidades del proyecto  
- ✅ **Colocar la lista de amigos**: Agrega los nombres de los participantes.  
- ✅ **Sortear los amigos**: El sistema elige aleatoriamente un amigo de la lista.  
- ✅ **Mostrar el resultado**: Se muestra el nombre del amigo seleccionado.  

## 🔖 Tecnologías utilizadas  
- 🟢 **JavaScript** – Lógica del sorteo y manipulación del DOM.  
- 🔵 **HTML** – Estructura del sitio web.  
- 🟣 **CSS** – Estilos y diseño visual.  

## ⚠️ Problemas y soluciones comunes  

### 1️⃣ **El botón de sorteo no funciona**  
**Posible causa:** No se ha vinculado correctamente el evento `click` en JavaScript.  
**Solución:** Asegúrate de que el script está cargado correctamente y que el evento `addEventListener` está bien aplicado.  

### 2️⃣ **El resultado muestra "undefined" o "null"**  
**Posible causa:** La lista de amigos está vacía o el código intenta acceder a un índice inexistente.  
**Solución:** Verifica que la lista contenga elementos antes de hacer el sorteo.  

### 3️⃣ **Los estilos no se aplican correctamente**  
**Posible causa:** La hoja de estilos (CSS) no está bien enlazada o hay errores en las clases.  
**Solución:** Asegúrate de que el `<link>` a CSS está bien escrito y que los nombres de clases coincidan.  

### 4️⃣ **No se actualiza la lista de amigos al agregar nuevos nombres**  
**Posible causa:** La manipulación del DOM no está refrescando la visualización correctamente.  
**Solución:** Usa `innerHTML` o `appendChild()` correctamente después de modificar la lista.  

## 💡 Reflexión Final  

Este proyecto no solo es una práctica de programación, sino también una oportunidad para aprender a resolver problemas de forma estructurada. Cada error es una lección, cada solución un paso adelante. No importa cuán pequeño parezca un proyecto, cada línea de código escrita es un avance en el camino del aprendizaje.  

✨ ¡Sigue explorando, sigue aprendiendo y sigue creando! 🚀  

📌 ¡Contribuciones y mejoras son bienvenidas!  
