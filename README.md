# Custom Watermark

[![](https://img.shields.io/badge/custom--watermark-0.0.2-green.svg)](https://www.npmjs.com/package/custom-watermark)

## props

```ts
interface Options {
  txt: string[]
  width?: number
  height?: number
  x?: number
  y?: number
  font?: string
  fontSize?: number
  color?: string
  alpha?: number
  angle?: number
  watch?: boolean
  css?: CSSStyleDeclaration
  destroy?: boolean
  container?: string | HTMLElement
}
```


## methods

```js
cwm.create({
  txt: ['demo', '96731', 'FIGHT'],
  watch: false,
  fontSize: 12,
  font: 'sans-serif',
  alpha: 0.2,
  angle: -15,
  color: '#8a2be2',
  destroy: false,
  // document.querySelector
  container: '.demo'
});
cwm.observing(() => console.log('sign'))
cwm.cancel()
```
