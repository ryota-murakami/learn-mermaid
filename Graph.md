https://mermaid-js.github.io/mermaid/#/flowchart

### A node(default)

```mermaid
flowchart LR
    id
```

### A node with text

```mermaid
flowchart LR
    id1[this is the text in the box]
```

## Graph

```mermaid
flowchart TD
    Start --> Stop
```

```mermaid
flowchart LR
    Start --> Stop
```

## Node shapes

### A node with round edges

```mermaid
flowchart LR
    id1(this is the text in the box)
```

### A stadium-shaped node

```mermaid
flowchart LR
    id([This is the text in the box])
```

### A node in a subroutine shape

```mermaid
flowchart LR
    id1[[This is the text in the box]]
```

### A node in a cylindrical shape

```mermaid
flowchart LR
    id[(Database)]
```

### A node in the form of a circle

```mermaid
flowchart LR
    id((This is the text in the circle))
```

### A node in an asymmetric shape

```mermaid
flowchart LR
    id>This is the text in the box]
```

### A node(rhombus)

```mermaid
flowchart LR
    id1{This is the text in the box}
```

### A hexagon node

```mermaid
flowchart LR
    id1{{This is the text in the box}}
```

### Parallelogram

```mermaid
flowchart TD
    id[/This is the text in the box/]
```

### Parallelogram alt

```mermaid
flowchart TD
    id[\This is the text in the box\]
```

### Trapezoid

```mermaid
flowchart TD
    A[/Christmas\]
```

### Trapezoid alt

```mermaid
flowchart TD
    B[\Go shopping/]
```
