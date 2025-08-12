// if port not get from dotenv then use this in package.json after the nodemon and before the ./src/*.js
-r dotenv/config --experimental-json-modules

// never add / at the end of mongodb url as it save you from multiple errors.