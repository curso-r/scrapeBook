# scrapeBook

Livro sobre Web Scraping em R.

Estrutura que pensamos até agora:

0. Abertura
  - Quem somos
  - Conteúdo
  - Quando usar web scraping
  - Quando não usar web scraping
1. Identify
  - Introdução
  - Encontrar o que você quer
2. Browse
  - Inspect
  - HTML
  - CSS
3. Replicate
  - Request (protocolo HTTP)
  - Response
  - Network
  - GET e POST
  - httr
  - JSON/XML
4. Parse
  - rvest
  - html node (css path e xpath)
  - httr
  - xml2
5. Validate
  - Event validation e view state (asp)
  - Páginas jsp
  - Hackear a URL
  - Evitar armadilhas (catpchas, etc)
6. Iterate
  - Armazenando dados
  - Tibble
  - Paralelização e distribuição
  ? Blacklist e barragem de requisição (IPs elásticos e proxys)
  ? Processo de bidding da amazon (EC2 spot)
7. Revalidate
  - Interatividade
    - JS (V8, etc)
    - Selenium, phantom
    - RMouse
  - Captchas
    - Modelos ad hoc
    - Modelos keras
    - decryptr