# Laboratorio 6. Taller de refuerzo HTML y CSS

Este laboratorio está diseñado para que los participantes puedan aprender y reforzar sus conocimientos de HTML y CSS mediante la creación de una lista de Pokemones y un formulario para agregar nuevos Pokemones. Utilizando pruebas unitarias y autograding con Jest para asegurar que las vistas están correctamente estructuradas.

## Tareas a realizar
1. Crear una lista de Pokemones en el archivo index.hmtml.
2. Crear un formulario para el ingreso de un nuevo Pokémon.
3. IMPORTANTE!!! Editar el archivo styles.css con las propiedades que el estudiante crea conveniente para mejorar la apariencia de los componentes gráficos

## Prerrequisitos

- [Node.js](https://nodejs.org/) (v20 o superior)
- [npm](https://www.npmjs.com/) (v10 o superior)

## Instalación

1. Clona este repositorio en tu máquina local:

   ```bash
   git clone https://github.com/...
   ```
2.	Navega al directorio del proyecto:
    ```bash
    cd taller-html-css-jest
    ```
3.	Instala las dependencias del proyecto:
    ```bash
    npm install
    ```
## Estructura del Proyecto

- `index.html` - Lista de Pokemones
- `form.html` - Formulario para ingresar nuevos Pokemones
- `styles.css` - Archivo CSS para estilizar las vistas
- `tests/`
  - `list.test.js` - Pruebas unitarias para `index.html`
  - `form.test.js` - Pruebas unitarias para `form.html`
- `package.json` - Archivo de configuración de npm
- `jest.config.js` - Configuración de Jest

## Ejecutar las Pruebas

Para ejecutar las pruebas, usa el siguiente comando:

```bash
npm test
```

Para ejecutar una por una las pruebas ejecuta:
```bash
npm test tests/01-list.test.js
```
```bash
npm test tests/02-form.test.js
```