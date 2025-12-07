# The Memory of Crime: Using Historic Brooklyn Felony Data to Forecast Future Events

### Team 1 Final Project 

### USD MADS 506: Applied Time Series Analysis

### Fall 2025 (B), Professor David Hurst

#### Authors:

-   April Chia
-   Mark Henry Villanueva
-   Katherine "Katie" Kimberling

### **Abstract**

Brooklyn’s felony activity demonstrates clear temporal structure, making it well suited for time series forecasting.
Using nearly two decades of open-sourced NYPD data from January 2006 through December 2024, this project analyzes daily and hourly felony counts to identify long term trends, seasonal patterns, weekly cycles, and the effects of major external shocks.
Exploratory analysis revealed strong recurring rhythms, including elevated activity in summer months, higher felony levels on Fridays, and consistent midday and evening peaks.
A pronounced structural break appeared at the start of the COVID shutdown, where felony counts declined sharply before rebounding and stabilizing at a higher post pandemic baseline.
Forecasting models including ETS, ARIMA, TSLM, and NNETAR were developed to evaluate predictive performance and assess how well they captured these observed patterns.
The results showed that ETS models generalized best, while NNETAR tended to overfit.
Understanding these temporal dynamics supports data-informed decision making for resource allocation, proactive policing strategies, and ongoing monitoring of changes in Brooklyn’s crime environment.

Keywords: Brooklyn, felonies, crime, time series, ETS, ARIMA, TSLM, NNETAR

## To see all of the output of this project, please do the following:

1.  Clone the following repository:

```         
git clone https://github.com/aprilchia/ADS-506-Applied_Time_Series_Analysis.git
```

2.  Run the file:

```         
Technical Notebook.qmd
```

3.  Be amazed.
4.  Alternatively, view the rendered [Technical-Notebook.pdf](https://github.com/aprilchia/ADS-506-Applied_Time_Series_Analysis/blob/main/Technical-Notebook.pdf "Technical-Notebook.pdf") here.

### **Goal**

Use time-series forecasting methods, including exponential smoothing (ETS), time series linear modeling (TSLM), ARIMA, and seasonal ARIMA, to model felony complaints in Brooklyn, NY compiled from January 2006 through December 2024, nearly two full decades of data.
The objective is to analyze temporal crime patterns based on the dates the crimes occurred (not just when they were reported) to identify trends, seasonal effects, and any short-term fluctuations, holiday-based patterns, or unexpected time-associated anomalies that may exist.
Understanding these patterns provides insights that support data-driven decision-making in resource allocation, crime prevention, and public safety policy.
Success will be measured by forecasting accuracy on held-out validation data and the clarity of insights gained about the temporal patterns.

### **Data Source:**

-   [NYC Open Data](https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i/about_data)
    -   The dataset, NYPD Complaint Data Historic, was harvested from NYC Open Data, and includes all valid felony, misdemeanor, and violation crimes reported to the New York City Police Department (NYPD) from 2006 to the end of (2024).

### **Data Story Presentation:**

-   [Felonies in Brooklyn: A True Crime Story](https://www.canva.com/design/DAG51swojBY/rsJL_R94zuZbIfSleRN7yg/edit?utm_content=DAG51swojBY&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

-   Professor David Hurst for such an insightful (if challenging!) class.
-   The members of Team One for their communication and dedication to project success.
