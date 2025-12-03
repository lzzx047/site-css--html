📘 README – Site de Filmes, Livros e Música

Este projeto é um site simples desenvolvido utilizando HTML e CSS, com foco no uso das tecnologias Flexbox e CSS Grid para organizar o conteúdo.
O objetivo é demonstrar como estruturar páginas responsivas e esteticamente agradáveis com técnicas modernas de layout.

🏗️ Tecnologias Utilizadas
🔹 HTML5

Responsável pela estruturação do conteúdo em diferentes seções:

Menu de navegação usando <nav>

Seções separadas para Filmes, Livros e Música

Uso de listas, divisões e títulos organizados semanticamente

🎨 CSS3

O projeto utiliza CSS para estilização visual e organização do layout.

🔸 Estilos Gerais

Fonte base configurada (Arial, sans-serif)

Paletas de cores personalizadas para cada seção

Bordas arredondadas, box-shadow e espaçamentos para dar profundidade aos elementos

📦 Flexbox — Seção de Filmes

A seção Filmes utiliza CSS Flexbox, que facilita organizar itens horizontalmente e ajustá-los conforme o espaço disponível.

Principais propriedades usadas:

display: flex;

flex-wrap: wrap;

justify-content: center;

gap: 20px;

Essas propriedades permitiram criar uma grade flexível que se adapta ao tamanho da tela.

🧱 CSS Grid — Seção de Livros

A seção Livros utiliza CSS Grid, ideal para criar grades bidimensionais de forma simples.

Propriedades utilizadas:

display: grid;

grid-template-columns: repeat(3, 1fr);

gap: 18px;

Com isso, foi criada uma grade uniforme com 3 colunas para exibir os livros recomendados.

🎵 Lista Simples — Seção de Música

A seção Música utiliza uma lista estilizada com:

list-style: none;

Cartões brancos com sombra

Bordas arredondadas para melhorar a estética

Essa parte do site não usa flexbox ou grid, apenas CSS básico para formatar uma lista vertical.

🧭 Navegação

O menu superior permite acesso rápido a cada seção usando links âncora (href="#filmes" por exemplo).
Ele permanece no topo e é estilizado com:

Cor de fundo escura

Texto branco

Efeito hover com sublinhado

🦶 Rodapé

Inclui um rodapé simples com:

Fundo escuro

Texto centralizado

Informações sobre o autor

📌 Resumo do que foi aprendido;
✔ Uso de Flexbox para organização unidimensional (filmes)
✔ Uso de CSS Grid para organização bidimensional (livros)
✔ Estilização de listas e seções individuais
✔ Estruturação semântica com HTML5
✔ Aplicação de sombras, espaçamentos e cores personalizadas
✔ Navegação interna com âncoras