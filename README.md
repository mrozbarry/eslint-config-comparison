# eslint-config-comparison

This was part of a tech talk I did for work, which you can [find here](https://docs.google.com/presentation/d/1pTHOknXru5s1IGKk4NSKjCEcx-1GQ2S8iN7qEGBsvDE/edit?usp=sharing).

## Setup

### Pre-reqs

 - [nvm](https://github.com/creationix/nvm)

### Install stuff

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
