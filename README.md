# Lightning Web Components Recipes Open Source

[![Github Workflow](https://github.com/trailheadapps/lwc-recipes-oss/workflows/CI/badge.svg)](https://github.com/trailheadapps/lwc-recipes-oss/actions) [![codecov](https://codecov.io/gh/trailheadapps/lwc-recipes-oss/branch/master/graph/badge.svg)](https://codecov.io/gh/trailheadapps/lwc-recipes-oss)

A collection of easy-to-digest code examples for Lightning Web Components Open Source. Each recipe demonstrates how to code a specific task in 30 lines of code or less. A View Source link takes you right to the code in GitHub. From Hello World to data access and third-party libraries, there is a recipe for that!

## Recipes Live Version

Check out [https://lwc-recipes-oss.herokuapp.com](https://lwc-recipes-oss.herokuapp.com) live on Heroku. Or on [https://recipes.lwc.dev](https://recipes.lwc.dev).

## Deploy to Heroku

If you want to deploy LWC Recipes Open Source to Heroku - there's a button for that.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Local Development

1. Clone the `lwc-recipes-oss` repository:

```
git clone https://github.com/trailheadapps/lwc-recipes-oss
cd lwc-recipes-oss
```

2. Install the project dependencies using `yarn` (or `npm`, if you prefer that alternatively)

```
yarn install
```

3. Start the app in watch mode.

```
yarn watch
```

4. Enjoy the app!

## Modifications for Edge browser users

The Edge browser currently doesn't support native shadow DOM. If you want to use this application you have to manually add the synthetic shadow DOM to your clone. Add to the first line of the [index.js](https://github.com/trailheadapps/lwc-recipes-oss/blob/master/src/index.js#L1) this code:

```javascript
import '@lwc/synthetic-shadow';
```
