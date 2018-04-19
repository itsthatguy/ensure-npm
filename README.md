# ensure-npm

Use this to make sure that your users are using the right version of npm.

### cli usage

```
$ ensure-npm '5.0.0'
$ ensure-npm '>= 4.3.0'
```

### use with npm install

Install it to your project as a devDependency

```sh
$ npm install ensure-npm --save-dev
```

Then edit your package.json

```
# package.json
"scripts": {
  "preinstall": "ensure-npm '>=5.0.4'"
}
```
