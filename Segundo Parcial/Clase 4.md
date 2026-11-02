# Modelos de costeo y decisiones de gestión — Clase 08/10/2026

En el parcial probablemente haya que armar un estado de resultados (no todo será verdadero/falso o multiple choice). La TIR no se calcula en el parcial: alcanza con saber su definición. Parcial estimado: 19 de noviembre.

## Cierre de la clase anterior

### Estado de resultados: repaso

El estado de resultados es una herramienta **económica**, no financiera: una venta hecha en diciembre de 2026 y cobrada en enero de 2027 impacta en el P&L de 2026.

```
  Ingresos
− Costos (OPEX)
= Resultado bruto          → margen bruto = resultado bruto / ingresos
− Gastos (OPEX)
= EBITDA
− Amortizaciones (CAPEX)
= EBIT (resultado operativo)
± Resultados financieros
− Impuestos (sobre EBIT ± resultados financieros)
= Resultado neto
```

OPEX son los gastos cotidianos del período; CAPEX son gastos puntuales, en general inversiones.

### Amortizaciones según el tipo de bien

Cada inversión se prorratea según la **vida útil** del bien. Equipos de computación y software se amortizan en 3 años; rodados en 5; instalaciones, maquinarias y muebles y útiles en 10. Por ejemplo, $10.000 en notebooks impactan $3.333 por año en un P&L anual, o $278 por mes en uno mensual; $10.000.000 en equipos de aire acondicionado (instalaciones) impactan $1.000.000 por año.

### Control presupuestario

Es la etapa de control del proceso administrativo aplicada al presupuesto: evaluar la gestión y detectar los desvíos en cada línea (ingresos, costos, amortizaciones, gastos, impuestos). Variaciones típicas:

- **Volumen**: menos clientes o unidades vendidas.
- **Precio**: precio promedio menor, por ejemplo por más competencia o importaciones.
- **Ejecución**: lanzamiento demorado (se proyectaba vender desde enero y se empezó en marzo).
- **Contexto**: caída del mercado. Las premisas externas no se cumplieron; en una recesión suele haber desvío tanto de precio como de volumen.

El presupuesto del año siguiente suele empezar a armarse entre agosto y octubre.

### Reforecast

Es ajustar las proyecciones del presupuesto inicial a la realidad actual y construir un nuevo escenario. Ante un cambio fuerte de premisas, por ejemplo una devaluación que dispara los costos dolarizados y obliga a redefinir precios, no tiene sentido sostener un presupuesto que ya se sabe que no se va a cumplir. Sirve para actualizar ingresos, costos y resultados, y para mejorar la precisión del control presupuestario.

## Clasificación de costos según su comportamiento

- **Costos variables**: cambian con el volumen de actividad (materia prima: no es lo mismo producir 1.000 que 2.000 remeras).
- **Costos fijos**: no cambian dentro de un rango de actividad (el alquiler del galpón es el mismo si se producen una o 5.000 remeras, mientras no se supere la capacidad).
- **Costos semivariables**: tienen una parte fija y una parte variable (un servicio de seguridad con abono fijo que factura un adicional por cada turno extra).

## Otros conceptos de costos

**Costo hundido.** Es un costo que ya se realizó y que no se va a recuperar. Figura en los estados contables, pero **no debe influir en las decisiones de negocio** futuras: por ejemplo, lo que se pagó para desarrollar el botón de pago de una web no cambia la decisión de qué marcas vender. Solo es relevante para analizar el repago de esa inversión.

**Costo de oportunidad.** Es lo que se deja de ganar por elegir una alternativa en lugar de otra. Si alguien gana $100.000 por día manejando un Uber y decide no trabajar ese día, su costo de oportunidad es $100.000; si en cambio trabaja en otro lugar por $50.000, eligió una alternativa menor a su costo de oportunidad.

## Modelos de costeo

Un modelo de costeo es una forma de organizar y asignar los costos. El mismo negocio puede verse distinto según el modelo que se use.

| | Costeo por absorción | Costeo variable |
|---|---|---|
| **Qué asigna al producto** | Todos los costos de producción: variables (materia prima, mano de obra directa) y fijos de fabricación, repartidos entre las unidades producidas | Solo los costos variables. Los costos fijos son costos del período: van directo al resultado, no al inventario |
| **Objetivo** | Valuar inventarios y determinar el resultado contable | Apoyar decisiones: precio, mezcla de productos, punto de equilibrio |
| **Ventaja** | Cumple normas contables y fiscales | Muestra la contribución marginal de cada producto |
| **Desventaja** | Puede distorsionar el resultado de corto plazo: los fijos se reparten aunque cambie la producción | No se acepta para valuar inventarios contablemente |

### Ejemplo: cuánto cuesta una remera

Una fábrica produce 1.000 remeras por mes y tiene $2.000.000 de costos fijos fabriles.

