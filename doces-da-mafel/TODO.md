# Entregas do projeto — Doces da Mafel

## 1. Site multipágina e navegação
- [x] A estrutura do projeto contém `index.html`, `produtos.html`, `sobre.html`, `contato.html`, `css/style.css` e pasta `img/` para imagens locais quando utilizadas.
- [x] Todos os arquivos HTML utilizam o mesmo padrão visual de cabeçalho e rodapé.
- [x] O cabeçalho contém o logotipo “Doces da Mafel ♡” e menu com Página inicial, Produtos, Sobre nós e Contato, com links reais entre as páginas e destaque visual para contato ou catálogo.
- [x] A navegação é adaptável sem JavaScript; não usar hambúrguer Bootstrap que dependa de JavaScript.
- [x] Utilizar HTML5, CSS3 e Bootstrap 5 por CDN para layout, grid, componentes e responsividade. Bootstrap Icons por CSS e Google Fonts: Poppins nos títulos e Inter nos textos.
- [x] Não incluir tags `<script>`, arquivos JavaScript, frameworks JavaScript ou interações que dependam de JavaScript.
- [x] O site funciona em celulares, tablets, notebooks e monitores grandes, sem rolagem horizontal, imagens distorcidas, textos cortados ou botões pequenos.

## 2. Página inicial
- [x] Exibir layout principal em duas colunas no desktop com título “Um docinho de felicidade em cada mordida.”, texto acolhedor, botões “Conheça os produtos” e “Ver promoções” e foto grande de bolo de chocolate decorado com morangos.
- [x] Incluir detalhes gráficos rosa e branco.
- [x] Incluir seção “Feitos para adoçar seus melhores momentos” com quatro cartões, cada qual com imagem, nome, descrição, preço ilustrativo e botão/link para produtos.
- [x] Incluir banner elegante de promoções, caixas de presentes e novidades, com botão para produtos.
- [x] Apresentar diferenciais: ingredientes selecionados, preparação cuidadosa, doces para presentear e carinho em cada detalhe.
- [x] Rodapé completo com navegação, contatos demonstrativos e identificação do projeto.

## 3. Catálogo de produtos
- [x] `produtos.html` contém título “Doces que tornam a vida mais doce.”, subtítulo e categorias chocolates, bombons, balas, bolos, cupcakes e kits para presente.
- [x] Cada produto apresenta imagem, nome, descrição curta, preço ilustrativo em reais identificado como demonstrativo, etiqueta visual opcional e link/botão para contato e consulta de pedidos.
- [x] Organizar cards pelo grid Bootstrap em até quatro colunas em telas grandes, duas ou três em tablets e uma ou duas em celulares.
- [x] Cards com alturas consistentes, imagens bem enquadradas, bordas suaves e efeitos de hover CSS.
- [x] Não implementar filtros dinâmicos, busca funcional, carrinho ou ordenação automática.

## 4. Página sobre
- [x] `sobre.html` apresenta subtítulo “Quem somos”, título “Uma história feita de carinho e açúcar.”, história fictícia sobre dedicação aos doces e criação de momentos especiais, sem inventar fatos reais de empresa existente, e imagem temática.
- [x] Incluir quatro cartões: Nossa paixão (dedicação em cada receita); Cuidado com os ingredientes (atenção à qualidade e ao preparo); Missão (levar felicidade por meio dos doces); Nossos valores (carinho, criatividade, respeito e compromisso).
- [x] Incluir área rosa-claro com ícone de coração e frase “Feito com carinho, para adoçar seu dia.”
- [x] Finalizar com link para produtos.

## 5. Contato e formulário
- [x] `contato.html` inclui subtítulo “Vamos conversar?”, título “Seu próximo doce favorito começa aqui.” e convite para tirar dúvidas ou imaginar pedido especial.
- [x] Exibir e-mail demonstrativo, telefone de exemplo claramente identificado, perfil social ilustrativo e horário de atendimento demonstrativo.
- [x] Formulário HTML contém nome, e-mail (`type="email"`), assunto, mensagem e botão “Enviar mensagem ♡”, com `form`, `label`, `input`, `select`, `textarea` e `button` apropriados.
- [x] Campos obrigatórios usam `required`; rótulos associados aos campos; validação básica nativa do navegador.
- [x] Estilo profissional com campos arredondados, fundo suave, espaçamento adequado e foco CSS visível.
- [x] Sem JavaScript/backend, não simular confirmação de envio, nem alegar que mensagens são armazenadas ou encaminhadas.

## 6. Design, imagens, acessibilidade e entrega
- [x] Aplicar paleta: rosa `#E76BA6`, rosa-claro `#FCEAF2`, rosa suave `#F4C7DA`, branco `#FFFFFF`, fundo `#FFF9FC`, marrom `#49313D`, cinza `#857780` e dourado `#D5A45B`.
- [x] CSS personalizado organizado em `css/style.css`, com variáveis, tipografia, estilos de cabeçalho/rodapé, hero, cartões, botões, formulário, hover/focus, sombras, bordas, media queries, espaçamento e animações discretas em CSS que respeitam `prefers-reduced-motion`.
- [x] Usar imagens bonitas, nítidas e diferentes para bolos, bombons, chocolates variados, balas, cupcakes e caixas-presente; preferir recursos gratuitos ou imagens locais fornecidas; verificar endereços externos. Aplicar `object-fit: cover`, proporções uniformes, cantos arredondados e alt text descritivo. Se imagem falhar, manter layout organizado.
- [x] Semântica HTML, contraste adequado, navegação por teclado e estados de foco visíveis; evitar textos pequenos.
- [x] Entregar instruções para abrir e testar no VS Code e verificar o visual em diferentes tamanhos de tela.
- [x] Verificar os links entre páginas, o formulário dentro de suas limitações e a ausência de JavaScript.