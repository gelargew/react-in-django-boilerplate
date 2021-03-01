```
git clone https://github.com/gelargew/react-in-django-boilerplate
cd frontend
```
## choose one with yarn or npm

#### yarn
```
sh -e commands.txt
```

#### npm
```
npm i webpack webpack-cli --save-dev
npm i @babel/core babel-loader @babel/preset-env @babel/preset-react --save-dev
npm i react react-dom --save-dev
```

then in `frontend/package.json` add
```
...
"name":"frontend",
...
"scripts": {
    "watch": "webpack --mode development --watch",
    "build": "webpack --mode production"
  },
  ...
```