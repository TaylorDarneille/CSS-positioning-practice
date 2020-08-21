# FLEXBOX: #
- Single-axis oriented 
- Widely implemented 
 - If an element is targeted by display: flex; it becomes a flex container 
-> **flex-direction** property orients flex container's main-axis (sets directional flow of flex-items)
-> **justify-content** property aligns content relative to main-axis
-> **align-content** property controls how rows/ columns are arranged relative to the cross-axis (flex-start, flex-end, strech, center, space-between, space-around)

# CSS GRID: #
- Newer than Flexbox, but not as widely implemented (and might not be supported on all browsers)
- Optimized for 2D layouts
- Can divide screen into rows and columns of various sizes, specifying how many rows and columns each cell can take up
- Sizings can be fixed or dynamic
- Components of the grid: **grid rows, grid columns, grid tracks (cells in a line in a row/column), grid areas (group of adjacent grid cells)** that can be linked to HTML containers

# Summary #
Both Flexbox and CSS Grid are very useful. Flexbox is widely implemented and helps you better control the layout of your website by organizing it into boxes. CSS Grid is newer and adds even more flexibility, but is not as widely implemented yet.