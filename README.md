CSS Grid
Grid-based layout, two-dimensional system

Example makes dynamic auto-fill grid:

.image-gallery {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  grid-gap: 10px;
}

Example makes 5 x 5 grid, where each column and each row is divided into 5 parts each filling 20% of the column and row, respectively:

.image-gallery {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
  grid-gap: 10px;
}
Example makes 3x3 grid, where each column is divided into 3 fractional units and each row is divided into 3 fractional units:

.image-gallery {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-template-rows: 1fr 1fr 1fr;
  grid-gap: 10px;
}

grid-template is another way to generate your grid, and it combines both grid-template-columns and grid-template-rows

You can also target specific elements within the grid and specify where there should start/end via: grid-column-start, grid-column-end, grid-row-start, grid-row-end, grid-column, grid-row, grid-area

CSS transitions

https://cubic-bezier.com/#.17,.67,.83,.67
