# ⚽ Premier League Investment Impact Analysis

Python data analysis project examining the correlation between capital injection and sports performance in the English Premier League, focusing on Newcastle United and Everton FC (2017-2024).

## 📋 Overview

Comparative study analyzing how foreign investment affects competitive performance in professional football. Uses 7 seasons of data to quantify the relationship between transfer spending, squad value, and league standings for two contrasting case studies.

## 🎯 Research Question

**"How relevant is capital injection for maintaining competitive status in the English Premier League?"**

## ✨ Features

- **Multi-season Analysis** - 7 seasons of comprehensive data (2017-18 to 2023-24)
- **Interactive Menu System** - Navigate between different visualizations and reports
- **Comparative Statistics** - Side-by-side analysis of Newcastle vs Everton
- **Data Visualization** - Multiple chart types for performance metrics
- **User Session Tracking** - Logs user navigation and accessed reports
- **Automated Reporting** - Generates summary statistics and findings

## 📊 Analysis Categories

### Sports Performance Metrics
- League position per season
- Points accumulated
- Wins and losses
- Goals scored and conceded

### Financial Metrics
- Net transfer spending
- Squad market value evolution
- Spending vs performance correlation

### Visualization Types
- Line graphs for trend analysis
- Correlation heatmaps
- Comparative bar charts
- Position tracking over time

## 🛠️ Technologies

- **Language:** Python 3.x
- **Data Processing:** pandas
- **Visualization:** matplotlib, seaborn
- **Data Format:** CSV files
- **Platform:** Google Colaboratory (recommended)

## 📁 Project Structure

```
.
├── Proyecto_Integrador.py              # Main analysis program
├── Newcastle_Transfermarkt.csv         # Newcastle financial data
├── Everton_Transfermarkt.csv          # Everton financial data
├── 2017-18.csv to 2023-24.csv         # Season-by-season league data
├── Proyecto_Integrador.pdf            # Full research report
├── texto.txt                          # User session logs
└── README.md
```

## 🚀 Setup & Execution

### Prerequisites
```bash
pip install pandas matplotlib seaborn
```

### Running in Google Colab (Recommended)
1. Upload all CSV files to Colab environment
2. Upload `Proyecto_Integrador.py`
3. Run the main script
4. Navigate through interactive menu

### Local Execution
```bash
python Proyecto_Integrador.py
```

**Important:** Ensure all CSV files are in the same directory as the script.

## 🎮 How to Use

Upon running, you'll see an interactive menu:

```
Usuario: [Your Name]

¿Qué acción deseas realizar?
1) Visualizar gráficas de rendimiento por partido
2) Visualizar gráficas económicas
3) Visualizar gráficas de rendimiento por temporada
4) Deseas salir?
```

### Menu Options

**Option 1: Sports Performance by Match**
- Victory trends
- Goals scored progression
- Goals conceded analysis
- Loss trends

**Option 2: Economic Analysis**
- Net spending vs squad value (Newcastle)
- Net spending vs squad value (Everton)
- Comparative spending analysis

**Option 3: Season Performance**
- Final league positions
- Points per season
- Correlation matrices
- Season-by-season comparison

## 📈 Key Findings

### Newcastle United (Post-2021 Saudi Investment)
- ✅ **Squad value increase:** 315% growth
- ✅ **League position:** From mid-table to top 7
- ✅ **Goals scored:** 39 → 62 per season
- ✅ **Net spending:** -€519M (investment)
- ✅ **Wins:** 12 → 18 per season

### Everton FC (Conservative Youth Policy)
- ⚠️ **Squad value change:** -€30M from baseline
- ⚠️ **League position:** Top 10 → relegation battle
- ⚠️ **Performance decline:** More losses, more goals conceded
- ⚠️ **Net spending:** -€181M (sales > purchases)
- ⚠️ **Strategic shift:** Focus on youth development

## 🔬 Methodology

### Data Collection
- Source: Transfermarkt, Football-Data.co.uk
- Period: 7 seasons (2017-2024)
- Teams: Newcastle United, Everton FC

### Data Processing
1. CSV file loading with pandas
2. Data cleaning (removing null/object types)
3. Season-by-season filtering
4. Statistical aggregation

### Analysis Techniques
- Descriptive statistics
- Correlation analysis
- Trend visualization
- Comparative benchmarking

## 📊 Correlation Analysis

The program generates heatmaps showing correlation between:
- Transfer spending ↔ League position
- Squad value ↔ Points earned
- Investment ↔ Goals scored
- Financial strategy ↔ Competitive performance

## 💡 Conclusions

**Main Finding:** Direct correlation exists between capital injection and sports performance in the Premier League.

**Newcastle Case Study:** Strategic investment leads to:
- Improved squad quality
- Better league standings
- Increased goal-scoring ability
- European competition qualification

**Everton Case Study:** Conservative spending results in:
- Squad value depreciation
- Declining league position
- Relegation threat
- Reduced competitive edge

## 📝 Session Logging

The program automatically logs user interactions to `texto.txt`:
```
Usuario: Luis
Historial de busqueda:
Accedio: Graficas de rendimiento deportivo
Accedio: Grafica de Puntos
...
```

## 🎓 Academic Context

**Course:** Computational Thinking  
**Institution:** Tecnológico de Monterrey  
**Team:**
- Luis Enrique Aguilera Novoa (A01646551)
- Pablo Emiliano Gonzales Rios (A01647192)
- Angelo Dayvis Farfan Torres (A01647200)

**Date:** October 16, 2024

## 📚 Libraries Used

```python
import pandas as pd              # Data manipulation
import matplotlib.pyplot as plt  # Plotting
import seaborn as sns           # Statistical graphics
```

## 🔧 Key Functions

- `victorias_en_temporada()` - Victory trends visualization
- `goles_anotados()` - Goals scored analysis
- `goles_recibidos()` - Goals conceded tracking
- `derrotas_en_temporada()` - Loss pattern analysis
- `gasto_neto_vs_valor_plantilla()` - Financial correlation
- `posiciones_vs_temporadas()` - League position evolution
- `puntos_vs_temporada()` - Points progression
- `correlaciones()` - Statistical correlation heatmaps

## 📖 Full Report

Complete findings, methodology, and individual conclusions available in `Proyecto_Integrador.pdf`

## ⚠️ Data Requirements

All CSV files must be uploaded before execution:
- Season data: 2017-18.csv through 2023-24.csv
- Transfer data: Newcastle_Transfermarkt.csv, Everton_Transfermarkt.csv

## 🤝 Contributing

Academic project completed. Suggestions welcome for future enhancements.

---

**Course:** Pensamiento Computacional  
**Group:** 418  
**Semester:** August - December 2024  
**Institution:** ITESM
