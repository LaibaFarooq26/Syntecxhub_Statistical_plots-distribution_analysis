# Biomedical Device Performance Analysis

A simple **Biomedical Engineering data analysis project** that demonstrates how statistical visualizations can be used to evaluate the performance of medical diagnostic devices.

This project analyzes diagnostic data such as **diagnosis time, device accuracy, and diagnosis success rate** using statistical plots like **Histogram, KDE Plot, and Boxplot**.

The goal is to visually understand **distribution patterns, outliers, skewness, and performance trends** in biomedical diagnostic devices.

## Project Overview

This project presents a web-based visualization of biomedical diagnostic device performance.  
It includes a structured dataset and statistical plots that help analyze how efficiently different devices perform in clinical scenarios.

The webpage displays:

- A brief overview of the project
- A sample biomedical dataset
- Statistical visualization cards
- Interpretation of device performance

## Features

- Clean and professional user interface
- Biomedical dataset representation
- Statistical visualization explanations
- Responsive layout using CSS Grid
- Interactive card hover effects
- Organized analysis sections

## Statistical Visualizations Used

### Histogram
Shows the **distribution of diagnosis time** across different biomedical devices.  
It helps identify the **most common diagnosis time range**.

### KDE Plot (Kernel Density Estimation)
Represents the **probability density of device accuracy values**.  
It helps understand how accuracy values are distributed across devices.

### Boxplot
Displays the **spread, quartiles, median, and potential outliers** in diagnosis time data.

## Sample Dataset

| Patient ID | Device     | Diagnosis Time | Accuracy | Result  |
|------------|------------|----------------|----------|---------|
| 1          | ECG        | 5 min          | 92%      | Success |
| 2          | MRI        | 18 min         | 96%      | Success |
| 3          | Ultrasound | 10 min         | 89%      | Success |
| 4          | ECG        | 6 min          | 85%      | Fail    |
| 5          | MRI        | 25 min         | 94%      | Success |

## Project Structure

```
Statistical_Plots_Distribution_Analysis
│
├── index.html
├── style.css
│
├── images
│   ├── histogram.png
│   ├── kde.png
│   └── boxplot.png
```

## Technologies Used

- HTML5  
- CSS3  
- Statistical Visualization Concepts  
- Biomedical Data Analysis

## Learning Objectives

This project demonstrates:

- Basic **biomedical data analysis concepts**
- Understanding **statistical distributions**
- Visualization interpretation
- Building a **clean scientific project interface**

It is suitable for:

- Biomedical engineering students
- Data science beginners
- Healthcare analytics learners

## Future Improvements

Possible enhancements include:

- Interactive charts using Python or JavaScript libraries
- Dynamic dataset integration
- Real-time biomedical device monitoring
- Machine learning models for diagnostic prediction
- Advanced analytics dashboard

## Author

Biomedical Engineering Statistical Analysis Project

Developed to demonstrate **statistical analysis of medical device performance using visualization techniques.**
