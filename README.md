# platzom

platzom es un idioma inventado para el curso 
de [fundamentos de platzi](https://platzi.com/js).

## Descripcion

- si la palabra termina en "ar" se le quitan esos dos caracteres
- si la palabra inicia con "z" se le agrega "p" al final
- si la palabra traducida tiene 10 o mas letras,se                                                debe partir a la mitad con un guion en el medio
- si la palabra es un palindromo ninguna regla anterior cuenta y se devuelve la misma palabra intercambiando mayusculas y minusculas

## Instalacion
```
npm install platzom
```

## Uso 

```
import platzom from from 'platzom'

platzom("Programar") // Program
platzom("Zorro") // Zorrope
platzom("Zarpar") // Zarppe
platzom("abecedario") // abece-dario
platzom("sometemos") // SoMeTeMoS
```

## Creditos 
- Hosward Villoria

## Licencia MIT
[MIT](https://opensource.org/licenses/MIT)