# Memória EIEM — site estático

Site para GitHub Pages ou Cloudflare Pages. Publique os quatro arquivos `index.html`, `styles.css`, `app.js` e `dados.json` na raiz do repositório. Não requer build, API ou backend.

## Conteúdo
- Apresentação e justificativa do acervo
- Página de edições e ficha do EIEM 2024
- Busca em título, autores, instituições, resumo e palavras-chave; filtro de tipo e ordenação
- Ficha completa dos 37 trabalhos com links do Google Drive

## Verificação editorial
Os 37 links foram associados pela ordem em que foram fornecidos (001 a 037). Os arquivos 001 e 002 foram confirmados pelo nome no Drive. Recomenda-se conferir os demais links e a validação bibliográfica dos metadados antes de divulgação definitiva.

O trabalho `EIEM2024-001` não tem resumo nem palavras-chave, por informação confirmada pelo responsável do acervo. O site não inventa esses campos.

A edição de 2024 é a única catalogada nesta versão. Não há estatísticas fictícias sobre outras edições.

Fonte das atas: https://spiem.pt/publicacoes/download-de-atas/


## Imagens incluídas
A pasta `assets/` contém quatro recortes das imagens ilustrativas do protótipo visual aprovado: Porto (destaque e cartão), Aveiro e Costa da Caparica. São imagens geradas para o mockup, não fotografias documentais verificadas das cidades ou das sedes do EIEM. A edição 2024 permanece a única com registros catalogados. Os cartões de outras cidades estão identificados como ilustrações, sem atribuir datas, temas ou quantitativos não confirmados.

Ao publicar no Cloudflare Pages, envie o conteúdo completo do ZIP, incluindo a pasta `assets/`.


## Fichas de autoria
Os dados estão em `dados.json` e `catalogo_eiem_2024.csv`. `FichaAutores` guarda
uma lista JSON por trabalho com Autor, Titulação, IES e País. A titulação fica
vazia quando não consta da fonte: não se infere titulação por afiliação.
A associação individual entre autores e IES é feita apenas quando a contagem
dos elementos permite alinhamento por posição. Confira as associações antes
de usar em análises bibliométricas. O texto integral das afiliações originais
é mantido em `Instituições`.
