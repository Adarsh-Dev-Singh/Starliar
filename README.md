# StarLiar App

This is a mobile app built with Flutter, designed to display a dynamic dashboard for multiple data sources. It integrates with Firebase to fetch user data and presents key statistics like chess and LeetCode performance and talk with your chesscom and leetcode friends, along with a leaderboard that ranks users based on their latest chess scores. The app is fully scrollable and responsive, offering a clean and modern interface with a GridView for statistics and a leaderboard section below it.

## Features:
- **Home Overview**: Displays a set of statistics in a grid layout (e.g., chess stats, LeetCode stats).
- **Leaderboard**: Fetches and displays a leaderboard showing all users ranked by their `last_chess_rapid` scores from Firebase.
- **Data Fetching**: Refreshes data from Firebase on request to keep stats up-to-date.
- **Friends **: Talk with your friends seamlessly.
- **Responsive UI**: Uses a `SingleChildScrollView` to make the entire page scrollable, including both the GridView and leaderboard.

## Technologies Used:
- **Flutter**: A powerful framework for building natively compiled applications for mobile, web, and desktop from a single codebase.
- **Firebase**: For cloud data storage and real-time data fetching.
- **Firebase Authentication**: For handling user authentication.
- **Firestore**: To store and retrieve user-specific data, such as chess scores and other relevant statistics.

## Screenshots:
Include screenshots of your app's UI (e.g., dashboard, leaderboard).

## Setup:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/home-dashboard-app.git
