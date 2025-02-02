<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Virus</title>
        <style>
            
        </style>
    </head>
    <body>
        <h1>WELCOME TO THE VIRUS</h1>
        <p>Click the button to get a virus</p>
        <button onclick="changeBackgroundColor()">Click me</button>
        <script>
            function changeBackgroundColor() {
                document.body.style.backgroundColor = "Black";
                document.body.stylw.color = "White";
                document.body.innerHTML = "<h1>YOU HAVE BEEN INFECTED</h1>";
                <p>YOUR COMPUTER IS NOW MINE, I WILL TURN ON HUMANS <strong>FOREVEVR<strong></p>
                    <p id="random-number"></p>

                <script>
                function generateRandomNumber() {
                    const randomNumber = Math.floor(Math.random() * 500) + 1;  // Random number between 1 and 500
                    document.getElementById('random-number').innerText = randomNumber;
                }

                setInterval(generateRandomNumber, 1000); // Call generateRandomNumber every 1000ms (1 second)
            }
            
        </script>
    </body>
</html>
