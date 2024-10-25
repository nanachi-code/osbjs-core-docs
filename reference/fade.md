# Fade

::: info
Inherits: [TypedCommand](./typedcommand)
:::

Change the opacity of the object (how transparent it is).

Example:

```ts
new Fade({
  startTime: 0,
  endTime: 1000,
  startValue: 0,
  endValue: 1,
  easing: 3
})
```

## Constructor details

```ts
new Fade({
  startTime,
  endTime,
  startValue,
  endValue,
  easing
})
```

- Parameters:
  - `startTime` (`string | number | Timestamp`) ([Timestamp](./timestamp.md)): The start time of the animation.
  - `endTime` (`string | number | Timestamp | undefined`) ([Timestamp](./timestamp.md)): The end time of the animation. Defaults to `undefined`.
  - `startValue` (`number`): The starting opacity value.
  - `endValue` (`number | undefined`): The ending opacity value. Defaults to `undefined`.
  - `easing` (`Easing | undefined`) ([Easing](./easing.md)): The easing function for the rotate animation. Defaults to `undefined`.

## Properties

_Properties inherited from [Command](./command):_

[`startTime`](./command#startTime)

_Properties inherited from [TypedCommand](./typedcommand):_

[`endTime`](./typedcommand#endTime), [`startValue`](./typedcommand#startValue), [`endValue`](./typedcommand#endValue), [`easing`](./typedcommand#easing)
