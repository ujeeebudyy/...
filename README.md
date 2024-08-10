<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FROM B</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1 class="h1-navbar">untuk wanita bernama Dinda Akila Aulia gw cuma mau bilang....</h1>
        <button id="revealButton">Reveal</button>


        <div id="heartContainer" class="hidden">
              <div class="heart">
                <img src="d5269a14-abda-4013-8063-09102bab4c46.jpeg" width="30%" height="30%"/>
              </div>
        <p class="p-content">LU CAKEP BANGET SUMPAH</p>
        </div>


</div>
</body>
<script>
    document.getElementById('revealButton').addEventListener('click', function() {
        document.getElementById('heartContainer').classList.remove('hidden');
    });
</script>
</html>
 61 changes: 61 additions & 0 deletions61  
style.css
Original file line number	Original file line	Diff line number	Diff line change
@@ -0,0 +1,61 @@
body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background: lightslategray;
    font-family: 'arival', sans-serif;
}

.h1-navbar {
    font-size: 140%;
}

.container {
    text-align: center;
}

button {
    padding:  10px 20px;
    font-size: 18px;
    cursor: pointer;
    background: #ff6f61;
    color: white;
    border: none;
    border-radius: 7px;
    transition: background 0.3s;
}

button:hover {
    background: #ff3b2f;
}

.hidden {
    display: none;
}

.p-content {
    display: flex;
    flex-direction: column;
    font-size: 140%;
    justify-content: center;
    align-items: center;
}

#heartContainer {
    margin-top: 20px;
    animation: fadeIn 2.5s ease-in-out;
}

.heart {
    display: flex;
    justify-content: center;
    align-items: center;
}



@keyframes fadeIn {
    0% { opacity: 0;}
    100% { opacity: 1;}
}
