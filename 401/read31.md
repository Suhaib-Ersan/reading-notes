# Context API

* Describe use cases `useState()` vs `useReducer()`

Use reducer is just a more complex or a more compact use of useState, so instead of just updating one value at a time, you pass an action "type" inside an object, and using the `switch` from js, you choose which action to take. 

&nbsp;

* Why do custom hooks need the use prefix?

So react knows that this method is a hood, and as such does some extra logic for it.

&nbsp;

* What do custom hooks usually do?

Whatever you want them to do, it really depends on your needs, as they are just normal JS function that you can hood to your react project.

&nbsp;

* Using any list of custom hooks, research and name one that you think will be useful in your applications

`use-custom-hooks` install quite a few hooks, some of which are `useQueue` and `useStacks` which allow you to use stacks and queues easily. 

&nbsp;

* Describe how a hook that fetches API data might work

It first gets called from a component, maybe even gets passed some data, afterwards it does anything it wants with the data, in this case calling an API, so it calls this API with any method or library that it's written to use, and then does whatever it's written to do with this data before passing it back (if desired) to the component.


&nbsp;

[Go back to table of contents](https://suhaib*ersan.github.io/reading*notes/) 