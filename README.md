# IBharatM Health Care AI Project

![Project Banner](https://via.placeholder.com/1200x400.png?text=IBharatM+Health+Care+AI)  
*An innovative solution for early detection of lung diseases using AI.*

---

## Introduction

**IBharatM Health Care AI** is a cutting-edge healthcare project aimed at assisting medical professionals and individuals in identifying lung diseases like **COVID-19**, **Pneumonia**, and normal conditions from chest X-rays. Built using **Microsoft Azure Custom Vision Service**, the application predicts disease probabilities and provides an interactive interface for better analysis. The project also integrates the **Microsoft Health Bot Service**, offering users healthcare-related guidance.

---

## Features
- **Chest X-ray Disease Detection**: Predict lung diseases from uploaded or URL-based chest X-rays.
- **Interactive Visualizations**: Analyze predictions using bar graphs, pie charts, and progress bars.
- **Health Bot Assistance**: Get healthcare-related advice and information from the integrated bot.
- **User-Friendly Interface**: A sleek desktop application built with **PySide6**.

---

## Technology Stack
- **Programming Language**: Python 3.8+
- **Cloud Services**: Microsoft Azure Custom Vision, Microsoft Health Bot
- **Libraries**:
  ```
  - PySide6: GUI framework
  - Pillow: Image processing
  - Requests: API interaction
  - Matplotlib: Data visualization
  ```

---

## Team Members
- **Atharva Deshmukh** (Team Lead)  
- **Gourav Kushwaha** (Team Lead)  
- **Sonu Kushwaha**  
- **Naushad Ali**

---

## How It Works
1. **Custom Vision AI Model**: Trained on datasets of chest X-ray images (COVID-19, pneumonia, normal lungs).
   - Upload or link an X-ray image.
   - Get predictions for potential diseases with associated probabilities.
2. **Interactive Results**:
   - View results in graph formats (bar graph, pie chart, etc.).
3. **Health Bot**:
   - Provides healthcare information, including disease symptoms, tips, and general assistance.

---

## Installation

### Prerequisites
```
- Python >= 3.8
```
- An active internet connection for API calls.

### Steps
1. Clone the repository:
   ```
   git clone https://github.com/your-username/ibharatm-healthcare-ai.git
   cd ibharatm-healthcare-ai
   ```
2.  Install dependencies:
```
     pip install -r requirements.txt
```
4. Run the application:
```
   python main.py
```

## Usage
Launch the application.
Upload a chest X-ray image or provide a URL.
Wait for the AI model to analyze the image.
View the prediction results along with interactive graphs.
Use the Health Bot for further healthcare-related guidance.

## Screenshots
1. Application Home Screen

2. X-ray Upload & Prediction

3. Health Bot Interface

## Demo Video

##  Set Up a Virtual Environment
It is recommended to use a virtual environment to isolate dependencies. Follow these steps:

On Windows:
```
python -m venv venv
venv\Scripts\activate
```

On macOS/Linux:
```
python3 -m venv venv
source venv/bin/activate
```


## Configure API Keys
Add your Azure Custom Vision Prediction Key and Endpoint in the predict_image() function in the main.py file:
```
headers = {
    "Prediction-Key": "YOUR_AZURE_PREDICTION_KEY"
}
url = "YOUR_AZURE_CUSTOM_VISION_URL"
```

## Requirements
Refer to the requirements.txt file for all dependencies:

### **requirements.txt File:**
```
plaintext
PySide6==6.6.0
requests==2.31.0
Pillow==9.2.0
matplotlib==3.8.0
```

## Contributions
We welcome contributions!
```
Fork the repository.
Create a new branch: git checkout -b feature/YourFeatureName.
Commit your changes: git commit -m 'Add some feature'.
Push to the branch: git push origin feature/YourFeatureName.
Open a pull request.
```
