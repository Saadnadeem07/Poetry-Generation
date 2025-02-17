# Roman Urdu Poetry Generator

## Overview
This project involves scraping Roman Urdu poetry, training an LSTM model to generate poetry, and deploying the model using Gradio. The goal is to create a web-based poetry generator that allows users to input a seed phrase and generate poetry based on learned patterns.

## Features
- **Web Scraping:** Poetry data collected from [Rekhta.org](http://rekhta.org/)
- **LSTM Model:** Trained on Roman Urdu poetry for text generation
- **Gradio UI:** User-friendly interface for generating poetry
- **Deployment:** Hosted via Streamlit for public access

## Demo
You can try out the poetry generator at: **[Streamlit Deployment Link]** (replace with actual link)

## Installation
To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/roman-urdu-poetry-generator.git
   cd roman-urdu-poetry-generator
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Gradio application:
   ```bash
   python app.py
   ```

## Dataset
- Scraped Roman Urdu poetry dataset from Rekhta.org.
- Cleaned and preprocessed for training.

## Model
- **Architecture:** LSTM-based recurrent neural network
- **Training:** Model trained on scraped poetry data
- **Parameters:** Tuned for optimal text generation performance

## Deployment
The model is deployed using Gradio and hosted via Streamlit. It provides an easy-to-use interface where users can input a seed phrase, set the number of words and temperature, and generate poetry.

## How It Works
1. Enter a seed phrase in Roman Urdu.
2. Adjust the number of words and temperature for variability.
3. Click **Submit** to generate poetry.
4. Poetry is displayed in real-time in the output box.

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests.

## License
This project is licensed under the MIT License.

---
### Contact
For any questions, feel free to connect with me on [LinkedIn](replace with actual link) or open an issue on GitHub.

