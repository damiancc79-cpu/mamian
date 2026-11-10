# Pesca 16-bit

Cartucho para la consola retro: versión pixel art de **Pesca 2.5D** que se juega en el navegador.

Abre `index.html` (mejor servido por http, p. ej. `python3 -m http.server`, para que carguen los sonidos)
o cárgalo desde la consola en un `<iframe src="pesca/index.html">`. Datos del cartucho en `cart.json`.

## Controles
| Botón | Teclado | Acción |
|---|---|---|
| ← → | flechas / A D | apuntar, contrarrestar al pez |
| A | Espacio / Z | mantener y soltar para lanzar; enganchar al ver **!**; mantener para recoger |
| B | X | álbum de especies (récords guardados) |
| Start | Enter | pausa |
| Select | C | créditos |
|  | M | música |

También funciona con mando (Gamepad API) y con botones táctiles en el móvil.

## Igual que el original
Misma lógica que la versión Godot: fuerza de lanzamiento, corcho que se hunde, tensión del sedal y aguante del pez,
tirones laterales, 6 especies (Mojarra, Carpa, Bagre, Trucha arcoíris, Lobina negra y el legendario Pez Dorado),
con las raras más lejos del muelle. Audio de SuperTux: ver `CREDITS.md`.
