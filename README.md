# README

KoakhNodeModuleTypescriptStarter

a simple starter to create typescript npm modules

- [repo](https://github.com/koakh/KoakhNodeModuleTypescriptStarter)

## Usage

```shell
# clone 
$ git clone https://github.com/koakh/KoakhNodeModuleTypescriptStarter.git typescript-rest-actions-api
# change package from `@koakh/typescript-node-module-starter` to `@koakh/typescript-rest-actions-api`, change koakh to your namespace
$ nano package.json
# install dependencies
$ rm package-lock.json
$ npm i
```

## Start develop in other project

to use local package (before publish) in other consumer project, just add a local dependency with

```shell
# add a local dependency
$ npm i /home/mario/Development/@Koakh/node-modules/@koakh/typescript-rest-actions-api
```

> Tip replace `"file:../../../../../../../../../home/mario/Development/@Koakh/node-modules/@koakh/typescript-rest-actions-api"` with `/home/mario/Development/@Koakh/node-modules/@koakh/typescript-rest-actions-api` in both files `package.json` and `package-lock.json`
