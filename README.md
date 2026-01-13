🏭 Smart Sensor Data Analyzer
A Python-based simulation and analysis toolkit for industrial sensor data. This project generates synthetic readings for temperature, humidity, and vibration, performs statistical analysis, and provides visual insights—mimicking a foundational pipeline for predictive maintenance systems.

Author: Sadek Dhokar | Industrial Computer Engineering (GII) Student | ENET'Com, University of Sfax
Tech Stack: Python, Pandas, Matplotlib

📁 Project Structure
smart-sensor-analyzer/
├── sensor_simulator.py    # Generates synthetic sensor data (CSV)
├── data_analyzer.py       # Performs statistical analysis & creates plots
├── simple_dashboard.py    # Displays a console-based summary dashboard
├── requirements.txt       # Python dependencies
└── README.md              # This file

🚀 Getting Started
1.Clone & Setup
  git clone https://github.com/Sadek-Dhokar/smart-sensor-analyzer.git
  cd smart-sensor-analyzer
  pip install -r requirements.txt
2.Run the Simulation & Analysis Pipeline
  a. Generate synthetic sensor data
  python sensor_simulator.py
  b. Analyze data and generate plots
  python data_analyzer.py
  c. View the console dashboard
  python simple_dashboard.py

🔍 Key Features & Implementation
Realistic Data Simulation: The sensor_simulator.py script creates timestamped sensor readings with injected anomalies (e.g., random high-vibration events) to simulate real industrial equipment behavior.
Statistical Analysis & Visualization: Using Pandas for data manipulation and Matplotlib for plotting, data_analyzer.py produces time-series graphs and highlights potential anomalies.
Console Dashboard: simple_dashboard.py provides an at-a-glance summary of key metrics, including the latest readings and system status alerts.

🎯 Project Context & Learning Goals
As an Industrial Computer Engineering (GII) student, this project served as a foundational hands-on exercise to build practical skills in data analysis and system simulation—core competencies for future specializations like Intelligent & Interconnected Systems (SII). The goal was to:
Bridge theoretical programming concepts with hands-on Python implementation.
Understand the fundamentals of data pipelines relevant to industrial applications.
Build a modular codebase that separates data generation, analysis, and presentation.

🔮 Future Enhancements
Potential directions to expand this project include:
Integrating a simple machine learning model (e.g., Isolation Forest) for automated anomaly detection.
Converting the console dashboard into an interactive web application using Streamlit.
Simulating data streams from multiple sensor types to model a more complex industrial environment.
