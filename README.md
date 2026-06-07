<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>TiFashion - Produtos Sustentáveis</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background-image:url("02-as-paisagens-naturais-mais-lindas-do-brasil-lencois-maranhenses2-min.avif");
    background-size:cover;
    background-position:center;
    background-attachment:fixed;
    background-repeat:no-repeat;
}

header{
    background:rgba(34,139,34,0.9);
    color:white;
    text-align:center;
    padding:30px;
    box-shadow:0 2px 10px rgba(0,0,0,0.3);
}

header h1{
    font-size:2.8rem;
}

header p{
    margin-top:10px;
    font-size:1.1rem;
}

.produtos{
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    gap:25px;
    padding:40px;
}

.produto{
    width:280px;
    background:rgba(255,255,255,0.95);
    border-radius:15px;
    overflow:hidden;
    box-shadow:0 5px 15px rgba(0,0,0,0.3);
    transition:transform .3s;
}

.produto:hover{
    transform:translateY(-5px);
}

.carrossel{
    display:flex;
    overflow-x:auto;
    width:100%;
    scroll-snap-type:x mandatory;
    scroll-behavior:smooth;
    scrollbar-width:none;
    -webkit-overflow-scrolling:touch;
}

.carrossel::-webkit-scrollbar{
    display:none;
}

.carrossel img{
    flex:0 0 100%;
    width:100%;
    height:220px;
    object-fit:cover;
    scroll-snap-align:start;
}

.info{
    padding:15px;
    text-align:center;
}

.info h3{
    color:#2e7d32;
    margin-bottom:10px;
}

.preco{
    font-size:1.5rem;
    color:#1b5e20;
    font-weight:bold;
}

footer{
    background:rgba(34,139,34,0.9);
    color:white;
    text-align:center;
    padding:15px;
    margin-top:20px;
}

@media(max-width:768px){
    .produto{
        width:90%;
    }
}
</style>
</head>

<body>

<header>
    <h1>🌱 TiFashion</h1>
    <p>Por um planeta mais sustentável</p>
</header>

<section class="produtos">

    <div class="produto">
        <div class="carrossel">
            <img src="https://images.unsplash.com/photo-1602143407151-7111542de6e8" alt="Garrafa 1">
            <img src="WhatsApp Image 2026-06-03 at 3.20.33 PM.jpeg">
        </div>

        <div class="info">
            <h3>Garrafa Reutilizável</h3>
        </div>
    </div>

    <div class="produto">
        <div class="carrossel">
            <img src="https://images.unsplash.com/photo-1466692476868-aef1dfb1e735" alt="Árvore 1">
            <img src="https://images.unsplash.com/photo-1441974231531-c6227db76b6e" alt="Árvore 2">
        </div>

        <div class="info">
            <h3>Muda de Árvore</h3>
        </div>
    </div>

    <div class="produto">
        <div class="carrossel">
            <img src="https://images.unsplash.com/photo-1492496913980-501348b61469" alt="Kit 1">
            <img src="https://images.unsplash.com/photo-1501004318641-b39e6451bec6" alt="Kit 2">
        </div>

        <div class="info">
            <h3>Kit Sustentável</h3>
        </div>
    </div>

    <div class="produto">
        <div class="carrossel">
            <img src="https://images.unsplash.com/photo-1511497584788-876760111969" alt="Planta 1">
            <img src="https://images.unsplash.com/photo-1463936575829-25148e1db1b8" alt="Planta 2">
        </div>

        <div class="info">
            <h3>Planta Decorativa</h3>
        </div>
    </div>

</section>

<footer>
    🌍 TiFashion | Cuidando do planeta, uma compra de cada vez.
</footer>

</body>
</html>
