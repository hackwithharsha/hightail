# highTail

- `highTail` plugin provides additional tailwind height utility classes from `h-1/7` to `h-1/14`

<div>
    <img src="./assets/cover.png" width="100%" height="250px" alt="cover-page" />
</div>

## Installation

```bash
>>> npm i @hackwithharsha/hightail
```

## Configuration

- In `tailwind.config.js` add `hightail` plugin to plugins section like following.

```js
module.exports = {
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [
    require('@hackwithharsha/hightail'),
  ],
}
```

## Usage

```html
<div class="h-full">
    <div class="h-1/10"></div>
    <div class="h-2/10"></div>
    <div class="h-3/10"></div>
    <div class="h-4/10"></div>
</div>
```

## Contributors

- [Hack With Harsha](https://github.com/hackwithharsha)
- [Satish Pokala](https://github.com/Satishpokala124)