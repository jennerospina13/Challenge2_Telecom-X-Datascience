# Challenge2_Telecom-X-Datascience

📊 Alura Store - Análisis de Evasión de Clientes

El Objetivo de este proyecto es realizar el análisis de datos a Telecom X, puesto que la empresa se enfrenta a una alta tasa de cancelaciones y necesita comprender los factores que llevan a la pérdida de clientes.

## 🎯 Propósito del Análisis

Realizar el analisis en detalle respondiendo al ¿Por que se presenta  an alta tasa de cancelaciones de clientes:
- Identificar Variables que estan incidiendo en esta situación.
- Identificar los diferentes segmentos de clientes.
- Identificar total de clientes activos y total de clientes retirados.

## 📁 Estructura del Proyecto

Archivo del proyecto ipynb, ejecutable en Google Colab y también en Jupyter Notebook.

## 📊 Ejemplos de Gráficos e Insights

- **Grafico Churn VS No Churn por Antiguedad** Gráfico de Barras que muestra un comparativo entre clientes retirados(CHURN) y clientes activos (NO CHURN) segun el tiempo de permanencia.
- **Grafico tasa de churn por Antiguedad** Grafico de barras que muestra en porcentaje los clientes retirados segun su tiempo de permanencia.
- **Grafico Churn VS No Churn por tipo de internet** Gráfico de Barras que muestra un comparativo entre clientes retirados(CHURN) y clientes activos (NO CHURN) segun el tipo de internet (DSL, Fibra Optica y Sin Internet).
- **Grafico tasa de churn por Tipo de Internet** Grafico de barras que muestra en porcentaje los clientes retirados segun el tipo de internet (DSL, Fibra Optica y Sin Internet).
- **Grafico Churn VS No Churn por Soporte Técnico** Gráfico de Barras que muestra un comparativo entre clientes retirados(CHURN) y clientes activos (NO CHURN) segun si poseen o no el servicio de soporte tecnico.
- **Grafico tasa de churn por Soporte Técnico** Grafico de barras que muestra en porcentaje los clientes retirados segun si poseen o no el servicio de soporte tecnico.
- **Grafico Churn VS No Churn por Metodo de pago** Gráfico de Barras que muestra un comparativo entre clientes retirados(CHURN) y clientes activos (NO CHURN) segun el metodo de pago (transferencia bancaria, tarjeta de credito, cheque electronico y cheque enviado por Mail).
- **Grafico tasa de churn por  Metodo de pago** Grafico de barras que muestra en porcentaje los clientes retirados segun el metodo de pago (transferencia bancaria, tarjeta de credito, cheque electronico y cheque enviado por Mail).

> ✅ Insight clave: Se encuantra una alta incidencia de retiro en clientes en clientes que llevan menos de 1 año y clientes hasta 2 años de antiguedad, asi mismo en clientes con red en Fibra optica, clientes que no cuenta con soporte tecnico y por ultimo clientes con medio de pago cheque electronico.

## 🚀 Cómo Ejecutar el Notebook

1. Abre el archivo `TelecomX_LATAM.ipyn` en Google Colab.
2. Ejecuta las celdas en orden para:
   - Cargar los datos.
   - Procesarlos y agruparlos.
   - Generar los gráficos.
   - Mostrar conclusiones y recomendaciones.

## 📌 Conclusión

Para concluir, según analisis realizados se encuentra que se debe tener en cuenta las siguientes recomendaciones:

- Planes de fidelización y contratos a largo plazo, además ofrecer descuentos o beneficios adicionales para clientes que elijan planes de 1 o 2 años.

- Mejoras en la red de Fibra Óptica, Abordar y planear mantenimientos preventivos-correctivos sobre la red de Fibra óptica ya que las fallas sobre estas pueden ser el origen de la alta tasa de cancelación.

- Programa de retención para clientes nuevos, Implementar estrategias específicas para clientes en sus primeros 6 meses.

- Incluir paquetes con servicio de soporte técnico, es notable que con la ayuda de un profesional se reduzca la cancelación de los servicios.

- Optimización en procesos de facturación electrónica, el alto porcentaje de churn en este método de facturación, sugiere malas experiencias de usuario.

- Es importante como el uso de Python, Pandas y Matplotlib, brinda y apoya con argumentos sólidos la solución al problema planteado e influye en la toma de decisiones.

---

**Desarrollado por:** *[Jenner Ospina]*  
Curso: *Formación en Data Science - Alura Latam*
