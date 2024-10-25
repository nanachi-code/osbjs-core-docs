# FlipV

::: info
Inherits: [TypedCommand](./typedcommand)
:::

Flip the element vertically.

Example:

```ts
new FlipV({
  startTime: 0,
  endTime: 1000
})
```

## Constructor details

```ts
new FlipV({ startTime, endTime })
```

- Parameters:
  - `startTime` (`string | number | Timestamp`) ([Timestamp](./timestamp.md)): Start time of the command.
  - `endTime` (`string | number | Timestamp`) ([Timestamp](./timestamp.md)): End time of the command.

## Properties

_Properties inherited from [Command](./command):_

[`startTime`](./command#startTime)

_Properties inherited from [TypedCommand](./typedcommand):_

[`endTime`](./typedcommand#endTime), [`startValue`](./typedcommand#startValue), [`endValue`](./typedcommand#endValue), [`easing`](./typedcommand#easing)
