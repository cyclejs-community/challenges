As a new Cycle.js user,
  I want to learn and practice Cycle.js
  I want to discover patterns I can use to write my apps
  I want to solve problems that are relevant real world Cycle.js issues

  I want help when I get stuck

As someone who has used Cycle.js in a few different projects
  I want to know alternative ways I might do things
  I want to learn about my unknown unknowns

Competencies:

Beginner
---

Can write Cycle app from scratch

DOM driver
  .select
  .events
  event.target.value
  .elements()
  hyperscript
    attrs
    props

Can use:
  .map
  .merge
  .combine
  .fold

Can write a counter or a guessing game

Intermediate
---

Can use actions + reducers + fold to represent state ('single state atom')
Can see that main function is a dataflow component
Can decompose main function into smaller components
Can manage lists of components
Can use component decorators

Can use isolate

hyperscript keys

HTTP driver
  requests
  responses
  categories

Can use:
  .flatten
  .compose and extras

Can write simple drivers

Can write a todo list or CRUD app

Advanced
---

Can combine aspects of components + state atom
Writes tests

Drivers
  Router
  Localstorage
  websockets

Can write any driver needed, recognizes when drivers are necessary
Can use virtual dom hooks

Can apply Cycle outside of browser context

Challenge map:

Hello world
---

Stage 0:
Render a div with the text 'Hello world'

Learnings
  xs.of
  Hyperscript view

Stage 1:
Add an input
Change the text to Hello ${name} where name is the value of the input

Learnings
  DOM.select.events
  event.target.value
  dynamic view using map


Counter
---

Depends on "Hello world"

Stage 0:

Create a counter. Need an 'add' button, and when you click the add button the counter should go up by one

Learnings
  xs.mapTo
  xs.fold

Stage 1:

Now add a 'subtract' button. When you click subtract, the count should go down by one

Learnings
  xs.merge



