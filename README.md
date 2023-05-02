# mern_first_jsx_core

# deployment

add:

```json
{
  "homepage": "https://www.tylermaxwell.co/mern_first_jsx_core"
}
  ```
and
```json
  {
  "scripts": {
    "predeploy": "npm run build",
    "deploy": "gh-pages -b deploy -d build",
    "start": "react-scripts start",
    "build": "react-scripts build"
  }
}
```

```
npm install --save gh-pages
```

```
npm run deploy
```