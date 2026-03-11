<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quantum Age Predictor</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            text-align: center;
        }.container {
        background: rgba(255, 255, 255, 0.1);
        padding: 40px;
        border-radius: 15px;
        backdrop-filter: blur(10px);
        width: 300px;
    }

    input {
        padding: 10px;
        width: 80%;
        border: none;
        border-radius: 5px;
        margin-top: 15px;
    }

    button {
        padding: 10px 20px;
        margin-top: 15px;
        border: none;
        border-radius: 5px;
        background: #00c6ff;
        color: white;
        cursor: pointer;
        font-weight: bold;
    }

    button:hover {
        background: #0072ff;
    }

    .result {
        margin-top: 20px;
        font-size: 18px;
        min-height: 40px;
    }

    .loading {
        animation: blink 1s infinite;
    }

    @keyframes blink {
        50% { opacity: 0.5; }
    }
</style>

</head>
<body><div class="container">
    <h2>Quantum Age Predictor</h2>
    <p>Enter your age:</p>
    <input type="number" id="ageInput" placeholder="Your age">
    <br>
    <button onclick="predictAge()">Predict Age</button>
    <div class="result" id="result"></div>
</div><script>
    function predictAge() {
        const age = document.getElementById("ageInput").value;
        const resultDiv = document.getElementById("result");

        if (age === "") {
            resultDiv.innerHTML = "Please enter your age first!";
            return;
        }

        resultDiv.innerHTML = "<span class='loading'>Solving quantum equations...</span>";

        setTimeout(() => {
            resultDiv.innerHTML = "🧠 Quantum Prediction Complete! Your age is " + age + "!";
        }, 10000);
    }
</script></body>
</html><!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quantum Age Predictor</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            text-align: center;
        }.container {
        background: rgba(255, 255, 255, 0.1);
        padding: 40px;
        border-radius: 15px;
        backdrop-filter: blur(10px);
        width: 300px;
    }

    input {
        padding: 10px;
        width: 80%;
        border: none;
        border-radius: 5px;
        margin-top: 15px;
    }

    button {
        padding: 10px 20px;
        margin-top: 15px;
        border: none;
        border-radius: 5px;
        background: #00c6ff;
        color: white;
        cursor: pointer;
        font-weight: bold;
    }

    button:hover {
        background: #0072ff;
    }

    .result {
        margin-top: 20px;
        font-size: 18px;
        min-height: 40px;
    }

    .loading {
        animation: blink 1s infinite;
    }

    @keyframes blink {
        50% { opacity: 0.5; }
    }
</style>

</head>
<body><div class="container">
    <h2>Quantum Age Predictor</h2>
    <p>Enter your age:</p>
    <input type="number" id="ageInput" placeholder="Your age">
    <br>
    <button onclick="predictAge()">Predict Age</button>
    <div class="result" id="result"></div>
</div><script>
    function predictAge() {
        const age = document.getElementById("ageInput").value;
        const resultDiv = document.getElementById("result");

        if (age === "") {
            resultDiv.innerHTML = "Please enter your age first!";
            return;
        }

        resultDiv.innerHTML = "<span class='loading'>Solving quantum equations...</span>";

        setTimeout(() => {
            resultDiv.innerHTML = "🧠 Quantum Prediction Complete! Your age is " + age + "!";
        }, 10000);
    }
</script></body>
</html>
