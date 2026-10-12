# Karting RPG

Roguelite de karts en vista cenital, en un solo archivo HTML (canvas 2D, sin dependencias).

- **Campeonato**: cuatro carreras por campeonato (la última, de 10 vueltas), clasificación a dos vueltas, piezas que se gastan, tienda, boxes y almacén de neumáticos.
- **Carrera rápida**: circuito, neumáticos, vueltas y nivel a elegir, con el kart de alquiler para todos.
- **Online, 2 jugadores**: uno crea la partida y comparte un código de 4 letras; el otro se une. Conexión directa entre navegadores (WebRTC con [PeerJS](https://peerjs.com), incluido en `peerjs.min.js`, licencia MIT). Opcionalmente con 4 rivales de la IA, que conduce el anfitrión.
- **Pruebas libres**: todos los circuitos y setups, con los ajustes de física.
- Rivales con física real e IA que conduce al límite por un trazado de carreras calculado para cada circuito.
- Sonido sintetizado en el navegador y circuitos con público, boxes, comisarios y pancartas.

## Jugar

Abre `index.html` en el navegador, o la web publicada con GitHub Pages.

Las opciones (asistencia, volumen, tema claro u oscuro, mando, nombres de los pilotos) están en el menú **Opciones**.

Controles: flechas o WASD, espacio para saltar y derrapar, o mando (stick, RT, LT, RB).
