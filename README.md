# coding-project-template

# e-plantShopping

## Paradise Nursery

**e-plantShopping** es una aplicación web de comercio electrónico desarrollada con **React** para una tienda de plantas llamada **Paradise Nursery**.

La aplicación permite visualizar plantas organizadas por categorías y gestionar un carrito de compras de forma dinámica.

## Funcionalidades

- Página de inicio con información de Paradise Nursery.
- Navegación entre la página principal, listado de plantas y carrito.
- Plantas organizadas por categorías.
- Tarjetas de productos con:
  - Imagen.
  - Nombre.
  - Descripción.
  - Precio.
  - Botón **Add to Cart**.

- Botón **Add to Cart** que se deshabilita cuando el producto ya está en el carrito.
- Contador dinámico de productos en el carrito.
- Carrito de compras con:
  - Cantidad de cada producto.
  - Incremento de cantidades.
  - Disminución de cantidades.
  - Eliminación de productos.
  - Costo individual.
  - Costo total por producto.
  - Costo total del carrito.

- Botón **Continue Shopping** para regresar al listado de plantas.
- Botón **Checkout** con mensaje de funcionalidad próximamente disponible.

## Tecnologías utilizadas

- React
- JavaScript
- Redux Toolkit
- React Redux
- Vite
- HTML
- CSS

## Gestión del estado

La aplicación utiliza **Redux Toolkit** para administrar el estado global del carrito.

Las principales acciones implementadas son:

- `addItem`: agrega una planta al carrito o incrementa su cantidad si ya existe.
- `removeItem`: elimina una planta del carrito.
- `updateQuantity`: actualiza la cantidad de una planta.

## Estructura principal

```text
src/
├── AboutUs.jsx
├── AboutUs.css
├── App.jsx
├── App.css
├── ProductList.jsx
├── ProductList.css
├── CartItem.jsx
├── CartItem.css
├── CartSlice.jsx
├── store.js
├── main.jsx
└── index.css
```

## Instalación y ejecución

Clona el repositorio:

```bash
git clone https://github.com/DevRobertoC/e-plantShopping.git
```

Entra en la carpeta del proyecto:

```bash
cd e-plantShopping
```

Instala las dependencias:

```bash
npm install
```

Ejecuta el proyecto:

```bash
npm run dev
```

Después abre en el navegador la dirección indicada por Vite.

## Repositorio

GitHub:

https://github.com/DevRobertoC/e-plantShopping

## Proyecto

**Paradise Nursery — e-plantShopping**

Aplicación desarrollada como proyecto final para practicar React, manejo de estado y Redux Toolkit.
