![Curious Reader Header](https://user-images.githubusercontent.com/95496577/182222723-980e7e6e-dee9-4a20-8dd9-ebee9dc6c0bb.png)

## Table of Contents

- [Table of Contents](#table-of-contents)
- [Abstract](#abstract)
- [Deployed Link](#deployed-link])
- [Illustrations](#illustrations)
- [Technologies Used](#technologies-used)
- [Application & Component Wireframes](#application-and-component-wireframes)
- [Context and Features](#context-and-features)
- [User Stories](#user-stories)
- [Lessons Learned](#lessons-learned)
- [Future Features](#future-features)
- [Application Set-Up](#application-set-up)
- [Contributor LinkedIns and GitHubs](#contributor-linkedin-and-github)
- [Project Specs](#project-specs)

## Abstract

- Curious Reader is built with TypeScript in the React.js framework. The application is built for users looking to find new books and check out the _New York Times Best Sellers_ lists. The top book from each genre is displayed on the home page with a side bar for navigation to specific genres.

## Deployed Link

- Check out our application [here!](https://curious-reader.herokuapp.com/) 

## Illustrations

![200](https://user-images.githubusercontent.com/98493391/182264909-a62c2156-6bd4-4378-bc95-ee81598e98c7.gif)

## Application Wireframe and Component Architecture

### Application Wireframes

![Curious Reader Wireframe](https://user-images.githubusercontent.com/98415017/182945106-5401e916-471c-491a-b0ba-d7696bc81e8b.png)

## Technology Stack

- CSS
- Cypress.io
- Fetch API
- Postman
- React.js
- React Router
- TypeScript

## User Stories

- As a user I should see a homepage that previews the book genres with the top book from each category. 

- As a user I should be able to select different book genres, which filters the books and book details displayed based on genre. 

- As a user I should be able to go back to the homepage where I can select a different genre of books to see. 

## Context and Features

- Curious Reader is a React.js application with a TypeScript basis. The app required type checking of API data, and properties passed from our app state to components. Given the design and data structure of our application, we made an interfaces file to be reusable. We kept our typing strict on our data sets which allowed us to develop our application without any type errors. 

- Aside from TypeScript, one of the primary features of our application is the ability to see the top books from each specific genre. To do this we used endpoint manipulation and React Router. Our `Navbar` component contains every genre from _The New York Times Best Sellers_ lists. Each genre in the `Navbar` component is a `NavLink` that navigates to the respective genre page `Route`. We made use of a `useState()` React hook and a `useEffect()` hook to maintain state for all of our genre pages dynamically. 

## Lessons Learned

- This was a Stretch Technology project. What that meant for me and my collaborators is that we had to teach ourselves TypeScript in order to build this application. It was the first time that most of us had had exposure to writing TypeScript, and the type checking involved in a React application. We made use of many resources online including but not limited to TypeScript docs, React docs, courses, walkthroughs, and video tutorials. This in combination with our prior experience writing code in JavaScript and React JSX made learning TypeScript a welcome and manageable challenge. This was our first time incorporating React hooks into a project as well. Coming from using class components, and incorporating the `useState()` and `useEffect()` hooks was an exciting addition for us. It’ll likely influence how we approach state in our future applications. 

## Future Features

Some future features we’d like to add to this application are:

- Add a search/filtering functionality for books.

- Have individual book detail pages for each book on the list.

- Supplement our Cypress tests with unit tests and integration tests by using the React Testing Library.

## Application Set-Up

1. Fork repository on GitHub.

2. `Git clone` the repository to your local machine.

4. `Cd` into the directory.

5. Run `npm install` in your terminal to install project dependencies.

6. Run `npm start` in the terminal to see the application. 

7. Run `npm run cypress` in the terminal  to run cypress tests. 

8. When finished with the application, type `Control + C` in the terminal to stop running the application. 

## Contributor LinkedIn’s

- [Catlyn Bowles: LinkedIn](https://www.linkedin.com/in/catlyn-bowles/)      
- [Megan Schuetz: LinkedIn](https://www.linkedin.com/in/megan-schuetz/)     
- [Michael Harrison: LinkedIn](https://www.linkedin.com/in/michael-j-harrison57/)    
- [Nickolai Orlov: LinkedIn](https://www.linkedin.com/in/nickolaio/)     

## Contributor GitHubs’s

- [Catlyn Bowles: GitHub](https://github.com/catlynbowles)       
- [Megan Schuetz: GitHub](https://github.com/megschuetz)       
- [Michael Harrison: GitHub](https://github.com/mikeharrison57)     
- [Nickolai Orlov: GitHub](https://github.com/orlov-n)      

## Project Specs

- The specs for this application can be found 
[here](https://frontend.turing.edu/projects/module-3/stretch.html)
