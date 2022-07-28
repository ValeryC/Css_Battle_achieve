# Battle #3 - Visibility

## #19 - Cube

[Link to the problem](https://cssbattle.dev/play/19)

![result](./images/cube.png)

```html
<p a><p b><p c>
<style>
body {
  display: flex;
  justify-content: center;
  background: #0b2429;
}
p {
  position: absolute;
}
p[a] {
  width: 100px;
  height: 100px;
  background: #f3ac3c;
  transform: rotate(45deg);
  position: relative;
  top: 112px;
  left: 0px;
}

p[b] {
  background: #998235;
  width: 71px;
  height: 70px;
  top: 64px;
  left: 130px;
  transform: skew(0, -45deg);
}

p[c] {
  background: #1a4341;
  width: 71px;
  height: 70px;
  top: 64px;
  left: 200px;
  transform: skew(0, 45deg);
}
</style>
```