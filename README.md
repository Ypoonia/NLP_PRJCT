# OpenSox

## Overview
OpenSox is a powerful tool designed to recommend top 3 GitHub issues for developers based on their preferred programming language. By leveraging NLP techniques, OpenSox efficiently identifies relevant issues to help developers contribute effectively to open-source projects.

## Features
- **Data Scraping:** Custom web scraping for fetching GitHub issues.
- **Pre-processing:** Includes cleaning text, removing stopwords, and tokenization.
- **Text Cleaning:** Ensures data is clean and organized for analysis.
- **TF-IDF Vectorization:** Uses Term Frequency-Inverse Document Frequency for effective text representation.
- **Cosine Similarity Calculation:** Identifies top 3 issues relevant to the provided language.

## Technologies Used
- **Python Libraries:**
  - NLP
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - NLTK (Natural Language Toolkit)

## Installation
1. Clone the repository:
   ```bash
   git clone <repository_link>
   ```
2. Navigate to the project directory:
   ```bash
   cd OpenSox
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Scrape or import the data.
2. Run the preprocessing script to clean the data:
   ```bash
   python preprocess.py
   ```
3. Execute the main script to find the top 3 issues related to a given language:
   ```bash
   python main.py <language_name>
   ```

## Data Processing Pipeline
1. **Data Scraping:** Custom scraping logic gathers GitHub issues data.
2. **Preprocessing Steps:**
   - Stopword removal
   - Tokenization
   - Text cleaning
3. **TF-IDF Vectorization:** Converts textual data into meaningful numerical representations.
4. **Cosine Similarity:** Measures text similarity to identify top 3 relevant issues.

## Example
```bash
python main.py Python
```
**Output:**
1. Memory Leak Handling
2. Import Errors
3. Dependency Conflicts

## Contribution
Feel free to contribute by creating pull requests or reporting issues.

## License
This project is licensed under the MIT License.

