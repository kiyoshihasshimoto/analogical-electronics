# Introdução

A eletrônica analógica é muito importante para o desenvolvimento de um equipamento. É aqui que iremos preparar o terreno para que o sistema funcione corretamente... tratando a tensão, limitando a corrente, limpando os ruídos e imperfeições da energia, bloqueando partes do circuito e muito mais.

Então, para começar, deve-se ter noção de alguns conceitos e como eles funcionam na prática, tanto em simulações, quanto na vida real.

## Conceitos básicos

![Circuito](/attachments/GIF%20LED.gif)
![Circuito2](/attachments/Circuito%20LED.png)

No circuito acima podemos ver algumas coisas acontecendo, além dos componentes ali instalados.

## Eletricidade

A eletricidade é o elemento **mais importante** para se conhecer quando se trata de eletrônica, pois, sem ela, não existiria-à, não é?

Mas...

## O que é a eletricidade?

A eletricidade é um sistema completo que transporta energia, por exemplo: a <ins>energia potencial elétrica</ins> se transformando em energia útil. 
> Para um estudo mais abrangente da eletricidade, acesse esse documento, que se trata propriamente da [eletrodinâmica](/beggining/subfiles/eletrodinamics.md), que seria o estudo da física em cima da eletricidade.

Porém, para que exista eletricidade, é necessário algumas coisas ***obrigatórias***:

1. Circuito fechado;
2. Diferença de potêncial.

É necessário um circuito fechado para que haja a movimentação dos elétrons, ou seja, se apenas um pequeno ponto, não houver contato, ***não haverá eletricidade***.

> Para uma explicação completa sobre a movimentação dos elétrons, acesse o mesmo documento citado acima.

Além da eletricidade, também é estritamente necessário uma ***diferença de potêncial***, que significa a ***diferença da quantidade de elétrons*** entre os dois pontos do circuito. É isso que irá fazer com que os elétrons se movam.

> Nos é ensinado que os elétrons se movem do ***lado positivo para o negativo***, mais conhecido como ***sentido convencional***. Porém, os elétrons se movem do ***lado negativo para o positivo***, conhecido como ***sentido real***.

Além disso, dentro do circuito, existe um LED vermelho, que irá "gastar" essa energia, no caso, é oque queremos obter com ela (Isso é chamado de Output).

> Ao dizer: "gastar energia"... não significa que ela some, porém, o LED utiliza a energia potencial elétrica que passam por ele e a transforma em energia luminosa.
 - Por enquanto, irei retratar os LEDS dessa forma, porém, eles funcionam de forma bem mais específica. [Confira](/beggining/subfiles/componentsbehavior.md).

 E também, por fim, temos um resistor, que irá **limitar a corrente elétrica** não apenas pelo LED, mas pelo circuito inteiro.

 > O resistor irá limitar a corrente, pois o LED tem um limite de corrente, caso ultrapasse, ele superaquece e acaba queimando.

# Observações pós-esclarecimentos

A partir daqui, iremos utilizar alguns termos específicos para a interpretação dos circuitos.

1. Chamaremos de tudo aquilo que trás a energia, prepara ela e constrói o circuito de **Input**.

> Entrada de energia, fios, resistores, capacitores, transistores, diodos, etc...

2. Tudo aquilo que nos retornar algo é chamado de **Output**.

> Luz, som, display, movimento, etc...

---

[Continuação...](/beggining/subfiles/analogicalelectricity2.md)