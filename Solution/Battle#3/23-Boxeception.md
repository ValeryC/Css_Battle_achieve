## #23 - Boxeception

[Link to the problem](https://cssbattle.dev/play/23)

![result](./images/boxeception.png)

```html
<div>
<p a>
</div>
<style>
  body {
    background: #F3AC3C;
    display:flex;
    justify-content:center;
    align-items:center;
  }
  div{
    background:#1A4341;
    width:200px;
    height:200px;
  }
  [a]{
    background:#998235;
    width:100px;
    height:100px;
    margin-top:100px;
  }
  [a]::after{
    background:#F3AC3C;
    width:50px;
    height:50px;
    content:"";
    position:absolute;
    top:200px;
    left:150px;
  }
</style>
```