# MarkDown

## Encabezados o Títulos

Mediante el carácter almohadilla # podemos crear encabezados
de forma extremadamente sencilla.

Markdown permite crear títulos o encabezados de nivel uno, dos, tres, cuatro,
cinco y seis de forma extremadamente sencilla.

Para crear un encabezado de nivel 1 escribimos una almohadilla # seguido de un
espacio y el nombre que queremos para el encabezado:

##### Ejemplo:

```MarkDown
# Titulo 1
## Titulo 2
### Titulo 3
#### Titulo 4
##### Titulo 5
###### Titulo 6
```
##### Resultado:

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

##### Ejemplo:

```MarkDown
> Linux es el sistema operativo mas chingon!!

Total mente de acuerdo!!
```

##### Resultado:

> Linux es el sistema operativo mas chingon!!

Total mente de acuerdo!!

---

## Listas

### Listas desordenadas

Mediante el símbolo * o – podemos crear listas.

##### Ejemplo:

```MarkDown
* Lunes
- Martes
* Miércoles
- Jueves
* Viernes
```
##### Resultado:

* Lunes
- Martes
* Miércoles
- Jueves
* Viernes

---

### Listas Ordenadas

Para obtener listados ordenados numéricamente tenemos que escribir un
número seguido de un punto y un espacio antes de comenzar a escribir


##### Ejemplo:

```MarkDown
1. Positivo
2. Negativo
3. Neutro
```

##### Resultado:

1. Positivo
2. Negativo
3. Neutro

---

## Anidar Listas

Para anidar una lista tan solo tenemos que incluir un espacio presionando la
tecla Tab (Tabulador).

##### Ejemplo:

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
##### Resultado

- lunes
   1. Mañana
   2. Tarde
   3. Noche
- Martes
   1. Mañana
   2. Tarde
   3. Noche

---

### Separaciones Físicas entre secciones de texto

Entre dos secciones de texto podemos incluir una separación física. Para ello
tenemos que escribir 3 guiones bajos seguidos ___

##### Ejemplo:

```MarkDown
Este parrafo es de prueba para mostrar la separación de texto por medio de ___ tres guiones
---
Este es otro párrafo agregado para el ejemplo de Separaciones físicas entre secciones de texto
```

##### Resultado:

>Este parrafo es de prueba para mostrar la separación de texto por medio de ___ tres guiones
>
>---
>
> Este es otro párrafo agregado para el ejemplo de Separaciones físicas entre secciones de texto

---

### Estilo al texto

Podemos definir que un texto esté en negrita, cursiva o tachado. Para ello tendremos que utilizar el siguiente código:

| Formato | Código | Resultado |
| --- | --- | --- |
| Negrita | ```**Negrita**``` | **Negrita** |
| Cursiva | ```*Cursiva*``` | *Cursiva* |
| Tachado | ```~~Tachado~~``` | ~~Tachado~~ |
| Negrita + Cursiva | ```***Palabra``` | ***Palabra*** |
| Tachado + Negrita + Cursiva | ```~~**palabra**~~``` | ~~**Palabra**~~ |
