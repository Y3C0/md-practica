# MarkDown

## Encabezados o Títulos

Mediante el carácter almohadilla # podemos crear encabezados
de forma extremadamente sencilla.

Markdown permite crear títulos o encabezados de nivel uno, dos, tres, cuatro,
cinco y seis de forma extremadamente sencilla.

Para crear un encabezado de nivel 1 escribimos una almohadilla # seguido de un
espacio y el nombre que queremos para el encabezado:

###### *Ejemplo:*

```MarkDown
# Titulo 1
## Titulo 2
### Titulo 3
#### Titulo 4
##### Titulo 5
###### Titulo 6
```
###### *Resultado:*

# Titulo 1
## Titulo 2
### Titulo 3
#### Titulo 4
##### Titulo 5
###### Titulo 6

---

## Citar

Para incluir una cita tenemos que usar el símbolo > seguido de un espacio antes
del texto que queremos citar. Por lo tanto, si quiero citar
un comentario y replicarlo deberíamos usar el siguiente código:

###### *Ejemplo:*

```MarkDown
> Linux es el sistema operativo mas chingon!!

Total mente de acuerdo!!
```

###### *Resultado:*

> Linux es el sistema operativo mas chingon!!

Total mente de acuerdo!!

---

## Listas

### Listas desordenadas

Mediante el símbolo * o – podemos crear listas.

###### *Ejemplo:*

```MarkDown
* Lunes
- Martes
* Miércoles
- Jueves
* Viernes
```
###### *Resultado:*

* Lunes
- Martes
* Miércoles
- Jueves
* Viernes

---

### Listas Ordenadas

Para obtener listados ordenados numéricamente tenemos que escribir un
número seguido de un punto y un espacio antes de comenzar a escribir


###### *Ejemplo:*

```MarkDown
1. Positivo
2. Negativo
3. Neutro
```

###### *Resultado:*

1. Positivo
2. Negativo
3. Neutro

---

## Anidar Listas

Para anidar una lista tan solo tenemos que incluir un espacio presionando la
tecla Tab (Tabulador).

###### *Ejemplo:*

```MarkDown
- Lunes
  1. Mañana
  2. Tarde
  3. Noche

- Martes
  1. Mañana
  2. Tarde
  3. Noche
```
###### *Resultado:*

- lunes
   1. Mañana
   2. Tarde
   3. Noche
- Martes
   1. Mañana
   2. Tarde
   3. Noche

---

## Separaciones Físicas entre secciones de texto

Entre dos secciones de texto podemos incluir una separación física. Para ello
tenemos que escribir 3 guiones bajos seguidos ___

###### *Ejemplo:*

```MarkDown
Este parrafo es de prueba para mostrar la separación de texto por medio de ___ tres guiones
---
Este es otro párrafo agregado para el ejemplo de Separaciones físicas entre secciones de texto
```

###### *Resultado:*

>Este parrafo es de prueba para mostrar la separación de texto por medio de ___ tres guiones
>
>---
>
> Este es otro párrafo agregado para el ejemplo de Separaciones físicas entre secciones de texto

---

## Estilos al texto

Podemos definir que un texto esté en negrita, cursiva o tachado. Para ello tendremos que utilizar el siguiente código:

| Formato | Código | Resultado |
| --- | --- | --- |
| Negrita | ```**Negrita**``` | **Negrita** |
| Cursiva | ```*Cursiva*``` | *Cursiva* |
| Tachado | ```~~Tachado~~``` | ~~Tachado~~ |
| Negrita + Cursiva | ```***Palabra``` | ***Palabra*** |
| Tachado + Negrita + Cursiva | ```~~**palabra**~~``` | ~~**Palabra**~~ |

---

## Insertar enlaces de texto o descarga

Para incluir enlaces en un texto tenemos que utilizar el siguiente tipo de sintaxis:

```MarkDown
[texto_de_ancla](URL_que_queremos_enlazar_o_enlace_de_descarga)
```
###### *Ejemplo:*

```MarkDown
[Sigueme!!](https://www.facebook.com/yeco13)
```
###### *Resultado:*

