<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Calculadora Envíos</title>
<style>
body {
  font-family: Arial;
  background: #0f172a;
  color: white;
  text-align: center;
  padding: 20px;
}
input, button {
  padding: 12px;
  margin: 10px;
  font-size: 18px;
  width: 90%;
  border-radius: 10px;
  border: none;
}
button {
  background: #22c55e;
  color: white;
}
.result {
  margin-top: 20px;
  font-size: 22px;
  color: #facc15;
}
</style>
</head>

<body>

<h2>💸 Calculadora Bolivia</h2>

<input type="number" id="bs" placeholder="Monto en Bs">

<input type="number" id="cambio" value="150">

<button onclick="calcular()">Calcular</button>

<div class="result" id="resultado"></div>

<script>
function calcular() {
  let bs = document.getElementById("bs").value;
  let cambio = document.getElementById("cambio").value;
  let total = bs * cambio;

  document.getElementById("resultado").innerHTML =
    "💰 Cobrar: " + total.toLocaleString() + " ARS";
}
</script>

</body>
</html>
