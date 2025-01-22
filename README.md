# Flutter HTTP GET Example

A Flutter application demonstrating how to fetch and display data from a REST API using HTTP GET requests.

## Features

- Fetches posts from JSONPlaceholder API
- Displays posts in a scrollable list
- Shows post details in a separate screen
- Handles loading and error states
- Uses Flutter's `FutureBuilder` for async operations

## Project Structure

- [`lib/http_service.dart`](lib/http_service.dart) - HTTP service class for API calls
- [`lib/post_model.dart`](lib/post_model.dart) - Post data model
- [`lib/posts.dart`](lib/posts.dart) - Main posts list screen
- [`lib/post_detail.dart`](lib/post_detail.dart) - Detailed view of a post

## How It Works

1. The app uses the `http` package to make GET requests to JSONPlaceholder API
2. Data is fetched in [`HttpService`](lib/http_service.dart) class
3. JSON response is parsed into [`Post`](lib/post_model.dart) objects
4. [`PostsPage`](lib/posts.dart) displays the list of posts
5. Tapping a post opens [`PostDetail`](lib/post_detail.dart) screen

## Getting Started

1. Clone this repository
2. Install dependencies:
```sh
flutter pub get
```
3. Run the app:
```sh
flutter run
```

## Dependencies
Add this to your [`pubspec.yaml`](pubspec.yaml)

```yaml
dependencies:
  http: ^1.1.0
```
## Api Reference
This example uses the JSONPlaceholder API:
- Endpoint: https://jsonplaceholder.typicode.com/posts
- Returns: List of post objects

## Learn More
-Collecting workspace information

Still building the workspace index, response may be less accurate.

Here's a better 

README.md

 that explains the HTTP GET example in Flutter:

```markdown
# Flutter HTTP GET Example

A Flutter application demonstrating how to fetch and display data from a REST API using HTTP GET requests.

## Features

- Fetches posts from JSONPlaceholder API
- Displays posts in a scrollable list
- Shows post details in a separate screen
- Handles loading and error states
- Uses Flutter's `FutureBuilder` for async operations

## Project Structure

- [`lib/http_service.dart`](lib/http_service.dart) - HTTP service class for API calls
- [`lib/post_model.dart`](lib/post_model.dart) - Post data model
- [`lib/posts.dart`](lib/posts.dart) - Main posts list screen
- [`lib/post_detail.dart`](lib/post_detail.dart) - Detailed view of a post

## How It Works

1. The app uses the `http` package to make GET requests to JSONPlaceholder API
2. Data is fetched in [`HttpService`](lib/http_service.dart) class
3. JSON response is parsed into [`Post`](lib/post_model.dart) objects
4. [`PostsPage`](lib/posts.dart) displays the list of posts
5. Tapping a post opens [`PostDetail`](lib/post_detail.dart) screen

## Getting Started

1. Clone this repository
2. Install dependencies:
```sh
flutter pub get
```
3. Run the app:
```sh
flutter run
```

## Dependencies

Add this to your 

pubspec.yaml

:
```yaml
dependencies:
  http: ^1.1.0
```

## API Reference

This example uses the JSONPlaceholder API:
- Endpoint: https://jsonplaceholder.typicode.com/posts
- Returns: List of post objects

## Learn More

- [Flutter HTTP documentation](https://docs.flutter.dev/cookbook/networking/fetch-data)
- [JSONPlaceholder API](https://jsonplaceholder.typicode.com/)
