# Grid CheatSheet

Here is a small cheatsheet to understands grids in CSS

### Initialize a grid

- in CSS

```css
.exemple{
    display: flex
}
```

- to create rows and columns you can use multiples declaration, you can also use px, em or % for their size

> 5 rows and columns, each being 20% of the parent width / height.
```css
.exemple{
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    grid-template-rows: 20% 20% 20% 20% 20%;
}
```
> same with another way to do it
```css
.exemple{
    display: grid;
    grid-template-columns: repeat(5,20%);
    grid-template-rows: repeat(5,20%);
}
```
- the fr unit make the affect columns or row take a fraction of the free space
> the two columns will take 1/3 and 2/3 of the space,
while the rows take 5/7 and 2/7
```css
.exemple{
    display: grid;
    grid-template-columns: 1fr 2fr;
    grid-template-rows: 5fr 2fr;
}
```
