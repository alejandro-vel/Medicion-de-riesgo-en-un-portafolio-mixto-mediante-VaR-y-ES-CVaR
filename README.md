# Medicion-de-riesgo-en-un-portafolio-mixto-mediante-VaR-y-ES-CVaR
Se presenta un análisis de riesgo de mercado para un portafolio mixto (renta variable y bonos gubernamentales) a partir de una serie
de rendimientos diarios de horizonte 1 día (n = 250). Se caracteriza la distribución empírica mediante estadísticos descriptivos
y se diagnostica la adecuación del supuesto de normalidad usando pruebas formales y gráficos Q–Q. Posteriormente se estiman
medidas de riesgo en cola: el Valor en Riesgo (VaR) y el Expected Shortfall (ES), también conocido como Conditional Value at
Risk (CVaR), para niveles de confianza α = 0,95 y α = 0,99. Se comparan tres familias metodológicas: (i) histórico (empírico)
y bootstrap histórico, (ii) paramétrico normal y (iii) paramétrico t-Student, en ambos casos con estimación analítica y validación
por simulación Monte Carlo. Los resultados evidencian volatilidad no constante (clustering) y desviaciones moderadas respecto a
normalidad (asimetría y curtosis), lo que afecta principalmente las medidas de cola al 99 %. Se discute la inestabilidad del enfoque
histórico en niveles extremos dada la cola efectiva reducida en muestras finitas, y se argumenta la conveniencia del ES/CVaR como
medida de severidad promedio condicional frente al VaR, que sólo proporciona un umbral.
