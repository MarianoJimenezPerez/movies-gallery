# Movie Gallery Exercise

This is a simple exercise to test your skills in the following areas:

- NodeJS
- Typescript
- React
- Full Stack Development

<!-- TOC -->

- [Movie Gallery Exercise](#movie-gallery-exercise)
  - [Description](#description)
  - [Functional Requirements](#functional-requirements)
    - [Bonus Functional Features](#bonus-functional-features)
  - [Technical Requirements](#technical-requirements) \* [Bonus Technical Features](#bonus-technical-features)
  <!-- TOC -->

## Description

Develop a simple web application that allows users to view a gallery of movies. The main focus should be on covering
the **functional and technical requirements**, but also on the overall architecture and code quality, the UI/UX is
not as essential as making sure the application is working as expected.

## Functional Requirements

- The application should have a home page displaying a **gallery of movies**, each item must show the following
  information:
  - Title
  - Release Year
  - Poster
  - Duration
  - Amount of Ratings & Average Rating
  - Amount of Comments
- By clicking on a movie, the user should be able to see the **movie details**, which are the fields previously
  mentioned, plus the following:
  - Genre
  - Release Date
  - Plot
  - List of Comments
- The application must have a search bar that allows the user to search for movies by title
- The application must have a filter that allows the user to filter movies by:
  - Release Year
  - Genre
- The application must have a sort option that allows the user to sort the movies by:
  - Release Year
  - Average Rating
  - Amount of Ratings
  - Amount of Comments
- Allow visitors to register and login to the application
- All visitors should be able to do the following:
  - See the movie gallery
  - See the movie details
  - Search for movies
  - Use the filters
- Only logged-in users should be able to do the following:
  - Add a Movie
  - Edit a Movie
  - Rate a movie (1-5 stars)
  - Change their own rating
  - Mark a movie as favorite
  - Add comments (up to 200 characters)

### Bonus Functional Features

- The application must have a **pagination system** that allows the user to navigate through the movies
- Only the **"Creator"** of the Movie is allowed to **edit it**
- Add a "My Favorites" filter that displays the movies that the user has **marked as favorite**
- Add a "Top 10" filer that displays the top 10 movies by **average rating**
- Add a "Most Commented" filter that displays the 10 movies with the **most comments**
- Add a "Most Recent" filter that displays the 10 **most recent added** movies
- Add a "Random" filter that displays 10 **random** movies
- Add a "Freshies" filter that displays the 10 movies with the **most recent release date**
- Add a sort option that allows the user to sort the movies by **Amount of Ratings**
- Add a sort option that allows the user to sort the movies by **Amount of Comments**

## Technical Requirements

- The application must be developed using **NodeJS** and **Typescript** (both backend and frontend)
- The backend must be developed with **[Apollo Server][apollo-server]**
- The frontend must be developed with **[Next.js][nextjs]**
- The fronted can use **any kind of CSS framework** (e.g. Bootstrap, Tailwind, etc.... or none)
- The application must use a **SQL database** (e.g. PostgreSQL, MySQL, MariaDB, etc.)
- The application must use **[TypeORM][typeorm]** as ORM
- Both backend and frontend must have a simple **Readme** file with instructions on how to run the application
- Both backend and frontend must have a simple **Dockerfile** that allows to run the application as a container
- The application must have a **CI/CD pipeline** that runs the tests and builds the application
- The code must be hosted in a **Git repository** (e.g. GitHub, GitLab, Bitbucket, etc.) and temporal access must be
  granted to the reviewers

### Bonus Technical Features

- The application must have a **Docker Compose** file that allows to run the application as a set of containers
- The backend uses Migrations definitions from the ORM to mutate the database schema
- Any kind of testing (e.g. Unit, Integration, E2E, etc.)
- A **seed functionality** that allows to populate the database with some initial data
- The backend uses a **"Code First"** approach to generate the GraphQL schema with the library
  **[TypeGraphQL][typegraphql]**

[apollo-server]: https://www.apollographql.com/docs/apollo-server/
[nextjs]: https://nextjs.org/
[typeorm]: https://typeorm.io/
[typegraphql]: https://typegraphql.com/

Code Exercise - NodeJS FullStack.md
Mostrando Code Exercise - NodeJS FullStack.md
