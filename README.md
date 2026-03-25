
<!DOCTYPE html>
<html>
<head>
    <title>Simple Calculator</title>
</head>
<body>

<h2>Simple Calculator</h2>

<input type="number" id="num1" placeholder="Number 1">
<input type="number" id="num2" placeholder="Number 2">

<br><br>

<button onclick="add()">Add</button>

<p id="result"></p>

<script>
function add() {
    let n1 = document.getElementById("num1").value;
    let n2 = document.getElementById("num2").value;
    document.getElementById("result").innerText = Number(n1) + Number(n2);
}
</script>

</body>
</html>
