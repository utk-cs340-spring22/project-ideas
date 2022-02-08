# CSOC 340: Project Ideas

- Abram Bradley
- abradl11
- [GitHub](https://github.com/seeker-3)

## Proposal

A web service that helps developers find open source projects on GitHub they are interested in to help developers gain experience and grow the open source community.

## Rational

### Job Experience

More and more developers are gaining their skills from online resources. However, there can be this limbo phase, called "tutorial hell", where a developer has acquired enough skill to get a job, but they do not have the "experience" they need. It could help them to find projects to work to gain job experience.
It could also help developers looking to branch out and try something new.

### Open Source Networking

Many developers spend their whole career working on open source projects. It could be used as a networking tool to connect them with other open source projects to expand their community outreach.

### Why GitHub

GitHub is one of the most popular spots for developers and open source projects. It is the biggest pool of developers and projects on the internet. GitHub has rich first party [APIs](https://docs.github.com/en/graphql) that provide lots of information about developers and projects an algorithm could use to create matches.

## Features

Would try not to reinvent the wheel for features GitHub and other social media services already provide.

- A user can log in and authorize access to their GitHub account (OAuth).
- A database with user accounts, API tokens, liked projects, user preferences, and maybe cached search results.
- A simple algorithm on the server to match developers with projects.
- A feed of open source GitHub projects a user can browse through.
- _(optional)_ A page of information about the projects so the user does not have to leave the app.
- _(optional)_ A way for the user to favorite projects they like to view for later and maybe some way to organize them.
- _(optional)_ An advanced ML algorithm that uses lots of GitHub data to produced optimized results.
- _(optional)_ A preferences pane to tweak the results of the search algorithm.

## Technologies

- Frontend framework: Svelte, React
- Backend: Rust, NodeJS, Flask
- APIs: GitHub GraphQL
- Runtime Environment: Docker
- Host: AWS, Raspberry Pi
- Database: PostgreSQL , MongoDB
- ML Algorithm: Tensorflow

## Consumers

Inexperienced developers, developers looking for something new, or open source community members.
