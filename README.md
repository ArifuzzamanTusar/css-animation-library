# Looping Animation CSS Library

A lightweight, ready-to-use CSS library for adding continuous, looping animations to your web projects. Just add a class to an element, and it will animate forever.

---

## How to Use

Using the library is simple. Follow these two steps:

**1. Link the Stylesheet**

First, include the `looping-animations.css` file in the `<head>` of your HTML document.

```html
<head>
  <link rel="stylesheet" href="path/to/your/looping-animations.css">
</head>
```

**2. Add an Animation Class**

Next, add the desired animation class to any HTML element you want to animate. All animations in this library loop by default.

```html
<!-- This div will float up and down continuously -->
<div class="float-y">I'm floating!</div>

<!-- This icon will spin forever -->
<i class="spin">🔄</i>
```

---

## Available Animations

Here is a complete list of all the animation classes available in the library.

### Movement

| Class Name            | Description                                                  |
| --------------------- | ------------------------------------------------------------ |
| `.float-y`            | Gently floats the element up and down.                       |
| `.float-x`            | Gently floats the element left and right.                    |
| `.float-top-left`     | Floats diagonally towards the top-left corner and back.      |
| `.float-top-right`    | Floats diagonally towards the top-right corner and back.     |
| `.float-bottom-left`  | Floats diagonally towards the bottom-left corner and back.   |
| `.float-bottom-right` | Floats diagonally towards the bottom-right corner and back.  |
| `.patrol-x`           | Moves an element back and forth horizontally. (Requires `position: absolute` on the element and `position: relative` on its parent). |
| `.orbit`              | Rotates an element in a circular path.                       |

### Rotation

| Class Name | Description                                    |
| ---------- | ---------------------------------------------- |
| `.spin`    | Rotates an element 360 degrees continuously.   |
| `.rocking` | Rocks an element back and forth like a pendulum. |

### Emphasis & Attention

| Class Name    | Description                               |
| ------------- | ----------------------------------------- |
| `.breathing`  | A slow, calm scaling effect.              |
| `.wiggle`     | A quick, slight side-to-side rotation.    |
| `.jello`      | A wobbly, jelly-like shake.               |
| `.vibrate`    | A very subtle, high-frequency shake.      |
| `.heartbeat`  | A fast, intense pulse like a heartbeat.   |
| `.blink`      | Fades an element's opacity in and out.    |

### Glows, Colors & Fills

| Class Name           | Description                                                        |
| -------------------- | ------------------------------------------------------------------ |
| `.pulse-glow`        | Pulses the element with a soft, colored `box-shadow`.              |
| `.color-change`      | Cycles the `background-color` through several preset colors.       |
| `.glow-border`       | Cycles the `border-color` through several preset colors.           |
| `.text-shadow-glow`  | Adds a glowing, pulsing `text-shadow` to text elements.            |
| `.gradient-shift`    | Animates the position of a background gradient for a shifting effect. |

### Skew & Distort

| Class Name | Description                                  |
| ---------- | -------------------------------------------- |
| `.skew-x`  | Skews an element back and forth on the X-axis. |
| `.skew-y`  | Skews an element back and forth on the Y-axis. |

---

## Customization

You can easily customize any animation by editing the CSS file. Feel free to change properties like `animation-duration`, `animation-timing-function`, or the transform values inside the `@keyframes` to better suit your needs.

## License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).
