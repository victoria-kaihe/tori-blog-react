# A starter webpack project for React

This is a starter project that uses webpack to transpile and bundle ES6 React code. To use, consider these steps:

* Fork this repo
* Rename your repo according to the app you're building

```sh
git clone https://github.com/[your-account]/[your-app].git
cd [your-app] && yarn
```

To start the development server with a watcher that rebuilds your code, run `yarn dev`. The assets built by webpack are placed in `server/public`. This folder is defined as a static folder in an Express.js server that can be started with `npm run server`.

Additional components should be placed in `client/components`.

# tori-blog-react
Rebuilding victoria-kaihe.github.io using React

To run - clone repo, <code>cd</code> into it, and run <code>yarn dev</code> in the terminal

OR

If you're like me and have Windows problems that you can't be bothered finding a proper solution for, open two terminals and run <code>yarn dev</code> in one, and <code>yarn webpack</code> in the other.
