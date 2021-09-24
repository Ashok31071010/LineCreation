<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<title>Your Canvas</title>

<style type="text/css"><!--
#container { position: relative; }
#imageTemp { position: absolute; top: 1px; left: 1px; }
--></style>

</head>
<body>
<canvas id="imageView" width="600" height="500"></canvas>

<script type="text/javascript">
var canvas, context, canvaso, contexto;
canvaso = document.getElementById('imageView');
context = canvaso.getContext('2d');
context.lineWidth = 5;

context.strokeStyle = '#000000';
context.beginPath();
context.moveTo(252, 25);
context.lineTo(135, 178);
context.stroke();
context.closePath();

context.strokeStyle = '#000000';
context.beginPath();
context.moveTo(327, 156);
context.lineTo(326, 320);
context.stroke();
context.closePath();

context.strokeStyle = '#000000';
context.beginPath();
context.moveTo(245, 233);
context.lineTo(431, 235);
context.stroke();
context.closePath();

context.strokeStyle = '#000000';
context.strokeRect(229, 394, 242, 44);
</script>
</body>
</html>
