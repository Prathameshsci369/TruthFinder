# TruthFinder

TruthFinder is a web application designed to detect fake news by analyzing trending topics from social media platforms like Reddit and YouTube. It utilizes natural language processing techniques to validate claims and provide insights into the accuracy of information.

## Requirements

### Python Packages
- `streamlit`: For building the web application interface.
- `nltk`: For natural language processing tasks, including stopword removal.
- `spacy`: For advanced NLP tasks.
- `torch`: For running the machine learning model.
- `transformers`: For using pre-trained models for claim validation.
- `json`: For handling JSON data.
- `requests`: For making HTTP requests to fetch data from APIs.
- `google-api-python-client`: For interacting with the YouTube API.
- `youtube-transcript-api`: For fetching video transcripts.
- `googletrans`: For translating text.
- `langdetect`: For detecting the language of the text.
- `praw`: For interacting with the Reddit API.

### Model Requirements
- Pre-trained language model (e.g., `microsoft/Phi-3-mini-4k-instruct`) for validating claims.

### Data Requirements
- Access to Reddit and YouTube APIs for scraping trending topics and posts.
- JSON file format for storing scraped data.

### Environment
- Python 3.7 or higher.
- A suitable environment for running the application (e.g., local machine, cloud server).

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Prathameshsci369/TruthFinder.git
   cd TruthFinder
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the application:
   ```bash
   streamlit run app1.py
   ```

2. Open your web browser and navigate to `http://localhost:8501` to access the application.

3. Enter topics of interest and select the desired time frame to fetch trending topics.

4. The application will display the scraped data and validated claims.

## Contributing. 
Contributions are welcome! Please open an issue or submit a pull request for any improvements or features.

## Pro Tip
This project need high power resourceed computer for the havy computing task. So i suggest first you can scrap the data locally after that you will be upload that json file on the you github accound with the analysis.py file. after that you can open the github codespace to changing the url github.com to github.dev , it will be open vs code format open terminal and select the 16gb ram 6 core cpu, and ther you will see the analysis.py and json file , after that theere you can donwnload necessory pakages on mentioned on the anlaysis.py file 1 and 2 line as it command you can copy paste. after that you run the analysis.py file , it will take significantly time to run. after 4 to 5 min you will see the result.
## License
This project is licensed under the MIT License.
