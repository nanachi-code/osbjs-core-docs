# Move

::: info
Inherits: [TypedCommand](./typedcommand)
:::

Move the object to a new position in the play area.

Example:

```ts
new Move({
  startTime: 0,
  endTime: 1000,
  startValue: [0, 0],
  endValue: [100, 200],
  easing: 3
})
```

## Constructor details

```ts
new Move({
  startTime,
  endTime,
  startValue,
  endValue,
  easing
})
```

- Parameters:

  - `startTime` (`number | string | Timestamp`) ([Timestamp](./timestamp)): The start time of the animation.
  - `endTime` (`number | string | Timestamp | undefined`) ([Timestamp](./timestamp)): The end time of the animation. Defaults to `undefined`.
  - `startValue` (`IVector2 | Vector2Tuple`) ([Vector2](./vector2)): The starting value of the move.
  - `endValue` (`IVector2 | Vector2Tuple | undefined`) ([Vector2](./vector2)): The ending value of the move. Defaults to `undefined`.
  - `easing` (`Easing | undefined`) ([Easing](./easing)): The easing function for the move animation. Defaults to `undefined`.

## Properties

_Properties inherited from [Command](./command):_

[`startTime`](./command#startTime)

_Properties inherited from [TypedCommand](./typedcommand):_

[`endTime`](./typedcommand#endTime), [`startValue`](./typedcommand#startValue), [`endValue`](./typedcommand#endValue), [`easing`](./typedcommand#easing)
