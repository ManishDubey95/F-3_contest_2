# F-3_contest_2

# User Authentication System with Local Storage
# Overview
This repository contains a User Authentication system with local storage, featuring a "Signup" page, "Profile" page, and secure logout functionality.

# Features
# Signup Page
Mandatory fields for user details.
Adheres to Figma design specifications.
# User State
Successful signup stores user details and a 16-byte access token in local storage.
# Profile Page
Displays user details from local storage.
Central hub for user-related activities.
# Logout
"Logout" button clears local storage, including the access token.
Securely redirects users to the "Signup" page.
# Access Control
JavaScript ensures access control:
Redirects unauthorized users from "Profile" to "Signup."
Redirects logged-in users from "Signup" to "Profile."

# Usage
Navigate to the root URL for the "Signup" page.
Fill mandatory fields and click "Signup."
Successful signup redirects to the "Profile" page.
"Logout" clears storage and redirects to "Signup."
# Contributing
Fork the repository.
Create a branch for your changes.
Submit a pull request.

# Acknowledgments
Thanks to Figma for design inspiration.

For questions or feedback, feel free to reach out. Thank you for using our User Authentication System!
