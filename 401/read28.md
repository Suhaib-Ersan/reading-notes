# Component Lifecycle / `useEffect()` Hook

* Why do we not need more .html pages in a multi-page React app?

Because the app keeps re-rendering everything to the same page.

&nbsp;

* If we wanted a component to show up on every page, where would we put it and why?
  * Outside the `<BrowserRouter/>`
  * Inside the `<BrowserRouter />`, outside a `<Route />`
  * Inside a `<Route />`

Inside the `<BrowserRouter />`, outside a `<Route />`, because we have to wrap everything in the BrowserRouter tag. 

&nbsp;

* What does routing do with the components that were rendered when a new route is requested

They are unmounted.

&nbsp;

* What does props.children contain?

The "children" variable that was passed from a parent component.

&nbsp;

* How do useState() and this.setState() differ?

`useState()` is used in functional react components, and `this.setState()` is used in class react components"



[Go back to table of contents](https://suhaib*ersan.github.io/reading*notes/) 