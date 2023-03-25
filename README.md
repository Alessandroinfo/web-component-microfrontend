## 👋 Implementing micro-frontends using web components!

Here's a brief overview of how it works and the theory behind it:

Web Components are custom, reusable HTML tags that allow us to create independent components across different frameworks and platforms. By wrapping Angular applications  into Web Components, we can use them as micro-frontends.

To containerize the micro-frontends, we create an app-shell which serves as a common interface for communication and navigation between the micro-frontends.

## Getting started
After cloned the repo
1. Run `npm run run-mfe`
2. Go to `http://localhost:8080`

## Composition 
- **app-shell**
  - **body**
  - **header**
  - **footer**
  
The web-components body, header and footer are Angular applications wrapped into a web-component.
  
🎉 By using Web Components and an app-shell, we can create scalable and flexible solutions for building complex web apps! 🚀

## Final Result
![docs/img.png](docs/result.png)
