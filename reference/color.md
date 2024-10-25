# Color

::: info
Inherits: [TypedCommand](./typedcommand)
:::

The virtual light source color on the object. The colors of the pixels on the object are determined subtractively.

Example:

```ts
new Color({
  startTime: 0,
  endTime: 1000,
  startValue: [0, 0, 0],
  endValue: [0, 255, 255],
  easing: 3
})
```

## Constructor details

```ts
new Color({
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
  - `startValue` (`IColor3 | Color3Tuple`) ([Color3](./color3.md)): The starting color value.
  - `endValue` (`IColor3 | Color3Tuple | undefined`) ([Color3](./color3.md)): The ending color value. Defaults to `undefined`.
  - `easing` (`Easing | undefined`) ([Easing](./easing.md)): The easing function for the rotate animation. Defaults to `undefined`.

## Properties

_Properties inherited from [Command](./command):_

[`startTime`](./command#startTime)

_Properties inherited from [TypedCommand](./typedcommand):_

[`endTime`](./typedcommand#endTime), [`startValue`](./typedcommand#startValue), [`endValue`](./typedcommand#endValue), [`easing`](./typedcommand#easing)
