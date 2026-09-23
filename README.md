Taller integrador individual - CARLOS ESTEBAN REALES GAMEZ

| Defecto encontrado | Porque era un problema | Como lo corrigió |
|---|---|---|
| Nombres de archivo "Mi Pagina De Notas.HTML" y "Estilos Del Sitio.CSS". | Tenían espacios y mayúsculas sueltas, lo que no sigue la convención de nombres de archivo. | Renombre los archivos a "index.html" y "estilos.css", en kebab-case. |
| Variable "x". | No indicaba qué representaba, obligaba a leer todo el código para entenderla. | Renombrada a "cantidadNotas". |
| Variable "TempValue2". | Nombre que no describe su contenido (promedio calculado). | Renombrada a "promedio". |
| Variables "a", "b", "c". | Nombres de una sola letra que no dicen qué almacenan. | Renombradas a "nota1", "nota2", "nota3". |
| Función "calc()". | nombre que no explica qué calcula. | Renombrada a "calcularPromedio()". |
| Identificadores HTML "n1", "n2", "n3", "r", "r2". | No son descriptivos, dificultan entender qué representa cada elemento. | Renombrados a "nota1", "nota2", "nota3", "resultadoPromedio", "resultadoEstado". |
| Titulo de pagina "pagina". | No identifica cual es la funcion que cumple el sitio | Cambiado a "Calculadora de Promedio". |
| Función comentada "calcularAntiguo". | Código muerto que no cumple ninguna función y genera confusión. | Eliminada por completo. |
| Variable "data1" sin usar. | Se declaraba un array que nunca se utilizaba en el código. | Eliminada. |
| "console.log" de prueba | Eran mensajes que solo servían para revisar mientras se construía la página, y se quedaron olvidados en el código final. | Eliminados los tres "console.log". |

Link a netify:
https://calculadora-notas-correcion-reales.netlify.app