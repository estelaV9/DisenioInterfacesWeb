## Tema 2: Elementos para el diseño web. Color, matiz y saturación

### 1. Interfaz web: navegación y contenido
La **maquetación web** consiste en establecer qué elementos principales constituyen las páginas web y sus zonas:
- **Zona de navegación**: permite acceder a todos los contenidos del sitio, dando al usuario la sensación de saber dónde está y cómo moverse; debe indicar la ubicación actual y permitir consultar el índice de contenidos globales
- **Zona de contenido e interacción**: parte principal donde se muestra el contenido (textos, campos de entrada, imágenes, vídeos, etc)

<br>

### 2. Maquetación web
Tres preguntas clave antes de crear el prototipo:
1. ¿Qué elementos va a tener el sitio web?
2. ¿Cuántas páginas va a contener?
3. ¿Cómo se van a distribuir los elementos en cada página?

#### 2.1 Elementos de una interfaz web
| Elemento | Función |
|---|---|
| **Cabecera (header)** | Identifica el sitio web y le da un sello de imagen que lo distingue del resto |
| **Sistema de navegación** | Muestra el nombre de todas las páginas del sitio; se sitúa debajo de la cabecera y da acceso a cada página al pinchar sobre su nombre |
| **Pie de página (footer)** | Zona inferior con información importante: créditos, licencia, enlace a contacto, etc |
| **Cuerpo** | Parte central donde aparece la información principal, situada bajo la cabecera y el menú de navegación |

#### 2.2 Mapa de navegación
Los sitios web pueden tener desde una sola página hasta muchas secciones. La página de inicio suele ser accesible desde cualquier parte del sitio, mientras que otras páginas solo lo son desde determinados lugares. Se recomienda crear un esquema que recoja todos los vínculos entre secciones y páginas
**Nielsen** propone tres preguntas fundamentales para el diseño de sistemas de navegación:
- ¿Dónde estoy?
- ¿Dónde he estado?
- ¿Dónde puedo ir?

<br>

### 3. El color
#### 3.1 Sistema RGB
El ordenador representa los colores mediante el sistema **RGB (red-green-blue)**, indicando la proporción de cada uno de los tres colores en la combinación
- Cada color se codifica con **8 bits**, dando una escala monocromática de **256 valores** (2⁸)
- Los colores pueden representarse en sistema decimal (0-255) o hexadecimal (bloques de 4 bits)
- El número total de combinaciones posibles es 256 × 256 × 256 = **16 777 216 colores**

#### 3.2 Matiz, saturación y brillo
| Propiedad | Descripción |
|---|---|
| **Matiz** | Atributo que distingue un color de otro; los tres matices primarios (aditivos) son rojo, verde y azul; dos colores son complementarios cuando están enfrentados en el círculo cromático |
| **Saturación** | Define la intensidad de un color; a mayor nivel de gris, menor saturación e intensidad |
| **Brillo** | Define la cantidad de luz de un color (más oscuro con negro, más claro con blanco); cuanto más brillante, más cerca parece estar el color |

#### 3.3 Colores seguros
Los **colores seguros (web-safe colors)** se representan igual en cualquier navegador, dispositivo o sistema operativo, garantizando la misma experiencia cromática a todos los usuarios (aunque hoy en día casi todos los soportes admiten cualquier color)
Se consiguen combinando exclusivamente estos valores hexadecimales: `00, 33, 66, 99, AA, CC, FF`

<br>

### 4. Elementos de diseño
#### 4.1 Elementos conceptuales: punto, línea, plano y volumen
No son visibles ni tienen existencia física, pero se interrelacionan generando figuras más complejas:
| Elemento | Características |
|---|---|
| **Punto** | Indica posición; no tiene largo ni ancho; no ocupa espacio; es el principio y fin de una línea y el lugar donde se cruzan dos líneas |
| **Línea** | Tiene largo pero no ancho; está limitada por puntos; forma los bordes de un plano; el recorrido de una línea en movimiento genera un plano |
| **Plano** | Tiene largo y ancho, pero no grosor; tiene posición y dirección; está delimitado por líneas; define los límites externos de un volumen |
| **Volumen** | Tiene posición en el espacio; está limitado por planos; en un diseño bidimensional el volumen es ilusorio |

#### 4.2 Elementos visuales: forma, medida, color y textura
Son las características visuales de los elementos conceptuales que permiten crear formas más complejas

#### 4.3 Elementos de relación: dirección, posición, espacio y gravedad
Definen las características de ubicación e interrelación de las formas entre sí

#### 4.4 Elementos prácticos: representación, significado y función
Se centran en el contenido y alcance de un diseño; son interpretados por la mente, permitiendo atribuir características y significados a las formas, con una interpretación más subjetiva que el resto de elementos

<br>

---
>_Estela de Vega Martín | IES Ribera de Castilla 26/27._
