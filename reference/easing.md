# Easing <Badge type="info" text="enum" /> <Badge type="info" text="type" />

Easing indicates if the command should "accelerate".

```ts
const Easing = {
  Linear: 0,
  Out: 1,
  In: 2,
  InQuad: 3,
  OutQuad: 4,
  InOutQuad: 5,
  InCubic: 6,
  OutCubic: 7,
  InOutCubic: 8,
  InQuart: 9,
  OutQuart: 10,
  InOutQuart: 11,
  InQuint: 12,
  OutQuint: 13,
  InOutQuint: 14,
  InSine: 15,
  OutSine: 16,
  InOutSine: 17,
  InExpo: 18,
  OutExpo: 19,
  InOutExpo: 20,
  InCirc: 21,
  OutCirc: 22,
  InOutCirc: 23,
  InElastic: 24,
  OutElastic: 25,
  OutElasticHalf: 26,
  OutElasticQuarter: 27,
  InOutElastic: 28,
  InBack: 29,
  OutBack: 30,
  InOutBack: 31,
  InBounce: 32,
  OutBounce: 33,
  InOutBounce: 34,
} as const

type Easing = (typeof Easing)[keyof typeof Easing]
```
