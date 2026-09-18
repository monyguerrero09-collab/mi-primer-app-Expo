# mi-primer-app-Expo
# 📱 Introducción a Expo (React Native) — Hola Mundo

Proyecto práctico desarrollado para la asignatura de **Desarrollo de Dispositivos Móviles**. Consiste en una actividad de exposición teórica y demostración práctica frente a docente y compañeros sobre los fundamentos del framework **Expo** y la compilación/ejecución de una primera aplicación móvil multiplataforma ("Hola Mundo").

---

## 🎯 Objetivo de la Actividad

1. **Comprender qué es Expo:** Entenderlo como un framework y ecosistema montado sobre React Native que organiza herramientas, librerías y convenciones para simplificar el desarrollo multiplataforma (Android, iOS y Web).
2. **Conocer el ecosistema y flujo de trabajo:** Familiarizarse con Expo SDK, Expo Router, Expo CLI y Metro Bundler con soporte para *Fast Refresh*.
3. **Demostración en vivo:** Ejecutar el ciclo completo de inicialización, arranque del servidor de desarrollo y compilación en tiempo real para visualizar la app tanto en dispositivo físico (vía Expo Go) como en emulador o navegador web.

---

## 🏗️ Pila Tecnológica y Requisitos

* **Entorno de ejecución:** [Node.js](https://nodejs.org/) (LTS recomendada con `npm`)
* **Framework:** [Expo](https://expo.dev/) (con Expo Router y Expo SDK)
* **Librería base:** [React Native](https://reactnative.dev/)
* **Lenguaje:** TypeScript / JavaScript
* **Herramienta de pruebas:** Aplicación móvil **Expo Go** (Android / iOS) o emulador/navegador web

---

## 📂 Estructura del Proyecto

El proyecto utiliza la convención recomendada con estructura basada en la carpeta `src/`:

```text
├── assets/             # Recursos estáticos (imágenes, iconos, splash)
├── src/
│   ├── app/            # Rutas y pantallas (Expo Router)
│   │   ├── _layout.tsx # Estructura y navegación compartida
│   │   └── index.tsx   # Pantalla principal ("Hola Mundo")
│   ├── components/     # Componentes reutilizables
│   ├── constants/      # Constantes de configuración/estilos
│   └── hooks/          # Hooks personalizados
├── app.json            # Configuración general de Expo (slug, versión, splash)
├── package.json        # Dependencias y scripts de ejecución
└── tsconfig.json       # Configuración de TypeScript
