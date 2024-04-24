# Web Scraper


estudo sobre Web Scraper.

Instale as dependências.
```js
npm i axios cheerio express 
```

como usar 

> forma de execurar **node** **{nome_do_aqruivo}**


 Executar o comando abaixo no terminal do vscode em seguida abrir o navegador de internet no endereço http://localhost:3000/posts a **saída esperada** será apresem dada na pagina.

```javascript
node index.js
```

Exemplo 1

```javascript
node index.js
```
### 

> OBS.: o resultado sofrear mudara (mudança) devido o Web Scraper ser feito em uma pagina de notícias.


```json
saída esperada >>

posts	
0	
url	"https://g1.globo.com/economia/noticia/2024/04/24/haddad-vai-ao-congresso-entregar-projeto-de-regulamentacao-da-reforma-tributaria.ghtml"
title	"Haddad entrega ao Congresso regras da reforma tributária"

1	
url	"https://oglobo.globo.com/economia/noticia/2024/04/24/reforma-tributaria-cashback-sera-para-familias-que-ganham-ate-meio-salario-minimo-por-pessoa.ghtml"
title	"Entenda a proposta de 'cashback' a baixa renda"

2	
url	"https://g1.globo.com/politica/noticia/2024/04/24/moraes-mantem-medidas-cautelares-de-bolsonaro-apos-estadia-na-embaixada-hungara.ghtml"
title	"Moraes arquiva ação sobre Bolsonaro em embaixada húngara"

3	
url	"https://oglobo.globo.com/blogs/malu-gaspar/post/2024/04/alexandre-de-moraes-vai-a-evento-em-londres-de-empresaria-que-ja-criticou-cidadaos-de-toga-e-canetaco-do-stf.ghtml"
title	"Moraes vai a evento de empresária crítica ao STF"

4	
url	"https://g1.globo.com/sp/sao-paulo/noticia/2024/04/24/acidente-entre-carretas-deixa-mortos-na-rodovia-regis-bittencourt-em-sp.ghtml"
title	"SP: grave acidente com carretas e carro deixa quatro mortos"

5	
url	"https://g1.globo.com/globonews/globonewsmais/video/acidente-entre-caminhoes-e-carro-deixa-mortos-na-rodovia-regis-bittencourt-em-sp-12545392.ghtml"
title	"Colisão aconteceu na Rodovia Régis Bittencourt"

6	
url	"https://g1.globo.com/mt/mato-grosso/noticia/2024/04/24/video-novas-imagens-mostram-acao-de-mae-e-filho-em-invasao-que-deixou-dois-idosos-mortos-e-padre-ferido-em-mt.ghtml"
title	"MT: vídeo mostra ação de mãe e filho em morte de idosos"

7	
url	"https://gshow.globo.com/tudo-mais/tv-e-famosos/noticia/padre-baleado-da-detalhes-de-crime-no-encontro-e-perdoa-mae-e-filho-que-invadiram-casa-e-mataram-idosos.ghtml"
title	"Padre baleado diz que perdoa mãe e filho; vídeo"

8	
url	"https://oglobo.globo.com/politica/noticia/2024/04/24/camara-aprova-a-lei-taylor-swift-que-criminaliza-cambismo-digital.ghtml"
title	"Câmara aprova 'Lei Taylor Swift' contra cambismo digital"

9	
url	"https://g1.globo.com/politica/noticia/2024/04/24/lei-taylor-swift-camara-aprova-projeto-anti-cambista-que-coibe-pratica-em-shows-e-eventos-esportivos.ghtml"
title	"Entenda o que muda com o projeto aprovado"

10	
url	"https://g1.globo.com/rj/rio-de-janeiro/show-da-madonna/noticia/2024/04/24/3-avioes-90-quartos-45-baus-os-numeros-superlativos-do-mega-show-da-madonna-no-rio.ghtml"
title	"3 aviões, 90 quartos: os números do show de Madonna no Rio"

11	
url	"https://g1.globo.com/sp/campinas-regiao/em-cena/noticia/2024/04/24/madonna-em-copacabana-equipamentos-do-mega-show-chegam-ao-aeroporto-de-viracopos.ghtml"
title	"Parte de equipamentos de megashow chega a SP"
```

