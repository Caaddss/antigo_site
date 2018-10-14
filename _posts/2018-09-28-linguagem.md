---
layout: post
title: "[Serie AI e Neurociência] O processamento da linguagem e a suas nuances"
date:   2018-10-15 13:02:59
comments: true
categories: series
description: O processamento da linguagem é uma das funções mais fascinantes do ser humano, e uma desafio para os entusiastas da Inteligência Artificial, vamos abordar um pouco sobre como entender a biologia por trás desse processo pode ser valioso para insights.
---

# O Processamento da Linguagem

*Esse texto não pretende fazer uma discussão sobre métodos de NLP, mas trazer provocações da neurociência para a área.*
[Aqui](http://carolinedantas.com/series/2018/08/05/neuro.html) você encontra o primeiro texto da série, que dá um overview sobre neurociência

## Termos importantes
Antes de começar com o texto propriamente dito, vou deixar algumas definições aqui que serão importantes do decorrer da nossa discussão:

*Afasia*: É a perda, parcial ou total, da fala ou compreensão da linguagem, em decorrência de uma lesão cerebral.

*Fonema* : "Qualquer um dos traços distintivos de um som da fala capaz de diferenciar uma palavra da outra" [1](https://www.dicio.com.br/fonema/)

*Grámatica* : Regras para o uso correto da linguagem

*Língua* : "Conjunto dos elementos que constituem a linguagem falada ou escrita peculiar a uma coletividade, idioma" [1](https://www.dicio.com.br/lingua/)

*Linguagem* : "Faculdade que têm as pessoas de se comunicar umas com as outras, exprimindo pensamentos e sentimentos por palvras, que podem ser escritas, quando necessário"[1](https://www.dicio.com.br/linguagem/)

*Morfema* : "Menor unidade linguistica que apresentam significado"[1](https://www.dicio.com.br/morfema/)

*Prosódia*: "Parte da gramática normativa que trata da reta acentuação dos vocábulos e ainda dos fenômenos de entonação"[1](https://www.dicio.com.br/prosodia)

*Processamento de Linguagem Natural* : "Consiste no desenvolvimento de modelos computacionais para a realização de tarefas que dependem de informações expressas em alguma língua natural" [1](https://www.ime.usp.br/~slago/IA-pln.pdf)


## A linguagem

Dentre as chamadas funções corticais de ordem superior, a linguagem é uma das mais avançadas, sendo encontrada apenas em humanos, isso não significa que outras espécies não se comuniquem, isso acontece, mas não da mesma forma que nós fazemos: expressamos sentimentos, emoções, informações sobre passado, presente e futuro, temos a capacidade de transformar em linguagem, nossa imaginação, ou seja, cenários ficticios. Para tal, são necessários certos níveis funcionais: os fonemas, morfemas, frases e palavras. 

Sendo responsável por grande parte da nossa interação social, a linguagem é essencial desde os nossos mais tenros dias, os bebês tem uma grande capacidade de identificação de padrões como a diferenciação da voz dos pais, e a já conhecida informação que para eles é mais fácil aprender uma segunda língua, não é um mito, nossa capacidade analítica da linguagem era muito melhor quando éramos pedacinhos de gente. A audição, que é essencial para o  desenvolvimento dessa função, é magnífica quando éramos pequenos, foi feito um estudo onde bebês poderiam escolher entre um áudio falando com eles de uma forma voltada para bebês, e outra que era falada como se fosse para adultos, e pasmem eles escolheram ficar com o chamado Maternês/Paternês (então quando ver alguém falando com um bebê como se fosse um bebê, não julgue mais ok?! Essa pessoa está ajudando no desenvolvimento do pequenino!!! *Isso não vale para namorados que se tratam como bebês, ok?!*), o que nos dá mais uma evidência dessa boa distinção que eles fazem, fora que o nosso tom de voz, não falamos com nenéns, aumenta uma oitava, o que ajuda na distinção da fala.

E por citar a fala, vamos falar um pouco dela agora!!

## A fala

Quem nunca passou por aquela situação de falar com o seu assistente de voz, e falar para ligar para o @ , e o assistente vai e abre o mapas. (*Eu sei que ninguém liga mais hoje em dia, mas só pela didática, vai?!*). Ai você vai lá e xinga o pobre desenvolver por trás dessa tecnologia, pobre programador, mais xingado que juiz em final de campeonato.

Mas você já parou para se perguntar de onde vem esse problema?? Você ter que ficar falando diversas vezes e em todas o assistente erra, parece que *ta* de brincadeira com a sua cara?!

Porém a fala é algo extremamente complexo, porque o processo de detecção das palavras é para além de identificar os sons separados pelo silêncio. SIM!!!! Nós buscamos sinais não só nas pausas, e isso é desafio computacional, a fala em fluxo normal é um problema para computadores identificarem as palavras corretamente, como nós fazemos, porque passamos sinais que não estão só nas quebras do silêncio...


## E onde fica tudo isso aqui na minha cabecinha?

Primeiramente: Não é possível estudar a linguagem através de modelos animais!! EITAA, sim, não dá, porque lembra, isso só é encontrado entre nós, humanos!!!

Então Dantas, como estudam?? Como descobriram tudo isso ai que você falou até agora??

Então jovem padwan, estudamos em humanos mesmos, mas esses estudos começaram em pessoas que apresentavam Afasias, assim que os circuitos foram identificados

Wernick e Broca, foram pioneiros nesses estudos, e áreas descobertas por eles são nomeadas área de Wernick e Broca, e o tipo de afasias que cada um descobriu também!! Então já viu que foi bem importante a descoberta deles né?!!!

*O que cada hemisfério cuida na linguagem*

O hemisfério esquerdo é responsável pelo processamento dos níveis funcionais: fonética, palavras e frases

Mesmo em quem é canhoto???!!!
(a questão de processamento cruzado serão abordados em outros textos :) )

Sim jovem, mesmo em quem é canhoto, cerca de 95% dos indivíduos tem essa construção fonética no lado esquerdo.

Já o nosso lado direito, é responsável pelas informações emocionais, como as intenções e estado de espírito, logo intimamente ligado a interpretação das frases.

Mas a *Prosódia* é processada por ambos os lados.

Lembra quando falei que não era mito sobre bebês e a facilidade com uma segunda língua?!

Então,a partir de estudos com bilígues precoces e tardios, são percebidas as diferenças de processamento: nos tardios, as línguas são processadas em regiões afastadas, já em precoces, são processadas na mesma região (*não vou entrar em detalhes de neuroanatomia*)

Ainda não sabemos como acontece a separação dessas funções nos hemisférios!! Mas estamos estudando arduamente!!!

## Por fim, a NLP

Caramba, foi bastante informação hoje hein?!!!

Nossos estudos com o processamento de linguagem natural, ainda tem um longo caminho a percorrer, principalmente o grande desafio da Interface Homem- Máquina, podemos perceber que estamos lidando com um função extremamente refinada, temos que ter em mente que estamos mexendo com uma produção que vai além da gramática!!!

Tratarei das Afasias em um texto separado, e o porque pensar nisso traz o lado de impacto social para os nossos estudos de NLP.

EXTRA: LIBRAS é a segunda língua oficial do nosso país!!! Língua e não linguagem :)



Bibliografia:
 Kandel, et al.Principios de Neurociência. 5ª edição - Capítulo 60: Linguagem