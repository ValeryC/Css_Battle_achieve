# Battle #4 - Display

## #28 - Cups & balls

[Link to the problem](https://cssbattle.dev/play/28)

![result](./images/cups&balls.png)

```html
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<style>
  body{
	  background: #1A4341;
    display:flex;
    justify-content:center;
    align-content:center;
    flex-wrap:wrap;
    padding:20px
  }
  div{
    width:50px;
    height:50px;
    border-radius:50px;
    background:#998235;
    margin:10px;
  }
  div:nth-of-type(2),
  div:nth-of-type(3){
    border-radius:50% 50% 0 0;
  }
  div:nth-of-type(5),
  div:nth-of-type(8){
    border-radius: 0 0 50% 50%;
  }
  div:nth-of-type(2),
  div:nth-of-type(4),
  div:nth-of-type(5),
  div:nth-of-type(7){
    background:#F3AC3C;
  }
</style>
```