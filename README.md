# Mind Mentor - Mental Health Chatbot  

## Overview  

Mind Mentor is an AI-powered chatbot designed to analyze user statements, assess mental health status, and provide supportive responses. Combining machine learning with natural language processing, it delivers personalized insights in a user-friendly interface.  

## Features  

- **Sentiment Analysis**: Uses VADER to classify statements as positive, negative, or neutral.  
- **Mental Health Prediction**: A machine learning model predicts the user’s mental health status.  
- **AI-Powered Responses**: Generates context-aware replies using Hugging Face's DistilGPT-2.  
- **Interactive Interface**: Gradio-based web UI for seamless and real-time interaction.  

## How It Works  

1. **Data Processing**  
   - Analyzes user input with VADER for sentiment detection.  
   - Uses a labeled dataset to train models for mental health assessment.  

2. **Machine Learning Models**  
   - LinearSVC classifiers predict sentiment and mental health status.  
   - TF-IDF vectorization ensures efficient text processing.  

3. **Response Generation**  
   - AI-generated responses tailored to the detected sentiment and mental health status.  

4. **User Interface**  
   - Simple, web-based chatbot powered by Gradio.  

## Installation  

### 1. Clone the Repository  
```bash
git clone https://github.com/sahilmundada/mind-mentor.git
cd mind-mentor
```  

### 2. Install Dependencies  
```bash
pip install -r requirements.txt
```  

### 3. Run the Chatbot  
Using Jupyter Notebook:  
```bash
jupyter notebook Mind_Mentor.ipynb
```  
Or using Python:  
```bash
python mind_mentor.py
```  

Once running, the chatbot will be available at `http://127.0.0.1:7860`.  

## File Structure  

```
mind-mentor/
├── Mind_Mentor.ipynb        # Main notebook  
├── Combined Data.csv        # Dataset file  
├── README.md                # Documentation  
└── requirements.txt         # Dependencies  
```

## Dataset  

- **Statement**: User input text related to mental health.  
- **Status**: Predicted mental health condition.  

## Performance  

- Accurate classification of mental health status and sentiment.  
- AI-generated responses tailored to the analysis.  

## Limitations  

- Response quality depends on the trained model.  
- Accuracy is influenced by dataset size and diversity.  
- Not a replacement for professional mental health support.  

## Future Enhancements  

- More advanced response generation.  
- Multi-turn conversations for deeper interactions.  
- Improved accuracy with larger datasets.  

## Get Involved  

This is an open-source project—contributions are welcome! Open an issue or submit a pull request to help enhance mental health accessibility.  
