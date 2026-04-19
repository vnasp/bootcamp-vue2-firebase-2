# Firebase Auth - Sistema de Autenticación

Proyecto desarrollado como desafío del Bootcamp Frontend Developer de Talento Digital para Chile. Sistema de autenticación con Firebase Auth que permite registro, login y logout de usuarios con rutas protegidas.

> **Nota:** Este es un proyecto académico para aprender autenticación con Firebase.

## Vista previa

[Ver en GitHub Pages](https://vnasp.github.io/bootcamp-vue2-firebase-2/)

## Funcionalidades

- Registro de usuarios con email y contraseña
- Login con credenciales
- Logout con redirección
- Rutas protegidas con navigation guards
- Estado de autenticación reactivo con `onAuthStateChanged`
- Navegación condicional según estado de sesión

## Tecnologías

- Vue.js 2
- Firebase 10 (Authentication)
- Vue Router 3
- Vuex 3
- Bootstrap 5

## Estructura

```
src/
├── App.vue              → Layout con navbar condicional y logout
├── main.js              → Punto de entrada con estado de auth reactivo
├── firebaseConfig.js    → Configuración Firebase y operaciones de auth
├── router/
│   └── index.js         → Rutas con guards de autenticación
└── views/
    ├── Home.vue         → Página principal (requiere auth)
    ├── Login.vue        → Formulario de login
    └── Register.vue     → Formulario de registro
```
