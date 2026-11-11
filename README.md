
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>World Cricket Live</title>
<style>
body{margin:0;background:#071b16;color:white;font-family:Arial}
header{background:#087443;padding:22px;text-align:center}
h1{margin:0}
nav{display:flex;justify-content:space-around;background:#12352a;padding:14px}
nav button{background:none;color:white;border:0;font-size:15px}
main{padding:18px}
.card{background:#174333;padding:18px;border-radius:14px;margin:15px 0}
.score{font-size:28px;color:#7dffad;font-weight:bold}
.small{color:#c8ded2}
</style>
</head>
<body>
<header>
<h1>🏏 WORLD CRICKET LIVE</h1>
<p>Worldwide Cricket Updates</p>
</header>
<nav>
<button onclick="show('Live')">Live</button>
<button onclick="show('Upcoming')">Upcoming</button>
<button onclick="show('Results')">Results</button>
</nav>
<main>
<h2 id="heading">Live Cricket Scores</h2>
<div id="matches">
<div class="card">
<h3>🇵🇰 Pakistan vs Sri Lanka 🇱🇰</h3>
<div class="score">434/9d</div>
<p class="small">Pakistan - 1st Innings</p>
<div class="score">114/3</div>
<p>Sri Lanka - 1st Innings</p>
<p>Day 2</p>
</div>
<div class="card">
<h3>🌍 World Cricket</h3>
<p>Welcome to World Cricket Live!</p>
<p>Live scores, matches and updates.</p>
</div>
</div>
</main>
<script>
function show(tab){
document.getElementById('heading').innerText=tab+' Cricket';
document.getElementById('matches').innerHTML=
'<div class="card"><h3>'+tab+' Matches</h3><p>World Cricket Updates</p></div>';
}
</script>
</body>
</html>
