# movies-app
A movies webpage developed using HTML, CSS and JavaScript for frontend and Node and MongoDB for backend. Movies data is fetched from [TMDB API](https://developer.themoviedb.org/docs/getting-started).

## Features:
- Fetch latest movies by popularity.
- Add, edit and delete reviews for movies.

## How to run the project?
1. Create or sign in to MongoDB. Craete a new project, then create a new database, then create username and password for connection authentication of that database.
2. Clone the repository.
3. Go to the backend folder.
4. Create a .env file in the root of this directory. Add MONGO_USERNAME and MONGO_PASSWORD from the first step.
5. Do "npm i".
6. Run "nodemon"
7. Now if you want to run Frontend just install the live server extension and click on "Go Live" from your bottom right corner.

**NOTE:** Backend must be running first.

## For contribution
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Make your changes.
4. Push your branch: `git push origin feature-name`.
5. Create a pull request.