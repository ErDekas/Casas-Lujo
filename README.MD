# Documentación Final

## Paleta de Colores

Este proyecto utiliza una paleta de colores cuidadosamente seleccionada para garantizar una experiencia visual atractiva y coherente. A continuación se presenta la lista de colores definidos en la hoja de estilo:

- **Blanco**: #d7d7d7
- **Negro**: #111111
- **Azul**: #3838ff
- **Azul Claro**: #50a8ff
- **Amarillo**: #fcfca2
- **Rojo**: #ff5d5d
- **Lima**: #7dff7d
- **Oro**: #fbe35d
- **Oro Oscuro**: #dcb34c
- **Plata**: #bcb2b2
- **Gris Claro**: #dbd8d8

La función `color($color-name)` permite acceder a estos colores, pasando el nombre como parámetro. Ejemplo de uso:

```scss
background-color: color(azul_claro);
```

## Fuentes

Se utilizan dos fuentes principales para el proyecto:

1. **Quicksand**: Fuente principal para el texto. Se importa desde Google Fonts con el siguiente código:
   ```scss
   @import url('https://fonts.googleapis.com/css2?family=Quicksand&display=swap');
   ```
   
2. **Italiana**: Se utiliza de forma secundaria para algunos títulos o elementos destacados. Se importa también desde Google Fonts:
   ```scss
   @import url('https://fonts.googleapis.com/css2?family=Italiana&display=swap');
   ```

El `font-family-text` se establece como `Quicksand` para garantizar una tipografía limpia y legible.

## Iconos

Los iconos deben ser elegidos y cargados a través de una librería como FontAwesome, Material Icons, o cualquier otra que se adapte al proyecto. A continuación, se muestra un ejemplo de cómo incluir FontAwesome:

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
```

Los iconos se utilizarán para mejorar la interacción visual y la usabilidad de la aplicación.

## Elementos de Accesibilidad, Usabilidad y Experiencia de Usuario

### Accesibilidad

Para mejorar la accesibilidad, se han tomado en cuenta las siguientes prácticas:

- **Contraste de colores**: Se asegura que haya suficiente contraste entre el texto y el fondo, siguiendo las pautas WCAG 2.1.
- **Teclas de acceso rápido**: Se implementan atajos de teclado para facilitar la navegación a los usuarios con discapacidad motora.
- **Soporte para lectores de pantalla**: Se han agregado etiquetas ARIA donde es necesario para mejorar la accesibilidad con lectores de pantalla.
  
### Usabilidad

Se enfoca en hacer la interfaz intuitiva y fácil de usar para todo tipo de usuarios:

- **Diseño responsivo**: El diseño se adapta automáticamente a diferentes tamaños de pantalla, optimizando la experiencia tanto en dispositivos móviles como de escritorio.
- **Navegación clara y consistente**: Se emplea una estructura de navegación fácil de seguir, asegurando que los usuarios puedan encontrar lo que buscan sin dificultad.
  
### Experiencia de Usuario (UX)

- **Interacción fluida**: El diseño es interactivo y responde de manera fluida a las acciones del usuario. Se utilizan animaciones suaves para mejorar la experiencia sin distraer al usuario.
- **Retroalimentación visual**: Los botones, enlaces y otros elementos interactivos ofrecen retroalimentación visual al usuario (cambio de color, sombreado, etc.), garantizando que las interacciones sean claras.
- **Espaciado adecuado**: Se emplea un espaciado adecuado entre los elementos para evitar que la interfaz se sienta sobrecargada o difícil de usar.

## Tamaños de Fuente

Se utilizan diferentes tamaños de fuente según el contexto. Los tamaños están definidos en la variable `$font-sizes`:

- **XXL**: 6rem
- **XL**: 3rem
- **LG**: 2rem
- **SM**: 1rem

La función `size($size)` se utiliza para aplicar estos tamaños. Ejemplo de uso:

```scss
font-size: size(xl);
```

## Pesos de Fuente

Los pesos de fuente disponibles son los siguientes:

- **Light**: 300
- **Regular**: 400
- **Bold**: 700

La función `weight($weight)` permite obtener el peso correspondiente. Ejemplo de uso:

```scss
font-weight: weight(bold);
```
## Iconos
El proyecto utiliza iconos de FontAwesome para mejorar la experiencia visual. A continuación, se incluye la integración de los iconos en el código HTML.

## Integración de FontAwesome
Los iconos se cargan desde el servicio de FontAwesome mediante la siguiente línea:

``` html
<script src="https://kit.fontawesome.com/ba6470173b.js" crossorigin="anonymous"></script>
```
### Uso de Iconos
**En el sitio web se utilizan diversos iconos de FontAwesome. Algunos ejemplos son:**

- Icono de medalla: <i class="fa-solid fa-medal"></i>
- Icono de usuarios: <i class="fa-solid fa-users"></i>
- Icono de la Tierra (Europa): <i class="fa-solid fa-earth-europe"></i>
- Icono de etiqueta: <i class="fa-solid fa-tag"></i>
- Icono de tarjeta de crédito Visa: <i class="fa-brands fa-cc-visa"></i>
- Icono de tarjeta de crédito Mastercard: <i class="fa-brands fa-cc-mastercard"></i>
- Icono de tarjeta de crédito Paypal: <i class="fa-brands fa-cc-paypal"></i>
- Icono de tarjeta de crédito Amazon Pay: <i class="fa-brands fa-cc-amazon-pay"></i>
- Iconos de redes sociales (Instagram, Facebook, Twitter):
- Instagram: <i class="fab fa-instagram footer-icon"></i>
- Facebook: <i class="fab fa-facebook-f footer-icon"></i>
- Twitter: <i class="fab fa-twitter footer-icon"></i>
Estos iconos se utilizan en la navegación y en el pie de página para facilitar la interacción del usuario.