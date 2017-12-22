# Markdown compiler

## Screenshot

[![Screenshot](https://s9.postimg.org/qk1qv6pr3/2017-12-22_10.58.30.png)](https://postimg.org/image/96rggbufv/)

## Deployment manual
* Installed and started MongoDB server required
* Installed nodeJS required

  1. Clone the repository: `$ git clone https://github.com/centr82009/markdown-compiler.git`
  2. Install all dependencies `$ npm install`
  3. Change config/DB.js to your server params
  4. Start the NodeJS server `$ nodemon server`
  5. Run `$ npm start`
  6. Webpack development server will start at: http://localhost:3000 (port configured in webpack.config.js)

## Changhelog

### 0.0.1
- Simple markdown compiler with saving documents
