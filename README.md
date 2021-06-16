# Shoe Store Project

This web-app is intended to act like a mock online shoe store, and replicates the process of a user browsing and buying a pair (or several) of shoes.

## Quick Start locally

Run the following commands:

```
npm install
npm start
```

This will install dependencies, then start the app.

## Live Application URL

You can view the live deploy by clicking [here](https://shoe-store.pages.dev/)

## Starter Project Overview

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

I made the following enhancements:

1. Added a mock API using [json-server](https://my-json-server.typicode.com/).
1. Installed [react-router-dom](https://www.npmjs.com/package/react-router-dom), and [history](https://www.npmjs.com/package/history) (React Router peer dependency).
1. Created a React component `Spinner` that is used on all pages.
1. Added styles to App.css
1. Added `/public/images`.
1. Added data fetching functions in `/src/services` by using custom hooks.
1. Overwrote App.css with custom styles
1. Deleted from src: index.css, logo.svg, serviceWorker.js, App.test.js
1. Deleted from public: logo files, manifest.json, robots.txt
1. Customized App.js and renamed to App.jsx

### Main tools used in this project

- React router
- fetching off mock API server
- custom hooks
- centralized change handlers
- state enums
- persisting state through localStorage
- form validations
- error boundaries and 404s handling
- useNavigation
