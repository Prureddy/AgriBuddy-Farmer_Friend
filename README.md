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

## Screenshots
![Screenshot 2025-02-01 190513](https://github.com/user-attachments/assets/075fc208-8ca2-4f3d-90cd-b3713cbbe24d)
---------
![Screenshot 2025-02-01 190600](https://github.com/user-attachments/assets/729e5f86-d445-4a7e-ac63-6320d0f4b0ef)
---------
![Screenshot 2025-02-01 190537](https://github.com/user-attachments/assets/c0e047c4-f5ba-46c7-b6f5-4a1e27a8b337)
--------
![Screenshot 2025-02-01 190644](https://github.com/user-attachments/assets/b8adfb02-ff09-4244-ae76-5b62163e11cf)
---------
![Screenshot 2025-02-01 190631](https://github.com/user-attachments/assets/e390b4f5-ebf7-4b1f-bb32-acc7e88c5092)
---------
![Screenshot 2025-02-01 190619](https://github.com/user-attachments/assets/bb34cf9b-571a-43f8-b6de-a2052d4b9d95)
---------
![Screenshot 2025-02-01 190829](https://github.com/user-attachments/assets/9adec7ca-2f7a-44d9-97d7-13519cd9858e)
---------
![Screenshot 2025-02-01 190750](https://github.com/user-attachments/assets/15c9e61b-bdba-4b92-b25c-3275b9b93fe8)
---------





