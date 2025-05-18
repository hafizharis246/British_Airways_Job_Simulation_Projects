# British Airways Virtual Experience Program

This repository contains the work completed during the British Airways Virtual Experience Program, focusing on two main tasks: customer review analysis and predictive modeling of customer bookings.

## Task 1: Customer Review Analysis

### Overview
This task involved analyzing customer reviews of British Airways to understand customer sentiment and identify key areas of improvement.

### Data Processing Steps
1. Data Import and Initial Exploration
   - Imported customer reviews from CSV file
   - Performed initial data inspection and cleaning

2. Text Preprocessing
   - Implemented comprehensive text transformation pipeline:
     - Lowercasing
     - Word tokenization
     - Punctuation removal
     - Stopword removal
     - Lemmatization

3. Analysis and Visualization
   - Generated word clouds to visualize most common terms
   - Analyzed sentiment patterns in reviews
   - Identified key themes and topics in customer feedback

## Task 2: Predictive Modeling of Customer Bookings

### Overview
This task focused on building a predictive model to understand customer booking behavior and identify factors that influence successful bookings.

### Dataset Features
- `num_passengers`: Number of passengers
- `sales_channel`: Booking channel (e.g., Internet)
- `trip_type`: Type of trip (e.g., RoundTrip)
- `purchase_lead`: Days between booking and flight
- `length_of_stay`: Duration of stay
- `flight_hour`: Hour of flight
- `flight_day`: Day of flight
- `route`: Flight route
- `booking_origin`: Country of booking
- `wants_extra_baggage`: Extra baggage request
- `wants_preferred_seat`: Preferred seat request
- `wants_in_flight_meals`: In-flight meal request
- `flight_duration`: Duration of flight
- `booking_complete`: Target variable (booking completion status)

### Analysis Approach
1. Exploratory Data Analysis
   - Statistical analysis of features
   - Correlation analysis
   - Distribution analysis

2. Feature Engineering
   - Data preprocessing
   - Feature selection
   - Handling categorical variables

3. Model Development
   - Implementation of predictive models
   - Model evaluation and validation
   - Performance metrics analysis

## Technologies Used
- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebooks

## Project Structure
```
├── Task 1/
│   ├── Collecting Reviews Data.ipynb
│   └── Preprocessing and Analysing.ipynb
├── Task 2/
│   ├── Getting Started.ipynb
│   └── data/
│       └── customer_booking.csv
└── README.md
```

## Key Findings
1. Customer Review Analysis
   - Identified common themes in customer feedback
   - Discovered patterns in customer satisfaction
   - Highlighted areas for service improvement

2. Booking Prediction
   - Identified key factors influencing booking completion
   - Developed insights into customer booking behavior
   - Created predictive models for booking success

## Future Improvements
- Implement more advanced NLP techniques for review analysis
- Explore additional features for booking prediction
- Develop real-time monitoring systems for customer feedback
- Create automated reporting dashboards 