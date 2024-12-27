# React Router Dom v6 - Route Not Found Error

This repository demonstrates a common error encountered when using React Router Dom v6: the "Route not found" error.  This occurs when attempting to navigate to a route that is not defined in your `Routes` component.  The example shows how this can happen and how to resolve it using the `useNavigate` hook or `Navigate` component for redirects.

## The Problem

The primary cause is a mismatch between the URL a user tries to access and the routes defined in your application. This can result from typos, incorrect route configurations, or links pointing to outdated or non-existent routes.  The error often manifests as an unhandled exception or simply renders nothing.

## Solution

The provided solution focuses on implementing error handling.  We add a catch-all route (`/*`) with a component that gracefully handles navigation to non-existent routes.  Alternatively, if you are certain that this scenario should only ever lead to redirection, the use of a redirect as shown in App.js, solution provides a more streamlined approach.

## How to Run

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install` to install dependencies.
4. Run `npm start` to start the development server. 
