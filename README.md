# German Grocery Substitute Finder

A Streamlit-based application that helps users find suitable substitutes for ingredients in German grocery stores. The app uses LangChain and ChromaDB to provide intelligent recommendations along with price information and store availability.


## Features

- Real-time ingredient substitute recommendations
- Store availability in German supermarkets (Lidl, Aldi, Penny, etc.)
- Approximate price information
- Similarity scores for recommended substitutes
- Quick response time through optimized caching

<video src="https://github.com/Joemol94/Grocery_substitutes_LLM/blob/main/app_substitutes.mp4" width="300" />

## Tech Stack

- **Frontend**: Streamlit
- **Language Models**: LangChain
- **Vector Database**: ChromaDB
- **Web Scraping**: Custom implementation for price data
- **Python 3.8+**

## Project Structure
├── app.py # Main Streamlit application

├── response_generator.py # Response template and logic

├── llm_initialize.py # LLM initialization and configuration

├── web_scraping.py # Price data scraping functionality from URLs

└── README.md # Project documentation

## Usage
1. Clone the repo
2. Install dependencies - pip install -r requirements.txt
3. Run the app - streamlit run app.py

## Future Improvements
1. To add in store availablity and store locator using specific store api
2. Make it a conversational bot
3. Extend for other country substitutes
