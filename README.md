# GitHub Actions Log Viewer

This project provides a simple web-based interface to view and track GitHub actions, such as pushes, pull requests, and merges. The data is fetched from a Flask API, which serves the logs of various GitHub actions. The UI is modern, responsive, and continuously updates in real-time to provide up-to-date information on the latest GitHub activities.

## Features

- **Real-time Updates**: The list of GitHub actions is automatically refreshed every 15 seconds to ensure the latest data is always visible.
- **Customizable Actions**: It supports multiple types of GitHub actions like `PUSH`, `PULL_REQUEST`, and `MERGE`, making it easy to track your repository's activity.
- **User-Friendly UI**: A clean, modern design with smooth hover effects and animations, improving the overall user experience.
- **Manual Refresh**: Users can manually refresh the log by clicking the "Refresh Now" button.
- **Action Details**: For each action, you can see the author, action type, branch details, and timestamp.

## Demo

You can view a live demo of the project here: [GitHub Actions Log Demo](#)

## Screenshots

![GitHub Actions Log Viewer Screenshot](screenshot.png)

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python Flask (API for serving GitHub action data)
- **Design**: Custom styles for a modern, responsive user interface
- **Fetch API**: For pulling the latest GitHub actions from the backend

## Installation

To run this project locally, follow the steps below:

### Prerequisites

- [Node.js](https://nodejs.org/) for the web server (if applicable)
- [Flask](https://flask.palletsprojects.com/) for the backend API
- A running Flask server that serves the `/webhook/actions` endpoint, returning JSON data of GitHub actions

### Setup

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/your-username/github-actions-l
