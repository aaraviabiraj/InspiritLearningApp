

## To deploy this app

### Amplify CLI

1. Clone the project and change into the directory

```sh
git clone https://github.com/aaraviabiraj/InspiritLearningApp.git
cd InspiritLearningApp
```

2. Install the dependencies

```sh
npm install

# or

yarn
```

3. Initialize and deploy the amplify project

```sh
amplify init

amplify push
```

4. Run the app

```sh
npm start
```



5. Render either the private (Users) or public (Patches) example in __src/App.js__:

```javascript
import React from 'react'
import Products from './Products'
import Users from './Users'

function App() {
  return (
    <Users />
   
  )
}

export default App;

```