| Concepto | Por remera |
|---|---|
| Tela | $3.000 |
| Mano de obra directa | $1.500 |
| Otros insumos variables | $500 |
| **Costo variable unitario** | **$5.000** |
| Costo fijo absorbido ($2.000.000 ÷ 1.000) | $2.000 |
| **Costo unitario por absorción** | **$7.000** |

Costeo variable: **$5.000**. Costeo por absorción: **$7.000**. Si produce 2.000 remeras, cada una absorbe $1.000 de fijos y el costo por absorción baja a $6.000: depende del volumen.

## Punto de equilibrio

Es el volumen de ventas en el que los **ingresos cubren todos los costos**, fijos y variables: no se gana ni se pierde. A partir de ahí, cada unidad adicional genera ganancia. Se calcula en unidades (cuántas hay que vender) o en valor (cuánto hay que facturar).

```
En unidades = Costos fijos ÷ (Precio − Costo variable unitario)
En valor    = Costos fijos ÷ (1 − Costo variable unitario ÷ Precio)
```

Ejemplo: precio $50, costo variable unitario $25, costos fijos $12.500.
En unidades: 12.500 ÷ (50 − 25) = **500 unidades**. En valor: 12.500 ÷ (1 − 25/50) = **$25.000**. Control: 500 u × $50 = $25.000.

**Margen de contribución** = precio − costo variable unitario. Es lo que cada unidad aporta para cubrir los costos fijos. En el ejemplo, $25 por unidad: hacen falta 500 para cubrir $12.500.

### Margen de seguridad y capacidad en equilibrio

```
Margen de seguridad       = (Ventas actuales − Ventas de equilibrio) ÷ Ventas actuales
Capacidad en equilibrio   = Ventas de equilibrio ÷ Ventas actuales
```

- **Margen de seguridad**: cuánto podrían caer las ventas antes de entrar en pérdida. Mide el riesgo operativo.
- **Capacidad en equilibrio**: qué proporción de las ventas actuales hace falta solo para cubrir costos.

Margen de seguridad + capacidad en equilibrio = **100%**. Un margen de seguridad bajo indica que una caída chica de ventas lleva a pérdida.

### Ejercicio: equilibrio, margen de seguridad y capacidad

Datos: precio $5 · costo variable unitario $3 · costos fijos $1.000 · volumen de ventas 900 u (ventas actuales = 900 × $5 = $4.500).

| Cálculo | Fórmula | Resultado |
|---|---|---|
| Equilibrio en unidades | 1.000 ÷ (5 − 3) | **500 u** |
| Equilibrio en valor | 1.000 ÷ (1 − 3/5) | **$2.500** |
| Margen de seguridad | (4.500 − 2.500) ÷ 4.500 | **44%** |
| Capacidad en equilibrio | 2.500 ÷ 4.500 | **56%** |

En el gráfico, el costo fijo es una línea horizontal constante; el costo variable crece con las unidades; el costo total es la suma de ambos y parte desde el costo fijo. La línea de ventas cruza al costo total en el punto de equilibrio (500 u, $2.500).

## Gestión financiera: las cuatro decisiones

Administrar los recursos para sostener la operación, invertir en proyectos rentables, elegir cómo financiarse y definir qué hacer con las ganancias.

- **Operación**: gestión diaria de la caja, el capital de trabajo, los costos y el riesgo financiero. Dato clave: presupuesto financiero y control de gestión.
- **Inversión**: asignar recursos a proyectos que maximicen el valor de largo plazo, según flujos, retorno y riesgo. Dato clave: VAN, TIR y período de repago.
- **Financiamiento**: elegir entre capital propio, deuda o una combinación. Define la estructura y el costo de capital. Dato clave: % de endeudamiento, control y tasa de la deuda vs. rentabilidad.
- **Dividendos**: qué parte de las ganancias se reparte (efectivo, acciones, recompras) y qué parte se reinvierte. Dato clave: repartir de más puede indicar falta de proyectos para reinvertir.

## Decisiones de inversión

### Evaluación de proyectos

Es analizar una decisión que requiere **invertir recursos hoy para obtener beneficios futuros**. Si el proyecto es bueno, al aceptarlo la organización pasa a valer más que antes.

Un proyecto no es solo un producto o servicio nuevo: también puede ser una reducción de costos, el reemplazo de máquinas (por una nueva o que ahorre horas de trabajo) o una nueva plataforma o sistema.

Las tres herramientas: **VAN** (valor actual neto), **TIR** (tasa interna de retorno) y **payback** (período de repago).

### Flujo de fondos (cash flow)

Mide los **movimientos de efectivo** en un período. Busca que siempre haya caja disponible y evitar el "bache" o "quiebre de caja". La evaluación de proyectos se mira desde el lado financiero, no económico. En un proyecto de inversión rigen dos reglas:

1. **Es efectivo, en su fecha**: cada valor es plata que entra o sale, ubicada en el momento en que se cobra o se paga. No es el P&L: la amortización no es una salida de caja.
2. **Es incremental**: solo cuenta lo que cambia por hacer el proyecto. Si un ingreso o egreso ocurre igual, se haga o no, no va en el flujo.

