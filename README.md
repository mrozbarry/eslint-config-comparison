# eslint-config-comparison

## Setup

```
$ nvm use
$ npm install -g yarn
$ yarn
```


## How to switch out configs

```
./bin/use-linter <name>
```

Where do the names come from?

```
ls config/eslint-*.json
```

Any text after `eslint-` and before `.json` is the name of your linter config

```
./bin/use-linter airbnb
```

## How to run the linter

```
$ yarn lint
```
