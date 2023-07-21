# Quiz App

The Quiz App is a web application developed using Next.js, a popular React framework for building server-side rendered and static websites. This app allows users to participate in quizzes on various topics and test their knowledge while having a fun and interactive experience.

## Features

    Multiple-choice questions: Users can answer multiple-choice questions from various categories.
    Score tracking: The app keeps track of the user's score as they progress through the quiz.
    Responsive design: The app is fully responsive and works seamlessly on different devices, including desktops, tablets, and smartphones.

## Installation

To run the Quiz App on your local machine, follow these steps:

    Clone the repository: git clone https://github.com/Frs2304/Quiz-App.git

    Navigate to the project directory: cd quiz-app

    Install dependencies: npm install

    Start the development server: npm run dev

    Open your web browser and go to http://localhost:3000 to access the Quiz App.

## Usage

    On the home page, click on the "Start Quiz" button to begin the quiz.
    Each question will be displayed one at a time with multiple answer choices.
    The app will provide immediate feedback on the correctness of your answer.
    At the end of the quiz, you will see your final score and the option to start a new quiz.

## Customization

The Quiz App can be easily customized to suit your needs:

    Adding or modifying questions: You can update the quiz questions by editing the data/questions.json file.
    Each question follows a specific JSON format and includes the question itself, an array of answer choices, and the index of the correct answer.

    Changing quiz categories: To add or modify quiz categories, update the data/categories.json file with the desired categories and their corresponding IDs.

    Adjusting timer and scoring: You can modify the quiz timer and scoring system by changing the appropriate constants in the utils/constants.js file.

## Deployment

To deploy the Quiz App to a live server, follow the steps provided in the Next.js documentation for deployment.
### Technologies Used

    Next.js: A React framework for server-side rendering and static site generation.
    React.js: A JavaScript library for building user interfaces.
    CSS: Used for styling and layout.
    JSON: Used to store quiz data.

