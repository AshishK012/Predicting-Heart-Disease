<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Flight Booking Data Analysis</title>
</head>
<body>
  <header>
    <h1>Flight Booking Data Analysis</h1>
    <p>This repository contains the analysis and modeling of flight booking data.</p>
  </header>

  <section>
    <h2>Data Overview</h2>
    <p>The dataset contains information about flight bookings, including attributes such as airline, flight details, source and destination cities, duration, days left before departure, and price.</p>
    <p>Total Entries: 300,153</p>
    <p>Columns:
      <ul>
        <li>Airline</li>
        <li>Flight</li>
        <li>Source City</li>
        <li>Departure Time</li>
        <li>Stops</li>
        <li>Arrival Time</li>
        <li>Destination City</li>
        <li>Class</li>
        <li>Duration</li>
        <li>Days Left</li>
        <li>Price</li>
      </ul>
    </p>
  </section>

  <section>
    <h2>Data Visualization</h2>
    <p>Visualizations have been created to explore relationships between different variables:</p>
    <ul>
      <li>Airline vs Price</li>
      <li>Days Left vs Price</li>
      <li>Airline vs Price (Bar Plot)</li>
      <li>Class vs Price (Grouped by Airline)</li>
      <li>Days Left vs Price (Grouped by Source and Destination Cities)</li>
      <li>Frequency of Attributes: Airline, Source City, Departure Time, Stops, Arrival Time, Destination City, Class</li>
      <li>Correlation Heatmap</li>
    </ul>
  </section>

  <section>
    <h2>Modeling</h2>
    <p>Three regression models have been trained on the data:</p>
    <ul>
      <li>Linear Regression</li>
      <li>Decision Tree Regressor</li>
      <li>Random Forest Regressor</li>
    </ul>
    <p>Performance Metrics:
      <ul>
        <li>R-squared (R2) score</li>
        <li>Mean Absolute Error (MAE)</li>
        <li>Mean Squared Error (MSE)</li>
      </ul>
    </p>
  </section>

  <section>
    <h2>Conclusion</h2>
    <p>The Random Forest Regressor achieved the highest R-squared score (0.985), indicating its effectiveness in predicting flight prices based on the given features.</p>
  </section>

  <footer>
    <p>For detailed code and analysis, please refer to the Jupyter Notebook provided in this repository.</p>
  </footer>
</body>
</html>
