# Animal Parallax

![gif](http://g.recordit.co/CMJKa5x72d.gif)

### Parallax scrolling is an effect where the background content (usually an image) is moved at a different speed than the foreground context while scrolling.

Use `flexbox` and viewport height and width to center the `background-image`

```
section {
  align-items: center;
  background-attachment: fixed;
  background-repeat: no-repeat;
  background-size: cover;
  display: flex;
  height: 100vh;
  justify-content: center;
  width: 100vw;
}
```

Use `nth-of-type` to set a specific `background-image` to each `section`

```
section:nth-of-type(2) {
  background-image: url('../img/bunny.jpg');
}
```
