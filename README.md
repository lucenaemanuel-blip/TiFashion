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

/* HEADER */
header{
    background:rgba(25, 118, 210, 0.92);
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

/* LAYOUT */
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

/* CARROSSEL */
.carrossel{
    display:flex;
    overflow-x:auto;
    scroll-snap-type:x mandatory;
    scroll-behavior:smooth;
    -webkit-overflow-scrolling:touch;
}

.carrossel::-webkit-scrollbar{
    display:none;
}

.carrossel img{
    min-width:100%;
    height:450px;
    object-fit:cover;
    scroll-snap-align:start;
}

/* MINIATURAS */
.miniaturas{
    display:flex;
    justify-content:center;
    gap:8px;
    padding:10px;
    background:#fff;
}

.miniaturas img{
    width:55px;
    height:55px;
    object-fit:cover;
    border-radius:6px;
    border:2px solid #ddd;
    cursor:pointer;
    transition:.3s;
}

.miniaturas img:hover{
    transform:scale(1.05);
    border-color:#1976d2;
}

/* TEXTO */
.info{
    padding:15px;
    text-align:center;
}

.info h3{
    color:#1976d2;
    margin-bottom:10px;
}

/* FOOTER */
footer{
    background:rgba(13, 71, 161, 0.95);
    color:white;
    text-align:center;
    padding:15px;
    margin-top:20px;
}

/* RESPONSIVO */
@media(max-width:768px){
    .produto{
        width:90%;
    }

    .carrossel img{
        height:400px;
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

<!-- PRODUTO 1 -->
<div class="produto">
    <div class="carrossel">
        <img src="WhatsApp Image 2026-06-07 at 8.46.01 PM.jpeg">
        <img src="WhatsApp Image 2026-06-07 at 8.46.12 PM.jpeg">
        <img src="WhatsApp Image 2026-06-03 at 3.20.33 PM.jpeg">
    </div>
    <div class="miniaturas">
        <img src="WhatsApp Image 2026-06-07 at 8.46.01 PM.jpeg" onclick="irParaImagem(this,0)">
        <img src="WhatsApp Image 2026-06-07 at 8.46.12 PM.jpeg" onclick="irParaImagem(this,1)">
        <img src="WhatsApp Image 2026-06-03 at 3.20.33 PM.jpeg" onclick="irParaImagem(this,2)">
    </div>
</div>

<!-- PRODUTO 2 -->
<div class="produto">
    <div class="carrossel">
        <img src="WhatsApp Image 2026-06-07 at 8.45.54 PM.jpeg">
        <img src="WhatsApp Image 2026-06-07 at 8.46.09 PM.jpeg">
        <img src="WhatsApp Image 2026-06-03 at 3.20.37 PM.jpeg">
    </div>
    <div class="miniaturas">
        <img src="WhatsApp Image 2026-06-07 at 8.45.54 PM.jpeg" onclick="irParaImagem(this,0)">
        <img src="WhatsApp Image 2026-06-07 at 8.46.09 PM.jpeg" onclick="irParaImagem(this,1)">
        <img src="WhatsApp Image 2026-06-03 at 3.20.37 PM.jpeg" onclick="irParaImagem(this,2)">
    </div>
</div>

<!-- PRODUTOS 3 A 9 -->
<!-- repetidos já prontos com estrutura igual -->

<div class="produto">
    <div class="carrossel">
        <img src="WhatsApp Image 2026-06-07 at 8.45.56 PM.jpeg">
        <img src="sla.jpeg">
        <img src="WhatsApp Image 2026-06-03 at 3.20.35 PM.jpeg">
    </div>
    <div class="miniaturas">
        <img src="WhatsApp Image 2026-06-07 at 8.45.56 PM.jpeg" onclick="irParaImagem(this,0)">
        <img src="sla.jpeg" onclick="irParaImagem(this,1)">
        <img src="WhatsApp Image 2026-06-03 at 3.20.35 PM.jpeg" onclick="irParaImagem(this,2)">
    </div>
</div>

<div class="produto">
    <div class="carrossel">
        <img src="WhatsApp Image 2026-06-07 at 8.46.02 PM.jpeg">
        <img src="WhatsApp Image 2026-06-07 at 8.46.09 PM.jpeg">
        <img src="WhatsApp Image 2026-06-03 at 3.20.38 PM.jpeg">
    </div>
    <div class="miniaturas">
        <img src="WhatsApp Image 2026-06-07 at 8.46.02 PM.jpeg" onclick="irParaImagem(this,0)">
        <img src="WhatsApp Image 2026-06-07 at 8.46.09 PM.jpeg" onclick="irParaImagem(this,1)">
        <img src="WhatsApp Image 2026-06-03 at 3.20.38 PM.jpeg" onclick="irParaImagem(this,2)">
    </div>
</div>

<div class="produto">
    <div class="carrossel">
        <img src="WhatsApp Image 2026-06-07 at 8.46.04 PM.jpeg">
        <img src="WhatsApp Image 2026-06-07 at 8.46.09 PM.jpeg">
        <img src="WhatsApp Image 2026-06-03 at 3.20.43 PM.jpeg">
    </div>
    <div class="miniaturas">
        <img src="WhatsApp Image 2026-06-07 at 8.46.04 PM.jpeg" onclick="irParaImagem(this,0)">
        <img src="WhatsApp Image 2026-06-07 at 8.46.09 PM.jpeg" onclick="irParaImagem(this,1)">
        <img src="WhatsApp Image 2026-06-03 at 3.20.43 PM.jpeg" onclick="irParaImagem(this,2)">
    </div>
</div>

<div class="produto">
    <div class="carrossel">
        <img src="WhatsApp Image 2026-06-07 at 8.45.57 PM.jpeg">
        <img src="WhatsApp Image 2026-06-07 at 8.46.06 PM.jpeg">
        <img src="WhatsApp Image 2026-06-07 at 8.46.46 PM.jpeg">
        <img src="WhatsApp Image 2026-06-07 at 8.46.46 PM.jpeg">
    </div>
    <div class="miniaturas">
        <img src="WhatsApp Image 2026-06-07 at 8.45.57 PM.jpeg" onclick="irParaImagem(this,0)">
        <img src="WhatsApp Image 2026-06-07 at 8.46.06 PM.jpeg" onclick="irParaImagem(this,1)">
        <img src="WhatsApp Image 2026-06-07 at 8.46.46 PM.jpeg" onclick="irParaImagem(this,2)">
        <img src="WhatsApp Image 2026-06-07 at 8.46.14 PM.jpeg" onclick="irParaImagem(this,3)">
        <img src="WhatsApp Image 2026-06-07 at 8.46.47 PM.jpeg" onclick="irParaImagem(this,3)">
        <img src="WhatsApp Image 2026-06-07 at 8.46.52 PM.jpeg" onclick="irParaImagem(this,3)">
    </div>
</div>

<div class="produto">
    <div class="carrossel">
        <img src="https://images.unsplash.com/photo-1511497584788-876760111969">
        <img src="https://images.unsplash.com/photo-1492496913980-501348b61469">
        <img src="https://images.unsplash.com/photo-1501004318641-b39e6451bec6">
    </div>
    <div class="miniaturas">
        <img src="https://images.unsplash.com/photo-1511497584788-876760111969" onclick="irParaImagem(this,0)">
        <img src="https://images.unsplash.com/photo-1492496913980-501348b61469" onclick="irParaImagem(this,1)">
        <img src="https://images.unsplash.com/photo-1501004318641-b39e6451bec6" onclick="irParaImagem(this,2)">
    </div>
</div>

<div class="produto">
    <div class="carrossel">
        <img src="https://images.unsplash.com/photo-1501004318641-b39e6451bec6">
        <img src="https://images.unsplash.com/photo-1466692476868-aef1dfb1e735">
        <img src="https://images.unsplash.com/photo-1492496913980-501348b61469">
    </div>
    <div class="miniaturas">
        <img src="https://images.unsplash.com/photo-1501004318641-b39e6451bec6" onclick="irParaImagem(this,0)">
        <img src="https://images.unsplash.com/photo-1466692476868-aef1dfb1e735" onclick="irParaImagem(this,1)">
        <img src="https://images.unsplash.com/photo-1492496913980-501348b61469" onclick="irParaImagem(this,2)">
    </div>
</div>

<div class="produto">
    <div class="carrossel">
        <img src="https://images.unsplash.com/photo-1463936575829-25148e1db1b8">
        <img src="https://images.unsplash.com/photo-1511497584788-876760111969">
        <img src="https://images.unsplash.com/photo-1501004318641-b39e6451bec6">
    </div>
    <div class="miniaturas">
        <img src="https://images.unsplash.com/photo-1463936575829-25148e1db1b8" onclick="irParaImagem(this,0)">
        <img src="https://images.unsplash.com/photo-1511497584788-876760111969" onclick="irParaImagem(this,1)">
        <img src="https://images.unsplash.com/photo-1501004318641-b39e6451bec6" onclick="irParaImagem(this,2)">
    </div>
</div>

</section>

<footer>
🌍 TiFashion | Cuidando do planeta, uma compra de cada vez.
</footer>

<script>
function irParaImagem(el, index){
    const produto = el.closest(".produto");
    const carrossel = produto.querySelector(".carrossel");

    const largura = carrossel.offsetWidth;

    carrossel.scrollTo({
        left: largura * index,
        behavior: "smooth"
    });

    produto.querySelectorAll(".miniaturas img").forEach(img=>{
        img.style.border="2px solid #ddd";
    });

    el.style.border="2px solid #1976d2";
}
</script>

</body>
</html>
