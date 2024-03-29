# Advanced react components pattern

## 1. Introducing

Idea to make react simple flexible.

## 2. Build a Toogle component

Implementing `Switch` in the `index.html`.

## 3. Write Compound Components

Create `Toogle.On`, `Toogle.Off`, `Toogle.Button` which help to shows cmpound pattern

## 4. Compound components flexibility

Implementing context in the `Toogle` component which was inherited by `Toogle.On`, `Toogle.Off`, `Toogle.Button`.
In this case you can put your components regardless to deep level.

## 5. Make Enchanced Components with HOC

Create Higher Order Components.

## 6. Handle prop namespace clashes with Higher Order Components

Avoiding overide props by making extra prop inside.

## 7 debuggability in HOC

Add prop `displayName` for debugging app.

## 8 handle ref with HOC

Make hoc handle ref (via property `innerRef`)

## 9 unit testability for HOC

Add additional prop `WrappedComponent` inside HOC to make tests

## 10 static properties

Use external method `hoistNonReactStatics` to render static

## 11 use render props

Implement different approach to render `Switch`.

## 12 Use prop collections with Render

## 13 Use prop Getters with Render

Handle custom `onClick` and native method in the same component. Composing actions in the `Toggle` component.

## 14 Use Component state initializers

Allow set initial state outside and reset to initial state meanwhile by `reset` action.

## 15 make controlled react components

## 16 implement context provider

## 17 HOC with redner props

## 18 Rerender Descendants Through shouldComponentUpdate

Using `ReactBroadcast`

## 19 with Redux