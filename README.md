# NLP Sentiment and text analysis
Sentiment analysis for financial feed data + news API + analysis for text and news articles

## Guidelines
**Install Libraries from Requirements Using pip**
1. Open your terminal (macOS/Linux) or command prompt (Windows).
2. Navigate to the directory where you have downloaded/cloned the repository.
    ```sh
    cd path/to/your/project
    ```
3. (Optional) Create and activate a virtual environment:
      ```sh
      python3 -m venv env
      source venv/bin/activate
      ```
5. Install the required libraries using `pip`:

    ```sh
    pip install -r requirements.txt
    ```
**Run Jupyter Lab with the Notebook and Data**

To run the Jupyter Notebook with all the data in the GitHub repository, follow these steps:

1. Ensure you are still in the project directory.
2. Start Jupyter Lab:

    ```sh
    jupyter lab
    ```
3. A new tab will open in your default web browser, displaying the Jupyter Lab interface.
4. In Jupyter Lab, navigate to the directory where the notebook file (`.ipynb`) is located.
5. Open the notebook file to begin working with it.


**Get NEWS API**

To get your NEWS API Key follow these steps:

1. Navigate to https://newsapi.org/
2. Click on "Get API Key"
3. Register for your API Key
4. Paste it into the file API_KEY
5. Add your API_KEY file to the .gitignore file

## Analysis tasks
**Tasks:**
1. **Get sentiment score out of RSS feed**
    - Score the total sentiment for the selected keyword and ticker
    - Determine positive/negative or neutral sentiment

2. **Get sentiment score out of NEWS API**
    - Score the total sentiment for the selected keyword and date (free API Key get one-day old data)
    - Determine positive/negative or neutral sentiment
3. **Simple text analysis using Bag of Words**
    - Converting text into numerical vectors by counting the frequency of each word in the document 
    - Determine who send the mystery text
4. **Simple news articles analysis using frequency-inverse document frequency (tf-idf)**
    - Evaluating the importance of a word in article collections (news articles)
    - Determining highest scoring term for each article
