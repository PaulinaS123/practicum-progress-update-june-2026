# practicum-progress-update-june-2026

## AD 350

## Victoria Salomon

## Project Overview

Over the past four weeks, I have continued developing my Travel Organization App, a full-stack web application designed to help users organize trips, activities, itineraries, polls, notifications, and group travel planning in a single platform.

The goal of this project is to simplify travel coordination by providing a centralized application where users can manage trip information, collaborate with trip members, and organize activities efficiently.

## My Role

I am the sole developer responsible for the application's database design, backend integration, API testing, frontend development, project documentation, and deployment preparation.

## Work Completed

### Database Design and Implementation

* Designed and implemented a relational PostgreSQL database schema using Supabase.
* Created tables for:

  * Trips
  * Activities
  * Itinerary Items
  * Trip Members
  * Notifications
  * Polls
  * Poll Options
  * Votes
* Implemented primary keys, foreign keys, and table relationships.
* Added sample data for testing and validation.

### Authentication and Security

* Configured Supabase authentication.
* Implemented Row Level Security (RLS) policies.
* Tested authorization rules and access controls.
* Troubleshot and corrected policy-related issues during development.

### API Development and Testing

* Created and tested REST API endpoints using Postman.
* Validated CRUD operations for:

  * Trips
  * Activities
  * Itinerary Items
  * Poll Options
  * Votes
  * Trip Members
  * Notifications
* Documented API requests and testing procedures.

### Frontend Development

* Built a React + Vite frontend connected to Supabase.
* Implemented:

  * Home Dashboard
  * Trips Page
  * Trip Details Page
  * Activities Page
  * Itinerary Page
* Developed navigation using React Router.
* Integrated frontend components with Supabase data.

### Documentation

* Maintained weekly development updates.
* Created project documentation covering:

  * Database schema
  * API testing
  * Security policies
  * Project setup instructions

## Challenges and Solutions

One of the biggest challenges was troubleshooting Supabase Row Level Security policies. Several API requests initially failed due to authorization restrictions. Through testing and debugging, I learned how RLS policies interact with authenticated requests and adjusted the policies to allow the correct operations while maintaining security.

Another challenge was integrating the frontend with Supabase while maintaining a clean project structure. I addressed this by organizing the project into separate frontend, database, documentation, and testing sections.

## Key Learnings

During this period I strengthened my skills in:

* PostgreSQL database design
* Supabase backend services
* Row Level Security policies
* REST API development and testing
* Postman workflows
* React and Vite frontend development
* React Router navigation
* Git and GitHub project management
* Technical documentation

I also gained valuable experience managing a project from database design through frontend implementation, which helped me better understand full-stack application development.

## Next Steps

Future development goals include:

* Enhancing the user interface and user experience
* Adding user authentication workflows
* Expanding collaboration features
* Improving mobile responsiveness
* Preparing the application for deployment

This project has provided valuable hands-on experience with modern web development tools and has strengthened my confidence in building full-stack applications from concept to implementation.
