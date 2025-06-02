# Digital Exposome Dataset Analysis

## 🌍 Environmental Health Impact Assessment

This project presents a comprehensive exploratory data analysis (EDA) of the Digital Exposome dataset, investigating the relationships between environmental pollutants and human physiological responses in real-time.

## 📊 Dataset Overview

- **Records**: 42,436 observations
- **Variables**: 12 features (environmental + physiological)
- **Data Quality**: Complete dataset with no missing values

### Variables Analyzed

**Environmental Pollutants:**
- PM1, PM2.5, PM10 (Particulate Matter)
- CO (Carbon Monoxide)
- NH3 (Ammonia)  
- NO2 (Nitrogen Dioxide)
- Noise levels

**Physiological Measures:**
- HR (Heart Rate)
- EDA (Electrodermal Activity)
- BVP (Blood Volume Pulse)
- IBI (Inter-Beat Interval)

**Target Variable:**
- Label (Wellbeing Score: 1-5 scale)

## 📈 Visualizations

The analysis includes comprehensive visualizations:
- **Correlation heatmaps** showing environmental-physiological relationships
- **Box plots** revealing dose-response patterns across pollution quartiles
- **Hexbin density plots** displaying pollution co-occurrence patterns
- **Time series analysis** of extreme pollution events
- **Distribution analysis** of all environmental and physiological variables

## 🛠️ Technologies Used

```python
# Core Libraries
pandas          # Data manipulation and analysis
numpy           # Numerical computing
matplotlib      # Static plotting
seaborn         # Statistical visualization
plotly          # Interactive visualizations

# Specific Tools
plotly.express  # Quick interactive plots
plotly.graph_objects  # Custom interactive plots
```

