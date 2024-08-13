If you were expecting a proper readme, you would be disappointed.
youtube.html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Piped</title>
    <link rel="apple-touch-icon" sizes="128x128" href="img/piped.svg">
  <link rel="icon" type="image/x-icon" href="img/piped.svg">

<script src="style.js">styleload();</script>
<link id="style" rel="stylesheet" href="">
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>YoHoHo IO</title>
</head>
<body onload="changeIframeSrc('https://tiny-garage-loud.on-fleek.app/')">

<div id="buttons" style="
  position:fixed;
  top:0;  
  width: 50%;
  margin: auto;
  z-index:99;
  left:0;
  right:0;">
<center>
<a id="server" style="text-color: #000000; background-color: #d0d0d0" onclick="changeIframeSrc('https://tiny-garage-loud.on-fleek.app/')">Server 1</a>
<a id="server" style="text-color: #000000; background-color: #d0d0d0" onclick="changeIframeSrc('https://alerbra8.top')">Server 2</a>
    <a id="server" style="text-color: #000000; background-color: #d0d0d0" onclick="changeIframeSrc('https://tiny-garage-loud.vercel.app/')">Server 3</a>

</center>
</div>
<center>
<iframe id="game" src="https://example.com" style="position:fixed; top:0; left:0; bottom:0; right:0; width:100%; height:100%; border:none; margin:0; padding:0; overflow:hidden;">
    Your browser doesn't support iframes
</iframe>

<script>
function changeIframeSrc(newSrc) {
    var iframe = document.getElementById('game');
    iframe.src = newSrc;
    styleload();
}
</script>
</center>


</body>
</html>
