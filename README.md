# Anime Streaming Clone

A modern anime discovery platform built with React and powered by the Jikan API.

This project was created to explore large-scale frontend application development, API-driven user experiences, client-side routing, and scalable React architecture.

The application allows users to discover anime, browse detailed information, search titles, filter content, view recommendations, and navigate across multiple routes through a rich and responsive user interface.

Although the project does not stream video content due to API limitations, it recreates many of the core features found in modern anime streaming and content discovery platforms.

This repository represents one of the most significant milestones in my frontend development journey and my transition toward building production-style React applications.

## Live Demo

https://axce-j.github.io/tutorial/#/home

## Screenshots

### Home Page

(Add screenshot)

### Anime Details Page

(Add screenshot)

### Search & Filtering

(Add screenshot)

### Mobile View

(Add screenshot)

## Features

* Multi-route React application
* Anime discovery and browsing
* Anime search functionality
* Search parameter-based filtering
* Pagination system
* Detailed anime information pages
* Anime recommendations
* Dynamic data fetching
* Client-side routing
* Responsive navigation
* Animated user interface
* Mobile-friendly design

## Technologies Used

* React
* Vite
* React Router DOM
* Axios
* TanStack React Query
* Chakra UI
* Framer Motion
* Swiper
* CSS3

## API Integration

This project consumes data from the Jikan API, an unofficial MyAnimeList REST API.

API Website:

https://api.jikan.moe

### Endpoints Used

* Anime Search
* Anime Details
* Recommendations
* Top Anime
* Seasonal Anime
* Genre Filtering

Working with external APIs helped strengthen my understanding of real-world frontend development and data-driven applications.

## What I Learned

During this project I gained experience with:

* Building large React applications
* Structuring scalable frontend architectures
* Designing reusable components
* Creating custom React hooks
* Consuming REST APIs
* Managing asynchronous application state
* Implementing client-side routing
* Managing URL search parameters
* Working with React Query caching strategies
* Implementing filtering systems
* Building pagination workflows
* Creating responsive user experiences
* Organizing projects using modular folder structures
* Deploying production-ready React applications

## Challenges

Some of the challenges encountered during development included:

* Managing API refetching behaviour
* Handling asynchronous loading and error states
* Synchronizing URL search parameters with application state
* Implementing efficient pagination logic
* Designing reusable components across multiple routes
* Organizing a growing React codebase
* Working around API limitations that did not provide streaming content
* Optimizing user experience while fetching remote data

These challenges provided valuable experience in solving problems commonly encountered in modern frontend applications.

## Project Structure

```text
src/
├── Components/
├── Pages/
├── hooks/
├── modules/
├── config/
│   └── axios/
├── App.jsx
├── export.jsx
├── main.jsx
└── index.css
```

## Installation

```bash
git clone https://github.com/axce-j/anime-streaming-clone.git

cd anime-streaming-clone

npm install

npm run dev
```

## Looking Back

This project marked a major transition in my development journey from building static websites to architecting feature-rich frontend applications.

It introduced concepts such as component composition, API-driven applications, client-side routing, caching strategies, scalable project organization, and advanced state management patterns.

Since completing this project, I have progressed into building larger systems involving:

* Full-stack development
* Authentication and authorization systems
* AI-powered platforms
* Database architecture
* Cloud deployment
* Scalable application design
* Product development and system architecture

I have intentionally preserved this repository as an important milestone in my growth as a software engineer.

## Future Improvements

Potential future enhancements include:

* User authentication
* Personalized watchlists
* Favorites and bookmarking
* Advanced recommendation systems
* User reviews and ratings
* Backend integration
* Anime episode tracking
* Performance optimizations
* Progressive Web App (PWA) support

## Author

**Obinna Jachike Ezeani**

Software Engineer | Product Builder | Co-Founder

GitHub: https://github.com/axce

LinkedIn: https://www.linkedin.com/in/obinna-jachike-ezeani-a072b9284/
