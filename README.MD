# EASYPAGO

**EASYPAGO** es una aplicación web sencilla que permite a los usuarios calcular el valor de cada cuota para pagar un monto determinado con un interés y un número de cuotas especificadas.

## Funcionalidades

1. **Cálculo del pago total y las cuotas:**
   - El usuario ingresa el monto que debe pagar.
   - El usuario indica el porcentaje de interés sobre el monto.
   - El usuario elige el número de cuotas en las que desea dividir el pago.
   - La aplicación calcula el valor de cada cuota sumando el interés al monto original y lo divide entre el número de cuotas especificado.
   
2. **Interfaz amigable:**
   - Diseño simple y limpio utilizando Bootstrap.
   - Campos de entrada con validación para asegurar que los datos ingresados sean válidos.
   
3. **Resultados de la cuota:**
   - El valor de cada cuota es mostrado en un formato fácil de entender, con los valores separados por puntos como en el formato numérico alemán.

## Estructura del Proyecto

El proyecto se divide en los siguientes archivos:

- `index.html`: Contiene el formulario donde los usuarios ingresan los datos para calcular las cuotas.
- `script.js`: Contiene la lógica de la aplicación, incluida la validación y el cálculo de las cuotas.
- `styles.css`: Contiene estilos adicionales que mejoran el diseño de la página.
- `README.md`: Este archivo.

## Cómo Usar

1. Clona o descarga el repositorio.
2. Abre el archivo `index.html` en tu navegador.
3. Ingresa el monto a pagar, el porcentaje de interés y el número de cuotas.
4. Haz clic en el botón **¿CÓMO LO PAGO?** para ver el valor de cada cuota calculado.

## Dependencias

- **Bootstrap**: Para el diseño y los componentes de la interfaz de usuario.

```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" />

https://sebaspatric.github.io/Easypago/
