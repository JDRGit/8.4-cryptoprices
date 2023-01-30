# SPAs with Multiple Pages

## React Router BitCoin PriceFinder
Purpose of this lesson is to Build A Crypto Price Discovery App and learn

- How to setup react router
- How to create Router, Route, Link and Switch components
- How to pass router props
- How to use URL Params

## The Problem

We are often used to making websites with several "pages" which would be split across several html delivered statically or rendered by templates on a server. When making a React app, the application is a single page with one html file. We can have components conditionally render to make the illusion of pages but it doesn't quite feel as intuitive as using a tags to link to different html files.

What the React-Router library does is allow us to define components that render based on the url in the address bar. We link to them with Link components which feel similar to the a tags we are used to. It allows to create a single page application in a way that feels like a multi-page application.