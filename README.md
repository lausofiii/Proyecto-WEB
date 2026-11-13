# UNO Web

Versión del clásico juego de cartas **UNO** que se juega directamente en el navegador, contra jugadores controlados por la computadora. Hecho con **HTML, CSS y JavaScript puro**, sin frameworks.

> Proyecto académico de la materia **Programación Orientada a la Web** (UCAB).

## Características

- Partidas de **2, 3 o 4 jugadores** (tú contra bots).
- **Mazo completo de 108 cartas:** números del 0 al 9 en cuatro colores y cartas especiales (Salto, Reversa, +2, Cambio de color y +4).
- Reglas implementadas: validación de jugadas por color o valor, robar del mazo cuando no hay jugada, cambio de sentido, selección de color con comodines y **cantar "UNO"** (con penalización).
- **Sistema de puntos por rondas:** gana quien llegue primero a 500 puntos.
- Pantalla de **reglas** dentro del juego.
- **Efectos de sonido y música de fondo** para cada acción (robar, saltar, ganar, error, UNO...).
- Interfaz con modales, animaciones y diseño adaptable.

## Tecnologías

| Área       | Herramientas                                       |
| ---------- | -------------------------------------------------- |
| Estructura | HTML5                                              |
| Estilos    | CSS3                                               |
| Lógica     | JavaScript (DOM, `async/await`, manejo de eventos) |
| Audio      | API de audio de HTML5                              |

## Estructura
```
UNO WEB/
├── index.html            # Pantalla de inicio, reglas y selección de jugadores
├── interfazdejuego.html  # Mesa de juego
├── script.js             # Lógica del juego
├── style.css             # Estilos
└── Assets/               # Cartas, fondos, logo y sonidos
```
## Cómo ejecutarlo

No requiere instalación.

1. Clona el repositorio:
   ```bash
   git clone https://github.com/lausofiii/Proyecto-WEB.git
   ```
2. Abre `UNO WEB/index.html` en tu navegador (o usa la extensión _Live Server_ de VS Code).
3. Pulsa **JUGAR**, elige el número de jugadores y ¡a jugar!
