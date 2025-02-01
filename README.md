# Crop Yield Prediction

This project is a web application designed to predict crop yield based on various input parameters and visualize the data through different charts and maps. It also provides a chatbot for answering agricultural queries and weather-based agricultural advice.

## Features
- **Crop Yield Prediction:** Predict crop yield based on input parameters such as year, average rainfall, pesticides used, average temperature, area, and crop type.
- **Data Visualization:** Visualize crop yield data through various charts, including yearly yield, crop-wise comparison, and time series analysis.
- **Mapping:** Display top crops by area on a world map.
- **Chatbot:** Answer agricultural queries using a chatbot powered by Google Generative AI.
- **Weather-based Agricultural Advice:** Provide agricultural recommendations based on current weather conditions.

## Project Structure
```
.
├── .gitignore
├── app.py
├── Crop Yield Prediction.ipynb
├── dtr.pkl
├── indian_map.html
├── LICENSE
├── preprocessor.pkl
├── README.md
├── requirements.txt
├── static/
│   └── images/
├── templates/
│   ├── chatbot.html
│   ├── index.html
│   ├── mapping.html
│   └── visualization.html
├── venv/
│   ├── ...
├── world_map.html
└── yield_df.csv
```

## Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/crop-yield-prediction.git
   cd crop-yield-prediction
   ```

2. **Create and activate a virtual environment:**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages:**
   ```sh
   pip install -r requirements.txt
   ```

4. **Set up environment variables:**
   ```sh
   export GOOGLE_API_KEY=your_google_api_key
   export WEATHER_API_KEY=your_weather_api_key
   ```

## Usage

1. **Run the Flask application:**
   ```sh
   python app.py
   ```

2. **Open your web browser and navigate to:**
   ```
   http://127.0.0.1:5000/
   ```

## Routes

| Route          | Description                                        |
|---------------|--------------------------------------------------|
| `/`           | Home page for crop yield prediction.             |
| `/mapping`    | Displays a world map with top crops by area.     |
| `/visualization` | Shows various visualizations of crop yield data. |
| `/chatbot`    | Chatbot interface for answering agricultural queries. |
| `/farmAI`     | Endpoint for handling agricultural queries.      |
| `/weatherAI`  | Endpoint for providing weather-based agricultural advice. |

## Data
- **yield_df.csv:** CSV file containing crop yield data.
- **dtr.pkl:** Pickle file containing the trained decision tree regression model.
- **preprocessor.pkl:** Pickle file containing the preprocessor for input features.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements
This project utilizes:
- Flask
- Pandas
- Matplotlib
- Seaborn
- Folium
- Google Generative AI

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

