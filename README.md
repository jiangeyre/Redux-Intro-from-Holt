# Redux-Intro-from-Holt

## Notes: ##
-going over synchronous Redux
-React state management: call setState and let React re-render
-Redux:
    User types in input box
    Call action creator to get an action
    Dispatch action to Redux
    Redux inserts the action into the root reducer
    The root reducer returns a new state given the old state and the action object
    The new state becomes the store's state
    React is then called by Redux and told to update