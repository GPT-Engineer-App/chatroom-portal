# Welcome to your GPT Engineer project

## Project info

**Project**: chatroom-portal 

**URL**: https://run.gptengineer.app/projects/0fbe1d35-7dcd-436e-8ef5-43be9c67526c/improve

**Description**: First thing that the user sees is the register/login page where he has to create an account. When an account is created we have to do email verification. The user should stay logged in a session so that when he opens the dashboard page, he can change his data. On the dashboard, he should be able to change the password, his username and avatar image (which has to be the URL which we store to the database). When connecting to the database make sure to use 127.0.0.1 instead of “localhost.
When coming to the homepage, first we check if the user is logged in and then, the user can choose to join one global chat or type the name of the room that he wants to join. Messages sent only in global chat should be stored in the database for 24 hours. Messages from all other rooms are not stored in the database. When sending messages in chat first it should be timestamp (HH:MM in 24h format), then username and after that message. There should also be sound notification when a message is received.
When a user is creating a new room (that currently does not exist) he should be prompted to pick if the room will have a password to join or is it open without password for anyone who wants to join. Once a room is empty for 1 minute it is “deleted” and if a user tries to join it he will be prompted as if the room is being created for the first time.
Styling and design should be done using basic html css and bootstrap. Make sure it looks nice and that the app is responsive.
Don't do anything related to backend and create only the frontend part the app. 

## Who is the owner of this repository?
By default, GPT Engineer projects are created with public GitHub repositories.

However, you can easily transfer the repository to your own GitHub account by navigating to your [GPT Engineer project](https://run.gptengineer.app/projects/0fbe1d35-7dcd-436e-8ef5-43be9c67526c/improve) and selecting Settings -> GitHub. 

## How can I edit this code?
There are several ways of editing your application.

**Use GPT Engineer**

Simply visit the GPT Engineer project at [GPT Engineer](https://run.gptengineer.app/projects/0fbe1d35-7dcd-436e-8ef5-43be9c67526c/improve) and start prompting.

Changes made via gptengineer.app will be committed automatically to this repo.

**Use your preferred IDE**

If you want to work locally using your own IDE, you can clone this repo and push changes. Pushed changes will also be reflected in the GPT Engineer UI.

The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps: 

```sh
git clone https://github.com/GPT-Engineer-App/chatroom-portal.git
cd chatroom-portal
npm i

# This will run a dev server with auto reloading and an instant preview.
npm run dev
```

**Edit a file directly in GitHub**

- Navigate to the desired file(s).
- Click the "Edit" button (pencil icon) at the top right of the file view.
- Make your changes and commit the changes.

**Use GitHub Codespaces**

- Navigate to the main page of your repository.
- Click on the "Code" button (green button) near the top right.
- Select the "Codespaces" tab.
- Click on "New codespace" to launch a new Codespace environment.
- Edit files directly within the Codespace and commit and push your changes once you're done.

## What technologies are used for this project?

This project is built with .

- Vite
- React
- shadcn-ui
- Tailwind CSS

## How can I deploy this project?

All GPT Engineer projects can be deployed directly via the GPT Engineer app. 

Simply visit your project at [GPT Engineer](https://run.gptengineer.app/projects/0fbe1d35-7dcd-436e-8ef5-43be9c67526c/improve) and click on Share -> Publish.

## I want to use a custom domain - is that possible?

We don't support custom domains (yet). If you want to deploy your project under your own domain, then we recommend GitHub Pages.

To use GitHub Pages you will need to follow these steps: 
- Deploy your project using GitHub Pages - instructions [here](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site#creating-your-site)
- Configure a custom domain for your GitHub Pages site - instructions [here](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)