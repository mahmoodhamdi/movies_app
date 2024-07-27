# Movies Clean Architecture App

This project is developed as part of a learning and practice exercise for implementing Clean Architecture using Flutter. The course on Udemy provides detailed instructions and guidance in Arabic on building this app with Flutter.

## Project Overview

This application demonstrates a clean architecture approach for a movies app. It is not intended for deployment but serves as a practice project to understand and apply clean architecture principles.

## Project Structure

The project is divided into three main layers:

1. **Data Layer:** Handles data fetching and storage.
2. **Domain Layer:** Contains business logic and entities.
3. **Presentation Layer:** Manages the user interface and state.

### Data Layer

- [x] **movie_remote_data_source:** Handles API calls to fetch movie data.
- [x] **recommendation_model:** Represents the data model for movie recommendations.
- [x] **movie_model:** Represents the data model for movies.
- [x] **movie_details_model:** Represents the data model for movie details.
- [x] **genres_model:** Represents the data model for genres.
- [x] **movies_repository:** Provides an interface for data access.

### Domain Layer

- [x] **entities:** Contains domain entities such as genres, movie_detail, movie, and recommendation.
- [x] **base_movies_repository:** Defines the contract for the movies repository.
- [x] **get_movie_details_usecase:** Use case for fetching movie details.
- [x] **get_now_playing_movies_usecase:** Use case for fetching now playing movies.
- [x] **get_popular_movies_usecase:** Use case for fetching popular movies.
- [x] **get_recommendation_usecase:** Use case for fetching movie recommendations.
- [x] **get_top_rated_movies_usecase:** Use case for fetching top-rated movies.

### Presentation Layer

- [x] **now_playing_component:** UI component for displaying now playing movies.
- [x] **popular_component:** UI component for displaying popular movies.
- [x] **top_rated_component:** UI component for displaying top-rated movies.
- [x] **movie_details_bloc:** BLoC for managing movie details state.
- [x] **movie_details_event:** Events for movie details BLoC.
- [x] **movie_details_state:** States for movie details BLoC.
- [x] **movies_bloc:** BLoC for managing movies state.
- [x] **movies_event:** Events for movies BLoC.
- [x] **movies_state:** States for movies BLoC.
- [x] **movie_detail_screen:** UI screen for displaying movie details.
- [x] **movies_screen:** UI screen for displaying movies list.

## Features

- [x] Fetch and display now playing movies
- [x] Fetch and display popular movies
- [x] Fetch and display top-rated movies
- [x] View movie details
- [x] Get movie recommendations

## Getting Started

### Prerequisites

- Flutter SDK: [Install Flutter](https://flutter.dev/docs/get-started/install)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/cinemascope.git
   cd cinemascope
   ```

2. Install dependencies:

   ```bash
   flutter pub get
   ```

3. Run the app:

   ```bash
   flutter run
   ```

## Resources

- [Udemy Course: Flutter Clean Architecture 2022 - Flutter 3 in Arabic](https://www.udemy.com/course/flutter-clean-architecture-2022-flutter-3-in-arabic/)

## Acknowledgments

- Thanks to [Usama Elgindy](https://github.com/usamaaelgendy) for the excellent course
