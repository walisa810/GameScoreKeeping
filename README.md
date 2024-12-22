# The Tennis Score Tracker Ap

## Overview
The Tennis Score Tracker App is a simple Android application built using Kotlin and the MVVM (Model-View-ViewModel) architecture. The app allows you to track the scores of two teams playing a tennis match. It tracks scores round by round, and at the end of the third round, it declares the winner based on the most rounds won.

## Features
Two teams can compete, and their scores are tracked independently.
After each point, the score for each team is updated.
A round ends when a team scores 10 points.
After three rounds, the app declares the final winner based on the most rounds won.
Score is displayed on the screen, and toast messages are shown for round and final winners.

## Architecture
This project uses the MVVM (Model-View-ViewModel) pattern:

Model: Holds the business logic and data (in this case, the score tracking).
View: The UI components (TextViews and Buttons) that the user interacts with.
ViewModel: Acts as a bridge between the Model and View, handling UI-related data and logic.
