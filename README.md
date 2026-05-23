# Solemne-II Pensamiento Computacional
[link] (https://editor.p5js.org/Anais06/sketches/9vRxvzx14)
[link] (https://editor.p5js.org/Anais06/full/9vRxvzx14) 

## información del proyecto
*BAUHAUS INTERACTIVO*


![imagen] (<img width="466" height="700" alt="Copia de Bauhaus XI_20x30-1743091906222" src="https://github.com/user-attachments/assets/8a2f466d-f466-45bc-99af-9fe00de17c0e" />
)

Es una reinterpretación contemporánea, autor desconocido.

- Qué es el proyecto
  
  Es un diseño generativo, que tiene como base un diseño de afiche de la Bauhaus. No es el afiche completo, solo usa sus figuras principales y su nombre, pero a través del sistema computacional para que se pueda interactuar con este.

- Qué se ve en pantalla
  
  Lo primero que se aprecia son los seis circulos y bajo ellos, un texto. Al mover el mouse a la derecha, cambia el tamaño y se agrega un borde. Al mover el mouse hacia abajo y arriba, los colores de los circulos cambian.

  - Elementos visuales
    
    figuras geométricas simples (circulos)
    texto
    paleta de colores cálidos y frios

  - Inputs
    mouseX
    mouseY

  - Outputs
    Imagen con constantes cambios; tamaño, color, bordes.

## Descripción del proyecto

La idea era hacer la base del afiche estilo Bauhaus, donde se pueda interactuar con los colores de los circulos y sus tamaños, a demás  de agregar un borde a las figuras y el texto.

El referente es la Bauhaus y el diseño moderno.
Esta creada por diversos estudios de diseño gráfico moderno que rinden homenaje a la escuela.
 
# Reglas que gobiernan el sistema
Detección: El programa siempre sabe dónde está el puntero.
Acción: Al mover el mouse, se dibuja un círculo.
Variación: Si el mouse se mueve en el eje X (horizontal), el color cambia; si se mueve en el eje Y (vertical), el tamaño cambia.

# Explicación del sistema de interactividad
Es un sistema de respuesta inmediata. No hay menús ni botones; la interacción es orgánica: el dibujo nace directamente de la trayectoria del mouse.

# Datos de entrada (Inputs)
Posición horizontal (mouseX).
Posición vertical (mouseY).

# Transformación y Proceso
El código lee esas coordenadas y las convierte en valores de color (RGB) y diámetro. Básicamente, traduce "espacio" en "color".

# Respuesta visual (Outputs)
Cambios de color.
Cambios en el tamaño.

