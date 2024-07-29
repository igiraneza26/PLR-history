# Prince Louis Rwagasore Legacy Website

Welcome to the Prince Louis Rwagasore Legacy Website. This website is dedicated to sharing and preserving the historical legacy of Prince Louis Rwagasore, a significant figure in the history of Burundi.

## Purpose

The purpose of this web application is to provide a centralized repository of historical facts, anecdotes, and educational content about Prince Louis Rwagasore. Our goal is to educate users about his contributions, leadership, and impact on the history of Burundi.

## Value Proposition

By using this web application, users can:
- Access a wealth of curated historical facts and stories about Prince Louis Rwagasore.
- Learn about the historical context and significance of his actions and leadership.
- Engage with multimedia content, including articles, videos, and images.
- Learn about other Burundi political figures and landscape in general.

## Features

- **Curated Content**: High-quality, well-researched historical facts and stories.
- **Multimedia Integration**: Videos, images, and articles to enhance learning.
![alt text](image.png)
![alt text](image-1.png)
![alt text](image-2.png)

## Deployment Procedure
### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/)
- [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli)

### Installation Steps

1. Clone the Repository
   git clone https://github.com/igiraneza26/PLR-history.git
   cd PLR-history
2. Create necessary files
    Profcile
    index.js
    package.json
3. Install dependencies:
    npm install
4. Initialize Git Repository
    git init
    git add .
    git commit -m "Initial commit"
5. Create Heroku app
    heroku create your-heroku-app-name
6. Add Heroku remote
    heroku git:remote -a plr-history
7. Deploy to Heroku
    git push heroku main  # or `git push heroku master` if you are using the master branch
8. Open your app
    heroku open
    