# authentication_system
User registration and authentication in nodejs with data stored in MongoDB.

It is basic authentication system, with just email, name and password. 
The system bases on access token, which expires after given time, 
and the refresh token, which is persistent and stored in DB. It is used to generate new access token.
Email, refresh token and access token must be stored at the frontend. It is needed for relogin.

Instructions:
1. Create new table in MongoDB.
2. Change data in config file.
3. Read API docs.
4. Develop frontend. Server is adapted to Android, iOS and websites.
5. Run the index.js file.