<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>RenderX - Catalogo & Estrategias de Vendas</title>
  <style>
    /* fundo degradê azul */
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: linear-gradient(180deg, #e6f8ff 0%, #bfe9ff 30%, #66c6ff 70%, #0aa0e6 100%);
      min-height: 100vh;
      display: flex;
      align-items: flex-start;
      justify-content: center;
      color: #222;
    }

    /* area branca central (card) */
    .wrap {
      width: 92%;
      max-width: 1100px;
      background: #ffffff;
      margin: 40px 20px;
      border-radius: 12px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.15);
      padding: 30px 40px;
    }

    header {
      text-align: center;
      margin-bottom: 10px;
    }

    img.logo {
      max-width: 340px; /* logo maior */
      width: 60%;
      height: auto;
      display: block;
      margin: 0 auto 12px;
    }

    h1 {
      color: #00aef0;
      margin: 4px 0;
      font-size: 28px;
      letter-spacing: 0.5px;
    }
    h2 {
      color: #0097d6;
      margin: 6px 0 8px;
      font-size: 18px;
      font-weight: 600;
    }
    .subtitle {
      color: #6b6b6b;
      font-size: 14px;
      margin-bottom: 18px;
    }

    .offers-title {
      color: #007db3;
      font-weight: 700;
      margin: 18px 0;
      text-align: center;
    }

    /* tabela estilizada */
    .table-wrap {
      overflow-x: auto;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin: 10px 0 26px;
      font-size: 14px;
    }
    thead th {
      background: #333;
      color: #fff;
      font-weight: 700;
      padding: 12px 10px;
      text-align: center;
      border-top-left-radius: 8px;
      border-top-right-radius: 8px;
    }
    tbody td {
      padding: 12px 10px;
      text-align: center;
      border: 1px solid #ddd;
      background: #fff;
    }
    tbody tr:nth-child(even) td {
      background: #fafafa;
    }

    /* secao e textos */
    .section {
      margin-top: 18px;
    }
    .section-title {
      color: #007db3;
      font-size: 18px;
      margin: 18px 0 8px;
      font-weight: 700;
    }
    .section-text {
      color: #444;
      font-size: 14px;
      line-height: 1.5;
      margin-bottom: 8px;
    }
    .highlight {
      color: #e64a3a; /* vermelho suave */
      font-weight: 700;
    }

    /* responsividade pequena */
    @media (max-width: 640px) {
      .wrap { padding: 18px; }
      img.logo { max-width: 220px; }
      h1 { font-size: 22px; }
      h2 { font-size: 16px; }
      .section-title { font-size: 16px; }
      table { font-size: 13px; }
    }
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <!-- coloque a imagem 'logo.png' na mesma pasta do index.html -->
      <img src="logo.png" alt="RenderX Logo" class="logo">
      <h1>RenderX</h1>
      <h2>Catalogo & Estrategias de Vendas</h2>
      <div class="subtitle">Transformando imagens em experiencias visuais impactantes</div>
      <div class="offers-title">Ofertas Exclusivas - RenderX</div>
    </header>

    <div class="table-wrap">
      <table>
        <thead>
          <tr>
            <th>Pacote</th>
            <th>Quantidade de Imagens</th>
            <th>Preco</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Pacote Premium</td>
            <td>10 imagens</td>
            <td>R$ 97,00</td>
          </tr>
          <tr>
            <td>Pacote Intermediario</td>
            <td>5 imagens</td>
            <td>R$ 47,00</td>
          </tr>
          <tr>
            <td>Pacote Essencial</td>
            <td>3 imagens</td>
            <td>R$ 37,00</td>
          </tr>
        </tbody>
      </table>
    </div>

    <div class="section">
      <div class="section-title">Para Restaurantes</div>
      <div class="section-text"><span class="highlight">A primeira impressao do seu prato comeca pela foto!</span></div>
      <div class="section-text">Fotos bem trabalhadas aumentam o apetite e as vendas.</div>
      <div class="section-text">Transforme seu cardapio digital em uma verdadeira vitrine gourmet.</div>
    </div>

    <div class="section">
      <div class="section-title">Para Veiculos</div>
      <div class="section-text">Fotos profissionais valorizam ainda mais o seu carro.</div>
      <div class="section-text">Destaque os detalhes que fazem toda diferenca na hora da venda.</div>
      <div class="section-text">Uma imagem de qualidade acelera a decisao do comprador.</div>
    </div>

    <div class="section">
      <div class="section-title">Para Anuncios em Geral</div>
      <div class="section-text">Uma imagem restaurada e um anuncio mais convincente.</div>
      <div class="section-text">Atraia mais clientes com fotos claras e impactantes.</div>
      <div class="section-text">Invista em qualidade visual para turbinar seus resultados.</div>
    </div>

    <div class="section">
      <div class="section-title">Beneficios Extras</div>
      <div class="section-text"><span class="highlight">Quanto mais imagens voce adquire, mais economia voce garante!</span></div>
      <div class="section-text">Pacotes pensados para atender sua necessidade e caber no seu bolso.</div>
      <div class="section-text">Garanta ja suas imagens profissionais com o melhor custo-beneficio.</div>
      <div class="section-text">Ideal para empresas que desejam impacto visual sem gastar muito.</div>
      <div class="section-text">Escolha o pacote que mais se encaixa no seu momento e comeca hoje mesmo!</div>
      <div class="section-text">Investir em qualidade nunca foi tao acessivel.</div>
      <div class="section-text highlight">Aproveite essa oportunidade exclusiva da RenderX!</div>
    </div>
  </div>
</body>
</html>
