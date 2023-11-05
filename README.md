# Workout-planing---Angular

This application is designed to assist users in planning their sports training routines by providing a user-friendly and straightforward web application interface. The application allows users to create a training plan by selecting exercises and setting exercise parameters. Users can access the application through any web browser.

 Functional Requirements
  - User registration
  - User login
  - Displaying available exercises
  - Grouping exercises into categories
  - Displaying user's training plans
  - Adding a new training plan
  - Adding exercises to a training plan
  - Entering the number of repetitions and weight for an exercise
  - Confirming the completion of an exercise
  - Editing the number of repetitions and weight
  - Viewing statistics for an exercise
  - Removing an exercise from a training plan
  - Deleting a training plan
  - User logout

 Views
  - Login window
  - Overview of available exercises (available to all)
  - Review of user's plans (available to logged-in users)
  - View of a specific plan (available to logged-in users)
  - Review of exercise statistics (available to logged-in users)
  - View for adding/editing an exercise (available to logged-in users)

  Technology Stack
   - Database: MySQL XAMPP
   - Backend: Node.js
   - Frontend: Angular 8
     
  Database Tables
   - user - stores user information
   - workoutplan - holds data about workout plans
   - training - contains training sessions details
   - category - lists categories for grouping exercises
   - exercise - includes exercise details
   - unit - records units for exercises, like reps and weight
