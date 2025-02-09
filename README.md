# K-Culture
<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>K-Culture Hub</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f5f5f5;
        }
        h1 {
            color: #ff4081;
        }
        .container {
            width: 80%;
            margin: auto;
        }
        button {
            padding: 10px;
            margin: 10px;
            font-size: 18px;
            cursor: pointer;
            border: none;
            background-color: #ff4081;
            color: white;
            border-radius: 5px;
        }
        #output {
            margin-top: 20px;
            font-size: 20px;
            color: #333;
        }
    </style>
</head>
<body>
    
</body>
    <h1>K-Culture Hub</h1>
    <div class="container">
        <button onclick="showDictionary()">Dicționar Coreean</button>
        <button onclick="showKdramas()">K-Dramas</button>
        <button onclick="showKpop()">K-Pop</button>
        <button onclick="showNews()">Știri</button>
        <div id="output"></div>
    </div>
    <script>
        function showDictionary() {
            document.getElementById("output").innerHTML = `
                <h2>Dicționar Coreean</h2>
                <p>안녕하세요 - Bună ziua</p>
                <p>감사합니다 - Mulțumesc</p>
                <p>사랑해요 - Te iubesc</p>
            `;
        }
        function showKdramas() {
            document.getElementById("output").innerHTML = `
                <h2>K-Dramas Populare</h2>
                <ul>
                    <li>Crash Landing on You</li>
                    <li>Vincenzo</li>
                    <li>Goblin</li>
                    <li>Start-Up</li>
                </ul>
            `;
        }
        function showKpop() {
            document.getElementById("output").innerHTML = `
                <h2>Artiști K-Pop</h2>
                <ul>
                    <li>BTS</li>
                    <li>BLACKPINK</li>
                    <li>Twice</li>
                    <li>Stray Kids</li>
                </ul>
            `;
        }
        function showNews() {
            document.getElementById("output").innerHTML = `
                <h2>Ultimele Știri</h2>
                <p><a href="https://www.soompi.com/" target="_blank">Vezi știrile pe Soompi</a></p>
            `;
        }
    </script>

</body>
</html>
