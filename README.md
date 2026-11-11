# salary-exchange-calculator

Calculadora para quienes ganan en dólares y gastan en su moneda local. Es un solo `index.html`: se abre en el navegador, sin instalar nada.

## Qué hace

**¿Convierto o espero?**
Pones tu monto en USD y la tasa de hoy, mueves la tasa futura esperada (±30%) y ves cuánto recibirías. Si tu plataforma te deja fijar la tasa de hoy pagando una comisión, la comparación te dice cuándo conviene y cuál es la tasa de equilibrio.

**¿Cuánto he perdido?**
Pones tu salario y la fecha en que empezaste (o la de tu último aumento). Te muestra cuánto recibías entonces y cuánto recibes hoy, cuánto pierdes al mes y al año, el cambio en tu poder de compra con inflación incluida, y qué salario necesitarías para quedar igual que al empezar.

## Detalles

- **TRM automática para COP**: trae la TRM oficial de la Superintendencia Financiera desde [datos.gov.co](https://www.datos.gov.co/Econom-a-y-Finanzas/Tasa-de-Cambio-Representativa-del-Mercado-TRM/32sa-8pi3), la de hoy y la de cualquier fecha pasada. Si escribes una tasa a mano, se respeta. Para otras monedas, escríbela a mano.
- **Spread de la plataforma**: Deel, Payoneer y los bancos suelen pagarte 1–3% por debajo de la tasa oficial. Ponlo para ver lo que de verdad te llega.
- **Recuerda tus datos** solo en tu navegador (localStorage). No se envía nada a ningún servidor.

No es recomendación financiera ni una predicción de tasas de cambio.
