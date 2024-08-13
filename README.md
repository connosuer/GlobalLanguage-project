# Language Clustering using Word Embeddings

## Project Overview
This project uses K-means clustering to group languages based on their semantic similarities using word embeddings. It visualizes how different languages relate to each other in terms of meaning and structure, providing insights into linguistic relationships.

## Features
- Utilizes pre-trained word embeddings (GloVe) for multiple languages
- Applies dimensionality reduction (PCA) for visualization
- Implements K-means clustering to group similar languages
- Visualizes language clusters in a 2D plot

## Requirements
- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Gensim

## Installation
1. Clone this repository
2. Install the required packages:
   ```
   pip install numpy pandas matplotlib scikit-learn gensim
   ```

## Usage
Run the script `language_clustering.py`:
```
python language_clustering.py
```

The script will download the necessary word embeddings, perform the analysis, and display a plot showing language clusters.

## How it works
1. Downloads pre-trained word vectors using Gensim
2. Creates language vectors by averaging word embeddings for each language
3. Applies PCA to reduce dimensionality to 2D for visualization
4. Uses K-means clustering to group languages
5. Visualizes the results in a scatter plot

## Results
The resulting plot shows language clusters based on semantic similarities. Observations include:
- Grouping of languages with similar origins (e.g., Romance languages)
- Isolation of languages with unique features (e.g., Arabic)
- Clustering of Asian languages

## Future Improvements
- Expand the list of languages
- Experiment with different clustering algorithms
- Create an interactive visualization
- Analyze specific words or features contributing to the clustering

## Contributing
Contributions to improve the project are welcome. Please fork the repository and submit a pull request with your changes.

## License
[MIT License](https://opensource.org/licenses/MIT)
