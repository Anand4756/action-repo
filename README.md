# GitHub Actions Log Viewer

This project provides a simple web-based interface to view and track GitHub actions, such as pushes, pull requests, and merges. The data is fetched from a Flask API, which serves the logs of various GitHub actions. The UI is modern, responsive, and continuously updates in real-time to provide up-to-date information on the latest GitHub activities.

## Features

- **Real-time Updates**: The list of GitHub actions is automatically refreshed every 15 seconds to ensure the latest data is always visible.
- **Customizable Actions**: It supports multiple types of GitHub actions like `PUSH`, `PULL_REQUEST`, and `MERGE`, making it easy to track your repository's activity.
- **User-Friendly UI**: A clean, modern design with smooth hover effects and animations, improving the overall user experience.
- **Manual Refresh**: Users can manually refresh the log by clicking the "Refresh Now" button.
- **Action Details**: For each action, you can see the author, action type, branch details, and timestamp.



## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python Flask (API for serving GitHub action data)



changes to check push, pull and merge
