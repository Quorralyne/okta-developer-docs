Define a route that handles a path like `/implicit/callback`. Here's how to do it in [react-router](https://github.com/ReactTraining/react-router):


```jsx
import React from 'react';
import { BrowserRouter as Router, Route } from 'react-router-dom';

const CALLBACK_PATH = '/implicit/callback';

const App = () => { 
  return (
    <Router>
      <Route path={CALLBACK_PATH} />
    </Router>
  );
};

export default App;
```
