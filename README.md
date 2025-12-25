<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>PlayerJS M3U8</title>
<style>
html, body {
    margin: 0;
    padding: 0;
    background: #000;
}
#player {
    width: 100%;
    height: 100vh;
}
</style>
</head>
<body>

<div id="player"></div>

<script src="playerjs.js"></script>
<script>
var player = new Playerjs({
    id: "player",
    file: "https://test-streams.mux.dev/x36xhzz/x36xhzz.m3u8"
});
</script>

</body>
</html>
