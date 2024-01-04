# Music-Streaming-App-using-Flask
# Description
This is a Flask-based web application for managing a music library, allowing users to explore, search, and interact with a collection of songs and albums. The application supports different user roles, including regular users and creators. Regular users can browse, search, rate songs, and create playlists, while creators can upload and manage their own songs and albums.

# Features
User Authentication: Supports user registration and login with hashed passwords for security.
Role-Based Access Control: Distinguishes between regular users and creators, each with specific privileges.
Music Library: Allows users to explore and search for songs based on titles, singers, and genres.
Song Ratings: Users can rate songs, and the application displays average ratings for each song.
Playlist Management: Users can create and manage playlists by adding songs.
Creator Dashboard: Creators have access to a dashboard to manage their uploaded songs and albums.
Album Upload: Creators can upload albums by associating existing songs.

# Technologies Used
Flask: Web framework for building the application.
Flask-SQLAlchemy: Integration with SQLAlchemy for database management.
Flask-Login: Handles user authentication and session management.
Flask-WTF: Integrates WTForms for form creation and validation.
Flask-Bcrypt: Provides password hashing for user security.

# Database
The application uses a SQLite database to store user information, music library details, user playlists, song ratings, albums, and creator information.


# Configuration
The application uses a configuration file (config.json) for admin credentials.
Admin credentials can be configured in the config.json file.

# Usage
Visit the application in a web browser: http://localhost:5000
Register or log in as a user or creator.
Explore the music library, rate songs, create playlists, and more.
