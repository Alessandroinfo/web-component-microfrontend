## 👋 Implementing micro-frontends using web components!

Here's a brief overview of how it works and the theory behind it:

Web Components are custom, reusable HTML tags that allow us to create independent components across different frameworks and platforms. By wrapping Angular applications  into Web Components, we can use them as micro-frontends.

## Composition 
- **app-shell**
  - **body**
  - **header**
  - **footer**
 
The `app-shell` dir contains the build of each app and the index.html contains each micro-frontend.

The web-components body, header and footer are Angular applications wrapped into a web-component.

## Getting started
After cloned the repo
1. Run `npm run run-mfe`
2. Go to `http://localhost:8080`

## Final Result
![docs/img.png](docs/result.png)

🎉 By using Web Components we can divideour applications in domains (using DDD) and let the teams work vertically for a specific module / domain!

🚀 Also we can implement Self-Contained System so we can have isolated module that don't interfere in any way with others module, for bugs too.

