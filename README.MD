# Version del curso
Version Actual: v1.2.2

# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
-----------

Underline 2
===========

# Formatos de énfasis
- Letra *itálica* de la primera forma.
- Letra _itálica_ de la segunda forma.
- Formato **bold o strong** de la primera forma.
- Formato __bold o strong__ de la segunda forma.
- Formato ~~tachado~~ forma normal.
- Aquí podemos usar *formato itálico*, pero también **bold** y ~~tachado~~.

# Listas
1. Esto es un ítem de lista ordenada.
2. Esto es un ítem de lista ordenada.
3. Esto es un ítem de lista ordenada.
- Esto es un ítem de lista desordenada.
- Esto es un ítem de lista desordenada.
- Esto es un ítem de lista desordenada.

# Links
- <a href="https://www.google.com"> Esto es un link HTML</a>
- [Esto es un link en Markdown](https://www.google.com)
- [Esto es un link al Index](index.html)

# Imágenes
![Logo Github](https://cdn.pixabay.com/photo/2022/01/30/13/33/github-6980894_960_720.png)

# Code Snippets
Código en JSON
```JSON
[
    {
	    "type": "basket",
	    "beans": 47,
	    "apples": 7,
	    "oranges": 23,
	    "brand": "ConvertSimple",
	    "ratio": 33.9,
	    "fees": {
		    "cleaning": "$4.50",
		    "baking": "$27.30",
		    "commission": "$93.10"
	    },
	    "descriptors": ["clean", "fresh", "juicy", "delicious"]
    }
]
```
Otro código en JSON
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
| Maxi   | Burgos   | 3546481   |
| Tomás  | Tompson  | 3243243   |

# Citas
Esto es un texto referente a una cita que escribiremos debajo:
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior.
> Esto es otra cita.

# Líneas Divisorias
Esto es un texto que sera dividido por guiones medios.

---
Esto es otro texto dividido por asteriscos.

***

Esto es otro texto dividido por guiones bajos.

# Saltos de Línea
Esto es nuestro primer párrafo.

Esto es nuestro segundo párrafo.

Esto es nuestro tercer párrafo.
- Lista