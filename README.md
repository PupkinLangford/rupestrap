# Rupestrap

<div align="center">A CSS grid-based framework modeled after Bootstrap. </div>

## Grid
Use the `.container` class to create a grid. Each grid is 12 units wide, and fills the width of its parent.

### Columns
 Use the `col-{numColumns}` and `.col-{size}-{numColumns}` classes to define columns of `numColumns` units of width, which collapse to 12 units when their respective `size` breakpoint is hit. 

#### Breakpoints:
* md breakpoint: 768px.
* lg breakpoint: 992px.

### Column Gap

Use the `.gap-{number}` class to add a grid-column-gap of `number` pixels. The `.gap-sm` class defines a gap of 10px. The `.gap-md` class defines a gap of 25px. The `.gap-lg` class defines a gap of 50px.

### Alignments

Use the `.align-{alignment}` class to set the align-content value of the container. Supported alignment classes include:
* `align-start`
* `align-end`
* `align-center`
* `align-stretch`
* `align-space-around`
* `align-space-between`
* `align-space-evenly`