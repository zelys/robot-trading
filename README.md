# Bot Trader de Bitcoin

Este proyecto implementa un bot de trading algorítmico básico para Bitcoin (BTC) en Python, con lógica avanzada, indicadores técnicos y visualización interactiva. Permite analizar el mercado, tomar decisiones de compra/venta y automatizar el monitoreo en tiempo real.

## Características principales

- Obtención automática de datos históricos de BTC/USD desde Yahoo Finance (`yfinance`).
- Web Scraping para obtener el precio y tendencia actual de BTC desde CoinMarketCap (`BeautifulSoup`).
- Limpieza y simplificación de datos para análisis robusto.
- Cálculo de indicadores técnicos: Media Móvil Simple (SMA), Media Móvil Exponencial (EMA) y RSI.
- Estrategia de trading mejorada basada en medias móviles, RSI y umbrales para evitar señales falsas.
- Visualización interactiva de precios, indicadores y decisiones con `plotly`.
- Automatización del análisis y toma de decisiones en tiempo real.

![Gráfico de precios de BTC](img/newplot.png)

## Estructura del repositorio

- `Bot_trading.ipynb`: Notebook mejorado con lógica avanzada, indicadores y visualización.
- `Bot_Trader.ipynb`: Versión básica del bot para referencia.
- `requirements.txt`: Lista de dependencias necesarias para ejecutar el proyecto.
- `img/`: Carpeta para imágenes y gráficos generados.

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/zelys/robot-trading.git
   cd robot-trading
   ```
2. (Opcional) Crea y activa un entorno virtual:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```
3. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```

## Uso

1. Abre el archivo `Bot_trading.ipynb` en JupyterLab o VS Code.
2. Ejecuta las celdas del notebook para analizar, visualizar y automatizar el monitoreo del mercado de Bitcoin.
3. Puedes personalizar los parámetros de la estrategia y la frecuencia de actualización.

## Requisitos

- Python 3.8+
- Conexión a internet

## Créditos

Desarrollado por Zelys.

## Licencia

Este proyecto se distribuye bajo la licencia MIT.
