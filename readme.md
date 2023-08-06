## CSS LAYOUT PROPERTIES & UNIT NOTE

### 1. CSS FLEX
- display: ` flex;`
- flex-direction:` row | column | row-reverse | column-reverse`
- flex-wrap:` nowrap | wrap`
- flex-flow: ` flex-direction flex-wrap`
- justify-content:`flex-start | flex-end | center | space-between | space-evenly | space-around`
- align-items:` flex-start | flex-end | center`
- align-content:` flex-start | flex-end | center | space-between | space-evenly | space-around`
- aign-self:` flex-start | flex-end | center`
- flex-grow: `0, 1, 2, 3,...`
- flex-shrink: `1, 2, 3,...`
- flex-basis: `..px | ..% | ...`
- flex: `flex-grow flex-shrink flex-basis`
- order: ` ...-3, -2 -1 0 1, 2, 3 ...`
- row-gap: `...px | ..% | ...`
- column-gap: `...px | ..% | ...`
- gap: `row-gap colum-gap` `// Example: gap: 10px 20px`
- gap: `10px;`  `// Means: row-gap = 10px and column-gap = 10px`

### 2. CSS GRID
- display: `grid`
- grid-template-columns:`none | ...px | ...em | ...% | ...fr | ...`
- grid-template-columns: `repeat(time, ...px | ...em | ...% | ...fr | ...)`
- grid-template-columns: `minmax(minValue, maxValue)`
- grid-template-columns: `fit-content(...px | ...em | ...% | ...fr | ...)`
- grid-template-rows: `none | auto | ...px | ...em | ...% | ...fr | ...`
- grid-template-rows: `repeat(time, ...px | ...em | ...% | ...fr | ...)`
- grid-template-rows: `minmax(minValue, maxValue)`
- grid-template-rows: `fit-content(...px | ...em | ...% | ...fr | ...)`
- grid-template-areas: `none`
- grid-template-areas: `"a b b"` `// Example: 3 columns`
- grid-template-areas: <br/> `"a b b"` <br/> `"a c d"` `  // Example: 2 rows 3 columns`
- grid-area: `your_grid_area_name`
- grid-row:  `...px | ...em | ...% | ...fr | ...`
- grid-row-start:  `...px | ...em | ...% | ...fr | ...`
- grid-row-end: `...px | ...em | ...% | ...fr | ...`
- grid-column: `...px | ...em | ...% | ...`
- grid-column-start:  `...px | ...em | ...% | ...fr | ...`
- grid-column-end: `...px | ...em | ...% | ...fr | ...`
- grid-auto-columns: `auto | ...px | ...em | ...% | ...fr | ...`
- grid-auto-columns: `min-content | max-content | fit-content(...px | ...fr. | ...% | ...)`
- grid-auto-columns: `minmax(minvalue, maxvalue)`
- grid-auto-rows: `auto | ...px | ...em | ...% | ...fr | ...`
- grid-auto-rows: `min-content | max-content | fit-content(...px | ...fr. | ...% | ...)`
- grid-auto-rows: `minmax(minvalue, maxvalue)`
- grid-auto-flows: `row | column | dense`
- row-gap: `...px | ..% | ...`
- column-gap: `...px | ..% | ...`
- gap: `row-gap colum-gap` `// Example: gap: 10px 20px`
- gap: `10px;`  `// Means: row-gap = 10px and column-gap = 10px`
- justify-items:` start | center | end | space-between | space-around`
- align-items: ` start | center | end`
- place-items:` start | center | end`
- place-content:` start | center | end`
- justify-content:` start | center | end | space-between | space-around`
- align-content: ` start | center | end | space-between | space-around`

### 3. CSS UNIT
#### Absolute Units
- Pixel: `px`
- Point: `pt`
- Inch: `in`
- Centimeter: `cm`
- Millimeter: `mm`

#### Percentage Units
- Percentage: `%`
#### Relative Units
> Relative to font size
- em
- rem `// root em`
> Relative to view port / document
- vw
- vh
- wmin
- wmax