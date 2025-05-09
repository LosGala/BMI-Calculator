# BMI Calculator App

Este es un calculador de índice de masa corporal (BMI) desarrollado utilizando `Shiny` y `ShinyThemes` en R. La aplicación permite al usuario ingresar su altura y peso, y luego calcular y mostrar el BMI correspondiente en una tabla.

## Requisitos

Para ejecutar esta aplicación, necesitarás tener instaladas las siguientes bibliotecas en R:

- `shiny`
- `shinythemes`

Puedes instalar estas bibliotecas utilizando el siguiente comando en R:

```r
install.packages(c("shiny", "shinythemes"))
Instrucciones de uso
Interfaz de usuario
La aplicación consta de dos paneles principales:

Home (Página principal):

En esta sección, puedes ingresar tus parámetros de entrada:

Altura: Control deslizante para ajustar la altura en centímetros (entre 40 y 250 cm).

Peso: Control deslizante para ajustar el peso en kilogramos (entre 20 y 100 kg).

Submit: Botón para enviar los datos y calcular el BMI.

Al presionar el botón Submit, el BMI se calculará y se mostrará en una tabla.

Además, un cuadro de texto de estado te indicará si la aplicación está lista para calcular o si ya se ha realizado el cálculo.

About (Acerca de):

En esta sección, puedes encontrar información sobre la aplicación. Está escrita en un archivo markdown llamado about.md.

Salida
Una vez que se ingresen los valores de altura y peso y se presione el botón de envío, se mostrará lo siguiente:

Estado/Salida: Un texto que indica si la calculadora ha completado el cálculo o está lista para uno nuevo.

Tabla de resultados: Una tabla con el valor del BMI calculado.

Funcionamiento
El BMI se calcula utilizando la fórmula:

ini
Copiar
Editar
BMI = peso / (altura en metros)^2
El valor resultante del cálculo de BMI se mostrará en una tabla en la interfaz de usuario.

Ejemplo
Abre la aplicación.

Ajusta la altura y el peso según tus datos.

Haz clic en el botón Submit.

Verás el cálculo de tu BMI y el mensaje de "Cálculo completo."

