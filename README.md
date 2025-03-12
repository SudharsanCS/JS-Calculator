

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="/Calculator/style.css" rel="stylesheet" />
    
</head>
<body>
    <div class="calculator">
        <h1>Calculator</h1>
        <input type="text" id="display"/>
        <div class="buttons">
            <button onclick="clearDisplay()" class="btn">C</button>
            <div class="button-wrap">
                <button onclick="displayValue(7)" class="btn">7</button>
                <button onclick="displayValue(8)" class="btn">8</button>
                <button onclick="displayValue(9)"  class="btn">9</button>
                <button onclick="displayValue('/')"  class="btn">/</button>
            </div>
            <div class="button-wrap">
                <button  onclick="displayValue(4)" class="btn">4</button>
                <button onclick="displayValue(5)"  class="btn">5</button>
                <button onclick="displayValue(6)"  class="btn">6</button>
                <button onclick="displayValue('*')"class="btn">*</button>
            </div>
            <div class="button-wrap">
                <button onclick="displayValue(1)"class="btn">1</button>
                <button onclick="displayValue(2)" class="btn">2</button>
                <button onclick="displayValue(3)"class="btn">3</button>
                <button onclick="displayValue('-')" class="btn">-</button>
            </div>
            <div class="button-wrap">
                <button  onclick="displayValue('.')" class="btn">.</button>
                <button  onclick="displayValue(0)" class="btn">0</button>
                <button  onclick="displayValue('+')"class="btn">+</button>
                <button  onclick="calculate('=')"class="btn">=</button>
            </div>

        </div>

    </div>
    
</body>
<script src="/Calculator/js-calci/calci-script.js"></script>
</html>
