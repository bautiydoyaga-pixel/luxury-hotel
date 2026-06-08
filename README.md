<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Luxury Hotel Jamaica</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#f5f5f5;
    color:#333;
}

header{
    background:url("https://images.unsplash.com/photo-1566073771259-6a8506099945?w=1600") center/cover;
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    color:white;
}

.hero{
    background:rgba(0,0,0,0.5);
    padding:30px;
    border-radius:15px;
}

.hero h1{
    font-size:4rem;
}

.hero p{
    font-size:1.2rem;
    margin-top:10px;
}

.btn{
    display:inline-block;
    margin-top:20px;
    padding:12px 25px;
    background:gold;
    color:black;
    text-decoration:none;
    border-radius:8px;
    font-weight:bold;
}

section{
    padding:60px 10%;
}

h2{
    text-align:center;
    margin-bottom:30px;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.card{
    background:white;
    padding:20px;
    border-radius:12px;
    box-shadow:0 0 10px rgba(0,0,0,0.1);
}

.precio{
    color:green;
    font-weight:bold;
    margin-top:10px;
}

.lista{
    max-width:700px;
    margin:auto;
    background:white;
    padding:25px;
    border-radius:12px;
}

.lista li{
    margin:12px 0;
}

footer{
    background:#111;
    color:white;
    text-align:center;
    padding:25px;
}
</style>
</head>

<body>

<header>
    <div class="hero">
        <h1>Luxury Hotel</h1>
        <p>Disfruta de Jamaica con comodidad, lujo y las mejores vistas.</p>
        <a href="#habitaciones" class="btn">Ver habitaciones</a>
    </div>
</header>

<section id="habitaciones">
    <h2>🏨 Alojamientos</h2>

    <div class="cards">

        <div class="card">
            <h3>Económico</h3>
            <p>Ideal para viajeros que buscan comodidad a bajo costo.</p>
            <div class="precio">$40 - $90 por noche</div>
        </div>

        <div class="card">
            <h3>Todo Incluido</h3>
            <p>Comidas, bebidas y servicios incluidos.</p>
            <div class="precio">$150 - $400 por noche</div>
        </div>

        <div class="card">
            <h3>Lujoso</h3>
            <p>Suites premium con atención exclusiva.</p>
            <div class="precio">Desde $400 por noche</div>
        </div>

    </div>
</section>

<section>
    <h2>📍 Ubicaciones</h2>

    <div class="cards">
        <div class="card"><h3>Montego Bay</h3></div>
        <div class="card"><h3>Negril</h3></div>
        <div class="card"><h3>Ocho Ríos</h3></div>
    </div>
</section>

<section>
    <h2>💵 Gastos diarios estimados</h2>

    <ul class="lista">
        <li>🍽️ Restaurante: $10 - $18</li>
        <li>🚕 Transporte: $12 - $48</li>
        <li>🎟️ Entradas a sitios turísticos: $20 - $70</li>
        <li>💰 Presupuesto recomendado: desde $80 por día</li>
    </ul>
</section>

<section>
    <h2>📞 Contacto</h2>

    <div class="lista">
        <p>Email: reservas@luxuryhotel.com</p>
        <br>
        <p>Teléfono: +1 876 000 0000</p>
    </div>
</section>

<footer>
    <p>© 2026 Luxury Hotel Jamaica</p>
</footer>

</body>
</html>
