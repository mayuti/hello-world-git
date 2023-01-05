# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# 
# Underlines 
Underline 1
--------------

Underline 2
============

# Formatos de enfasis

- Formato *italica* de la primer forma.
- Formato _italica_ de la segunda forma.
- Formato **bold o strong** de la primer forma.
- Formato __bold o strong__ de la segunda forma.
- Formato ~~tachado~~, formato normal.
- Aqui podemos usar *Italica*, pero también
**bold** y ~~tachado~~.

# Listas
1. Esto es un item de lista orenada.
2. Esto es un item de lista orenada.
3. Esto es un item de lista orenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links
- <a href="http://www.google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://wwww.google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Git](https://upload.wikimedia.org/wikipedia/commons/3/3f/Git_icon.svg)

# Code Snippets
Codigo en JSON
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```

Código en Javascript
```Javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```
# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Cristian | Mayuti | 12345678 |
| Andres | García | 87654321 |

# Citas
Esto es un texto referente a una cita:
> Esto es una cita.

Este es otro texto no relacionado con la cita anterior:
> Esto es otra cita

# Lineas Divisorias
Este es un texto que será dividido por guiones medios

---
Este es otro texto dividido por asteriscos

***
Este es otro texto dividido por guiones bajos

___

# Saltos de línea
Esto es el primer párrafo

Esto es el segundo párrafo

Esto es el tercer párrafo
- Lista
