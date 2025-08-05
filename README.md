</head>
<body>
    <div class="container">
        <h1>Airline Passenger Time Series Prediction</h1>

  <h2>📝 About</h2>
        <p>This project implements a time series prediction model for airline passenger data starting from 1949. It uses historical data to visualize trends, scale features, split data into training and testing sets, and train a simple neural network to predict future passenger numbers.</p>

  <h2>🚀 Technologies</h2>
  <div>
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" class="badge">
      <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" class="badge">
      <img src="https://img.shields.io/badge/Seaborn-0b6623?style=for-the-badge&logo=python&logoColor=white" class="badge">
      <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white" class="badge">
      <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" class="badge">
      <img src="https://img.shields.io/badge/Scikit%20Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" class="badge">
      <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" class="badge">
  </div>

  <h2>Features</h2>
  <ul>
      <li>Loads historical passenger data from a public CSV file.</li>
      <li>Scales data using <code>StandardScaler</code> for neural network compatibility.</li>
      <li>Splits data into 90% training and 10% testing sets.</li>
      <li>Visualizes raw, scaled, training, and testing data using line plots.</li>
      <li>Trains a neural network with a single dense layer for time series prediction.</li>
  </ul>

  <h2>Installation</h2>
  <ol>
      <li>Clone the repository:<br>
          <code>git clone https://github.com/your-username/airline-passenger-prediction.git</code>
      </li>
      <li>Install dependencies:<br>
          <code>pip install pandas seaborn matplotlib numpy scikit-learn tensorflow</code>
      </li>
  </ol>

  <h2>Usage</h2>
  <ol>
      <li>Open the <code>passenger_prediction.ipynb</code> notebook in Jupyter or run the Python script.</li>
      <li>Ensure the dataset URL is accessible or provide a local copy of <code>Passageiros.csv</code>.</li>
      <li>Execute the code to process data, train the model, and view results.</li>
  </ol>

  <h2>Project Structure</h2>
  <ul>
      <li><code>passenger_prediction.ipynb</code>: Main notebook with data processing, visualization, and model training logic.</li>
      <li><code>requirements.txt</code>: List of required Python packages.</li>
  </ul>

  <h2>Example</h2>
  <p>The project processes a dataset of airline passengers, scales it, splits it into training (90%) and testing (10%) sets, and trains a neural network to predict future passenger numbers. The output includes line plots showing data trends and training/testing splits.</p>
  <p>
      <a href="https://colab.research.google.com/github/your-username/airline-passenger-prediction/blob/main/passenger_prediction.ipynb">
          <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">
      </a>
  </p>

  <h2>License</h2>
  <p>Licensed under the <a href="LICENSE">MIT License</a>.</p>

  <h2>Contact</h2>
  <p>For inquiries or contributions, open an issue on the <a href="https://github.com/your-username/airline-passenger-prediction">GitHub repository</a>.</p>
</div>
</body>
</html>
