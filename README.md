# 🗝️ MoguApp — Tracker de Orfebrería KH

**MoguApp** es una aplicación web interactiva diseñada para facilitar el seguimiento del progreso de orfebrería (síntesis de objetos) en *Kingdom Hearts* / *Kingdom Hearts Final Mix (HD 1.5 ReMIX)*.

Permite consultar recetas por fases de desbloqueo, verificar qué materiales necesitas en tiempo real, llevar un inventario de tus recursos y consultar una guía completa de enemigos y ubicaciones.

---

## ✨ Características Principales

* 📜 **Recetas de Síntesis Actualizadas Progresivamente:**
  * Incluye únicamente los objetos y materiales confirmados al desbloquearlos en el juego.
  * Checkbox interactivo para marcar los objetos que ya has fabricado.
  * Indicador dinámico que resalta los ingredientes que ya posees en verde.
  * Cálculo automático de materiales restantes considerando solo lo que te falta por sintetizar.

* 👾 **Guía de Enemigos y Zonas (Bestiario):**
  * Lista detallada de qué sincorazón suelta cada material.
  * Incluye las estrategias y ubicaciones de los **enemigos especiales de *Final Mix*** (*Níscalo Rosa, Gigasombra, Avizor Salvaje, Alacrán de Tinaja, etc.*).
  * Buscador rápido por enemigo, objeto o mundo, y filtros por tipo de material.

* 📦 **Inventario de Materiales en Tiempo Real:**
  * Control total de tu stock con botones `+` / `-` e introducción manual de cantidades.
  * Comparativa directa entre lo que tienes en el inventario y lo que necesitas para completar todas las recetas pendientes.

* 💾 **Persistencia Automática:**
  * Guarda automáticamente todo tu progreso y materiales en el almacenamiento local de tu navegador (`LocalStorage`). No perderás tus datos al cerrar la pestaña.


---

## 🚀 Cómo Usar / Despliegue

La aplicación está construida en un **único archivo autónomo (`index.html`)**, por lo que no requiere instalación ni proceso de compilación (*build*).

### Ver en Local
1. Descarga el archivo `index.html`.
2. Haz doble clic en él para abrirlo en cualquier navegador web (*Chrome, Firefox, Edge, Safari*).


---

## 🛠️ Tecnologías Utilizadas

* **HTML5 / JavaScript (ES6+):** Lógica del sistema y manipulación del DOM.
* **Tailwind CSS (via CDN):** Maquetación y estilos visuales adaptativos.
* **Lucide Icons:** Iconografía moderna y ligera.
* **Web Storage API:** Guardado local de datos.

---

## 🤝 Contribuciones y Notas

Los datos del juego corresponden a la versión **Kingdom Hearts Final Mix** (*KH HD 1.5 ReMIX*). 

¡Siéntete libre de clonar este repositorio, modificar el código o adaptarlo para otras entregas de la saga!
