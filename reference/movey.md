# MoveY

::: info
Inherits: [TypedCommand](./typedcommand)
:::

Move the object along the y axis.

Example:

```ts
new MoveY({
  startTime: 0,
  endTime: 1000,
  startValue: 0,
  endValue: 100,
  easing: 3
})
```

## Constructor details

```ts
new MoveY({
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
  - `startValue` (`number`): The starting Y position.
  - `endValue` (`number | undefined`): The ending Y position. Defaults to `undefined`.
  - `easing` (`Easing | undefined`) ([Easing](./easing)): The easing function for the moveY animation. Defaults to `undefined`.

## Properties

_Properties inherited from [Command](./command):_

[`startTime`](./command#startTime)

_Properties inherited from [TypedCommand](./typedcommand):_

[`endTime`](./typedcommand#endTime), [`startValue`](./typedcommand#startValue), [`endValue`](./typedcommand#endValue), [`easing`](./typedcommand#easing)
