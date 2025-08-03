# 🎶 Hertz Music Streaming Service

A relational database project built with MySQL for Hertz, a music streaming service inspired by platforms like Spotify and Apple Music. The project showcases SQL scripts for creating and populating tables, with a focus on SQL schema design, data modeling, and complex querying. Designed to handle large-scale data efficiently, this database management system ensures fast, responsive performance while managing user data, music libraries, playlists, subscriptions, and more. It highlights the importance of a well-structured DBMS for seamless data storage, retrieval, and scalability.

## 🗂️ Tables & Entities

1. **USERS**: Stores user details such as name, username, email, and date of birth.
2. **GENRES**: Defines different music genres with descriptions.
3. **ARTISTS**: Stores artist information, including name, bio, their main genre, and associated music label.
4. **ALBUMS**: Contains albums, linked to artists, with release dates.
5. **SONGS**: Stores song details, including title, artist, album, genre, release date, and duration.
6. **PLAYLISTS**: User-created playlists, with descriptions and creation information.
7. **PLAYLISTS_SONGS**: Joins playlists and songs, including song position within the playlist.
8. **USER_LIBRARY**: Tracks albums and artists added to a user’s personal library.
9. **PLAYBACK_HISTORY**: Tracks users' song plays, including playlist and date information.
10. **RECOMMENDATIONS**: Song recommendations for users based on playlists.
11. **SUBSCRIPTION_PLANS**: Various subscription tiers with cost and benefits.
12. **SUBSCRIPTIONS**: Records user subscriptions to plans, with start and expiration dates.
13. **PAYMENTS**: Tracks payment status for subscriptions.
14. **USER_REVIEWS**: Reviews for songs, including ratings and comments from users.
15. **MUSIC_CHARTS**: Music charts by genre and chart type.
16. **CHART_SONGS**: Joins charts and songs, indicating their rank.
17. **MUSIC_LABELS**: Records information about music labels, including founder and year founded.
18. **MUSIC_LICENSE**: Defines music license types and associated costs.
19. **ALBUM_LICENSE**: Tracks licenses associated with albums.
20. **FOLLOWERS**: Tracks which users follow which artists and when.

## 📊 Schema Visualizations

The **Entity Relationship Diagram (ERD)** represents the relationships between the various entities in the Hertz database.

![ER Diagram](https://github.com/FatimaNW/Hertz-Music-Streaming-Service/blob/main/Entity%20Relationship%20Diagram.png)

The **Physical ERD** shows the type of relationship between each table and the primary and foreign keys.

![Physical ERD.png](https://github.com/FatimaNW/Hertz-Music-Streaming-Service/blob/main/Physical%20ERD.png)

#
**Note:** This project was created during my second year of university as part of DataBase Management Systems (DBMS) course.
