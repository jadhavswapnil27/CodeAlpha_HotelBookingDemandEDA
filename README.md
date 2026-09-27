# CodeAlpha - Hotel Booking Exploratory Data Analysis

## Project Overview

This project was completed as part of the **CodeAlpha Data Analytics Internship**.

The project focuses on **Exploratory Data Analysis (EDA)** of a hotel booking dataset using Python. The analysis is performed to understand booking patterns, cancellations, customer behavior, pricing, and other important factors.

## Objectives

- Understand the structure of the hotel booking dataset
- Clean and preprocess the data
- Analyze booking and cancellation patterns
- Identify trends and relationships
- Create meaningful data visualizations
- Generate useful insights from the dataset

## Dataset

The dataset contains **119,390 booking records and 32 features** related to hotel reservations.

Important attributes include:

- Hotel Type
- Is Canceled
- Lead Time
- Arrival Date
- Customer Type
- Market Segment
- Country
- Room Type
- Average Daily Rate (ADR)
- Stay Duration
- Special Requests

## Data Preprocessing

The following preprocessing steps were performed:

- Checked the structure and data types
- Identified missing values
- Removed duplicate records
- Handled missing values in important columns
- Performed exploratory analysis on relevant variables

After removing duplicate records, **87,396 records** remained for analysis.

## Exploratory Data Analysis

The following analyses were performed:

- Booking cancellation analysis
- Hotel-wise cancellation analysis
- Monthly booking analysis
- Lead time analysis
- Average Daily Rate (ADR) analysis
- Customer type analysis
- Country-wise booking analysis
- Correlation analysis

## Visualizations

The project includes:

- Count plots
- Bar charts
- Box plots
- Histograms
- Correlation heatmap

## Key Insights

- **27.49%** of bookings were canceled.
- **City Hotel** had a higher cancellation rate than Resort Hotel.
- **August** recorded the highest number of bookings.
- Canceled bookings had a higher average lead time.
- City Hotel had a higher average ADR than Resort Hotel.
- **Transient** customers were the largest customer group.
- **Portugal (PRT)** had the highest number of bookings.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

```text
CodeAlpha_HotelBookingEDA/
│
├── HotelBookingEDA.ipynb
├── hotel_bookings.csv
└── README.md
