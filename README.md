# Roulette Wheel

## Rational

- Nice code (modular, simple API, no dependencies, vanilla JS, and easy to see how it works).
- Easy to implement and change the appearance.
- Extra features, like an animated pointer, flick gestures, etc.

## Features
- [x] No dependencies. 
- [x] Simple, easy to read API.
- [x] Realistic wheel rotation (no easing, just momentum and drag).
- [x] Resize the canvas automatically to fit inside it's container.
- [x] Implements `requestAnimationFrame` instead of `setTimeout`.
- [x] Items can have their own weight.
- [x] Adjust item labels appearance.
- [x] Change item background color.
- [x] Click region is localised to the shape of the wheel.
- [x] Callbacks (`spin`, and `finish`).
- [x] Support for clockwise and anticlockwise spinning.
- [x] Setting to allow clicking the wheel to spin it, otherwise you can manually call `spin()`.
- [x] Draw an image over the canvas (easily themeable).
- [ ] Drag the edge of wheel to spin in that direction (or flick gesture).
- [ ] Realistic pointer that moves when it hits pins on the spinning wheel.
- [ ] Each item can have its own image.
- [ ] Draw an image on the wheel (which will rotate with the wheel).
- [ ] Change appearance of the lines between each item.

## Acknowledgements

Inspired by [random-wheel](https://github.com/njradford/random-wheel).
