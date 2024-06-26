# CONCEPTOS IMPORTATES CSS

## SELECTORES

### SELECTOR DE ETIQUETA

```
h1{
  color: #fff;
}
```

### SELECTOR DE DESCENDENCIA

```
nav ul li {
  color: #fff;
}
```

## HERENCIA

```
.container {
    line-height: 1.5; /* Espaciado entre líneas para el contenedor */
}

p {
    /* Los párrafos dentro de .container heredan el espaciado entre líneas */
    margin-bottom: 10px;
}
```

## CASCADA

```
h1{
  color: red;
}

h1{
  color: blue;
}
```

## ESPECIFIDAD

- !important --> 1,0,0,0,0
- inline --> 0,1,0,0,0
- id --> 0,0,1,0,0
- clase --> 0,0,0,1,0
- etiqueta --> 0,0,0,0,1

## UNIDADES DE MEDIDA

- px --> toma la medida asignada por nosotros
- rem --> toma la medida de la etiqueta html (16px)
- em --> toma la medida del padre directo
- vh --> representa un porcentaje de la altura de la ventana
- vw --> representa un porcentaje del ancho de la ventana

## TIPOGRAFIA

```
body {
    font-family: Arial, Helvetica, sans-serif;
}
```

## PROPIEDADES DE FUENTES

- font-weight
- font-size
- font-style
- text-transform
- line-height
- letter-spacing
- word-spacing
- text-align
