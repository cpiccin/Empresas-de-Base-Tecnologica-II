# Unit economics, valuación y salidas (M&A – IPO) — Clase 12/11/2026

## Unit economics

**La plata compra tiempo, no éxito.** Levantar capital (deuda, subsidios o capital externo) no garantiza que el producto funcione: hay que demostrar que el modelo funciona antes de que se termine el runway. La pregunta del inversor es si el negocio gana o pierde plata con cada cliente que suma. No alcanza con mirar la facturación total: hay que bajar a la unidad mínima del negocio, un cliente. Esa mirada se llama **unit economics**. Si cada cliente deja más de lo que cuesta conseguirlo, el negocio escala sano; si no, crecer solo agranda las pérdidas.

Tres preguntas sobre un cliente: cuánto cuesta conseguirlo (**CAC**), cuánto tiempo se queda (**churn**) y cuánto deja mientras está (**LTV**).

### CAC, churn y LTV

**CAC (costo de adquisición de cliente):** cuánto se gasta en marketing y ventas (incluidos los ejecutivos comerciales) para sumar un cliente nuevo. Cuanto más bajo, mejor.

```
CAC = gasto en marketing y ventas ÷ clientes nuevos
Ej.: US$ 100.000 en un mes y 200 clientes nuevos → CAC = US$ 500
```

**Churn (tasa de abandono):** porcentaje de clientes que se van en un período. Define cuánto dura un cliente. Churn alto = balde agujereado.

```
Vida del cliente = 1 ÷ churn
Ej.: se va el 5% por mes → 1 ÷ 0,05 = 20 meses
```

**LTV (lifetime value):** cuánta ganancia deja un cliente durante toda su vida con la empresa. Es el techo de lo que conviene gastar por cliente.

```
LTV = (ingreso por cliente × margen) ÷ churn
Ej.: US$ 1.000/mes, margen 70%, churn 5% → LTV = US$ 14.000
```

### LTV / CAC

Cuántos pesos de ganancia devuelve cada peso invertido en conseguir un cliente.

| LTV / CAC | Lectura |
|---|---|
| < 1 | Pierde con cada cliente: crecer empeora las cosas |
| 1 a 3 | Zona gris: gana poco, cualquier error en los supuestos lo da vuelta |
| ≥ 3 | Negocio sano: cada peso en captar devuelve al menos tres |
| > 5 | ¿Invierte poco en crecer? Puede estar dejando mercado sobre la mesa |

**CAC payback:** en cuántos meses se recupera lo que costó conseguir al cliente (CAC ÷ ganancia mensual por cliente). Cuanto antes se recupera, menos caja se quema y menos capital hay que levantar.

### Ejercicio NubeFit

App de rutinas por suscripción. Gasto en marketing y ventas US$ 60.000, 300 clientes nuevos, ingreso US$ 20/mes por cliente, margen 80%, churn mensual 4%.

```
CAC          = 60.000 ÷ 300          = US$ 200
Vida         = 1 ÷ 0,04              = 25 meses (promedio)
LTV          = (20 × 0,80) ÷ 0,04    = US$ 400
LTV / CAC    = 400 ÷ 200             = 2 → zona gris
```

Cada cliente devuelve el doble de lo que costó, pero con poco margen de error: con churn de 6% el LTV caería a US$ 267 y el ratio a 1,3. Conviene bajar el churn (retención) antes de acelerar el gasto en marketing.

## Valuación

Valuar es ponerle precio a la empresa. Aparece en cada ronda de inversión y, sobre todo, en la salida.

| Enfoque | Pregunta | Cálculo | Uso |
|---|---|---|---|
| **Múltiplos** (relativo) | ¿A cuánto se venden empresas parecidas? | Múltiplo × una métrica (ingresos, EBITDA, usuarios) | Rápido y con referencia de mercado; depende de encontrar comparables. Se usa cuando hay poca información de la empresa pero sí de similares |
| **Flujo de fondos descontados (DCF)** (intrínseco) | ¿Cuánta plata va a generar en el futuro? | Suma de los flujos futuros traídos a hoy con una tasa que refleja el riesgo | El más "fundamental" y el más usado, pero muy sensible a los supuestos. Se apoya en información histórica (crecimiento y márgenes de años anteriores) |
| **Método VC** (startups) | ¿Cuánto vale hoy si se vende en el futuro? | Se estima el valor de salida y se divide por el retorno que exige el fondo | Startups sin información histórica, flujos ni comparables claros |

