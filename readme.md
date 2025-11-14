# 💡 Project Overview: Solar Production Forecast Dataset

## 1. Introduction and Context

The **Solar Production Forecast Dataset** project provides a high-fidelity, comprehensive data foundation for advancing machine learning and optimization techniques within the renewable energy sector. Developed by Techbrics S.r.l., this dataset serves as a crucial resource for energy analysts, researchers, and businesses focused on solar energy management, grid stability, and predictive maintenance.

The core objective is to offer granular, plant-specific performance metrics that enable the creation of highly accurate predictive models for energy yield and operational efficiency.

---

## 2. Dataset Description

This dataset details the solar energy production metrics from two distinct Photovoltaic (PV) plants, spanning a significant timeline of one month and nine days.

### Key PV Plant Specifications:

| Plant | Capacity (kW) | Role in Dataset |
| :--- | :--- | :--- |
| **PV Plant 1** | 999.8 kW | Represents large-scale solar production. |
| **PV Plant 2** | 239.4 kW | Provides a comparative perspective for mid-scale solar applications. |

## 3. Core Metrics and Insights

The dataset captures critical operational data necessary for robust forecasting and optimization, focusing on:

* **Daily Production Variations:** Records of day-to-day energy output fluctuations.
* **Peak Production Times:** Identification of periods when the PV systems achieve maximum output.
* **Potential Downtimes:** Data indicating periods of low or halted production for predictive maintenance.

---

## 4. Forecasting Methodology

This repository includes two separate, fully-analyzed notebooks where the solar production data was subjected to advanced time-series forecasting techniques:

### Prophet Forecasting Notebook
Utilizes **Meta's Prophet library** for time-series forecasting. Prophet is particularly well-suited for data with strong seasonal components and holidays (or in this case, daily cycles and weather effects), offering robust handling of missing values and trend changes.

### SARIMA Forecasting Notebook
Employs the **Seasonal Autoregressive Integrated Moving Average (SARIMA)** model. This classical statistical approach is used to capture the complex **seasonal dependencies** and temporal correlations present in solar energy generation data, providing a benchmark for forecasting performance.

## 5. Intended Applications

The insights and models derived from this project are directly applicable to:

* **Solar Energy Forecasting:** Building models to accurately predict future energy yields for grid management and trading.
* **Predictive Maintenance:** Analyzing downtime patterns to predict equipment failures proactively.
* **Optimization Algorithms:** Developing strategies for energy storage and consumption.