[Sigueme!!](https://www.facebook.com/yeco13)

También se puede añadir un título al enlace con la
siguiente sintaxis:

```MarkDown
[texto_de_ancla](URL_que_queremos_enlazar) titulo_del_enlace
```

###### *Resultado:*

[Sigueme!!](https://www.facebook.com/yeco13) Sergio

Ademas puedes agregan tooltype

```MarkDown
[texto_de_ancla](URL_que_queremos_enlazar ”Contenido tooltype”) titulo_del_enlace
```

###### *Resultado:*

[Sigueme!!](https://www.facebook.com/yeco13/”Y3C0”) Sergio Diaz

---

## Insertar Imágenes

El método para insertar imágenes es similar al método para insertar enlaces. La sintaxis es la misma y lo único que tenemos que modificar es:

1. Reemplazar el texto de ancla por el texto alternativo de la imagen.
2. Añadir el símbolo ! al principio de la sintaxis.

###### *Ejemplo:*

```MarkDown
![texto_alternativo_imagen](URL_imagen)
```

###### *Resultado:*

![Yo amo MarkDown](http://mikemclin.net/mmwp/wp-content/uploads/2013/03/markdown-syntax-language.png)

>Nota: La url puede ser una dirección local o una dirección que apunte a una imagen alojada en un servidor web.

### Insertar Imágenes con tooltype

```MarkDown
![texto_alternativo_imagen](URL_imagen "Texto tooltype")
```

###### *Resultado:*

![Yo amo MarkDown](http://mikemclin.net/mmwp/wp-content/uploads/2013/03/markdown-syntax-language.png "MarkDown es lo mejor!!")

La imagen siempre se insertará en tamaño real. Si la queremos redimensionar lo deberemos hacer en función del editor de markdown que usemos. Muchos editores de Markdown permitirán redimensionar las imágenes mediante código html.

### Simplificar la creación de enlaces e inserción de imágenes

Escribiremos un texto y cada vez que aparezca una palabra que queramos enlazar la pondremos entre corchetes:

```MarkDown
[Enlace] Espacio para comentarios sobre el enlace
```

Una vez finalizado el texto, al final del documento definiremos los enlaces del siguiente modo:

```MarkDown
[Enlace]: http://www.my-enlace.com
```

###### *Ejemplo:*

[Zaid Oigres] Pagina Personal de Sergio Diaz

[Zaid Oigres]: https://www.facebook.com/yeco13/

### Insertar imágenes de forma simple y ordenada

Si tenemos que insertar una imagen en varias partes del documento podemos escribir simplemente el texto alternativo de la imagen del siguiente modo:

```MarkDown
![insertando imágenes]
```
###### *Resultado:*

![insertando imágenes]

Al final del documento definiremos la URL de la imagen del siguiente modo:

```MarkDown
[insertando imágenes]: https://upload.wikimedia.org/wikipedia/commons/thumb/5/51/Octicons-markdown.svg/1024px-Octicons-markdown.svg.png
```

[insertando imágenes]: https://upload.wikimedia.org/wikipedia/commons/thumb/5/51/Octicons-markdown.svg/1024px-Octicons-markdown.svg.png

---

## Insertar cajas de código

Markdown permite incluir cajetines de código en cualquier lenguaje de programación. Para ello tan solo tenemos que seguir el siguiente procedimiento:

1. Antes de iniciar el código escribimos tres acentos abiertos  ``` ` ` ` ``` seguido del nombre del lenguaje que queremos insertar en el cajetín.

2. Presionamos enter y escribimos el código.

3. Para cerrar el cajetín volveremos a escribir tres acentos abiertos ``` ` ` ` ``` .

###### *Ejemplo:*

```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Hola Mundo</title>
  </head>
  <body>
    <h1>Hola Mundo!!</h1>
  </body>
</html>
```

### Resaltar código dentro de un texto párrafo

Para resaltar código dentro de una frase tenemos que usar el símbolo de acento grave o abierto `. Por lo tanto, para resaltar código tan solo tengo que poner entre acentos graves

###### *Ejemplo:*

El comando para buscar actualizaciones para distribuciones basadas en debian es: `apt update`,

Comando para listar las actualizaciones disponibles: `apt list --upgradable`

Comando para actualizar las aplicaciones: `apt upgrade`

 ---
 
