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
![WhatsApp Image 2024-12-12 at 21 28 55_99a7392c](https://github.com/user-attachments/assets/eafc9397-7bc4-44b2-99b3-24843dcaf1e6)

![WhatsApp Image 2024-12-12 at 21 28 55_e6d8ec5e](https://github.com/user-attachments/assets/02b933be-9f4b-42d8-9732-c3b4c2e1ccce)
![WhatsApp Image 2024-12-12 at 21 28 55_f38d3112](https://github.com/user-attachments/assets/7468ac50-2596-453b-9a69-d6e2875a7b11)
![WhatsApp Image 2024-12-12 at 21 28 56_7b0c7c9a](https://github.com/user-attachments/assets/a8a1ee4c-d55f-4047-ad32-0a3bb88a4e87)
![WhatsApp Image 2024-12-12 at 21 28 56_de785f8e](https://github.com/user-attachments/assets/46111e96-9912-46e8-8c4c-1c3752ea0f9c)





## Setup:

1. Clone the repository:
   ```bash
   git clone https://github.com/Adarsh-Dev-Singh/Starliar.git
