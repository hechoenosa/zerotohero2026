# Paw button

A furry dog paw you can press. It squashes, says "boof", and throws tennis balls, bones or paw prints.

**Try it live:** https://hechoenosa.github.io/zerotohero2026/components/paw-button/

Made for a rescue-animal fostering site. One file, plain HTML, CSS and JavaScript. No libraries.

## How it works

| Part | Where in `index.html` | What to change |
|---|---|---|
| Fur | Section 1 | `FUR_DARK` and `FUR_LIGHT` set the colour (black lab, golden, brindle). `STRANDS` sets how thick the fur is. |
| Pads | Section 1, `pad()` | The gradient colours and the number of bumps |
| Sound | Section 2 | Swap the made-up woof for a real bark: `new Audio('bark.mp3').play()` |
| Effects | Section 3 | Add your own icon to `ICONS` |
| What happens on press | Section 4 | Listen for the `paw` event to open the animals list or a donation |

```js
document.addEventListener('paw', () => {
  // show the animals, open donations, ...
});
```

## Already built in

- Works with mouse, touch and keyboard (Enter or Space)
- Screen readers hear "Meet the dogs"
- People who turn off motion on their device get no bouncing
- Sound has an on/off switch

## Ideas

- Record a real shelter dog barking and use that sound
- Give each animal's card a paw in that animal's fur colour
- Photograph a real paw and give it the same squash
