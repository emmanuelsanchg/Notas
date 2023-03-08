# Aprendiendo Markdown

- [titulos](#titulos)
- [parrafos](#parrafos)
- [formatos](#formato-de-texto)
  - [negritas](#negritas)
  - [cursivas](#cursiva)
  - [citas](#citas)
  - [convinacion de formatos](#convinacion-de-los-formatos)
- [enlaces](#enlaces)
- [imagenes](#imagenes)
- [listas](#listas)
  - [ordenadas](#listas-ordenadas)
  - [desordenadas](#listas-des-ordenadas)
  - [sub-listas](#sub-listas)
- [division de contenido](#divisiones-de-contenido)
- [tablas](#tablas)
- [insercion de codigo](#insertar-codigo)

---

## Titulos

un titulo define el tema que se tratara a continuacion, y podemos generarlos en md con el simbolo \#.

MD tiene 6 niveles de titulos, cada nivel define la inportancia del tema siendo el nivel mas bajo el mas importante y el mas alto el menos importante.

### - codigo

```
# titulo de nivel 1
## titulo de nivel 2
### titulo de nivel 3
#### titulo de nivel 4
##### titulo de nivel 5
###### titulo de nivel 6
```

### - representacion en md

> # titulo de nivel 1
>
> ## titulo de nivel 2
>
> ### titulo de nivel 3
>
> #### titulo de nivel 4
>
> ##### titulo de nivel 5
>
> ###### titulo de nivel 6

---

## Parrafos

los parrafos son el contenido de texto de cualquier documento o archivo y son los mas usados para generar texto.

en md podemos generar parrafos simplemente escribiendo el contenido de la sigueinte manera, no se requiere ningun simbolo.

---

### - codigo

```
este es un parrafo
```

### - representacion en md

> este es un parrafo

podemos agregar infinidad de parrafos y los separamos por un salto de linea.

### - codigo

```
parrafo uno

parrafo dos
texto que pertenece al parrafo 2
```

### - representacion en md

> parrafo uno
>
> parrafo dos
> texto que pertenece al parrafo 2

---

## Formato de texto

dar formato al texto sirve para dar un significado a un grupo de palabras.

en md podemos dar diferentes formatos a nuestros textos.

## Negritas

### - codigo

```
**negritas**

__negritas__
```

### - representacion en md

> **negritas**
>
> **negritas**

---

## Cursiva

### - codigo

```
*cursiva*

_cursiva_
```

### - representacion en md

> _cursiva_
>
> _cursiva_

---

## Citas

### - codigo

```
> cita textual en linea
```

```
> cita textual
>
> en bloque
```

### - representacion en md

> cita textual en linea

> cita textual
>
> en bloque

---

## Tachado

### - codigo

```
~~texto tachado~~
```

### - representacion en md

> ~~texto tachado~~

---

## Convinacion de los formatos

### - codigo

```
**texto en negrita con *cursiva* anidada**

**texto en ~~negrita tachado~~ con _cursiva_ anidada**

__texto en negrita con *cursiva* anidada__
```

### - representacion en md

> **texto en negrita con _cursiva_ anidada**
>
> **texto en ~~negrita tachado~~ con _cursiva_ anidada**
>
> **texto en negrita con _cursiva_ anidada**

---

## Enlaces

los enlaces nos permiten navegar entre las paginas web, y tambien entre documentos.

### - codigo

```
[Ir a Google](https://www.google.com)

[subir al menu](#aprendiendo-markdown)
```

### - representacion en md

[Ir a Google](https://www.google.com)

[subir al menu](#aprendiendo-markdown)

---

## Imagenes

### - codigo

```
![texto alternativo](https://i0.wp.com/www.silocreativo.com/wp-content/uploads/2019/05/typora-temas.jpg?resize=799%2C353&quality=100&strip=all&ssl=1)
```

### - representacion en md

![imagen de codigo en md](https://i0.wp.com/www.silocreativo.com/wp-content/uploads/2019/05/typora-temas.jpg?resize=799%2C353&quality=100&strip=all&ssl=1)

---

## Listas

podemos generar listas numericas o de biñetas, e incluso listas anidadas o sub-listas.

## Listas Ordenadas

### - codigo

```
1. markdown
1. linea de comandos
1. git & github
1. html
1. css
```

### - representacion en md

> 1. markdown
> 1. linea de comandos
> 1. git & github
> 1. html
> 1. css

---

## listas Des-ordenadas

### - codigo

```
- markdown
- linea de comandos
- git & github
- html
- css
```

```
* markdown
* linea de comandos
* git & github
* html
* css
```

### - representacion en md

> - markdown
> - linea de comandos
> - git & github
> - html
> - css

> - markdown
> - linea de comandos
> - git & github
> - html
> - css

---

## Sub-listas

### - codigo

```
- dev wev
  - html
  - css
  - js
- control de versiones
  - git
  - github
```

### - representacion en md

> - dev wev
>   - html
>   - css
>   - js
> - control de versiones
>   - git
>   - github

---

## Divisiones de Contenido

un divisor sirve para indicar cuando emos terminado de tratar un tema y estamos por comenzar a tratar uno nuevo.

### - codigo

```
tema 1

---
tema 2

```

### - representacion en md

> tema 1
>
> ---
>
> tema 2

---

## Tablas

podemos agregar contenido en tablas tipo excel.

### - codigo
```
| Pendiente     | Horario    | Importancia               |
| ------------- | ---------- | ------------------------- |
| Desayunar     | 8am - 9am  | Muy Importante 🚨         |
| Tomar Clases  | 9am - 12pm | Muy Importante            |
| ver peliculas | 12pm - 1pm | medianamente importante ⚠ |
```

### - representacion en md

| Pendiente     | Horario    | Importancia               |
| ------------- | ---------- | ------------------------- |
| Desayunar     | 8am - 9am  | Muy Importante 🚨         |
| Tomar Clases  | 9am - 12pm | Muy Importante            |
| ver peliculas | 12pm - 1pm | medianamente importante ⚠ |

---

# Insertar Codigo
podemos insertar codigo en un texto para dar un ejemplo de uso, en linea y bloque.

### - codigo
- en linea
  - \`let\`
- en Bloque
  - \`\`\` codigo \`\`\`

### representacion en md
`let`

```js
function suma(a,b){
  return a + b
}
```