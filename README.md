# Client Sentiment Analysis using Pre-trained ML Models

Client Sentiment Analysis using Pre-trained ML Models is a project aimed at analyzing and classifying the sentiment of client feedback using pre-trained machine learning models. The project leverages state-of-the-art natural language processing techniques to determine whether the sentiment expressed in the client's message is positive, negative, or neutral.

Due to miscalculation of project scope and cleaningness of initial data, project initial set-up took longer than expected, therefore the final output is not yet finished. The next steps of the project will include:
- Concordance and Collocation
- Message length / Sentiment label analysis, 
- Join post purchase data (that is cleaned already) and perform segmentation / linear regression model to analyse if specific words / message length contributes to bigger sub-cancelation / refund / chargeback rate. 

## Features

- Utilizes pre-trained ML models for sentiment analysis
- Supports analysis of client feedback in multiple languages (in progress)
- Provides sentiment classification for different types of client messages (in progress)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/whoislukas/ds_final.git
   ```

2. Navigate to the project directory:

   ```bash
   cd client-sentiment-analysis
   ```

3. Create a virtual environment:

   ```bash
   python3 -m venv venv
   ```

4. Activate the virtual environment:

   - For Linux/MacOS:

     ```bash
     source venv/bin/activate
     ```

   - For Windows:

     ```bash
     venv\Scripts\activate
     ```

5. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```
## Files this repository includes:
   - dataset folder (sample datasets)
   - ds_final.ipynb notebook 
   - requirements.txt
## Usage

1. Open ds_final.ipynb
2. Change placeholder generated_dataset.csv with original dataset.
3. Run the notebook and explore!

## Aknowlegment

Special thanks to CodeAcademy community and lecturers Domantas and Dainius for their time and effort during the course!