### Pre-money y post-money

**Pre-money:** valor de la empresa antes de que entre la plata de la ronda. **Post-money:** valor después de la ronda = pre-money + inversión. Toda ronda de inversión suma a la valuación.

```
% del inversor = Inversión ÷ Post-money   (se divide por el post-money, no por el pre-money)

Ej.: pre-money US$ 8 M + inversión US$ 2 M → post-money US$ 10 M
     Inversor: 2 ÷ 10 = 20%  ·  Fundadores: 80%
     Parte de los fundadores: 100% × 8 M = 80% × 10 M = US$ 8 M
```

**Dilución:** los fundadores no pierden plata, pierden porcentaje. Tienen una porción más chica de una torta más grande.

### Valuación por múltiplos

Valor ≈ múltiplo × métrica. El múltiplo sale de empresas comparables o de transacciones recientes.

| Múltiplo | Para |
|---|---|
| Valor / Ingresos | Startups que todavía no ganan plata, pero facturan |
| Valor / EBITDA | Empresas maduras, con resultado operativo positivo |
| Precio / Ganancia (P/E) | Empresas que cotizan en bolsa |

Ej.: SaaS parecidas se venden a 5× ingresos anuales; la startup factura US$ 2 M → valor ≈ US$ 10 M. Empujan el múltiplo hacia arriba: crecimiento rápido, ingresos recurrentes, márgenes altos y buen LTV/CAC.

### Flujo de fondos descontados (DCF)

La plata futura vale menos que la de hoy, porque la de hoy se puede invertir: con una tasa del 10%, $100 hoy son $110 en un año. **Descontar** es hacer el camino al revés: $110 dentro de un año valen $100 hoy.

Tres ingredientes:
- **Flujos:** la plata que el negocio va a dejar cada año. En general se usa el **EBITDA**, no los ingresos.
- **Tasa:** cuánto "pierde" la plata por esperar. A más riesgo, tasa más alta.
- **Tiempo:** cuanto más lejos está un flujo, menos vale hoy.

Una empresa vale la plata que va a generar en el futuro, traída a hoy: es el **VAN aplicado a toda la empresa**.

**Regla:** cada flujo se divide por (1 + tasa) una vez por cada año que falta para cobrarlo, y después se suman.

```
Carrito de café, tasa 10%
Año 1:  110 ÷ 1,10 = 100
Año 2:  121 ÷ 1,21 = 100
Valor hoy           = 200   → si lo venden a menos de $200, conviene comprarlo
```

**Si el negocio dura para siempre (perpetuidad):**

```
Valor = Flujo ÷ Tasa
Ej.: $100 por año para siempre, tasa 10% → 100 ÷ 0,10 = $1.000
```

Tener $1.000 hoy a una tasa del 10% o cobrar $100 por año para siempre vale lo mismo.

**Valor terminal:** todo lo que el negocio deja después del último año proyectado, resumido en un solo número con la fórmula de perpetuidad. Se calcula al final del último año proyectado y se trae a hoy con el mismo divisor de ese año. En la práctica se proyecta un período útil (ej.: 5 años de EBITDA) y en el último año se aplica el valor terminal.

```
Carrito: $110 año 1, $121 año 2 y desde el año 3 $121 para siempre. Tasa 10%.
Año 1:            110 ÷ 1,10 =   100
Año 2:            121 ÷ 1,21 =   100
Valor terminal: (121 ÷ 0,10 = 1.210) ÷ 1,21 = 1.000
Total                                      = 1.200   (83% viene del valor terminal)
```

El múltiplo de la perpetuidad también se negocia y depende del rubro: es menor (ej.: 3×) en mercados volátiles y mayor (ej.: 5×) en negocios muy asentados con clientes estables, como una empresa de gas.

