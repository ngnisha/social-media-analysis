# social-media-analysis
EDA is done on  sample data of social media to have insights on social media like Instagram, Facebook , Twitter etc   on Ms sql server  <br><br>

## Social Media Database

This repository contains a database schema for a social media platform. The database is designed to model various aspects of a social media platform, including users, posts, comments, likes, follows, hashtags, and more. Below is an overview of the key components of this database:

### Tables

- **users**: Stores user information, including their username, email, profile photo URL, bio, and registration date.

- **photos** and **videos**: Store multimedia content with information about the content's URL, owner, creation date, and size.

- **post**: Represents user-generated posts, which can include photos, videos, a caption, location, and creation date.

- **comments**: Contains user comments on posts, with the comment text, post ID, user ID, and creation date.

- **post_likes** and **comment_likes**: Track user interactions by recording likes on posts and comments.

- **follows**: Captures the relationships between users, indicating who follows whom.

- **hashtags**: Stores information about hashtags used in posts.

- **hashtag_follow**: Records the associations between users and hashtags they follow.

- **post_tags**: Represents the relationships between posts and the hashtags they use.

- **bookmarks**: Tracks which users have bookmarked which posts.

### Queries and Features

In this repository, we provide a set of advanced SQL queries that offer insights into the data, such as finding the most popular hashtags, calculating average comments per post, and updating follower counts when someone follows or unfollows a user.

This database schema can serve as a foundation for developing a social media application, and the queries and features can be used to analyze user engagement, content popularity, and more.

Feel free to explore the schema, queries, and features provided in this repository to better understand and utilize the social media database.

**Note**: When using the provided SQL queries, please ensure that you adapt them to your specific database environment, whether you are using SQL Server, MySQL, or another database system.



