# Tensão, corrente, resistência e potência

Se lembra daquele circuito simples que mostrei anteriormente? Aqui vão algumas coisas que são importantes saber!

![Circuito](/attachments/Circuito%20LED.png)

Dentro desse circuito, podemos ver algumas informações e também fornecer outras.

1. Temos uma bateria que, como exibido na imagem, contém 9V (9 Volts). Ou seja, para poder gerar a voltagem necessária para mover os elétrons, a bateria é um dos elementos que **utilizam uma estrutura que causa essa diferença de potêncial**, sendo estritamente necessária para criar um circuito.

> Os Volts, voltagem, ou tensão elétrica, é aquilo que usamos para medir a **diferença de potencial (ddp)** entre dois pontos do circuito, ou seja, a força que move os elétrons.

2. No LED vermelho vemos dois pinos principais, temos o **ânodo**, que é o pino onde há menos concentração de elétrons, por isso ele é ligado ao positivo, que também é pobre em concentração de elétrons. E no outro ponto, o **cátodo**, que é onde existe maior concentração de elétrons, por isso, negativo.

> O LED utiliza uma estrutura que foi pensada na [Junção PN](/beggining/subfiles/componentsbehavior.md), que não irei entrar em muitos detalhes aqui. Então ela não segue necessáriamente o sentido convencional, nem o real, mesmo que pareça.

3. O resistor será utilizado para resistir a corrente elétrica do circuito (Medido em Ohms $\Omega$), que, como citado anteriormente, será utilizado para não queimar o LED.

4. E por fim, os fios condutores, que são utilizados para fechar o circuito, criando um loop da movimentação dos elétrons.

## O princípio da eletrecidade

Ao causar a **ddp**, os elétrons irão automaticamente se mover. Esse movimento pode ser medido considerando a quantidade de elétrons que passam no circuito por segundo. A famosa ***corrente elétrica***.
> Quanto maior for a tensão elétrica, mais elétrons passarão pelo circuito, pois terão mais força para se movimentar.

A corrente elétrica é medida em Amperes, que é a mesma coisa que coulomb por segundo. Coulomb se refere à quantidade de elétrons, que, no fim, significa que ali passam uma certa quantidade de elétrons por segundo.

> Também pode se referir em carga elétrica, mas decidi colocar em elétrons para ficar mais fácil para entender. Mas, apenas para esclarecer: Um único elétron possui uma quantidade de carga, que é a menor quantidade de carga que existe no universo, que são dos elétrons (também nos prótons). 

> Essa carga carrega consigo energia potencial elétrica transportada pelos elétrons através da corrente elétrica, a mesma energia que geram os outputs.

> Então para não ficar como: $6,24 \times 10^{18}$ elétrons por segundo, apenas dizemos 1 Ampér.

> Não irei entrar em muitos detalhes em relação a isso, pois se trata de um estudo de um outro ramo. Mas resumidamente, seria isso.

Concluindo, pode-se dizer que a eletrecidade é surge a partir da movimentação dos elétrons, que carregam consigo suas respectivas cargas, que contém consigo energia potêncial elétrica

## Relacionando todos esses elementos

Olhando todos esses elementos: a tensão, corrente e resistência elétrica. Saiba que é possível relaciona-los atráves de uma equação, chamada Lei de Ohm.

$V = R \times I$

Isso significa que a tensão é igual a resistência vezes a corrente elétrica.

Relacionando-os, podemos dizer que quanto maior a tensão, maior será a corrente e quanto maior a resistencia, menor será a corrente. Assim como podemos descobrir a resistência necessária para entregar a corrente necessária para um componente qualquer.

$I=\frac{V}{R}$ também $R=\frac{V}{I}$ Essa é uma demonstação de que podemos manipular a equação para obter qualquer dado, desde que tenha os outros dois.

## Potência elétrica

A potência elétrica é utilizada para nos informar o quanto de energia pode ser transformada por um equipamento eletrônico. Isso se dá por:

$P = V \times I$
> Como uma equação, nós também podemos manipula-la para obter qualquer dado, desde que tenha os outros dois.

Onde P é medido em W (Watts). Onde, ***quanto maior a potência, maior o consumo de energia***. Logo, se um equipamento tem potência de 50W, ele consegue transformar 50W de energia, então, é necessário alimenta-lo com energia o suficiente para suprir essa demanda.

## Conclusão

Com tudo isso em mãos, pode-se obter todos os dados necessários para se construir um circuito completo. A partir disso, apenas escolher os componentes certos, suprir suas demandas e adaptar a tensão e corrente da forma desejada.