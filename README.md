# Word Cloud Generator

This project is the final submission for the "Crash Course on Python" offered by Google IT Automation with Python on Coursera. It generates a word cloud from any given text using Python.

## Tech Stack

- Python
- Jupyter Notebook

## Features

- Extracts words from text input
- Cleans and preprocesses text data
- Generates a visual word cloud

## Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/iCaran/wordcloud.git
   cd wordcloud
   ```
2. Install the required packages:
   ```sh
   pip install -r requirements.txt
   ```
3. Open the Jupyter notebook:
   ```sh
   jupyter notebook C1M6L2_Final_Project_V3.ipynb
   ```

## Usage

- Load text data from a file
- Clean and preprocess the text
- Generate and display the word cloud

## Example

```python
from wordcloud import WordCloud
import matplotlib.pyplot as plt

# Sample text
text = "Sample text for generating word cloud"

# Generate word cloud
wordcloud = WordCloud(width=800, height=400).generate(text)

# Display the word cloud
plt.figure(figsize=(10, 5))
plt.imshow(wordcloud, interpolation='bilinear')
plt.axis('off')
plt.show()
```

## Resources

- [Project on Coursera](https://www.coursera.org/learn/python-crash-course/)

---
