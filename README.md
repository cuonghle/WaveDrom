# WaveDrom
1. Put following line into your HTML page <header> or <body>:
<script src="http://wavedrom.com/skins/default.js" type="text/javascript"></script>
<script src="http://wavedrom.com/wavedrom.min.js" type="text/javascript"></script>

or from CDN:
<script src="https://cdnjs.cloudflare.com/ajax/libs/wavedrom/1.4.1/skins/default.js" type="text/javascript"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/wavedrom/1.4.1/wavedrom.min.js" type="text/javascript"></script>

2. Set onload event for HTML body.
<body onload="WaveDrom.ProcessAll()">

3. Insert WaveJSON source inside HTML <body> wrapped with <script> tag:
<script type="WaveDrom">
{ signal : [
  { name: "clk",  wave: "p......" },
  { name: "bus",  wave: "x.34.5x",   data: "head body tail" },
  { name: "wire", wave: "0.1..0." },
]}
</script>
