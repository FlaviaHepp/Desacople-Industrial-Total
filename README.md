# Desacople-Industrial-Total
Desacople Industrial Total

Desacople Industrial Total
El “Último Hombre en Pie”

Este proyecto implementa una consulta SQL que identifica empresas excepcionalmente resilientes dentro de sectores en crisis, detectando activos que mantienen una tendencia fuerte y saludable mientras todos sus pares entran en territorio de pánico.

La señal apunta a descubrir moats competitivos reales, visibles incluso cuando el mercado castiga indiscriminadamente a toda la industria.

🧠 Idea central

Durante crisis macro o shocks sectoriales:

el RSI promedio del sector colapsa

los flujos salen sin discriminar

incluso empresas sólidas son vendidas

Este enfoque busca el caso extremo:

Todo el sector está en sobreventa, excepto una empresa que sigue en tendencia alcista de largo plazo.

Ese activo es, literalmente, el último hombre en pie.

🏰 Valor de negocio

Identifica liderazgo estructural

Útil para:

estrategias defensivas

rotación hacia calidad

acumulación durante crisis sectoriales

Señal fuerte de ventaja competitiva sostenible

🗄️ Estructura de datos esperada
tickers
campo	descripción
ticker_id	Identificador del activo
sector	Sector económico
indicadores_tecnicos
campo	descripción
ticker_id	Identificador
fecha	Fecha
rsi_14	RSI de 14 períodos
adx_14	ADX de 14 períodos
sma_200	Media móvil simple de 200 períodos
precios_diarios
campo	descripción
ticker_id	Identificador
fecha	Fecha
close	Precio de cierre
⚙️ Lógica de la consulta

Calcula el RSI promedio del sector

Detecta sectores en pánico técnico (RSI < 30)

Dentro de esos sectores, filtra tickers que:

tengan RSI > 50

ADX > 45 (tendencia extremadamente fuerte)

precio por encima de la SMA 200

🔎 Interpretación de resultados

Señal de fortaleza relativa extrema

El mercado:

vende el sector

pero no logra quebrar a este activo

Suele anticipar:

liderazgo post-crisis

consolidación de cuota de mercado

outperformance prolongado

🚀 Posibles extensiones

Medir drawdown relativo vs sector

Confirmar con crecimiento de volumen

Incorporar métricas fundamentales

Backtesting en crisis históricas

📝 Notas finales

Señal poco frecuente pero muy potente

No es para trading rápido

Ideal para inversores de mediano y largo plazo
