[SOFTSPIDERS](https://github.com/softspiders/softspiders)

# *lerna-react-app-uilib-war-starter*

[React](https://reactjs.org/) application starter with ui library in [Lerna](https://lerna.js.org/) monorepo and war
building

---

## Feature tags

- app
- build
- lerna
- maven
- react
- spa
- starter
- template
- uilib
- war

---

## Direct ancestors

[React application starter with ui library in Lerna monorepo](https://github.com/softspiders/lerna-react-app-uilib-starter)

---

## Inspired by

[Antony Budianto](https://github.com/antonybudianto)'s [react-lib-starter](https://github.com/antonybudianto/react-lib-starter)

## Authors

[Alexander Lapygin](https://github.com/AlexanderLapygin) <<alexanderlapygin@gmail.com>>

---

## Install
1. Clone this repo
2. Install dependencies
```sh
# yarn is fine too
npm i
```
3. Run bootstrap
```sh
npm run bootstrap
```

   This will bootstrap and link between app and lib
4. Now, it's ready!

## Dev flow
1. Run start
```sh
npm run start:dev:lib
npm run start:dev:app
```
2. Try changing the lib, it should reflect the changes directly
3. Now, you can start developing your React library!

## Build war

Being at the root directory, execute

```sh
npm run build:war
```

After successful build the result will be the *packages/example-app/target/example-app-war.war* file.

---

### License

Licensed under the [MIT license](./LICENSE). 

