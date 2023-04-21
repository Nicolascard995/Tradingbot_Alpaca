## Bollinger Trading Bot

Este código es un ejemplo de un bot de trading basado en las bandas de Bollinger que utiliza la biblioteca Alpaca Trade API para realizar operaciones en el mercado de valores.

## Requisitos
Para utilizar este código, necesitarás tener instalado en tu computadora lo siguiente:

Python 3.x
La biblioteca pandas
La biblioteca alpaca_trade_api
También necesitarás una cuenta en la plataforma de trading de Alpaca y tus claves de API y clave secreta.

## Cómo usar
Para utilizar este bot de trading, primero deberás establecer una lista de acciones en la que deseas invertir. Puedes hacerlo editando el archivo y agregando o eliminando acciones en la lista stock_list. A continuación, ejecuta el archivo main.py y espera a que el bot realice operaciones de compra y venta de acciones.

El bot utiliza las bandas de Bollinger para determinar cuándo comprar y vender acciones. Si el precio de una acción cae por debajo del límite inferior de la banda de Bollinger, se activa una señal de compra. Si el precio sube por encima del límite superior, se activa una señal de venta. En cualquier otro caso, el bot no realiza ninguna operación.

## Limitaciones
Este código es solo un ejemplo y no es adecuado para su uso en un entorno de producción. Además, no se garantiza la precisión de las señales de compra y venta generadas por el bot. Es importante tener en cuenta que el mercado de valores es un entorno complejo y que cualquier inversión conlleva ciertos riesgos.

## Contribución
Siéntete libre de clonar y modificar este repositorio para adaptarlo a tus necesidades. Si encuentras algún problema o tienes alguna sugerencia para mejorar el código, no dudes en abrir un problema o enviar una solicitud de extracción.
