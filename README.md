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

.imagem-principal{
    width:100%;
    height:450px;
    object-fit:cover;
    display:block;
}

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
    border-color:#2e7d32;
    transform:scale(1.05);
}

.info{
    padding:15px;
    text-align:center;
}

.info h3{
    color:#2e7d32;
    margin-bottom:10px;
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

    .imagem-principal{
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

    <img class="imagem-principal"
         src="WhatsApp Image 2026-06-07 at 8.46.01 PM.jpeg">

    <div class="miniaturas">
        <img src="WhatsApp Image 2026-06-07 at 8.46.01 PM.jpeg"
             data-imagem="WhatsApp Image 2026-06-07 at 8.46.01 PM.jpeg"
             onclick="trocarImagem(this)"
             style="border:2px solid #2e7d32;">

        <img src="WhatsApp Image 2026-06-07 at 8.46.12 PM.jpeg"
             data-imagem="WhatsApp Image 2026-06-07 at 8.46.12 PM.jpeg"
             onclick="trocarImagem(this)">

        <img src="WhatsApp Image 2026-06-03 at 3.20.33 PM.jpeg"
             data-imagem="WhatsApp Image 2026-06-03 at 3.20.33 PM.jpeg"
             onclick="trocarImagem(this)">
    </div>

    <div class="info">
        <h3>Garrafa Reutilizável</h3>
    </div>

</div>

<!-- PRODUTO 2 -->
<div class="produto">

    <img class="imagem-principal"
         src="WhatsApp Image 2026-06-07 at 8.45.54 PM.jpeg">

    <div class="miniaturas">
        <img src="WhatsApp Image 2026-06-07 at 8.45.54 PM.jpeg"
             data-imagem="WhatsApp Image 2026-06-07 at 8.45.54 PM.jpeg"
             onclick="trocarImagem(this)"
             style="border:2px solid #2e7d32;">

        <img src="WhatsApp Image 2026-06-07 at 8.46.09 PM.jpeg"
             data-imagem="WhatsApp Image 2026-06-07 at 8.46.09 PM.jpeg"
             onclick="trocarImagem(this)">

        <img src="WhatsApp Image 2026-06-03 at 3.20.37 PM.jpeg"
             data-imagem="WhatsApp Image 2026-06-03 at 3.20.37 PM.jpeg"
             onclick="trocarImagem(this)">
    </div>

    <div class="info">
        <h3>Muda de Árvore</h3>
    </div>

</div>

<!-- PRODUTO 3 -->
<div class="produto">

    <img class="imagem-principal"
         src="https://images.unsplash.com/photo-1492496913980-501348b61469">

    <div class="miniaturas">
        <img src="https://images.unsplash.com/photo-1492496913980-501348b61469"
             data-imagem="https://images.unsplash.com/photo-1492496913980-501348b61469"
             onclick="trocarImagem(this)"
             style="border:2px solid #2e7d32;">

        <img src="https://images.unsplash.com/photo-1501004318641-b39e6451bec6"
             data-imagem="https://images.unsplash.com/photo-1501004318641-b39e6451bec6"
             onclick="trocarImagem(this)">

        <img src="https://images.unsplash.com/photo-1466692476868-aef1dfb1e735"
             data-imagem="https://images.unsplash.com/photo-1466692476868-aef1dfb1e735"
             onclick="trocarImagem(this)">
    </div>

    <div class="info">
        <h3>Kit Sustentável</h3>
    </div>

</div>

<!-- PRODUTO 4 -->
<div class="produto">

    <img class="imagem-principal"
         src="https://images.unsplash.com/photo-1511497584788-876760111969">

    <div class="miniaturas">
        <img src="https://images.unsplash.com/photo-1511497584788-876760111969"
             data-imagem="https://images.unsplash.com/photo-1511497584788-876760111969"
             onclick="trocarImagem(this)"
             style="border:2px solid #2e7d32;">

        <img src="https://images.unsplash.com/photo-1463936575829-25148e1db1b8"
             data-imagem="https://images.unsplash.com/photo-1463936575829-25148e1db1b8"
             onclick="trocarImagem(this)">
    </div>

    <div class="info">
        <h3>Planta Decorativa</h3>
    </div>

</div>

</section>

<footer>
🌍 TiFashion | Cuidando do planeta, uma compra de cada vez.
</footer>

<script>
function trocarImagem(miniatura){
    const produto = miniatura.closest(".produto");
    const imagemPrincipal = produto.querySelector(".imagem-principal");

    imagemPrincipal.src = miniatura.getAttribute("data-imagem");

    produto.querySelectorAll(".miniaturas img").forEach(img => {
        img.style.border = "2px solid #ddd";
    });

    miniatura.style.border = "2px solid #2e7d32";
}
</script>

</body>
</html>
