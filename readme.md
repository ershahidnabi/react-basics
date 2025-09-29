# Start a React Project

To create a new React project, use [Create React App](https://create-react-app.dev/):

```bash
npx create-react-app my-app
cd my-app
npm start
```

This will start the development server and open your new React app in the browser.

## Project Structure

After creating your project, you'll see a folder structure like this:

```
my-app/
├── node_modules/
├── public/
├── src/
│   ├── App.js
│   ├── index.js
│   └── ...
├── package.json
└── README.md
```

- `public/`: Static files like `index.html`.
- `src/`: Your React components and JavaScript code.
- `package.json`: Project dependencies and scripts.

You can now start building your React application by editing files in the `src` directory.

## Useful Scripts

Inside your project directory, you can run:

- `npm start`: Runs the app in development mode.
- `npm run build`: Builds the app for production.
- `npm test`: Launches the test runner.
- `npm run eject`: Exposes configuration files for advanced customization.

Refer to the [Create React App documentation](https://create-react-app.dev/docs/getting-started/) for more details.