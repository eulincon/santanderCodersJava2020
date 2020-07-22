# L1M1

## Lista de exercícios 01 - Módulo 1

1.

- a) As extensões de arquivos são sufixos que designam seu formato e principalmente a função que desempenham no computador. Cada extensão de arquivo tem funcionamento e características próprias, portanto demanda um software específico para trabalhar com ela. Deste modo, caso não se utilize a extensão .html, o computador não saberá como ler aquele arquivo. Naturalmente ele solicitará o usuário escolher com qual programa deseja abrir aquele arquivo, ainda sim, mesmo abrindo em um browser, será lido o código html como texto.

3.

- d) Sim. Funcionou corretamente pois não houve erro no atributo _href_ da tag _<link>_.

4.

- a) É possível utilizar uma fonte que não esteja no sistema do usuário de duas formas. Podemos baixar o arquivo da fonte e upar para o diretorio do site ou podemos acessa-los através de links que funcionam como CDN (Content Delivery Network). Os formatos mais utilizados de extensões de fontes são _.otf_, _.ttf_ e _.woff2_ sendo este ultimo o mais recomendados pois o tamanho do arquivo pode ser 30% menor do que os outros formatos mencionados. Através do Google Fonts podemos tanto baixar a familia de fontes para upar no diretorio do servidor como também temos acesso a um link que, através da API do Google Fonts, nos fornece acesso ao mesmo arquivo. Desde modo, quando o usuário acessar o site, caso o browser não encontre o fonte utilizada no site localmente, o browser então, procura a referencia a essa fonte para realizar o download da mesma e renderizar a página html corretamente.

- b) O formato de cor que começa com o caractere _#_ indica que aquela cor está escrita em código hexadecimal. Desde modo, os valores podem varia de 0 a f, sendo cada posição representada da seguinte forma: _#RRGGBB_ que correspondem a Red - Vermelho, Green - Verde, Blue - Azul. Como exemplo, o código hexadecimal _#00ff00_ represente a cor verde, pois os dois caracteres que representa tanto vermelho como azul estão em opacidade 0.

## Aula 03 - Exercício 01

3.
-d) Com o aumento da fonte através do _fonte-size_ pode-se observar também o aumento das margens entre os parágrafos. Com o tamanho padrão de 14px, a margem também era 14 px. Como o aumento da fonte para 23px, a margem aumentou para 22px.

## Aula 03 - Exercício 02

1.
-b) Mostrará uma mensagem _Cannot GET /hobbies.html_, pois o site está tentando enviar uma requisição via método GET para o site _hobbies.html_, no entanto, no momento o site não existe. Se abrirmos o console javascript do browser veremos uma mensagem informando que houve _falha ao carregar recursos - O servidor respondeu com o status 404 (Fot found)_. Esse status é informado quando tenta-se uma requisição, mas não se obtém resposta por parte do servidor para aquela requisição.
