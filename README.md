# Clon de Trello

## 🌐 Live Preview
[Ver Demo en Vivo](#) <!-- Reemplaza "#" con el enlace a tu despliegue en vivo, por ejemplo, en Vercel, Netlify, GitHub Pages, etc. -->

## 🛠️ Tecnologías Usadas
- **Frontend**: HTML, CSS, JavaScript
- **Frameworks/Librerías**: React
- **Backend**: Node.js, Express
- **Base de Datos**: MongoDB
- **Autenticación**: JWT (JSON Web Tokens)
- **Control de Versiones**: Git & GitHub
- **Despliegue**: Vercel / Heroku

## ✅ Buenas Prácticas Aplicadas
- **Componentización en React**: La aplicación está dividida en componentes reutilizables, lo que facilita el mantenimiento y escalabilidad del código.
- **Responsive Design**: Se han aplicado principios de diseño responsive para asegurar una experiencia óptima en dispositivos móviles y de escritorio.
- **Manejo de Estado Global**: Utilización de **React Context API** para el manejo de estado compartido entre componentes.
- **Estructura de Carpetas Modular**: Organización de archivos siguiendo una estructura **feature-based**, lo que mejora la claridad y modularidad del proyecto.
- **Validación de Entradas**: Validación tanto en frontend como en backend para mejorar la seguridad.
- **Autenticación Segura**: Implementación de JWT para proteger rutas y recursos.

## 📋 Detalles del Ejercicio
Este proyecto consistió en clonar la página de Trello, replicando tanto su interfaz como parte de su funcionalidad, incluyendo:

- **Creación de Tableros y Tarjetas**: Los usuarios pueden crear, editar y eliminar tableros y tarjetas.
- **Arrastrar y Soltar**: Implementación de la funcionalidad de arrastrar y soltar (drag and drop) para reorganizar tarjetas usando **React DnD**.
- **Autenticación de Usuarios**: Registro e inicio de sesión con autenticación basada en tokens.
- **Persistencia de Datos**: Almacenamiento de la información de usuarios, tableros y tarjetas en una base de datos NoSQL (MongoDB).

### 🚧 Retos y Soluciones
- **Implementación de Drag & Drop**: El mayor desafío fue implementar la funcionalidad de arrastrar y soltar. Se utilizó la librería **React DnD**, lo que implicó un aprendizaje inicial, pero permitió una integración fluida.
- **Gestión de Estados Complejos**: Manejar el estado de múltiples listas y tarjetas fue complicado. Opté por React Context API para evitar el **prop drilling** y facilitar la gestión del estado global.
- **Optimización de Rendimiento**: Se utilizaron **React.memo** y **useCallback** para optimizar el rendimiento de componentes y prevenir renders innecesarios.
