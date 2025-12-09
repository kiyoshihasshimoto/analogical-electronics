# Introdução

A eletrônica analógica é muito importante para o desenvolvimento de um equipamento. É aqui que iremos preparar o terreno da energia elétrica que iremos utilizar... tratando a tensão, limitando a corrente em pontos específicos, limpando os ruídos e imperfeições da energia.

Isso tudo é necessário para que, ao desenvolver um sistema, todo o sinal elétrico for enviado, **ele deve estar limpo**, sem oscilações e recebendo a energia necessária para que evite falhas na geração do resultado desejado.

Então, para começar, deve-se ter noção de alguns conceitos e como eles funcionam na prática, tanto em simulações, quanto na vida real.

## Conceitos básicos

[1^]: ![Circuito](/attachments/GIF%20LED.gif)
[1^]: ![Circuito2](/attachments/Circuito%20LED.png)

No circuito acima podemos ver algumas coisas acontecendo, além dos componentes ali instalados.

## Eletrecidade

A eletrecidade é o elemento **mais importante** para se conhecer quando se trata de eletrônica, pois, sem ela, não à existiria como conhecemos, não é?

Mas...

## O que é a eletrecidade?

A eletrecidade não é nada mais que a <ins>movimentação dos elétrons</ins>, não é algo que podemos ver, nem sentir, nem tocar, mas sim, apenas perceber **oque ela pode fazer**, como acender uma lâmpada, por exemplo.

Porém, para que haja essa movimentação, é necessário algumas coisas ***obrigatórias***:

1. Circuito fechado;
2. Diferença de potêncial.

É necessário um circuito fechado para que a eletrecidade consiga se mover, ou seja, se apenas um pequeno ponto, não houver contato, ***não haverá eletrecidade***.

> Para uma explicação completa sobre a movimentação dos elétrons, [acesse esse documento](/beggining/subfiles/electricitymovement.md). Porém, recomendo que tenha ciência do conceito da eletrecidade de forma mais geral, ou seja, siga até o final desse documento para acessar este. 

Além da eletrecidade, também é estritamente necessário uma ***diferença de potêncial***, que significa a ***diferença da quantidade de elétrons*** entre os dois pontos do circuito. É isso que irá fazer com que os elétrons se movam.

> Nos é ensinado que os elétrons se movem do ***lado positivo para o negativo***, mas conhecido como ***sentido convencional***. Porém, os elétrons se movem do ***lado negativo para o positivo***, conhecido como ***sentido real***.

Além disso, dentro do circuito, existe um LED vermelho, que irá "gastar" essa energia, no caso, é oque queremos obter com ela (Isso é chamado de Output).

> Ao dizer: "gastar energia"... não significa que ela some, porém, o LED utiliza a movimentação dos elétrons que passam por ele e transformam-os em energia luminosa.
 - Por enquanto, irei retratar dessa forma os LEDS, porém, eles funcionam de forma bem mais específica. [Confira](/beggining/subfiles/componentsbehavior.md).

 E também, por fim, temos um resistor, que irá **limitar a corrente elétrica** que irá passar não apenas pelo LED, mas pelo circuito inteiro.

 > O resistor irá limitar a corrente, pois o LED tem um limite de corrente, caso ultrapasse, ele superaquece e acaba queimando.

# Observações pós-esclarecimentos

A partir daqui, iremos utilizar alguns termos específicos para a interpretação dos circuitos.

1. Chamaremos de tudo aquilo que trás a energia, prepara ela e constrói o circuito de **Input**.

> Entrada de energia, fios, resistores, capacitores, transistores, diodos, etc...

2. Tudo aquilo que nos retornar algo é chamado de **Output**.

> Luz, som, display, movimento, etc...

---

[Continuação...](/beggining/subfiles/analogicalelectricity2.md)