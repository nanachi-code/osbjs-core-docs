# Rotate

::: info
Inherits: [TypedCommand](./typedcommand)
:::

Rotate the object around its origin.

Example:

```ts
new Rotate({
  startTime: 0,
  endTime: 1000,
  startValue: 0,
  endValue: Math.PI / 2,
  easing: 3
})
```

## Constructor details

```ts
new Rotate({
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
  - `startValue` (`number`): The starting rotation angle in radians.
  - `endValue` (`number | undefined`): The ending rotation angle in radians. Defaults to `undefined`.
  - `easing` (`Easing | undefined`) ([Easing](./easing)): The easing function for the rotate animation. Defaults to `undefined`.

## Properties

_Properties inherited from [Command](./command):_

[`startTime`](./command#startTime)

_Properties inherited from [TypedCommand](./typedcommand):_

[`endTime`](./typedcommand#endTime), [`startValue`](./typedcommand#startValue), [`endValue`](./typedcommand#endValue), [`easing`](./typedcommand#easing)
