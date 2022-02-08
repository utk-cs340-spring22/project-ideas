# CSOC 340: Project Ideas

- Abram Bradley
- abradl11
- [GitHub](https://github.com/seeker-3)

## Proposal

A web service that helps aspiring developers find open source projects on GitHub to contribute to.

## Rational

More and more developers are gaining their skills from online resources.
However, there can be this limbo phase, called "tutorial hell", where maybe a developer has acquired enough skill to get a job, but does not have any actual experience yet.
This service would help pair new developers or even experienced developers in transitioning to find new projects that capture their interest and help them move onto the next phase.

### Why GitHub?

GitHub is one of the most popular spots for developers and open source projects on the internet. There are tons of developers and open source projects to pool from.
GitHub also has rich first party [APIs](https://docs.github.com/en/graphql) that would provide lots of information about develops and projects an ML algorithm could use to find matches.

## Features

- The user could login with their GitHub account and allow access to their information.
- Some sort of ML algorithm to use the developers's information to find projects.
- A curated feed of open source GitHub projects the user could browse through.
- A page of information about the projects so the user does not have to leave the app.
- A preferences pane to tweak the results of the search algorithm.
- A way for the user to favorite projects they like to view for later and maybe some way to organize them.
- A database with user accounts, API tokens, liked projects, and maybe cached search results.

## Technology

- Frontend framework: Svelte, React
- Backend: Rust, NodeJS, Flask
- APIs: GitHub GraphQL
- Runtime Environment: Docker
- Host: AWS, Raspberry Pi
- Database: PostgreSQL , MongoDB
- ML Algorithm: Tensorflow

## Consumers

Inexperienced developers, developers looking for something new, or people just interested in open source.
