## Esto en una página creada con GitHub Pages

En el ejemplo de hoy hacemos una función que recibe una lista con las medidas de los paramentos de un local a reformar y la altura de los mismos, y nos devuelve la superficie total. Esta función se podrá integrar mas adelante en nuestra clase Local(), que nos facilitará la realización de las mediciones de los distintos elementos del local. 

### Markdown

Usamos Markdown para dar estilo a nuestro texto, pero también para escribir código:

```python
import numpy as np
paramentos = [2.35, 1.20, 4.56, 5.67, 9.70, 3.40, 1.40]
altura_local = 2.70 
def mide_paramentos(paramentos, altura_local):
	suma_paramentos=np.around(sum(paramentos), 2)
	superficie_paramentos = np.around(suma_paramentos*altura_local, 2)
	return superficie_paramentos

# si llamamos a la funcion mide_paramentos y le aportamos los datos necesarios nos devuelve la superficie con 2 decimales
mide_paramentos(paramentos, altura_local)
76.36

```


Ejemplos de Markdown:
```
# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/jgbarreda/jgbarreda.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
