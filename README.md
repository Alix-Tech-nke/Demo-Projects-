# Prediction of Disease Outbreaks

## Overview
This is a Streamlit-based web application that predicts the likelihood of three diseases: 
- **Diabetes**
- **Heart Disease**
- **Parkinson's Disease**

The application takes user input and uses pre-trained machine learning models to provide predictions.

## Features
- User-friendly interface with a sidebar menu for disease selection.
- Accepts user input for various medical parameters.
- Provides instant predictions using trained ML models.
- Built with Streamlit for easy deployment and interaction.

## Installation
### Prerequisites
Ensure you have Python installed on your system. You can download it from [Python's official website](https://www.python.org/).

### Clone the Repository
```sh
https://github.com/Alix-Tech-nke/Demo-Projects-.git
cd your-repository-folder
```

### Install Dependencies
Install the required Python libraries using:
```sh
pip install -r requirements.txt
```
![image](https://github.com/user-attachments/assets/249ff0ba-870f-4dca-b7d5-e5a6e9ec5569)

## Usage
### Running the Application
Execute the following command:
```sh
streamlit run app.py
```
This will start the Streamlit web application in your browser.

## Project Structure
```
.
├── app.py                 # Main application file
├── requirements.txt       # List of dependencies
├── saved_models/          # Folder containing trained ML models
└── README.md              # Project documentation
```

## Dependencies
The required Python libraries are listed in `requirements.txt`:
- `numpy==1.26.3`
- `scikit-learn==1.3.2`
- `streamlit==1.29.0`
- `streamlit-option-menu==0.3.6`

## Contributing
Feel free to fork this repository and submit pull requests with improvements.

## License
This project is licensed under the MIT License.

## Contact
For any questions or issues, please open an issue on the repository or contact the maintainer.
