# Widgets de progreso para Notion

Este proyecto sirve para mostrar en Notion widgets de progreso de forma visual y automática.

Por ejemplo:
- porcentaje del año transcurrido
- días restantes
- barra de progreso visual

## Uso directo

Los widgets ya están publicados y se pueden usar directamente aquí:

`https://cbeceiro.github.io/progressbarnotion/`

Para usarlo en Notion:
1. Escribe `/embed`
2. Pega la URL del widget que hayas elegido
3. Ajusta el tamaño del bloque

## Estructura

Los widgets están organizados por secciones:

- `progress/day`, `progress/week`, `progress/month`, `progress/quarter`, `progress/year`
- `cards/day`, `cards/week`, `cards/month`, `cards/quarter`, `cards/year`
- `hours/day`, `hours/week`, `hours/month`, `hours/year`
- `one-percent/compound`, `one-percent/compound-quarter`, `one-percent/compound-milestones`, `one-percent/compound-milestones-dates`
- `energy/curve-day`
- `counters/weekends-left`, `counters/mondays-left`
- Estilos compartidos en `shared/`

## Personalización

Si quieres tu propia versión, puedes editar `index.html`, publicarlo en GitHub Pages y luego embeber tu propia URL en Notion.
