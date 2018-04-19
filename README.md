# ensure-npm

Use this to make sure that your users are using the right version of npm.

### cli usage

```
$ ensure-npm '5.0.0'
$ ensure-npm '>= 4.3.0'
```

### use with npm install

```
# package.json
"scripts": {
  "preinstall": "ensure-npm '>=5.0.4'"
}
```
