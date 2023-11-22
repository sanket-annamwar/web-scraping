# web-scraping
# Web Scraping and Text Classification Application

This application performs web scraping on the NPR website to collect news articles and then applies text classification to categorize the articles into different sections. The classification model is trained using Natural Language Processing (NLP) techniques.

## Instructions to Run the Application

### Prerequisites

- Python 3.x installed
- Required Python packages installed (`selenium`, `beautifulsoup4`, `pandas`, `scikit-learn`, `nltk`)
- ChromeDriver installed and added to the system PATH

### Setup

1. **Clone the repository:**

    ```bash
    git clone https://github.com/sanket-annamwar/web-scraping.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd your-repo
    ```

3. **Install the required Python packages:**

    ```bash
    pip install -r requirements.txt
    ```
##Screenshots
  ![Screenshot1](wed-scraping/screenshots/Screenshot1)

### Web Scraping

1. **Run the web_scraping.py script to gather news articles from NPR:**

    ```bash
    python web_scraping.py
    ```

   This script scrapes articles from different sections of the NPR website and saves the data to CSV files (`scraped_data1.csv`, `scraped_data2.csv`, etc.).

### Text Classification

1. **Ensure you have the required datasets in the project folder (e.g., scraped_data1.csv, scraped_data2.csv).**

2. **Run the text_classification.py script to preprocess the text, train the classification model, and evaluate its performance:**

    ```bash
    python text_classification.py
    ```

   The script will display accuracy and classification reports for the text classification model.

## Notes

- Make sure to update the `section_list` variable in `web_scraping.py` to customize the sections you want to scrape.

- If needed, adjust the parameters in the text classification script (`text_classification.py`) such as vectorizer settings, model parameters, etc.

- Feel free to explore and modify the code to suit your specific use case or enhance functionality.

