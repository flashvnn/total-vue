# Total.js + Vue.js with Livereload

Using Vue components in Total.js' views

## Dependencies
* Total.js 3.x.x
* Vue.js 2.x.x

## Installation
1. Clone this repository
```bash
git clone https://github.com/flashvnn/total-vue.git
```

2. Install totaljs globally because the build.js will be minified using Total.js minify command
```bash
npm install -g total.js
```

3. Install dependencies
```bash
npm install
# or
yarn
```

## How to use
1. For development mode
```bash
# Complie Vue components
npm run client:dev

# Run Total.js in development mode
node debug.js
```

2. For production mode
```bash
# Complie Vue components
npm run client:prod

# Run Total.js in production mode
node release.js
```
