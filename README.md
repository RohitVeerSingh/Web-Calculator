# Web-Calculator
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Calculator</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-giJF6kkoqNQ00vy+HMDP7azOuL0xtbfIcaT9wjKHr8RbDVddVHyTfAAsrekwKmP1" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <form class="calculator" action="index.html" method="post" name="calc">
      <input class="value" type="text" name="txt" value="">
      <span class="num" onclick="document.calc.txt.value += '+'">+</span>
      <span class="num" onclick="document.calc.txt.value += '1'">-</span>
      <span class="num" onclick="document.calc.txt.value += '*'">×</span>
      <span class="num" onclick="document.calc.txt.value += '/'">÷</span>
      <span class="num" onclick="document.calc.txt.value += '7'">7</span>
      <span class="num" onclick="document.calc.txt.value += '8'">8</span>
      <span class="num" onclick="document.calc.txt.value += '9'">9</span>
      <span class="num equal" onclick="document.calc.txt.value = eval(document.calc.txt.value)">=</span>
      <span class="num" onclick="document.calc.txt.value += '4'">4</span>
      <span class="num" onclick="document.calc.txt.value += '5'">5</span>
      <span class="num" onclick="document.calc.txt.value += '6'">6</span>
      <span class="num" onclick="document.calc.txt.value += '1'">1</span>
      <span class="num" onclick="document.calc.txt.value += '2'">2</span>
      <span class="num" onclick="document.calc.txt.value += '3'">3</span>
      <span class="num zero" onclick="document.calc.txt.value += '0'">0</span>
      <span class="num" onclick="document.calc.txt.value += '.'">.</span>
      <span class="num clear" onclick="document.calc.txt.value = '' ">AC</span>
    </form>
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="index.js"></script>
  </body>
</html>
