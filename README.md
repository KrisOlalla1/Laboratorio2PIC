# Laboratorio2PIC
Este es el laboratorio 2
# **Proyecto: Aplicación Web Modular con Custom Elements**

## **Descripción**
Esta aplicación web utiliza **Custom Elements**, **Shadow DOM**, **Templates**, y **Slots** para crear una estructura modular, encapsulada y eficiente. Incluye componentes personalizados que representan diferentes secciones funcionales de la página.

## **Componentes del Proyecto**

### **1. `<custom-header>`**
- **Descripción**: Representa el encabezado de la aplicación.
- **Función**: Muestra el título principal de la página y proporciona una bienvenida al usuario.
- **Tecnologías usadas**: Shadow DOM para encapsular estilos y estructura.
- **Ubicación**: Archivo `header.js`.

### **2. `<custom-footer>`**
- **Descripción**: Es el pie de página.
- **Función**: Muestra información de derechos de autor o enlaces adicionales.
- **Tecnologías usadas**: Shadow DOM con estilos encapsulados.
- **Ubicación**: Archivo `footer.js`.

### **3. `<custom-main>`**
- **Descripción**: Contenedor principal para las páginas dinámicas.
- **Función**: Utiliza slots para cargar contenido dinámico (como el perfil, la tabla o la galería).
- **Tecnologías usadas**: Slots para inyectar contenido desde `index.html`.
- **Ubicación**: Archivo `main.js`.

### **4. `<custom-menu>`**
- **Descripción**: Menú de navegación.
- **Función**: Proporciona enlaces para navegar entre las secciones de la aplicación (Perfil, Tabla, Galería).
- **Tecnologías usadas**: Shadow DOM y estilos CSS encapsulados.
- **Ubicación**: Archivo `menu.js`.

### **5. `<custom-profile>`**
- **Descripción**: Página de perfil social.
- **Función**: Muestra datos personales como tu nombre, correo electrónico y una foto de perfil.
- **Personalización**: La foto se carga desde la carpeta `imagenes` (ejemplo: `foto1.jpg`).
- **Tecnologías usadas**: Shadow DOM, CSS encapsulado, y estructura modular con flexbox.
- **Ubicación**: Archivo `socialProfile.js`.

### **6. `<custom-table>`**
- **Descripción**: Tabla personalizada.
- **Función**: Carga y muestra datos desde una API externa: [JSONPlaceholder](https://jsonplaceholder.typicode.com/users).
- **Tecnologías usadas**: Fetch API para obtener datos dinámicos, Shadow DOM para estilos encapsulados.
- **Ubicación**: Archivo `customTable.js`.

### **7. `<custom-gallery>`**
- **Descripción**: Galería de imágenes.
- **Función**: Obtiene imágenes desde una API externa (como [PokéAPI](https://pokeapi.co/) o cualquier otra).
- **Tecnologías usadas**: Fetch API para datos dinámicos, Shadow DOM para encapsular estilos.
- **Ubicación**: Archivo `gallery.js`.

## **Tecnologías Utilizadas**
- HTML5
- JavaScript (ES6)
- Web Components
- Shadow DOM
- Fetch API
- CSS
