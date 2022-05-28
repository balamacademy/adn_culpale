# El Ahorcado
Desarrolle un programa para jugar al popular juego **elahorcado**, el cual consiste en un personaje, el cual está a punto de ser ejecutado.

Para salvarlo es necesario adivinar una palabra, de la cual sólo se conoce su longitud. El jugador debe ir eligiendo letra por letra, de modo de ir completando la palabra.

Si el jugador se equivoca en una letra, es decir, la letra seleccionada no pertenece a la **palabra** a adivinar, el personaje pierde alguna parte de su cuerpo (un brazo, una pierna, el tronco, etc).

Se puede jugar hasta que el personaje pierda la cabeza, el último resto de su trágica vida.

Lea cada letra de la palabra que debe adivinarse en elementos sucesivos de un string llamado palabra. El jugador debe adivinar las letras que pertenecen a la palabra y el programa debe terminar cuando todas las letras se hayan adivinado, es decir, ganar el juego, o bien se haya cometido un número establecido de desaciertos, es decir, gana el computador.

Observaciones:

- Utilice un string para anotar las soluciones.
- La palabra a adivinar la pueden poner fija o ingresarla al inicio del programa.
- Asigne el caracter “_” a cada elemento del string, y cada vez que se adivine una letra, substituya el caracter por la letra correspondiente.
- El programa debe realizarse utilzando **funciones**
- Considere las siguientes partes del cuerpo del **ahorcado**:
  - pierna derecha
  - pierna izquierda
  - brazo derecho
  - brazo izquierdo
  - tronco
  - cabeza

```
Ingrese la palabra: caramelo
Comienza el juego!
" _ _ _ _ _ _ _ _ "
Ingrese letra: a
" _ a _ a _ _ _ _ "
Ingrese letra: e
" _ a _ a _ e _ _ "
Ingrese letra: i
Pierde "pierna derecha"
Ingrese letra: o
" _ a _ a _ e _ o "
Ingrese letra: b
Pierde "pierna izquierda"
Ingrese letra: c
" c a _ a _ e _ o "
Ingrese letra: d
Pierde "brazo derecho"
Ingrese letra: f
Pierde "brazo izquierdo"
Ingrese letra: g
Pierde "tronco"
Ingrese letra: h
Pierde "cabeza"

Haz perdido el juego!
```
