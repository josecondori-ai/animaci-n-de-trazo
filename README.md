# 🖌️ SVG Text Animation / Animación de Texto SVG


https://github.com/user-attachments/assets/3e95170f-a47b-4353-a9f6-07be56431f86



Este proyecto demuestra una animación de texto SVG utilizando CSS para crear un efecto de "trazo", donde el contorno del texto se dibuja en diferentes colores y se repite infinitamente.

This project demonstrates an SVG text animation using CSS to create a "stroke" effect, where the text outline is drawn in different colors and loops infinitely.

## 🚀 Características / Features

- **Animación de Trazo / Stroke Animation**: El contorno del texto se anima para dar la apariencia de que se está "dibujando".
- **Colores Múltiples / Multiple Colors**: Cada línea de texto cambia de color según su posición, con diferentes retardos para crear un efecto escalonado.
- **Diseño Responsivo / Responsive Design**: El SVG es responsivo y ajusta su tamaño según el ancho de la ventana.

## 🎬 Demo

La animación dibuja continuamente el contorno del texto en cinco colores diferentes, con cada línea teniendo su propio retardo de animación para un efecto dinámico.

The animation continuously draws the outline of the text in five different colors, with each line having its own animation delay for a dynamic effect.

![SVG Text Animation Preview] (https://josecondori-ai.github.io/animaci-n-de-trazo/)

## ⚙️ ¿Cómo Funciona? / How It Works

1. **Trazo y Relleno / Stroke and Fill**: El texto utiliza `stroke` para el contorno y `fill: none` para asegurarse de que solo el trazo sea visible.
2. **Dasharray y Dashoffset**: Estas propiedades crean el efecto de guiones y controlan la posición de los guiones. A medida que `stroke-dashoffset` se anima, el guion se mueve a lo largo de la ruta del texto.
3. **Keyframes de CSS / CSS Keyframes**: La animación con `@keyframes stroke` anima el offset del guion de 0 a -400, creando el efecto de dibujo.
4. **Cambios de Color / Color Changes**: La pseudo-clase `nth-child` asigna diferentes colores de trazo a cada línea de texto y escalona la animación.

## 🔑 Propiedades Clave de CSS / Key CSS Properties

- `stroke-dasharray`: Define la longitud del guion y el espacio en el trazo.
- `stroke-dashoffset`: Mueve el punto de partida del guion, lo que se anima para crear el efecto de dibujo.
- `animation`: Se utiliza para repetir continuamente la animación de trazo.

## 🛠️ Instalación / Installation

Clona este repositorio y abre el archivo `index.html` en cualquier navegador web para ver la animación en acción.

Clone this repository and open the `index.html` file in any web browser to see the animation in action.

```bash
git clone https://github.com/yourusername/animaci-n-de-trazo

.git
cd animaci-n-de-trazo
open index.html
```

## ✏️ Personalización / Customization

Puedes modificar las siguientes propiedades para cambiar la animación:

You can modify the following properties to change the animation:

    Colores / Colors: Ajusta los valores de stroke en los selectores .text:nth-child para personalizar los colores.
    Velocidad / Speed: Cambia la duración de la animación en @keyframes stroke (el valor predeterminado es 6 segundos).
    Texto / Text: Modifica el texto SVG en el HTML para mostrar contenido diferente.

## 🧰 Tecnologías Utilizadas / Technologies Used

    HTML: Estructura básica / Basic structure.
    CSS: Animación y estilo del texto SVG / Animation and styling of SVG text.

## 🤝 Contribuciones / Contributing

¡Siéntete libre de hacer un fork de este proyecto y enviar pull requests para mejoras o nuevas funcionalidades!

Feel free to fork this project and submit pull requests for improvements or new features.
