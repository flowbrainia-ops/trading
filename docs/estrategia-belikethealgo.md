# Estrategia BELIKETHEALGO (Benjamín Carmona) — reglas extraídas

Fuentes estudiadas (noviembre 2026):
- Transcripción completa: *"Advanced Liquidity Masterclass"* (IKa5J8nEQ6c)
- Transcripción completa: *"Probé esta estrategia de scalping 1000 veces"* (bTEppMzqnrE)
- Transcripción completa: *"Perdí $2,000 en menos de dos horas"* (qYSeL6AGvlU)
- Listado de ~100 videos del canal, web belikethealgo.com (temario del curso), canal de Telegram @belikethealgooficial

> Él mismo dice que la estrategia no ha cambiado desde su primer video (hace más de 2 años), así que estas tres transcripciones cubren el núcleo. Lo que solo está en el curso de pago queda marcado como **DESCONOCIDO**.

---

## 1. Activo
- **Solo EURUSD.** Lo justifica porque es el par con más volumen y, según él, "el menos manipulado". Dice que se puede aplicar a otros pares, pero él no lo hace.
- Evita oro, NASDAQ y mercados muy tendenciales: allí la estrategia "le cuesta".

## 2. Horario (solo se opera en estas ventanas)
| Sesión | Hora España (CET/CEST) | UTC en invierno (actual) | UTC en verano |
|---|---|---|---|
| Londres | 09:00 – 11:00 | 08:00 – 10:00 | 07:00 – 09:00 |
| Nueva York | 14:00 – 16:30 | 13:00 – 15:30 | 12:00 – 14:30 |

- En NY, lo normal es que empiece a moverse **desde las 14:30** (hora España), que es cuando salen las noticias de EE. UU. (8:30 en Nueva York).
- **Noticias rojas** (NFP, CPI, PPI, desempleo, tipos): no se entra antes de que salgan. Se espera de **5 a 10 minutos** después de la publicación y entonces se mira qué máximo o mínimo se ha liquidado.
- Fuera de horario no se opera, aunque el patrón aparezca. Si un barrido ocurre fuera de horario, no vale: hay que esperar a que el precio vuelva a tomar ese nivel **dentro** de la sesión.
- Ojo: EE. UU. y Europa cambian de horario de verano en semanas distintas (marzo y octubre/noviembre). Esas semanas el desfase cambia una hora.

## 3. Niveles de liquidez (preparación antes de la sesión)
- La liquidez está en **todo máximo y todo mínimo previo que no haya sido tomado** ("disponible").
- Se marcan solo en **D1, H4 y H1**. Nunca en temporalidades menores a H1.
- Prioridad alta: **PDH / PDL** (máximo y mínimo del día anterior). Según su backtest, son los que mejor funcionan.
- Prioridad extra: liquidez en **línea de tendencia** (mínimos o máximos escalonados que forman una trendline).
- Objetivo (TP): el **siguiente punto de liquidez opuesto**, es decir, el siguiente mínimo o máximo disponible.

## 4. Escenarios de entrada (solo dos)

### Escenario A: barrido de liquidez (su favorito)
- Si el precio **rompe un máximo** de H1/H4/D1 dentro de la sesión → buscar **VENTAS**.
- Si el precio **rompe un mínimo** de H1/H4/D1 dentro de la sesión → buscar **COMPRAS**.
- La lógica es ir contra la mayoría: la ruptura es una "manipulación" para activar stops y luego el precio "distribuye" hacia el lado contrario (esquema AMD: acumulación, manipulación, distribución).

### Escenario B: imbalance (FVG) de H1
- Imbalance (FVG): hueco entre la mecha de la vela 1 y la de la vela 3, que no llegan a tocarse.
- Si el precio vuelve a un **FVG bajista de H1** dentro de la sesión → buscar ventas. Si vuelve a un **FVG alcista** → buscar compras.

