# Taller integrador individual — Parte A

## Nombre
Mariangell Cabrera Contreras

## Descripción
Auditoría y corrección de una calculadora de promedio de tres notas, aplicando buenas prácticas de desarrollo de software y control de versiones.

## Hallazgos de la auditoría

| Defecto encontrado | Por qué era un problema | Cómo lo corregí |
|---|---|---|
| El archivo HTML se llamaba `Mi Pagina De Notas.HTML` | El nombre contiene espacios y usa mayúsculas, dificultando la consistencia y referencia del archivo. | Se renombró a `index.html`. |
| El archivo CSS se llamaba `Estilos Del Sitio.CSS` | El nombre contiene espacios y mayúsculas innecesarias. | Se renombró a `estilos.css`. |
| El título era `pagina` | No describe correctamente el contenido de la página. | Se cambió a `Calculadora de Promedio`. |
| La función se llamaba `calc()` | El nombre es demasiado genérico y no comunica su propósito. | Se renombró a `calcularPromedio()`. |
| Las variables `a`, `b` y `c` | No permiten identificar qué dato almacena cada una. | Se renombraron a `nota1`, `nota2` y `nota3`. |
| La variable `TempValue2` | Es un nombre poco descriptivo y mezcla una abreviatura con un número. | Se reemplazó por `promedio`. |
| La variable `x` | No explica qué representa dentro del cálculo. | Se reemplazó por el valor `3`, correspondiente a las tres notas. |
| Los identificadores `n1`, `n2` y `n3` | Son poco descriptivos. | Se cambiaron a `nota1`, `nota2` y `nota3`. |
| Los identificadores `r` y `r2` | No indican qué resultado muestran. | Se cambiaron a `resultadoPromedio` y `resultadoEstado`. |
| La clase `cont1` | El nombre no describe la función del contenedor. | Se cambió a `contenedor`. |
| Existía `data1` sin uso | Era una variable declarada que no participaba en ninguna operación. | Se eliminó. |
| Existía una función antigua comentada | Era código muerto que no cumplía ninguna función en la aplicación. | Se eliminó. |
| Había mensajes `console.log()` innecesarios | No aportaban funcionalidad al usuario final y eran restos de depuración. | Se eliminaron. |

## Sitio publicado
https://taller-integrador-cabrera.netlify.app


