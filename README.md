Página web creada para proyecto final del curso de Front-End JS de Talento Tech

# ZonaGamer - Tienda Online de Componentes para PC


ZonaGamer es una tienda online pensada para gamers y entusiastas del hardware, donde podrás encontrar los mejores componentes y accesorios para armar tu PC. El sitio permite explorar productos destacados, ver detalles técnicos, agregar productos al carrito, gestionar tu compra y contactar al equipo de ZonaGamer.


## Tecnologías utilizadas

- **HTML5**
- **CSS3** (con Bootstrap 5 para estilos y componentes responsivos)
- **JavaScript** (manejo de carrito, modales, interacción y API de reseñas)
- **Font Awesome** (iconos)
- **Google Fonts** (fuentes personalizadas)
- **Formspree** (envío de formularios de contacto y compra)
- **RandomUser API** (para mostrar reseñas dinámicas de clientes)


## Características principales

- **Catálogo de productos:** Procesadores, placas madre, placas de video, fuentes, memorias RAM y SSD.
- **Detalles técnicos:** Cada producto tiene su propio modal con especificaciones detalladas.
- **Carrito de compras:** Agrega productos, modifica cantidades, elimina ítems y vacía el carrito.
- **Finalizar compra:** Modal con formulario para ingresar datos personales y enviar el pedido.
- **Contador dinámico:** El icono del carrito muestra la cantidad total de productos agregados.
- **Reseñas de clientes:** Se muestran reseñas dinámicas usando la API de RandomUser.
- **Formulario de contacto:** Permite enviar consultas directamente desde la web.
- **Diseño responsivo:** Adaptado para dispositivos móviles y escritorio.
## Installation

1. **Descarga o clona el repositorio**

```bash
  git clone <URL-del-repositorio>
```
2. **Estructura de carpetas recomendada**
```plaintext
ZonaGamer/
├── index.html
├── productos.html
├── carrito.html
├── contacto.html
├── nosotros.html
├── reseñas.html
├── ubicacion.html
├── css/
│   └── styles.css
├── img/
│   └── (todas las imágenes usadas)
├── fonts/
│   └── (fuentes personalizadas)
└── javascript.js
```
3. **Abrir el proyecto**
Abre el archivo `index.html` en tu navegador preferido.

4. **Requisitos**
- No requiere servidor backend, todo funciona en el navegador.
- Se recomienda usar navegadores modernos para mejor compatibilidad.
## Detalles relevantes

- **Carrito persistente:** Los productos agregados se guardan en `localStorage`, por lo que el carrito se mantiene aunque recargues la página.
- **Formularios:** El formulario de compra y contacto utiliza [Formspree](https://formspree.io/) para recibir los datos por email.
- **Reseñas:** Se obtienen datos aleatorios de usuarios reales usando la API [RandomUser.me](https://randomuser.me/).
- **Mensajes flotantes:** Al agregar productos al carrito, aparece un mensaje animado de confirmación.
- **Validaciones:** Los campos obligatorios en los formularios aseguran que el usuario complete la información necesaria.
## Personalización

- Puedes modificar los productos, imágenes y textos editando los archivos HTML y el archivo `javascript.js`.
- Para cambiar el correo de destino de los formularios, reemplaza el endpoint de Formspree por el tuyo.


## Autor

Desarrollado por **Franco Molina González**

Contacto: [molinagonzalezfranco@gmail.com](mailto:molinagonzalezfranco@gmail.com)

