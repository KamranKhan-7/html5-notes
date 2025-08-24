## marquee tag
The `<marquee>` tag in HTML is used to create scrolling text or images (horizontally or vertically).   

`⚠️ Note`: It is deprecated in HTML5 (not recommended) — use CSS animations instead. But you may still see it in old code.

#### 🔹 Syntax:
`<marquee>Scrolling Text</marquee>`

#### 🔹 Attributes:
| Attribute       | Description                                | Example                                          |
|-----------------|--------------------------------------------|--------------------------------------------------|
| `direction`     | Scroll direction (`left`, `right`, `up`, `down`) | `<marquee direction="right">Text</marquee>` |
| `behavior`      | Type of movement (`scroll`, `slide`, `alternate`) | `<marquee behavior="alternate">Text</marquee>` |
| `scrollamount`  | Speed (pixels per move)                    | `<marquee scrollamount="10">Fast</marquee>` |
| `scrolldelay`   | Delay (in ms)                              | `<marquee scrolldelay="200">Slow</marquee>` |
| `loop`          | Number of times to repeat (default = infinite) | `<marquee loop="3">Only 3 times</marquee>` |
| `bgcolor`       | Background color                           | `<marquee bgcolor="yellow">Hello</marquee>` |
| `width` & `height` | Size of marquee area                    | `<marquee width="200" height="50">Text</marquee>` |
 


🔹 Example:
```html <marquee behavior="alternate" direction="right" scrollamount="5" bgcolor="lightblue">
  Welcome to My Website!
</marquee>
```