# Brand Icons

A copy of heroicons but with brand's logos. Good place to find brand vectors is here: https://www.vectorlogo.zone/

Source code licensed under MIT, all logos are Copyright their respective brands.

## Basic Usage

The quickest way to use these icons is to simply copy the source for the icon you need from [optimized](https://github.com/zuplo/brandicons/tree/main/optimized) and inline it directly into your HTML:

```html
<svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
  <path
    stroke-linecap="round"
    stroke-linejoin="round"
    stroke-width="2"
    d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"
  />
</svg>
```

Unlike heroicons, these icons are not meant to be colored with styles.

## React

First, install `@brandicons/react` from npm:

```sh
npm install @brandicons/react
```

Now each icon can be imported individually as a React component:

```js
import { SalesforceIcon } from '@brandicons/react'

function MyComponent() {
  return (
    <div>
      <SalesforceIcon className="h-5 w-5" />
      <p>...</p>
    </div>
  )
}
```

The 20x20 icons can be imported from `@brandicons/react`.

Icons use an upper camel case naming convention and are always suffixed with the word `Icon`.

## Vue

_Note that this library currently only supports Vue 3._

First, install `@brandicons/vue` from npm:

```sh
npm install @brandicons/vue
```

Now each icon can be imported individually as a Vue component:

```vue
<template>
  <div>
    <BeakerIcon class="h-5 w-5 text-blue-500" />
    <p>...</p>
  </div>
</template>

<script>
import { SalesforceIcon } from '@brandicons/vue'

export default {
  components: { SalesforceIcon },
}
</script>
```

The 20x20 icons can be imported from `@brandicons/vue`.

Icons use an upper camel case naming convention and are always suffixed with the word `Icon`.

## License

This library is MIT licensed.
