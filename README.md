# react-redux-tutorial : Basic React Redux Implementation

# The Basic Redux Lifecycle
Internally, redux only works with synchronous data flow and doesn’t come with many “moving parts” or magic methods like some other solutions.

The most basic redux setup can be thought of as a single loop of state updates that is made up of just 2 components:

    The state tree
    The reducer function.
    
Actions are accessory objects that are required to figure out how to update the state for the next iteration.

The reducer function takes in the previous state and the dispatched action as its arguments and returns the next state. If there are no changes needed, it returns the previous state as-is. Otherwise, it creates new state and returns it.



# yarn start
    Starts the development server.

# yarn build
    Bundles the app into static files for production.

# yarn test
    Starts the test runner.

# yarn eject
    Removes this tool and copies build dependencies, configuration files
    and scripts into the app directory. If you do this, you can’t go back!

If you do clone this project, please follow the below few steps:

  cd react-redux-tutorial
  yarn start

Happy hacking!

