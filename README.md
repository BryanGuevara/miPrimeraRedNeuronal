# Red Neuronal

## Descripción

El proyecto **Red Neuronal** es una página web que simula una red neuronal simple en el navegador. Utiliza la biblioteca `jscolor` para permitir la selección de colores mediante un input color y ajusta dinámicamente el contenido y el estilo de la página basado en el color seleccionado. La página muestra valores calculados que simulan el funcionamiento de una red neuronal básica en función del color elegido.

## Funcionalidades

- Permite seleccionar un color mediante un input tipo color.
- Muestra el color seleccionado en el fondo de la página.
- Calcula valores simulados basados en los componentes de color (Rojo, Verde, Azul).
- Actualiza el texto en la página con los resultados de los cálculos.
- Cambia el color del texto de la página dependiendo del valor calculado.

## Uso

1. Abre el archivo HTML en un navegador web.
2. Usa el selector de color para cambiar el color de fondo de la página.
3. Observa cómo se actualizan los valores en la página:
   - **Neurona 1**, **Neurona 2**, y **Neurona 3** muestran los valores normalizados de los componentes de color Rojo, Verde y Azul, respectivamente.
   - **Calculos** muestra el resultado de una operación simulada basada en los componentes de color.
   - **Color del texto** muestra el color actual del texto en la página, que cambia en función del valor calculado.

## Estructura del Código

- **HTML**: Define la estructura de la página, incluyendo un campo de entrada para seleccionar el color y varios elementos para mostrar resultados.
- **CSS**: Aplica estilos a los elementos de la página, incluyendo el contenedor principal y el formato de texto.
- **JavaScript**: Gestiona la lógica del color y las actualizaciones de la página:
  - **`update(color)`**: Cambia el color de fondo y actualiza el valor hexadecimal del color.
  - **`brain(color1, color2, color3)`**: Realiza cálculos simulados basados en los componentes del color y actualiza el contenido de la página.
