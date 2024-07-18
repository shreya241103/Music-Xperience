# Music Xperience

Music Xperience is a comprehensive music management system designed to efficiently organize and store diverse music-related data. With a robust relational database at its core, the platform supports various functionalities, including user management, playlist creation, and subscription handling. This project aims to provide an engaging and secure music experience for users, along with powerful administrative tools for managing the system.

## Overview

Music Xperience is a music streaming web application built using Streamlit and connected to a MySQL database. It enables users to sign up, log in, create playlists, search for songs, view albums, and manage their music subscriptions. Administrators have additional functionalities to manage users and the music database.

## ER Diagram
<img width="1325" alt="Screenshot 2024-07-19 at 12 38 38 AM" src="https://github.com/user-attachments/assets/cb118d12-ee7a-40e2-af09-f53833a4aebd">

## Relational Schema
<img width="838" alt="Screenshot 2024-07-19 at 12 39 09 AM" src="https://github.com/user-attachments/assets/c9c9ebb2-4a01-4f10-bfa8-729ae817367f">

## Features

- **User Authentication:** Secure sign-up, login, and password recovery.
- **Admin and User Roles:** Distinct functionalities for administrators and regular users.
- **Music Management:** Create and manage playlists, search for songs, view albums, and play tracks.
- **Subscription Management:** Users can manage their subscriptions with different plans.
- **Custom Styling:** Personalized interface styling for an enhanced user experience.
- **Notifications:** Keep users informed about new content and subscription changes.

## Main Modules

### `app.py`

The main script that runs the Streamlit application. It handles user authentication, displays the main interface, and coordinates other functions based on user interaction.

### `login_signup.py`

Manages user authentication processes, including login, sign-up, password recovery, and admin login functionalities.

### `admin_operations.py`

Contains functions for administrative tasks such as managing users and the music database.

### `song_playlists_operations.py`

Handles operations related to songs, albums, and playlists, including searching for songs, displaying albums, and managing playlists.

### `notifications.py`

Manages user notifications, keeping users informed about important events like new content and subscription updates.

## Contributors
- Shreya Kashyap ([@Shreya241103](https://github.com/shreya241103))
- Sai Manasa Nadimpalli ([@Mana120](https://github.com/Mana120))
