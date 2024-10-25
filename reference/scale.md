# Scale

::: info
Inherits: [TypedCommand](./typedcommand)
:::

Change the size of the object relative to its original size.

Example:

```ts
new Scale({
  startTime: 0,
  endTime: 1000,
  startValue: 1,
  endValue: 0.5,
  easing: 3
})
```

## Constructor details

```ts
new Scale({
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
  - `startValue` (`number`): The starting scale value or vector.
  - `endValue` (`number | undefined`): The ending scale value or vector. Defaults to `undefined`.
  - `easing` (`Easing | undefined`) ([Easing](./easing)): The easing function for the scale animation. Defaults to `undefined`.

## Properties

_Properties inherited from [Command](./command):_

[`startTime`](./command#startTime)

_Properties inherited from [TypedCommand](./typedcommand):_

[`endTime`](./typedcommand#endTime), [`startValue`](./typedcommand#startValue), [`endValue`](./typedcommand#endValue), [`easing`](./typedcommand#easing)
