---
category: Components
type: Data Display
title: Empty
---

Empty state placeholder.

## When To Use

When there is no data provided, display for friendly tips.

## API

```jsx
<Badge count={5}>
  <a href="#" className="head-example" />
</Badge>
```

```jsx
<Badge count={5} />
```

| Property | Description | Type | Default |
| -------- | ----------- | ---- | ------- |
| count | Number to show in badge | ReactNode |  |
| dot | Whether to display a red dot instead of `count` | boolean | `false` |
| offset | set offset of the badge dot, like`[x, y]` | `[number, number]` | - |
| overflowCount | Max count to show | number | 99 |
| showZero | Whether to show badge when `count` is zero | boolean | `false` |
| status | Set Badge as a status dot | `success` \| `processing` \| `default` \| `error` \| `warning` | `''` |
| text | If `status` is set, `text` sets the display text of the status `dot` | string | `''` |
| title | Text to show when hovering over the badge | string | `count` |