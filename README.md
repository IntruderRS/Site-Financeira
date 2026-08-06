<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DindinFácil - Home</title>
    <link rel="stylesheet" href="style.css">
    <style>
        /* Estilo local da área promocional da Home */
        .area-destaque {
            background: linear-gradient(135deg, #0f2c59, #ff6600);
            color: white;
            padding: 40px;
            border-radius: 10px;
            margin-bottom: 40px;
        }

        .area-destaque h2 {
            font-size: 32px;
            margin-bottom: 10px;
            color: white;
        }

        .area-destaque p {
            font-size: 18px;
            margin-bottom: 20px;
        }
    </style>

</head>

<body>

    Lorem ipsum dolor sit amet consectetur adipisicing elit. Qui earum minus, quas necessitatibus accusantium ab excepturi hic, voluptas voluptatem nihil consectetur consequatur quo delectus expedita voluptate animi repellat enim nobis?

    <!--cabeçalho com o logo -->
    <header>
        <div class="logo-container">
            <!-- Logo -->
            <img src="imagens/logodindinfacil.png" alt="Logo DindinFácil" class="logo-img">

            <div class="logo-texto">
                <h1>Dindin<span>Fácil</span></h1>
            </div>
        </div>
    </header>

    
    <!--Menu Lateral-->
    <div class="container">
        <aside>
            <nav>
                <ul>
                    <!-- A classe 'active' serve para destacar em qual página o usuário está -->
                    <li><a href="index.html" class="active">Página Inicial</a></li>
                    <li><a href="emprestimos.html">Empréstimos</a></li>
                    <li><a href="cliente.html">Seja Nosso Cliente</a></li>
                </ul>
            </nav>
        </aside>

        <main>
            <!-- SEÇÃO DA OFERTA ESPECIAL (O CHAMARISCO) -->
            <section class="banner-oferta">
                
                <span class="oferta-etiqueta">Oferta Exclusiva da Semana</span>
                <h2>Precisa de dinheiro rápido? Antecipe seu décimo terceiro ou receba via PIX na hora!</h2>
                <p>A DindinFácil tem as menores taxas do mercado local. Faça uma simulação rápida agora e mude sua vida
                    financeira.</p>
                <a href="emprestimos.html" class="btn-oferta">Simular Empréstimo Já</a>
            </section>      

        <!-- Serviços Financeiros -->
         <div class="grid-servicos"></div>
        
            <section>
                <h2 class="secao-titulo">Nossos Serviços</h2>

                <!-- O "Grid" que segura as 3 caixas juntas -->
                <div class="grid-servicos">

                    <!-- Caixa 1: Empréstimos -->
                    <div class="caixa-servico">
                        <img src="imagens/emprestimo.jpg" alt="Serviço de Empréstimos">
                        <h3>Empréstimos</h3>
                        <p>Crédito rápido, pessoal ou consignado, com parcelas que cabem no seu bolso.</p>
                        <a href="emprestimos.html" class="link-detalhes">Ver detalhes e simular →</a>
                    </div>

                    <!-- Caixa 2: Financiamentos -->
                    <div class="caixa-servico">
                        <img src="imagens/financiamento.jpg" alt="Serviço de Financiamentos">
                        <h3>Financiamentos</h3>
                        <p>As melhores taxas para financiar seu veículo ou imóvel próprio de forma segura.</p>
                        <a href="cliente.html" class="link-detalhes">Conhecer planos →</a>
                    </div>

                    <!-- Caixa 3: Consignado -->
                    <div class="caixa-servico">
                        <img src="imagens/antecipacao.png" alt="Antecipação de Recebíveis">
                        <h3>Empréstimo Consignado</h3>
                        <p>Receba à vista o dinheiro das suas vendas a prazo e melhore o caixa da sua empresa.</p>
                        <a href="cliente.html" class="link-detalhes">Garantir fluxo →</a>
                    </div>

                </div>
            </section>
        </main>
    </div>
    </div>

    <!--Rodapé-->
    <footer>
        <!-- Logo da Financeira -->
        <div class="rodape-bloco rodape-logo">
            <img src="imagens/logodindinfacil.png" alt="Logo DindinFácil" class="rodape-img">
        </div>

        <!-- Central de Vendas -->
        <div class="rodape-bloco contato-central">
            <strong>Central de Vendas</strong>
            <span>0800 777 8000</span>
        </div>

        <!-- WhatsApp -->
        <div class="rodape-bloco contato-whats">
            <img src="imagens/whatsapp.jpg" alt="WhatsApp" class="icone-whats">
            <div class="whats-texto">
                <strong>WhatsApp</strong>
                <span>4004-8000</span>
            </div>
        </div>

        <!-- Redes Sociais -->
        <div class="rodape-bloco rodape-redes">
            <strong>Siga</strong>
            <div class="icones-redes">
                <a href="instagram/dindinfacil"><img src="imagens/instagram.jpg" alt="Instagram"></a>
                <a href="facebook/dindinfacil"><img src="imagens/facebook.jpg" alt="Facebook"></a>
                <a href="linkedin/dindinfacil"><img src="imagens/linkedin.jpg" alt="LinkedIn"></a>
            </div>
        </div>
    </footer>



</body>

</html>
