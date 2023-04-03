# Grid!

<img src="grid.jpeg" width="80%" alt="grid-image-collected from jonas.io">

# Grid Terminology!

<img src="grid-termonology.jpeg" width="80%" alt="grid-image-collected from jonas.io">

# Grid Overview!

<img src="grid-overview.jpeg" width="80%" alt="grid-image-collected from jonas.io">

### Basic setup

```
display: grid; <br>
grid-template-rows: 150px 150px;<br>
grid-template-columns: 150px 150px 150px;<br>
grid-row-gap: 30px;<br>
grid-column-gap: 30px;<br>
//grid-gap: 30px
```

### Repeat function

```
grid-template-rows: repeat(2, 150px);
```

### Repeat function with custom column size

```
grid-template-columns: repeat(2, 150px) 300px;
```

### Using fractional unit to occupy rest of space of grid container

```
grid-template-columns: repeat(2, 150px) 1fr;
```

### Grid column space with same size (1fr is fraction of available space- we can devide the available space in 3 parts)

```
grid-template-columns: repeat(3, 1fr);
```

### Available space is devided by 5 parts where 1fr for the left 3fr for the middle 1fr for the right column

```
grid-template-columns: 1fr 3fr 1fr;
```

### % unit are acceptable in grid column it's take 50% for grid container not count gutter size of the grid

```
grid-template-columns: 50% 1fr 1fr;
```

### Fractional unit are acceptable in grid row. which is help out to fillout the grid container height

```
grid-template-rows: repeat(2, 1fr);
```

### Manipulate the grid cell

```
grid-row-start: 2;
grid-row-end: 3;
grid-column-start: 2;
grid-column-end: 3;

```

---

**_Short hand syntax grid row start line 2 end 3, grid column start line 2 end 3_**

```
grid-row: 2/3;
grid-column: 2/3;
```

**_ Another Short hand _**

```
//line number to start / column number to start / line where it ends / column where it ends
grid-area: 1 / 3 / 2 / 4;
```
