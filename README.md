# Git Finder App

Simple JavaScript application for searching GitHub users and displaying their profile information and repositories.

## Features

- Search users by username
- Display basic profile information (avatar, bio, followers, following)
- Show list of public repositories
- Display repository details (stars, forks, language)
- Basic error handling for invalid input or missing users

## Technologies

- HTML
- CSS
- JavaScript (Vanilla)
- GitHub REST API

## API

The app uses GitHub API endpoints:

- https://api.github.com/users/{username}
- https://api.github.com/users/{username}/repos

## How it works

User enters a username, the app sends a request to the GitHub API and displays the returned data on the page.

## Installation

```bash
git clone https://github.com/your-username/git-finder.git
cd git-finder
open index.html
```

## Notes

API has rate limits for unauthenticated requests. If needed, a token can be added later.
