# 🎄 Cuenta Regresiva para Navidad (Christmas Countdown)

Un sencillo y elegante proyecto web que muestra cuánto tiempo falta para la próxima Navidad. Cuenta con opciones de personalización para el GIF de fondo y está optimizado para funcionar en cualquier dispositivo.

## ✨ Características

* **Cuenta Regresiva Precisa:** Calcula y muestra el tiempo restante en días, horas, minutos y segundos.
* **Diseño Responsivo:** Implementado con **Bootstrap 5.3** para una visualización perfecta en móviles y escritorio.
* **GIF Animado Personalizable:** Muestra un GIF navideño de fondo que se actualiza al recargar.
* **Configuración Avanzada:** Permite al usuario configurar el término de búsqueda y la cantidad de GIFs a solicitar para una experiencia personalizada.
* **Persistencia de Configuración:** Guarda las preferencias de búsqueda de GIF del usuario utilizando `localStorage`.

## 🚀 Uso e Instalación

Este proyecto es una aplicación web de un solo archivo y no requiere instalación ni dependencias (aparte de un navegador web moderno).

1.  **Guardar el Código:** Guarda el código HTML completo en un archivo llamado `index.html`.
2.  **Abrir en el Navegador:** Abre `index.html` directamente en tu navegador (Chrome, Firefox, Edge, etc.).

### Personalización de GIFs

Para cambiar el GIF y las opciones de búsqueda:

1.  Haz clic en el **icono de engranaje (⚙️)** ubicado en la esquina superior derecha de la pantalla.
2.  Aparecerá el modal de configuración con los siguientes campos:
    * **Término de búsqueda:** El texto que se usará en la API de Tenor (ej: `santa`, `snow`, `presents`).
    * **Cantidad de GIFs a solicitar:** El número de GIFs que se solicitarán a la API (máximo **50**). La aplicación elegirá un GIF aleatorio de esta lista.
3.  Haz clic en **"Guardar cambios"** para aplicar y ver el nuevo GIF.

## 🛠️ Tecnologías

* **HTML5:** Estructura base del proyecto.
* **CSS3:** Estilos personalizados.
* **JavaScript (ES6+):** Lógica principal de la cuenta regresiva, manejo de la API y persistencia de datos.
* **Bootstrap 5.3:** Framework CSS para el diseño responsivo y el componente Modal.
* **Font Awesome:** Para el icono de configuración (`fas fa-cog`).
* **Tenor API (Ejemplo):** Utilizado para obtener los GIFs animados de forma dinámica.

## 📝 Notas sobre la API

* El proyecto utiliza una clave de API de ejemplo (`LIVDSRZULELA`) de Tenor, que es pública y está destinada únicamente para demostraciones.
* El límite máximo de GIFs que se pueden solicitar por llamada es **50**. La lógica del código se asegura de no exceder este límite.