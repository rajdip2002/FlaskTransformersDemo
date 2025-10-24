# Flask NLP Web App with Hugging Face Transformers

A web application built with Flask and Hugging Face Transformers that allows users to perform multiple NLP tasks through a simple web interface.

---

## Features

The app supports the following NLP tasks:

1. Sentiment Analysis – Determine if a text is positive or negative.  
2. Text Generation – Generate text based on a user prompt.  
3. Translation – Translate text (English ↔ French).  
4. Summarization – Condense long texts into a summary.  
5. Named Entity Recognition (NER) – Identify entities like names, locations, and organizations.

---

## Installation

1. Clone the repository:

git clone https://github.com/rajdip2002/FlaskTransformersDemo.git
cd FlaskTransformersDemo

2. Create a virtual environment:

python -m venv myenv

3. Activate the virtual environment:

myenv\Scripts\activate

4. Install dependencies:

pip install -r requirements.txt


---

# Usage

1. Start the Flask server:

python 1_pipeline.py


2. Open your browser and go to:

http://127.0.0.1:5000/


3. Enter text, select the NLP task from the dropdown, and click Submit to see results.
