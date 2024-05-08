# GitHub API Client

## Overview
This Angular application allows users to interact with the GitHub API to search for repositories, view repository details, list issues, and visualize issue data using a PIE chart.

## Features
- Search GitHub repositories by keyword
- View repository details (URL, description, forks count, stargazers count, open issues count)
- List all issues for a repository
- Filter issues by state (Open/Closed)
- Display a PIE chart showing the breakdown of issues (Open vs Closed)

## Design Choices
- **Angular Framework**: Chosen for its robustness in building single-page applications and its support for TypeScript.
- **Bootstrap for Styling**: Utilized Bootstrap for responsive and clean UI design.
- **ngx-charts for PIE Chart**: Used ngx-charts library to create a visually appealing PIE chart for issue breakdown.

## Getting Started
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/github-sphiwe.git
## Navigate to the project directory:
cd github-api-client

## Install dependencies:
npm install
## Open your browser and 
go to http://localhost:4200/ to view the application.

## Usage
Search: Enter a search term in the input field and click the "Search" button to find GitHub repositories matching the keyword.
Repository Details: Click on a repository name to view detailed information such as URL, description, forks count, stargazers count, open issues count, etc.
Issues List: Navigate to the "Issues" tab to view all issues for a repository. Use the filter options to display Open or Closed issues.
PIE Chart: On the Issues tab, a PIE chart is displayed showing the breakdown of issues by state 
