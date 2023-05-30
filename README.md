# Spotify Song Popularity Prediction

## Description 

This project aims to predict the popularity of songs on Spotify using different regression models. A Spotify dataset is used that contains musical characteristics of the songs, such as danceability, energy, key, loudness, mode, speechiness, instrumentalness, liveness, valence, tempo, and duration_ms.
## Requirements

- Python 3
- Python Libraries: pandas, scikit-learn

## Install

1. Clone the code for this repository: `git clone https://github.com/tu_usuario/tu_repositorio.git](https://github.com/SebMoraG/Song-Popularity-Prediction/`
2. Use the dateset in this repository to put in the code and see the results: `SpotifySongP.csv`
3. If you want to do the project from 0 use tgis dateset to clear it first: 'SpotifySongPolularityAPIExtract'


## Uses
1. Make sure you have the data in CSV format and save it in the `data` folder.
2. Run `main.py` file to perform song popularity analysis and prediction on Spotify.

## Results

Different regression models have been used, including Linear Regression, Ridge, Lasso and Random Forest, in order to find the model with the best performance. The results obtained are the following:

- Linear Regression:
  - Puntaje: -409.23225691079836
  - Mejores parámetros: {}

- Ridge:
  - Puntaje: -409.2145178262232
  - Mejores parámetros: {'alpha': 10.0}

- Lasso:
  - Puntaje: -410.9271983131269
  - Mejores parámetros: {'alpha': 0.1}

- Random Forest:
  - Puntaje: -383.54391206106504
  - Mejores parámetros: {'n_estimators': 200}

## Contribution

Contributions to this project are welcome. If you have any suggestions, improvements, or fixes, please create a new pull request or open a new issue.

## License

This project is licensed under the MIT License. You can see more details in the [LICENSE](LICENSE) file.

****


# Song-opularity-Prediction
Thi is a ML projecto using the Spotify Song Polularity API Extract and making a grid search to find out with of those give us the best result to see the popularirty of the songs.