## 5. Ejecución (en M1 a M5)
1. Esperar a que se produzca el barrido (o el toque al FVG de H1) **dentro del horario**.
2. Bajar a **M1, M2, M3 o M5**. Va cambiando de temporalidad según cuál se vea más limpia.
3. Esperar un **impulso o desplazamiento** en la dirección contraria al barrido que deje uno o varios **FVG**.
   - El **cambio de estructura** (CHoCH, romper el último mínimo o máximo que creó el extremo) es una confirmación opcional: "no es necesario".
4. **Entrada:** orden límite en el **FVG más cercano** al precio, no en el más profundo. Prefiere sacrificar algo de ratio a quedarse fuera del trade.
5. **Stop loss:** por encima del máximo del barrido (en ventas) o por debajo del mínimo (en compras). Suele ser de **3 a 6 pips**.
6. **Take profit:** el siguiente punto de liquidez. Busca un ratio **mínimo de 1:2**, normalmente entre 1:2 y 1:3. Ha visto trades de 1:8, pero no los persigue porque psicológicamente le cuestan más.
7. Dice tener "unas 4 confirmaciones de entrada". Solo se ven claramente dos: el FVG y el CHoCH. **El resto: DESCONOCIDO** (está en el bloque 10 del curso).

## 6. Gestión de riesgo
- **1 % de riesgo por operación** en cuentas de fondeo (por ejemplo, 2.000 $ en una cuenta de 200k).
- Con un drawdown máximo del 8–10 %, eso da margen para 8–10 stops seguidos.
- Si toca el SL, **se acaba esa sesión**. Vuelve en la siguiente (Nueva York o el día siguiente). No hace trading de venganza.
- Prefiere operar con cuentas de fondeo antes que con capital propio.
- **DESCONOCIDO:** cuándo mueve el stop a break-even, si hace cierres parciales y cuál es su límite de trades por día (todo eso está en el bonus del curso).

## 7. Cuándo falla (según él)
- En mercados con **tendencia fuerte** sin acumulaciones (por ejemplo, subidas de 200–300 pips en dos días).
- Entrar demasiado pronto: en el trade de −2.000 $ la dirección era correcta, pero el movimiento llegó horas después, ya en NY.

## 8. Contenido del curso que no está en abierto
Order blocks, rango de Asia (AMD + indicador, escenarios "Judas" y "Retest"), London Killzone, liquidez interna/externa y su prioridad, plan de trading completo y la "Estrategia avanzada 3.0".
Ojo con una contradicción: en YouTube dice operar "sin order blocks", pero el curso los incluye.

## 9. Señales de alerta (análisis crítico)
- **No hay un track record auditado** (tipo Myfxbook o un estado de cuenta completo). Los payouts de cuentas de fondeo no equivalen a su P&L neto: no se ven los challenges y cuentas que ha perdido, cosa que él mismo admite.
- **Conflicto de interés:** publica enlaces de afiliado y códigos de descuento de la empresa de fondeo NYS Markets, y tiene un video de "review honesta" de esa misma empresa.
- **Su negocio principal visible es vender el curso** (llamadas de admisión, "solo quedan 7 plazas"). La web promete "resultados en 90 días".
- Los conceptos (barrido de liquidez, FVG, PDH/PDL, sesiones) son conceptos SMC/ICT populares, no algo exclusivo suyo.
- **Conclusión:** la estrategia es concreta y codificable en gran parte, pero su rentabilidad **no está demostrada de forma independiente**. Hay que comprobarla con backtest antes de arriesgar dinero.

## 10. Cómo se puede convertir en reglas para un bot (borrador)
- Antes de cada sesión: calcular los swings no tomados en H1/H4/D1, además de PDH y PDL.
- Durante la ventana horaria: detectar el barrido (precio más allá del nivel en X pips) y, en M1–M5, esperar el desplazamiento con FVG.
- Orden límite en el FVG más cercano. SL en el extremo del barrido más un pequeño margen (con un tope de 6–8 pips). TP en la siguiente liquidez, con un mínimo de 1:2.
- Filtros: calendario de noticias, como máximo 1 pérdida por sesión y 1 % de riesgo.
- Parámetros que hay que fijar y probar en el backtest: tamaño del swing, margen mínimo del barrido, tamaño mínimo del FVG y tiempo máximo para entrar tras el barrido.
