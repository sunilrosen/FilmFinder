# FilmFinder

A web-based application that provides personalized movie recommendations using content-based filtering. Built with **Streamlit**, this app leverages a pre-computed cosine similarity matrix and the TMDB API to suggest similar movies and display their posters.

## Features

- **Movie Recommendation**: Input a movie title and get 10 similar movie recommendations.
- **Poster Display**: Visualize movie recommendations with their posters fetched from the TMDB API.
- **Interactive UI**: User-friendly interface built with Streamlit.
- **Efficient Filtering**: Uses cosine similarity for content-based recommendations.

## Tech Stack

- **Frontend**: [Streamlit](https://streamlit.io/)
- **Backend**: Python
- **APIs**: [TMDB API](https://www.themoviedb.org/documentation/api)
- **Data Processing**: Pandas, Pickle