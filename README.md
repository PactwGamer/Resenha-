<!DOCTYPE html>

<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Global News | Urgente</title>

<style>
body {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
    background: #f4f4f4;
}

/* TOPO */
.topbar {
    background: #111;
    color: #fff;
    padding: 8px 15px;
    display: flex;
    justify-content: space-between;
    font-size: 13px;
}

.header {
    background: #c40000;
    color: white;
    padding: 15px;
    font-size: 28px;
    font-weight: bold;
}

/* MENU */
.menu {
    background: white;
    padding: 10px 15px;
    display: flex;
    gap: 20px;
    border-bottom: 1px solid #ddd;
}

/* LAYOUT */
.main {
    display: flex;
    max-width: 1200px;
    margin: auto;
}

/* CONTEÚDO */
.content {
    flex: 3;
    background: white;
    padding: 20px;
}

.sidebar {
    flex: 1;
    padding: 20px;
}

/* BREAKING */
.breaking {
    background: red;
    color: white;
    padding: 8px;
    font-weight: bold;
    animation: blink 1s infinite;
}

@keyframes blink {
    0% {opacity: 1;}
    50% {opacity: 0.5;}
    100% {opacity: 1;}
}

/* TEXTO */
.title {
    font-size: 34px;
    margin: 15px 0;
}

.subtitle {
    color: gray;
    margin-bottom: 15px;
}

.image {
    width: 100%;
    height: 350px;
    background: url('https://images.unsplash.com/photo-1495020689067-958852a7765e') center/cover;
    margin-bottom: 20px;
}

.article {
    font-size: 18px;
    line-height: 1.7;
}

/* SIDEBAR */
.card {
    background: white;
    padding: 15px;
    margin-bottom: 15px;
}

.card h3 {
    margin: 0 0 10px;
}

/* RODAPÉ */
.footer {
    margin-top: 30px;
    background: #111;
    color: #ccc;
    text-align: center;
    padding: 20px;
}
</style>

</head>

<body>

<div class="topbar">
<span>📡 Últimas notícias</span>
<span id="clock"></span>
</div>

<div class="header">GLOBAL NEWS</div>

<div class="menu">
<span>Política</span>
<span>Economia</span>
<span>Internacional</span>
<span>Tecnologia</span>
<span>Ao Vivo</span>
</div>

<div class="main">

<div class="content">

<div class="breaking">🔴 URGENTE: SITUAÇÃO GLOBAL EM DESENVOLVIMENTO</div>

<div class="title">
Conflito internacional entra em escalada e coloca países em alerta máximo
</div>

<div class="subtitle">
Atualizado em tempo real — 1º de abril de 2026
</div>

<div class="image"></div>

<div class="article">
Relatórios recentes indicam uma intensificação significativa de tensões entre grandes potências globais, levando autoridades a adotarem medidas emergenciais de segurança.

<br><br>

Espaços aéreos foram parcialmente fechados em diversas regiões, enquanto governos reforçam sistemas de defesa e monitoramento.

<br><br>

Analistas internacionais avaliam o cenário como uma das maiores crises geopolíticas das últimas décadas, com impactos potenciais na economia global e na segurança internacional.

<br><br>

A comunidade diplomática trabalha para conter a escalada e evitar consequências mais graves.

<br><br>

Mais informações serão divulgadas a qualquer momento.

</div>

</div>

<div class="sidebar">

<div class="card">
<h3>🔥 Agora</h3>
<p>Mercados globais registram queda após tensões.</p>
</div>

<div class="card">
<h3>🌍 Internacional</h3>
<p>Líderes discutem reunião de emergência.</p>
</div>

<div class="card">
<h3>📊 Economia</h3>
<p>Preço do petróleo sobe rapidamente.</p>
</div>

</div>

</div>

<div class="footer">
© 2026 Global News — Conteúdo fictício para simulação
</div>

<script>
function updateClock() {
    const now = new Date();
    document.getElementById("clock").innerText = now.toLocaleTimeString();
}
setInterval(updateClock, 1000);

/* Atualização automática de texto */
setTimeout(() => {
    document.querySelector(".breaking").innerText = "🔴 ATUALIZAÇÃO: Líderes convocam reunião urgente";
}, 5000);
</script>

</body>
</html>
