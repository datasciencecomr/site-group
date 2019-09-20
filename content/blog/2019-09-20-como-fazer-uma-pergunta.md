---
comments: true
date: "2019-09-20T11:21:28-03:00"
image: /images/blog/2.jpg
publishdate: "2019-09-20T11:21:28-03:00"
tags:
- StackOverflow
- Perguntas
- Exemplos
title: Como Fazer Uma Pergunta?
---

Quando eu estava começando a ingressar no mundo das linguagens de programação, eu tinha muita dúvida, eu não sabia nem como procurar, às vezes ficava a me perguntar "como eu sei que estou expert em tal assunto?". O problema, que na verdade não é exatamente um, é que quanto mais nós estudamos (nos aprofundamos) em uma área de conhecimento mais dúvidas surgirão dado que iremos enfrentar novos desafios.

Quando somos iniciantes podemos desconhecer os termos e palavras-chaves para resolver nossas questões, às vezes podemos nem fazer ideia que aquilo que procuramos é algo relativamente "comum" naquele domínio de conhecimento. Então colocamos nossas dúvidas no _StackOverflow_ ou em grupos e as pessoas vem com um [https://lmgtfy.com/](https://lmgtfy.com/) ou negativam nossa pergunta (nesse caso no _StackOverflow_), mas por que fazem isso e não nos ajudam? Vou elencar alguns motivos que suponho:

1. É provável que a sua pergunta possa ser respondida através de uma consulta no _Google_
2. Você provavelmente pode não ter explicado seu problema direito e gerado interpretações ambíguas
3. As pessoas podem ser apenas _haters_ e não terem paciência com iniciantes

## Situação 1:
Então, antes de fazer a sua pergunta, dê uma vasculhada no _Google_, _StackOverflow_, tutoriais e o que mais você conhecer. Por exemplo, se seu programa está dando algum erro estranho copie o código do erro e busque na _Internet_, **não copie o caminho todo** pois às vezes no erro pode estar o caminho do seu computador como `/usuário/fulaninho/python/biblioteca/blabla.h erro na linha 256, a variável não é do tipo inteiro`. Nesse caso você pode copiar a partir de "biblioteca ..". Se você tem dúvidas sobre como percorrer uma lista ou realizar algum tipo de operação você buscar algo similar a "selecionar elementos de um dataframe em R". Caso não tenha obtido o resultado desejado, você pode ir refinando (melhorando) os termos da consulta. 

## Situação 2:
Você tentou buscar na _Internet_ a sua dúvida e não conseguiu achar a resposta desejada :persevere:, então está na hora de pedir ajuda em grupos e sites como o _StackOverflow_. Quando você for fazer uma pergunta é importante facilitar o máximo possível para que as pessoas a compreendam. Na minha opinião, eu acho interessante a pessoa colocar **um exemplo do dado de entrada** (pode ser construído manualmente, similar a seu dado real), um exemplo do **resultado almejado** e o **progresso atual** (que pode ser o código que você tentou construir para atingir o resultado almejado). Se for um erro, você coloca o **exemplo de entrada**, o **código que gerou erro** e **texto do erro** em si. A seguir vou colocar um exemplo de pergunta e um código para facilitar a compreensão da mesma:

> Olá pessoal, eu estou com uma dúvida, estou querendo marcar elementos do dataframe como verdadeiro de acordo com a condição entre duas colunas, por exemplo, se a coluna A e a B tiver uma soma que resulte em um número maior que 5 quero marcar como verdadeiro. Eu fiz assim:

```r
# Meu dado de entrada, construído manualmente
dado_entrada <- data.frame(A=c(2,7,3,1), B=c(1,1,1,6))

# Meu progresso atual
for (i in dado_entrada){
  print(paste("entrada", i))
}

# Resultado que eu quero
dado_saida <- data.frame(A=c(2,7,3,1), B=c(1,1,1,6), 
                         C=c(3,8,4,7), R = c(FALSE, TRUE, FALSE,  TRUE))
```

O código acima foi dividido em três partes: (1) o dado de entrada que construímos manualmente, esse dado pode representar parte do nosso _dataset_; (2) progresso atual - corresponde a "tentativa" de obter a saída esperada; (3) dado de saída - representa o resultado que pretendemos atingir.

Com essas informações ficará mais fácil do próximo tentar lhe ajudar. Você pode compartilhar esse código em sites como o [pastebin](https://pastebin.com/), [hastebin](https://hastebin.com/) etc. Se você estiver no Telegram você pode usar o bot [@rextester_bot](http://t.me/rextester_bot) para compartilhar um pequeno código executável que não dependa de biblioteca externas.

## Situação 3

Infelizmente, ainda não sei como lidar com _haters_, entretanto, você não precisa se desmotivar se alguém falar que sua pergunta é simples demais e outras falas desmotivadoras. Apenas mantenha foco, esforce-se e não precisa ficar tímido/tímida. Como eu disse no começo, é normal às vezes nem conhecermos o termo exato da nossa dúvida.


É isso pessoas, conhecimento é bem-vindo, ajude seu/sua colega e se tiver dúvida pode perguntar lá no [@datasciencecomR](http://t.me/DataScienceComR). Qualquer sugestão/dúvidas/críticas sobre esse _post_ pode falar nos comentários ou no grupo.