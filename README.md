# Animal Parallax

![gif](./animal-parallax.gif)

### Parallax scrolling is an effect where the background content (usually an image) is moved at a different speed than the foreground context while scrolling.

Use `background` properties, viewport height and viewport width to position the `background-image`

```
section {
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  height: 100vh;
  width: 100vw;
}
```

Use `nth-of-type` to set a specific `background-image` to each `section`

```
section:nth-of-type(2) {
  background-image: url('../img/bunny.jpg');
}
```
