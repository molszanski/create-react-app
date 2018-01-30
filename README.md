This is fork. https://github.com/facebookincubator/create-react-app

Changes:
  - Coffeescript support
  - Stylus support
  - `src` path duct-tape fix for https://github.com/facebook/create-react-app/issues/3939
Usage:
```javascript
    {
      ...
      "dependencies": {
        "react": "^16.2.0",
        "react-dom": "^16.2.0",
        "@molszanski/react-scripts": "^1.1.1", // (!THIS LINE)
      },
      "scripts": {
        "start": "react-scripts start",
        "build": "react-scripts build",
        "test": "react-scripts test --env=jsdom",
        "eject": "react-scripts eject"
      },

    }
```
