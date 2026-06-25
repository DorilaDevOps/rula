# 🎲 Ruleta Europea

Ruleta Europea multijugador con fichas, apuestas simultáneas y pagos 36x. Funciona 100% en el navegador, mobile-first, sin servidor ni dependencias.

## Características

- **8 jugadores** con saldo individual (50 fichas iniciales)
- **Ruleta real** con orden europeo (`0, 32, 15, 19, ...`) y colores correctos (rojo, negro, verde)
- **Apuestas simultáneas** — todas las fichas de todos los jugadores se ven apiladas en el tablero al mismo tiempo
- **Denominaciones**: ×1, ×5, ×10, ×25
- **Pago 36x** por ficha acertada
- **Giro animado** con sonido de tic por segmento y melodía de victoria
- **Historial** de últimos 20 resultados
- **Modo oscuro/claro**
- **Mobile-first** — táctil, sin hover, scroll vertical

## Cómo usar

1. Abrí `index.html` en cualquier navegador
2. Seleccioná un jugador (tabs abajo)
3. Elegí denominación (×1, ×5, ×10, ×25)
4. Tocá un número en el tablero para apostar
5. Tocá **GIRAR** o la ruleta para jugar

### Estados especiales

- **Saldo bajo** (< 5 fichas): aparece advertencia y botón `+50💰` para comprar fichas
- **Saldo insuficiente** para mantener apuestas: el jugador queda bloqueado hasta que compre fichas o limpie sus apuestas
- Cada jugador puede limpiar sus apuestas individualmente con el botón ✕ en su tab

## Requisitos

Navegador moderno con soporte para:
- CSS Grid
- Canvas
- Web Audio API

## Archivos

| Archivo | Descripción |
|---------|-------------|
| `index.html` | Todo el juego en un solo archivo (HTML + CSS + JS) |
| `README.md` | Este archivo |

## Créditos

Creado por Kikiriya DevOps by Andres.

