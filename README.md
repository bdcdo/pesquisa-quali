# O efeito sombra dos tribunais

Slides da apresentação sobre Pavone e Stiansen (2022), publicados com GitHub Pages em https://brunodcdo.com.br/pesquisa-quali/. O visualizador (`ver.html`) mostra o PDF página a página e troca cada slide de animação pela página interativa (`animacao-*.html`), que mora na mesma pasta.

- `index.html`: a página inicial.
- `ver.html?deck=shadow-effect.pdf&moldura=cheia#N` abre na página N.
- `pdfjs/`: pdf.js, da Mozilla, sob a licença Apache 2.0 em `pdfjs/LICENSE`.

O visualizador busca o PDF por HTTP: para ver localmente, rode `python3 -m http.server` nesta pasta e abra `http://localhost:8000`.
