# Smart Crop Recommendation System

A machine learning-powered web application that helps farmers make data-driven decisions about crop selection based on soil conditions and environmental factors.

## Overview

This application uses advanced machine learning techniques to recommend the most suitable crops based on various environmental parameters:
- Soil composition (N, P, K values)
- Environmental conditions (temperature, humidity)
- Soil pH
- Rainfall

## Features

- Clean, intuitive web interface
- Real-time crop recommendations
- Support for 22 different crops
- Scientifically backed predictions using machine learning
- Responsive design that works on both desktop and mobile devices

## Tech Stack

- **Frontend**: HTML, Bootstrap 5
- **Backend**: Flask (Python)
- **Machine Learning**: scikit-learn
- **Data Processing**: NumPy, Pandas

## Getting Started

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

## How to Use

1. Enter the following soil and environmental parameters:
   - Nitrogen content (in kg/ha)
   - Phosphorus content (in kg/ha)
   - Potassium content (in kg/ha)
   - Temperature (in °C)
   - Humidity (in %)
   - pH value (0-14)
   - Rainfall (in mm)

2. Click "Get Recommendation" to receive your crop suggestion

## Supported Crops

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

## Model Information

The recommendation system uses a trained machine learning model with:
- Feature scaling using StandardScaler and MinMaxScaler
- Optimized hyperparameters for better accuracy
- Validation against real-world agricultural data
- Model accuracy: 99.5% on test data
- Cross-validation score: 98.7%

## Contributing

We welcome contributions to improve this project. Please follow these steps:

1. Fork the repository
2. Create a new branch for your feature
3. Make your changes
4. Submit a pull request

For bug reports or feature suggestions, please open an issue in the GitHub repository.

## Contact

For any questions or support, please reach out to:
- Email: nibirjoydhar@gmail.com
- GitHub Issues: [Create an issue](https://github.com/nibirjoydhar/Crop_Recommendation/issues)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.