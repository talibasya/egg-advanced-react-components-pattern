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