Ejemplo de flujo incremental: una zapatería vende 5.000 pares por mes en su local y, tras abrir su tienda online, pasa a 8.000. Para evaluar la tienda online solo cuentan los **3.000 pares adicionales**. Tampoco cuentan los costos hundidos: si un empleado que ya estaba en la estructura se reasigna a la tienda online, su sueldo no entra en la evaluación.

### Valor actual neto (VAN)

Mide cuánto valor genera un proyecto **en pesos de hoy**: trae los flujos futuros al presente con una tasa de descuento (tasa de corte) y les resta la inversión inicial.

```
VAN = Σ Flujo del año t ÷ (1 + r)^t − Inversión inicial
```

**r = tasa de corte**: la rentabilidad mínima que se le exige al proyecto (lo que rendiría la alternativa). En dólares se suele usar un 10% como referencia, porque instrumentos financieros como obligaciones negociables o fondos de inversión rinden entre 4% y 8% sin esfuerzo. En pesos, debería superar al menos la inflación esperada, y en general bastante más, para que valga el esfuerzo de montar el negocio frente a dejar la plata en un plazo fijo.

- **VAN > 0**: genera valor, conviene invertir.
- **VAN = 0**: rinde justo la tasa de corte, indistinto.
- **VAN < 0**: destruye valor, no conviene.

El análisis no es lineal: un VAN positivo pero muy chico puede no justificar el esfuerzo del proyecto.

**Ejemplo:** inversión inicial de $10.000, flujos durante 4 años y tasa de corte del 10%.

| Año | Flujo | Cálculo | Valor actual |
|---|---|---|---|
| 1 | $3.000 | 3.000 ÷ 1,10 | $2.727 |
| 2 | $4.000 | 4.000 ÷ 1,10² | $3.306 |
| 3 | $4.500 | 4.500 ÷ 1,10³ | $3.381 |
| 4 | $5.000 | 5.000 ÷ 1,10⁴ | $3.415 |
| **Suma de valores actuales** | | | **$12.829** |
| − Inversión inicial | | | ($10.000) |
| **VAN** | | | **$2.829** |

VAN positivo: el proyecto crea valor después de recuperar la inversión y pagar el 10% exigido.

### Tasa interna de retorno (TIR)

Es la **tasa de descuento que hace que el VAN sea cero**. Representa la rentabilidad propia del proyecto.

```
0 = Σ Flujo del año t ÷ (1 + TIR)^t − Inversión
```

Se calcula por aproximaciones: con calculadora financiera o en Excel con la función TIR().

- **TIR > tasa de corte**: el proyecto rinde más de lo exigido, conviene.
- **TIR < tasa de corte**: rinde menos que la alternativa, no conviene.

Si VAN y TIR se contradicen al comparar proyectos, manda el VAN.

### Período de repago (payback)

Es el **tiempo que tarda una inversión en recuperar su costo inicial** con los flujos que genera.

```
Flujos uniformes: Inversión inicial ÷ Flujo anual
```

Ajustes posibles:

- **Flujos no uniformes**: se suman los flujos de cada año hasta alcanzar la inversión inicial. Con flujos de $3.000, $4.000 y $4.500, al final del año 2 se acumulan $7.000 y al final del año 3, $11.500: la inversión de $10.000 se recupera durante el tercer año.
- **Repago descontado**: se usan los flujos traídos a valor actual; considera el valor tiempo del dinero.

Es útil como indicador de liquidez y riesgo: cuanto antes se recupera, menos expuesto queda el proyecto. **Limitación:** ignora lo que pasa después del repago.

### Ejercicio: ¿compramos la máquina?

Datos: costo de la máquina $10.000 · flujo neto anual $3.000 · duración de los flujos 5 años · tasa de corte anual 10%.

| Año | Flujo | Acumulado | Valor actual (10%) | VA acumulado |
|---|---|---|---|---|
| 0 | ($10.000) | ($10.000) | ($10.000) | ($10.000) |
| 1 | $3.000 | ($7.000) | $2.727 | ($7.273) |
| 2 | $3.000 | ($4.000) | $2.479 | ($4.793) |
| 3 | $3.000 | ($1.000) | $2.254 | ($2.539) |
| 4 | $3.000 | $2.000 | $2.049 | ($490) |
| 5 | $3.000 | $5.000 | $1.863 | $1.372 |

```
VAN    = 3.000/1,1 + 3.000/1,1² + … + 3.000/1,1⁵ − 10.000 = 11.372 − 10.000 = $1.372
TIR    ≈ 15,2%
Repago = 10.000 ÷ 3.000 = 3,33 años
```

**VAN $1.372 · TIR 15,2% (> 10%) · repago simple 3,3 años · repago descontado 4,3 años.**

¿Conviene? **Sí**: VAN positivo y TIR mayor que la tasa de corte, el proyecto crea valor. El repago simple (3,3 años) es optimista porque no descuenta: con valor tiempo del dinero, recién se recupera en el año 5.

