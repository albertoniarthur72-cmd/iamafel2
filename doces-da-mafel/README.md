# Doces da Mafel ♡

Protótipo acadêmico de uma confeitaria fictícia, feito com HTML5, CSS3 e Bootstrap 5 por CDN. O projeto não contém JavaScript nem backend.

## Estrutura

- `index.html` — página inicial, destaques e promoção.
- `produtos.html` — catálogo separado por seis categorias.
- `sobre.html` — história fictícia e valores.
- `contato.html` — informações demonstrativas e formulário visual.
- `css/style.css` — estilos compartilhados, responsividade, foco e movimento reduzido.
- `img/` — fotografias otimizadas armazenadas localmente.
- `manus-routes.json` — manifesto das páginas usado pela prévia gerenciada.

## Abrir no VS Code

1. Abra a pasta `docesmafel` no VS Code.
2. Para navegar localmente, instale a extensão **Live Server**, clique com o botão direito em `index.html` e escolha **Open with Live Server**. Os links entre páginas funcionam sem servidor ou JavaScript, mas a extensão facilita a navegação.
3. Alternativamente, com Python 3 instalado, abra o terminal integrado do VS Code nesta pasta e execute `python3 -m http.server 3000`. Depois, abra `http://localhost:3000` no navegador.
4. A conexão à internet é necessária para carregar Bootstrap, Bootstrap Icons e Google Fonts pelos CDNs.
5. Teste também `produtos.html`, `sobre.html` e `contato.html` e redimensione o navegador para larguras de celular, tablet e desktop.

## Limitações intencionais

- Os preços são ilustrativos e os contatos usam domínios/valores de exemplo. A confeitaria e sua história são fictícias.
- O formulário serve para demonstrar campos e validação nativa do navegador. Ele não envia, armazena nem encaminha mensagens; para isso seria necessário configurar um backend ou serviço externo autorizado.
- O site não tem busca, filtro, carrinho ou ordenação automática.
- As fotografias foram selecionadas em resultados gratuitos do [Pexels](https://www.pexels.com/) e do [Unsplash](https://unsplash.com/) e salvas na pasta `img/` para evitar dependência de URLs temporárias.

## Checagens rápidas

- Use `Tab` para percorrer links e campos; o foco é destacado.
- Na página de contato, tente enviar o formulário vazio para observar a validação nativa. Não há confirmação de envio nem serviço de recebimento conectado.
- As folhas de estilo, ícones e fontes externas dependem de acesso à internet; as fotos do projeto são locais.
