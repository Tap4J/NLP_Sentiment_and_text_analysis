# NLP Sentiment Analysis
Sentiment analysis for financial feed data + news API 

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
**Get NEWS API**

To get your NEWS API Key follow these steps:

1. Navigate to https://newsapi.org/
2. Click on "Get API Key"
3. Register for your API Key
4. Paste it into the file API_KEY
5. Add your API_KEY file to the .gitignore file

## Analysis task
**Tasks:**
1. Get sentiment score out of RSS feed
    - Score the total sentiment for the selected keyword and ticker
    - Determine positive/negative or neutral sentiment

2. Get sentiment score out of NEWS API
    - Score the total sentiment for the selected keyword and date (free API Key get one-day old data)
    - Determine positive/negative or neutral sentiment
