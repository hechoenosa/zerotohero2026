# Kitty paw

A bright pink, fuzzy kitty paw. Press it: the claws pop out, it meows, wobbles like jelly and throws tennis balls, yarn or fish.

**Try it live:** https://hechoenosa.github.io/zerotohero2026/components/kitty-paw/

One file, plain HTML, CSS and JavaScript. No libraries. Sister of the [paw button](../paw-button/).

## How it works

| Part | Where in `index.html` | What to change |
|---|---|---|
| Fur | Section 1 | `FUR_DARK` and `FUR_LIGHT` set the colour. `EDGE_FLUFF` sets how fuzzy the edges are. |
| Beans | Section 1, `bean()` | The three gradient colours |
| Claws | The `<svg id="claws">` in the HTML | Move, resize or remove them |
| Sound | Section 2 | Swap the made-up meow for a real one: `new Audio('meow.mp3').play()` |
| Effects | Section 3 | Add your own icon to `ICONS` |
| What happens on press | Section 4 | Listen for the `paw` event |

```js
document.addEventListener('paw', () => {
  // show the cats, open donations, ...
});
```

## Already built in

- Works with mouse, touch and keyboard (Enter or Space)
- Screen readers hear "Meet the cats"
- People who turn off motion on their device get no wobble or flying balls
- Sound has an on/off switch
