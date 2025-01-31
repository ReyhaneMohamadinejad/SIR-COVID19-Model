# SIR-COVID19-Model-Before-and-After-Beta-Calibration
COVID-19 Spread Simulation Using the SIR Model

📌 Overview

This project simulates the spread of COVID-19 using the Susceptible-Infected-Recovered (SIR) model. The model uses real-world fitted parameters (β and γ) from the provided dataset to analyze and predict the dynamics of the outbreak in different locations.

📊 Features

Reads real-world COVID-19 data from per_location_fitted_params.csv

Uses β (infection rate) and γ (recovery rate) from the dataset

Implements the SIR model using ODEs (Ordinary Differential Equations)

Simulates the spread of COVID-19 for a selected location

Visualizes the results using Matplotlib

🏗️ Installation

To run this project, you need Python 3.x and the following dependencies:

pip install numpy pandas scipy matplotlib

📈 Results

The output graph will show three curves:

🔵 Susceptible (S): People who have not been infected yet.

🔴 Infected (I): People currently infected with the virus.

🟢 Recovered (R): People who have recovered and gained immunity.

The model helps analyze peak infection time, herd immunity thresholds, and disease progression.

🛠️ Customization

You can change the location by modifying the region variable in the script.

Adjust the days parameter to simulate for a longer or shorter period.