### Ejercicio TurnoYa

App de turnos para peluquerías. Flujo año 1 $120, año 2 $144, tasa 20%; para siempre, $60 por año.

```
1. Dos años:       120 ÷ 1,20 = 100 ; 144 ÷ 1,44 = 100  → $200
2. Para siempre:   60 ÷ 0,20                           → $300
3. ¿Comprar a $250? Vale 300 y cuesta 250              → sí, conviene
4. Tasa al 30%:    60 ÷ 0,30                           → $200: ya no conviene
```

El negocio es el mismo; solo cambió el riesgo. Por eso valuar una startup es difícil: pequeñas diferencias en cómo se percibe el riesgo cambian mucho el valor.

## Salidas: M&A e IPO

El **exit** es el momento en que inversores y fundadores convierten su parte de la empresa en dinero. El éxito de un fondo no está solo en elegir bien la empresa, sino en elegir bien el momento de retirarse y vender su participación.

| | **M&A** (fusiones y adquisiciones) | **IPO** (oferta pública inicial) |
|---|---|---|
| Qué es | Una empresa más grande compra la startup o se fusiona con ella | La empresa vende acciones al público por primera vez y pasa a cotizar en bolsa |
| A favor | Salida más rápida y simple; liquidez inmediata para los socios | Mucho capital y prestigio; sigue siendo independiente |
| En contra | Se pierde la independencia (si el comprador toma el control, desde el 51%); depende de que aparezca un comprador | Costos, regulación y exposición pública: presentar información regular (estados trimestrales) que mueve la cotización; presión por resultados cada trimestre |

La mayoría de las startups termina en M&A; la IPO queda para las pocas que llegan a gran escala y son predecibles.

### ¿Por qué una empresa compra una startup?

- **Tecnología:** es más rápido comprar algo que ya funciona que desarrollarlo.
- **Equipo (acqui-hire):** se compra la empresa para quedarse con su gente.
- **Clientes:** sumar una base de usuarios (ej.: capturar transacciones de un día para otro) o entrar a un mercado nuevo.
- **Sinergias:** juntas valen más; se eliminan costos redundantes y hay venta cruzada.
- **Defensa:** sacarse de encima a un competidor antes de que crezca.

Para el fundador: liquidez rápida y un socio con espalda, a cambio de perder independencia. El precio no sale solo de la valuación: depende de cuánto valga la startup para ese comprador y de cuántos compradores interesados haya.

### Cuatro casos argentinos, cuatro etapas

| Empresa | Etapa |
|---|---|
| **Pomelo** | Expansión con VC. Infraestructura de pagos. Serie C de US$ 55 M (enero 2026); US$ 160 M levantados en total. Saliendo de la curva J |
| **Tiendanube** | Unicornio privado. SaaS de e-commerce. Ronda de US$ 500 M en 2021 que la valuó en US$ 3.100 M. Sigue privada |
| **Globant** | IPO en NYSE (2014). Una EBT también puede ser de servicios, no solo de producto |
| **Mercado Libre** | IPO en Nasdaq (2007). Recorrió la curva J completa; empresa madura |

### Información privilegiada

Operar acciones de la propia empresa usando información interna no pública (ej.: un lanzamiento) puede ser *insider trading*. Los empleados suelen firmar convenios de confidencialidad, y quienes tienen acceso a información sensible quedan sujetos a restricciones adicionales.

## Para llevarse

- **Unit economics:** si cada cliente deja más de lo que cuesta conseguirlo (LTV/CAC ≥ 3), el negocio escala sano.
- **Valuar es estimar:** múltiplos, DCF y método VC responden preguntas distintas; se usan juntos y se triangula.
- **DCF = VAN de la empresa:** la plata futura se trae a hoy con una tasa y se suma. En startups, leerlo como rango.
- **El exit cierra la historia:** M&A o IPO es donde el valor construido se convierte en plata.

En el parcial puede haber ejercicios de unit economics (CAC, vida, LTV, LTV/CAC) y de valuación simple por DCF. No todo será verdadero o falso: habrá algún ejercicio corto con resultado numérico exacto.
