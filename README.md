# Front-end assignment

# Countdown Timer

## 1. Introduction
Create a web application that allows users to input a specific date and time, after which the application will display a countdown timer that counts down to the specified date and time from the current date and time.

## 2. Features
- User input for the target date and time.
- Real-time countdown display.
- Ability to cancel and create a new countdown at any time.
- Responsive design for various screen sizes.
- Optional: Sound notification for when the countdown is complete
- Optional: Persist countdown even if the browser tab is reopened again.

## 3. User Stories
- As a user, I want to be able to easily input the target date and time for the countdown.
- As a user, I want to see a real-time countdown displayed in an easy-to-understand format.
- As a user, I want the countdown timer to be visually appealing and responsive on different devices.

## 4. Functional Requirements

### 4.1 Input Form
- Provide a form with fields for the user to input the target date and time.
- Validate the input to ensure it is a valid date and time format.

### 4.2 Countdown Timer
- Display the countdown timer in a visually appealing format.
- Update the countdown timer in real-time to reflect the remaining time.

### 4.3 Cancel / Stop Countdown timer
- Allow the user to stop the countdown timer at any point of time.

### 4.4 Validations
- The maximum days for the countdown timer should be 99 days.
- The maximum hours for the countdown timer should be 23 hours
- The maximum minutes for the countdown timer should be 59 minutes
- The maximum seconds for the countdown timer should be 59 seconds
- The cut-off date for the date picker should be 99 days from the current date
- The countdown timer should not go below 0

### 4.5 Responsive Design
- Ensure the application is responsive and displays correctly on desktop and mobile devices.

## 5. Technologies
- Frontend: HTML, CSS and Javascript. The implementations should be in react.
- Optional: Use typescript, add unit tests and e2e tests.

### 6. Mockups
- Screen 1: Enter the date and time for the countdown times
![Screen 1](https://github.com/scalereal/fe-assignment/assets/85559412/a673b190-4e47-468c-a66f-a0df247da425)
- Screen 2: Countdown Timer
![Screen 2](https://github.com/scalereal/fe-assignment/assets/85559412/a4d8a63f-1d1f-4e8a-81a8-1328a3152182)

### 7. Additional Pointers:
- The UI should include reusable components
- Do not use any component library for building the date and time picker
- The images above are just an example layout, but the final result should aim to have the same features and somewhat the same layout
- Use linting tools, to ensure consistent formatting and code quality.

### 8. Assets:
- Fonts used: [Roboto](https://fonts.google.com/specimen/Roboto?query=robot), [Orbitron](https://fonts.google.com/specimen/Orbitron?query=orbitron)
- Primary color: #387A77

### 9. Handling the assignment:
- You can hand in your assignment by creating a repository on GitHub and pushing it there.
