# Você decide o futuro da IA

Jogo educativo de escolhas sobre ética, privacidade, desinformação, vieses, autoria e uso responsável da inteligência artificial.

## Arquivos
- `index.html`: estrutura e telas do jogo.
- `style.css`: identidade visual responsiva.
- `js/perguntas.js`: perguntas, alternativas e explicações.
- `js/aleatorio.js`: função para embaralhar as perguntas e alternativas.
- `js/script.js`: lógica do jogo, pontuação, feedback e resultado.

## Publicar no GitHub Pages
1. Crie um repositório público no GitHub.
2. Envie todos os arquivos e pastas mantendo a estrutura.
3. Abra Settings → Pages.
4. Em Source, selecione Deploy from a branch.
5. Escolha `main` e `/ (root)` e salve.
6. Aguarde a publicação e abra o endereço informado pelo GitHub.

## Testar
Abra o site publicado pelo GitHub Pages. Como o projeto utiliza módulos JavaScript (`type="module"`), prefira testar por um servidor local ou pelo GitHub Pages em vez de abrir o HTML diretamente como arquivo.

## Personalização
Edite as perguntas no arquivo `js/perguntas.js`. Cada pergunta possui categoria, enunciado, contexto, alternativas, indicação de resposta correta e feedback explicativo.
