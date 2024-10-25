# Additive

::: info
Inherits: [TypedCommand](./typedcommand)
:::

Use additive-color blending instead of alpha-blending.

Example:

```ts
new Additive({
  startTime: 0,
  endTime: 1000
})
```

## Constructor details

```ts
new Additive({ startTime, endTime })
```

- Parameters:
  - `startTime` (`string | number | Timestamp`) ([Timestamp](./timestamp.md)): Start time of the command.
  - `endTime` (`string | number | Timestamp`) ([Timestamp](./timestamp.md)): End time of the command.

## Properties

_Properties inherited from [Command](./command):_

[`startTime`](./command#startTime)

_Properties inherited from [TypedCommand](./typedcommand):_

[`endTime`](./typedcommand#endTime), [`startValue`](./typedcommand#startValue), [`endValue`](./typedcommand#endValue), [`easing`](./typedcommand#easing)
