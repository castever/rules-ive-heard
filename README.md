# rules-ive-heard
Rules I've Heard While Working

### Don't resuse View Models

A view model should be specific to one view.  Reusing a view model in a different view doesn't make sense as that view model may/probably does have information it doesn't need.  And if it doesn't it may in the future.

### Don't modify state outside of a reducer

that's the second principle of redux http://redux.js.org/docs/introduction/ThreePrinciples.html#state-is-read-only
