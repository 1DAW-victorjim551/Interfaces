# 🌙 Luma – Framework CSS con Sass

**Luma** es un framework CSS ligero desarrollado con **Sass (SCSS)**, diseñado para crear interfaces **suaves, luminosas y agradables a la vista**.  
Su estética se basa en **colores pastel cálidos**, alejándose de estilos agresivos o chillones como los de frameworks tradicionales.

Este proyecto se ha desarrollado con fines académicos para el módulo de **Diseño de Interfaces Web**, aplicando buenas prácticas de arquitectura Sass moderna.

---

## 🎯 Objetivos

- Aplicar Sass moderno (`@use`, módulos, maps, mixins).
- Crear un framework escalable y mantenible.
- Diseñar una experiencia visual amable y coherente.
- Centralizar estilos mediante variables, funciones y mixins.
- Compilar todo el framework desde un único punto de entrada.

---

## 🗂️ Estructura del proyecto

```text
saas/
├── scss/
│   ├── abstract/
│   │   ├── _variables.scss
│   │   ├── _maps.scss
│   │   ├── _functions.scss
│   │   └── _mixins.scss
│   ├── base/
│   │   ├── _reset.scss
│   │   └── _typography.scss
│   ├── components/
│   │   ├── _buttons.scss
│   │   ├── _forms.scss
│   │   └── _cards.scss
│   ├── layout/
│   │   ├── _header.scss
│   │   ├── _grid.scss
│   │   └── _footer.scss
│   ├── utilities/
│   │   ├── _colors.scss
│   │   └── _spacing.scss
│   ├── themes/
│   │   ├── _light.scss
│   │   └── _dark.scss
│   └── main.scss
└── css/
   └── main.css
