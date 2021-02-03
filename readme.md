## for Grid Container

1. display: grid
2. grid-template-column: c1 c2 c3 ......cn
3. grid-template-row: r1 r2 r2 .......rn
4. grid-column-gap: 10px;
5. grid-row-gap: 5px;
6. grid-gap: grid-row-gap grid-column-gap

## for Grid Item

### consume multiple columns to one single column

7. grid-column: 1 / 3; start from 1 end to 3 line

### consume multiple rows to one single row

8. grid-row

### Align an Item Horizontally using justify-self

9. justify-self: start/end/center

### Align an Item Vertically using align-self

10. align-self: start/end/center;

### Align All Items Horizontally using justify-items

11. justify-items: center;

### Align All Items Vertically using align-items

12. align-items: center;

### Divide the Grid Into an Area Template

    1. You can group cells of your grid together into an area and give the area a custom name.

13. grid-template-areas:
    "header header header"
    "advert content content"
    "footer footer footer";

### Place Items in Grid Areas Using the grid-area Property

14. grid-area: header;
