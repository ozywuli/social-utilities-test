# Social Functions

## How To Install

```bash
bower install social-functions
```

## How To Use With Ember

After you've installed the package with bower, open your `ember-cli-build.js` file and import the necessary file:

```js
// ember-cli.build.js

...

// just make sure this line appears before `return app.toTree();`
app.import('bower_components/social-functions/sf_all.js');

return app.toTree();
```

