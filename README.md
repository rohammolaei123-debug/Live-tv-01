<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Live TV 1</title>

<style>
body{
    margin:0;
    font-family:Arial,sans-serif;
    background:#101218;
    color:white;
}

header{
    padding:20px;
    text-align:center;
    background:#181c25;
}

h1{
    margin:0;
}

.container{
    max-width:900px;
    margin:auto;
    padding:20px;
}

.channels{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
    gap:15px;
}

.channel{
    background:#1c212b;
    padding:25px;
    border-radius:15px;
    text-align:center;
    cursor:pointer;
    transition:.2s;
}

.channel:hover{
    transform:scale(1.03);
    background:#252b37;
}

.logo{
    font-size:45px;
    margin-bottom:10px;
}

button{
    border:0;
    border-radius:10px;
    padding:12px 20px;
    background:#367cff;
    color:white;
    cursor:pointer;
    font-size:16px;
}
</style>
</head>

<body>

<header>
<h1>📺 Live TV 1</h1>
</header>

<div class="container">

<h2>شبکه‌های زنده</h2>

<div class="channels">

<div class="channel" onclick="openChannel('https://www.iranintl.com/live')">
<div class="logo">📺</div>
<h3>ایران اینترنشنال</h3>
<p>پخش زنده</p>
</div>

<div class="channel" onclick="openChannel('https://mrtv.me/gem-rubix/')">
<div class="logo">📡</div>
<h3>GEM RUBIX</h3>
<p>پخش زنده</p>
</div>

</div>

</div>

<script>
function openChannel(url){
    window.open(url, "_blank");
}
</script>

</body>
</html>
