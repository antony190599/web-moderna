# WEB MODERNA  

## Autor  

- **Nombre:** Antony Francisco Cayo Melendez  
- **Curso:** CODE 201  
- **Email:** antonycayo19@gmail.com  
- **Fecha de creación:** 21 de noviembre de 2024  

## Sobre el Proyecto  

**Web Moderna** es un proyecto que explora las prácticas, herramientas y enfoques más avanzados en el desarrollo web, con el objetivo de crear aplicaciones rápidas, accesibles y visualmente atractivas. Este concepto engloba tecnologías de última generación que redefinen cómo los desarrolladores diseñan experiencias digitales adaptadas a las necesidades del usuario actual.  

### Tecnologías Clave  

- **HTML5, CSS3 y JavaScript:** Bases fundamentales para estructurar, estilizar y dotar de interactividad a las aplicaciones web.  
- **Frameworks y Librerías:** React.js, Angular o Vue.js, que facilitan el desarrollo modular y escalable de interfaces dinámicas.  
- **Arquitectura basada en APIs:** Integración de servicios externos y microservicios para crear aplicaciones más flexibles y modulares.  
- **Seguridad:** HTTPS, autenticación segura y protección contra vulnerabilidades, garantizando confianza en las interacciones del usuario.  

El proyecto también hace énfasis en la **experiencia del usuario (UX)**, priorizando tiempos de carga rápidos, accesibilidad universal y diseños intuitivos. Además, adopta metodologías ágiles y DevOps para optimizar la colaboración en equipo y la entrega de productos de alta calidad.  

## ESLINTRC  

### Explicación del Archivo de Configuración: `.eslintrc.json`  

Este archivo configura **ESLint**, una herramienta utilizada para mantener un código JavaScript limpio y libre de errores comunes.  

### Configuración Completa  

```json
{
  "env": {
    "browser": true,
    "es2021": true
  },
  "extends": ["eslint:recommended"],
  "parserOptions": {
    "ecmaVersion": "latest",
    "sourceType": "module"
  },
  "rules": {
    "indent": ["error", 2],
    "linebreak-style": ["error", "unix"],
    "quotes": ["error", "single"],
    "semi": ["error", "always"],
    "no-unused-vars": "warn",
    "no-console": "warn"
  }
}
```

### Explicación de las Secciones
### env

-"browser": true: Activa variables globales como window y document.
-"es2021": true: Permite el uso de funciones modernas de ECMAScript 2021.

### extends
- "eslint:recommended": Aplica reglas básicas recomendadas para mantener buenas prácticas.
- parserOptions
    - "ecmaVersion": "latest": Habilita la versión más   reciente de ECMAScript.
    - "sourceType": "module": Permite el uso de módulos (import y export).
### rules
    - "indent": ["error", 2]: Obliga a una indentación de 2 espacios.
    - "linebreak-style": ["error", "unix"]: Requiere saltos de línea estilo Unix (\n).
    - "quotes": ["error", "single"]: Obliga al uso de comillas simples.
    - "semi": ["error", "always"]: Exige el uso de punto y coma al final de las sentencias.
    - "no-unused-vars": "warn": Genera advertencias para variables no utilizadas.
    - "no-console": "warn": Muestra advertencias si se usa console.log.

### Propósito

    Esta configuración asegura que el código siga estándares consistentes y legibles, promoviendo la calidad y mantenibilidad del proyecto.

### Despliegue