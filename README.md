# Practicas
Encabezados 
# Titulo 1
## Titulo 2
### Titulo 3
#### Titulo 4

# Citas

Para resaltar una cita usamos el símbolo  mayor que “>” antes del texto:

> "El que no sirve para servir no sirve para vivir" Maria Teresa de Calculta 

# Cursiva & Negrita

Agregamos un asterisco  “*” antes y después de la palabra o frase que queremos resaltar para cursiva y dos para negrita “**”:

*Github*
**Github**

# Listas

Para los elementos de listas no ordenadas utilizamos  el asterisco “*“:
* Primer Punto 
* Segundo Punto
* Tercer Punto 

Para las listar ordenadas indicamos el número del elemento con un punto:

1. Primer Punto 
2. Segundo Punto 
3. Tercer Punto 

# Enlaces 

Para añadir un enlace a nuestro documento ponemos el texto del enlace entre corchetes y la url del enlace entre paréntesis:

[Google](https://www.google.com)

# Imagenes 

Para incluir imágenes utilizamos el símbolo de exclamación “!” y entre corchetes el texto alternativo de la imagen seguido entre paréntesis de la url de la imagen:

![animales](https://reviblog.net/wp-content/uploads/2018/06/IMG_20180608_104752.jpg)

# Lista de Tareas  📝

- [x] Completed task
- [ ] Incomplete task
  - [ ] Sub-task 1
  - [x] Sub-task 2
  - [ ] Sub-task 3

1. [x] Completed task
1. [ ] Incomplete task
   1. [ ] Sub-task 1
   1. [x] Sub-task 2

# Tabla ✒️

| Left Aligned | Centered | Right Aligned | Left Aligned | Centered | Right Aligned |
| :---         | :---:    | ---:          | :----------- | :------: | ------------: |
| Cell 1       | Cell 2   | Cell 3        | Cell 4       | Cell 5   | Cell 6        |
| Cell 7       | Cell 8   | Cell 9        | Cell 10      | Cell 11  | Cell 12       |


# Delimitadores :page_facing_up:
* YAML(---):
```
---
title: About Front Matter
example:
language: yaml
---
```
* TOML ( +++):

```
+++
title = "About Front Matter"
[example]
language = "toml"
+++
```

* JSON ( ;;;):

```
;;;
{
  "title": "About Front Matter"
  "example": {
    "language": "json"
  }
}
;;;
```

* PHP (---php)

```
---php
$title = "About Front Matter";
$example = array(
  'language' => "php",
);
---
```

# Diferencia de Lineas 

Las etiquetas de envoltura pueden ser llaves o corchetes:

`- {+ addition 1 +}`
`- [+ addition 2 +]`
