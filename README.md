# GitHub Profile Viewer

GitHub Profile Viewer is a web application built with Angular that allows users to view GitHub profiles and repositories.

## Features

- View user profiles: Enter a GitHub username to view the profile details.
- View user repositories: See a list of repositories for a specific user.
- Search repositories: Search for repositories by name.
- Authentication: Authenticate your requests using a personal access token for higher rate limits.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Node.js installed on your local machine
- Angular CLI installed globally (`npm install -g @angular/cli`)
- Personal access token from GitHub (optional, but recommended for higher rate limits)

## Getting Started

To get a local copy up and running, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/yourusername/github-profile-viewer.git
```
Navigate into the project directory:
```bash

bash
```

Copy code
```bash

cd github-profile-viewer
```

Install dependencies:
```bash

npm install
```

Run the development server:
```bash

ng serve
```

Open your browser and navigate to http://localhost:4200/.
Configuration
Personal Access Token
To authenticate your requests and avoid hitting the rate limit, you can use a personal access token from GitHub.

Generate a personal access token in your GitHub account settings.
Create a file named environment.ts in the src/environments directory.
Add your personal access token to the file:
typescript
Copy code
export const environment = {
  production: false,
  githubToken: 'YOUR_PERSONAL_ACCESS_TOKEN'
};
Replace 'YOUR_PERSONAL_ACCESS_TOKEN' with your actual token.
Usage
Enter a GitHub username in the search box on the homepage to view the profile details and repositories.
Click on the "Repositories" tab to see a list of repositories for the user.
Use the search functionality to search for repositories by name.
Contributing
Contributions are welcome! Please follow these guidelines:

Fork the repository
Create a new branch (git checkout -b feature/improvement)
Make your changes
Commit your changes (git commit -am 'Add new feature')
Push to the branch (git push origin feature/improvement)
Create a new Pull Request
