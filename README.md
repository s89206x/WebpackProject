# WebpackProject
Starter Repo for a Webpack course on Udemy, use webpack and webpack-dev-server to build Single Page Application, and implement load on demand

![alt text](https://github.com/smalltide/WebpackProject/blob/master/screenshot.png "WebpackProject")

1. webpack
2. webpack-dev-server
3. react
4. npm
5. babel
6. css-loader
7. style-loader
8. webpack.optimize.CommonsChunkPlugin
9. rimraf
10. chunkhash for different hash file name when build

```
  > git clone git@github.com:smalltide/WebpackProject.git
  > cd WebpackProject
  > npm install
  > npm install --save-dev html-webpack-plugin
  > npm install --save-dev rimraf
  > npm install --save-dev webpack-dev-server@2.2.0-rc.0

  > npm run bulid
  > npm run server
```

## Deploy Static Page

1. deploy to Surge
```
  > npm install -g surge
  > npm run build
  > surge -p dist
  > https://rare-respect.surge.sh
```

2. deploy to github pages(gh-pages)
```
  > git checkout -b gh-pages
  > git subtree push --prefix dist origin gh-pages
  > https://smalltide.github.io/WebpackProject
```

3. deploy to AWS S3
```
  > npm install -g s3-website
  > s3-website create webpack-deploy
  > s3-website deploy dist
```
npm install -g s3-website
## Deploy dynamic Page
1.
```
```

2.
```
```
