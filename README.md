# Dashboard

A simple dashboard to understand authentication with NextAuth.js.

## Features ##

**  Adding a user signup API route and sending signup requests from the frontend.
**  Encrypting passwords with Bcryptjs.
**  Add Custom auth provider in NextAuth.js to log in users.
**  Active sessions and managing logouts of users.
**  Protecting routes with client side and server-side-page auth guards.
**  Add page for user to there change password.

## ❯ Getting Started

### Step 1: Set up the Development Environment

You need to set up your development environment before you can do anything.

Install [Node.js and NPM](https://nodejs.org/en/download/)

- on OSX use [homebrew](http://brew.sh) `brew install node`
- on Windows use [chocolatey](https://chocolatey.org/) `choco install nodejs`

npm install or npm i

### Step 2: prepare environment variable

convert .**env.template** file to **.env**

### Step 3: Serve your App

Go to the project dir and start your app with this npm script.

npm run dev

> This starts a local server , which will watch for any file changes and will restart the server according to these changes.
> The server address will be displayed to you as `http://0.0.0.0:3000`.

### Step 4: Create auth collection inside mongodb schema
