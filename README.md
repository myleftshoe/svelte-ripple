# svelte-ripple

Ripple effect from [Svelte Materialify](https://svelte-materialify.vercel.app/) as a standalone npm package.

- zero dependencies
- works on any element (not just buttons)
- implemented as a [svelte action](https://svelte.dev/tutorial/actions)

## Install

```bash
npm install svelte-ripple
```

## Import

```js
import Ripple from 'svelte-ripple'
```

## Use | simplest

```html
<div use:Ripple>
    // div content
</div> 
```

## Use | with options

```html
<div use:Ripple={{ centered: false, color: 'red' }}>
    // div content
</div> 
```

These are the defaults, all can be passed in as options:

```js
const defaults = {
    color: 'currentColor',
    class: '',
    opacity: 0.1,
    centered: false,
    spreadingDuration: '.4s',
    spreadingDelay: '0s',
    spreadingTimingFunction: 'linear',
    clearingDuration: '1s',
    clearingDelay: '0s',
    clearingTimingFunction: 'ease-in-out',
}
```
