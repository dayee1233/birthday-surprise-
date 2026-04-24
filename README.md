<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>For My Love ❤️</title>
<style>
body {
  margin: 0;
  background: black;
  color: white;
  text-align: center;
  font-family: 'Arial', sans-serif;
  overflow: hidden;
}

h1 {
  margin-top: 20%;
  font-size: 3em;
  animation: fadeIn 3s ease-in-out;
}

p {
  width: 70%;
  margin: 20px auto;
  font-size: 1.2em;
  opacity: 0;
  animation: fadeIn 5s ease-in-out forwards;
  animation-delay: 3s;
}

@keyframes fadeIn {
  from {opacity: 0;}
  to {opacity: 1;}
}

/* Flower effect */
.flower {
  position: absolute;
  top: -10px;
  font-size: 20px;
  animation: fall linear infinite;
}

@keyframes fall {
  to {
    transform: translateY(100vh);
  }
}
</style>
</head>

<body>

<h1>🎉 Happy Birthday My Love ❤️ 🎉</h1>

<p>
From the moment you came into my life, everything changed...  
You are not just my wife, you are my peace, my happiness, my everything.  
Today is special because you were born… but for me, every day is special because I have you.  
I love you more than words can ever explain ❤️
</p>

<script>
// Create falling flowers
for (let i = 0; i < 30; i++) {
  let flower = document.createElement("div");
  flower.className = "flower";
  flower.innerHTML = "🌸";
  flower.style.left = Math.random() * 100 + "vw";
  flower.style.animationDuration = (3 + Math.random() * 5) + "s";
  document.body.appendChild(flower);
}
</script>

</body>
</html>
