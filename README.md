# Bot Battlr

## Learning Goals

The main objective of this project is to implement a React-based mini web application to hone skills in components, props, state, events, and data fetching.

## Instructions

This project entails the creation of a React application that showcases a list of available bots and incorporates various features. Carefully follow the instructions provided to ensure successful implementation.

## Requirements

To successfully complete this project, you are required to:

- Create a detailed README file.
- Retrieve data from a locally hosted server running JSON DB.
- Plan the application thoroughly before commencing the coding process.

## Project Setup

To set up your project, follow these steps:

1. Create a new folder for your project.
2. Initiate a new private GitHub repository.
3. Add your TM as a contributor to the repository (for evaluation purposes).
4. Commit your changes regularly to the repository.
5. In the project directory, create a `db.json` file and use provided data for your server DB.
6. Launch the backend by executing the following command:

```bash
json-server --watch db.json

## Project Guidelines

Your project should conform to the following set of guidelines:

### Core Deliverables

As a user, I should be able to:

- See profiles of all bots rendered in `BotCollection`.
- Add an individual bot to my army by clicking on it. The selected bot should render in the `YourBotArmy` component. The bot can be enlisted only **once**. The bot **does not** disappear from the `BotCollection`.
- Release a bot from my army by clicking on it. The bot disappears from the `YourBotArmy` component.
- Discharge a bot from their service forever by clicking the red button marked "x", which would delete the bot both from the backend and from the `YourBotArmy` on the frontend.
