# 🌱 Smart Crop Recommendation System

A machine learning-powered web application that helps farmers make data-driven decisions about crop selection based on soil conditions and environmental factors.

## 🎯 Overview

This application uses advanced machine learning techniques to recommend the most suitable crops based on various environmental parameters:
- Soil composition (N, P, K values)
- Environmental conditions (temperature, humidity)
- Soil pH
- Rainfall

## ✨ Features

- Clean, intuitive web interface
- Real-time crop recommendations
- Support for 22 different crops
- Scientifically backed predictions using machine learning
- Responsive design that works on both desktop and mobile devices

## 🛠️ Tech Stack

- **Frontend**: HTML, Bootstrap 5
- **Backend**: Flask (Python)
- **Machine Learning**: scikit-learn
- **Data Processing**: NumPy, Pandas

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip package manager

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Crop_Recommendation.git
   cd Crop_Recommendation
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv myenv
   source myenv/bin/activate  # On Windows: myenv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Application

1. Start the Flask server:
   ```bash
   python app.py
   ```

2. Open your browser and navigate to:
   ```
   http://localhost:5000
   ```

## 📝 How to Use

1. Enter the following soil and environmental parameters:
   - Nitrogen content
   - Phosphorus content
   - Potassium content
   - Temperature (in °C)
   - Humidity (in %)
   - pH value
   - Rainfall (in mm)

2. Click "Get Recommendation" to receive your crop suggestion

## 🌟 Supported Crops

The system can recommend various crops including:
- Rice
- Maize
- Jute
- Cotton
- Coconut
- Papaya
- Orange
- Apple
- Muskmelon
- Watermelon
- Grapes
- Mango
- Banana
- Pomegranate
- Various pulses (Lentil, Blackgram, etc.)
- Coffee
- And more!

## 📊 Model Information

The recommendation system uses a trained machine learning model with:
- Feature scaling using StandardScaler and MinMaxScaler
- Optimized hyperparameters for better accuracy
- Validation against real-world agricultural data

## 🤝 Contributing

Feel free to fork this project and submit pull requests. You can also open issues for bugs or feature suggestions.

## 📜 License

This project is open source and available under the MIT License.