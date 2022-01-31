<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <h1>Wordle</h1>
  <h3>Press 'ENTER' to guess</h3>
  <div id="warning"></div>
  <div id="alphabet"></div>
  <button type="button" onclick="javascript:window.dispatchEvent(new KeyboardEvent('keydown',{'key':'enter'}));">ENTER</button>
  <button type="button" onclick="javascript:window.dispatchEvent(new KeyboardEvent('keydown',{'key':'backspace'}));">BACKSPACE</button>
  <button type="button" onclick="javascript:window.location.href = window.location.href;">START NEW GAME</button>
  <div id="grid"></div>
  <div><button id="openKeyboard">Open Keyboard</button></div>
  <input id="hiddenInput" style="visibility: hidden; font-size:16px;">
<script src="index.js"></script>
</body>
</html>
