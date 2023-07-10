### The application is created by this command

```bash
$ npx create-react-app zetamotion --template redux-typescript
```

### To run application, first you need to install dependencies by running

```bash
$ yarn install
```

### Then

```bash
$ yarn start
```

### To run test

```bash
$ yarn test
```

### Some key features of the application

- The Grid is infinite
- Play with other people (X, O)
- Data is store in local storage so you can refresh the page
- Player can reset the game by clicking reset button
- Player can undo / redo the multiple steps
- Player can export PNG of the canvas
- Player can see the statistic information like `number of game`, `win rate of X`, `win rate of O`, `average steps of each game`.
- There will be only 1 state of game:
  - X/O winned
- There will be a `__tests__` folder for the unit test of App, BoardGame component and some utilities.
- The unit test for `slice` is put at the same level of the slice definition file.
