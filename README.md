# Teslo-Shop: Tienda Virtual

Este es un proyecto de E-commerce desarrollado con Next.js y TypeScript. La aplicación permite a los usuarios navegar por un catálogo de productos, ver detalles de los mismos y agregarlos a un carrito de compras.

## Características Principales

- **Catálogo de Productos:** Explora un catálogo de productos con imágenes y descripciones.
- **Páginas de Producto:** Vistas detalladas para cada producto.
- **Carrito de Compras:** Funcionalidad para agregar y gestionar productos en el carrito.
- **Diseño Responsivo:** Interfaz de usuario amigable y adaptable a diferentes dispositivos, construida con Tailwind CSS.
- **Frontend Moderno:** Interfaz de usuario reactiva y de alto rendimiento construida con Next.js.

## Tecnologías Utilizadas

### Frontend

- **Framework:** [Next.js](https://nextjs.org/)
- **Lenguaje:** [TypeScript](https://www.typescriptlang.org/)
- **Estilos:** [Tailwind CSS](https://tailwindcss.com/)
- **Gestión de Estado:** [Zustand](https://github.com/pmndrs/zustand)
- **Componentes:** [React Icons](https://react-icons.github.io/react-icons/), [Swiper](https://swiperjs.com/)

## Prerrequisitos

- [Node.js](https://nodejs.org/en/) (v18 o superior)
- [npm](https://www.npmjs.com/) o [yarn](https://yarnpkg.com/)

## Instalación

1.  **Clonar el repositorio:**

    ```bash
    git clone https://github.com/EmanuelRigo/Practica-NextJS-teslo-shop.git
    cd Practica-NextJS-teslo-shop
    ```

2.  **Instalar dependencias:**

    ```bash
    npm install
    ```

## Cómo Ejecutar la Aplicación

1.  **Iniciar la aplicación Frontend:**
    Desde el directorio raíz del proyecto:
    ```bash
    npm run dev
    ```
    La aplicación Next.js se ejecutará en `http://localhost:3000`.

Abre [http://localhost:3000](http://localhost:3000) en tu navegador para ver la aplicación en funcionamiento.

## Estructura del Proyecto

```
.
├── public/             # Contiene los archivos estáticos como imágenes y fuentes
├── src/                # Proyecto del Frontend (Next.js)
│   ├── app/            # Rutas de la aplicación
│   ├── components/     # Componentes reutilizables de React
│   ├── config/         # Configuraciones de la aplicación
│   ├── interfaces/     # Definiciones de tipos y interfaces de TypeScript
│   ├── seed/           # Datos iniciales para la base de datos
│   └── store/          # Lógica de gestión de estado con Zustand
├── package.json
└── README.md
```

- **`/public`**: Contiene todos los activos estáticos, como imágenes, que se sirven directamente.
- **`/src`**: Contiene la aplicación de frontend construida con Next.js, incluyendo páginas, componentes y lógica de cliente.
