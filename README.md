# ramadhan-grup-website
Grup ramadhan
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ramadhan Bersama Kami</title>

<style>
body{
    margin:0;
    font-family:Segoe UI, sans-serif;
    background:linear-gradient(180deg,#0b1d3a,#020817);
    color:white;
    text-align:center;
}

header{
    padding:50px 20px;
}

h1{
    color:gold;
    font-size:38px;
    margin-bottom:10px;
}

p{
    font-size:16px;
    color:#ddd;
}

.card{
    background:rgba(255,215,0,0.08);
    border:1px solid gold;
    border-radius:15px;
    padding:25px;
    width:85%;
    max-width:400px;
    margin:30px auto;
}

button{
    background:gold;
    color:#0b1d3a;
    border:none;
    padding:14px 25px;
    font-size:16px;
    border-radius:10px;
    cursor:pointer;
    transition:0.3s;
}

button:hover{
    background:#ffd700;
    transform:scale(1.05);
}

#info{
    display:none;
    margin-top:15px;
    color:#ccc;
}

footer{
    margin-top:40px;
    padding:15px;
    color:#888;
    font-size:14px;
}
</style>
</head>

<body>

<header>
<h1>🌙 Ramadhan Kareem 🌙</h1>
<p>Yuk isi Ramadhan dengan hal positif bersama kami!</p>
</header>

<div class="card">
<h2>Gabung Grup Ramadhan</h2>
<p>Berbagi ilmu, pengingat ibadah, dan kegiatan seru selama bulan suci.</p>

<a href="https://chat.whatsapp.com/JAP1VU4uy2DHLrVDwg4y3c?mode=gi_t" target="_blank">
<button>📲 Gabung Sekarang</button>
</a>

<br><br>

<button onclick="toggleInfo()">Apa Isi Grup Ini?</button>

<div id="info">
<p>✨ Sharing pengingat puasa</p>
<p>✨ Info kegiatan Ramadhan</p>
<p>✨ Diskusi positif</p>
<p>✨ Menambah teman & pahala</p>
</div>
</div>

<footer>
Semoga Ramadhan kita penuh berkah 🤲
</footer>

<script>
function toggleInfo(){
    let x = document.getElementById("info");
    x.style.display = (x.style.display === "block") ? "none" : "block";
}
</script>

</body>
</html>
