# Arduino---Wowki

Vamos apresentar um sistema simples e eficiente de alerta para enchentes, que pode ser usado para ajudar a prevenir danos causados por alagamentos em áreas urbanas. Usando tecnologia acessível, como sensores ultrassônicos e LEDs, criamos um dispositivo capaz de monitorar o nível da água e informar visualmente o risco de enchente.

As enchentes são um problema frequente em muitas cidades, principalmente durante períodos de chuva intensa. O acúmulo rápido de água em ruas, calçadas e áreas residenciais pode causar transtornos para moradores, danos a veículos e até riscos à segurança das pessoas. Por isso, é fundamental dispor de sistemas de alerta que possam avisar a população e as autoridades de forma rápida e clara.

Nosso sistema é composto basicamente por um sensor ultrassônico, três LEDs coloridos e uma placa controladora, chamada Wowki, que é semelhante ao Arduino. O sensor ultrassônico mede a distância entre ele e a superfície da água, enviando essa informação para a placa, que processa os dados e acende os LEDs conforme o nível da água.

O sensor ultrassônico emite ondas sonoras inaudíveis que refletem na superfície da água e retornam para o sensor. A placa calcula o tempo que a onda levou para voltar e transforma essa informação em uma distância em centímetros.

Temos três LEDs para indicar diferentes níveis de alerta, usando cores universalmente reconhecidas:

Quando a distância medida pelo sensor for maior que 200 centímetros, o LED verde acende. Isso significa que o nível da água está baixo, indicando segurança e ausência de risco imediato de enchente.

Quando a distância estiver entre 50 e 200 centímetros, o LED amarelo se acende. Essa faixa representa um alerta intermediário — o nível da água está subindo, e pode causar problemas caso continue aumentando. É um sinal para que as pessoas fiquem atentas.

Quando a distância for menor ou igual a 50 centímetros, o LED vermelho acende, indicando risco iminente de alagamento. Esse é o momento para ações preventivas, como evitar áreas alagadas e avisar as autoridades.

Um exemplo pratico é: Imagine que o sensor está instalado próximo a um bueiro que costuma entupir durante fortes chuvas. Conforme a água sobe, o sensor vai detectando a mudança na distância, e os LEDs vão indicando o risco. Se o LED verde estiver ligado, tudo está normal. Se passar para amarelo, é hora de ficar alerta, e se o vermelho acender, é sinal de que há perigo real.

Este sistema é simples, barato e fácil de instalar, podendo ser uma ferramenta valiosa para monitoramento de enchentes em áreas urbanas. Ele pode ajudar moradores, empresas e órgãos públicos a se prepararem melhor e evitarem prejuízos.



##Clique/Copie o link abaixo para entrar no projeto: 

https://wokwi.com/projects/432765578911581185

Em seguida, clique com o click esquerdo do mouse no botão verde a esquerda do botão azul com o símbolo de +...
Ápos isso espere o tempo que for necessario para o programa começar a rodar...
Com o programa em execução clique com o click esquerdo do mouse em cima do sensor de distância ultrassônico
Em sequência edite a distância do sensor para acender os led´s
> 200 = Led VERDE
> 50 / < 200  = Led AMARELO
< 50 = Led VERMELHO

##Video Demonstrativo: 

https://youtu.be/gRo5o3f1OGg?si=fcXG6RMAos5dUV25

##Desenvolvedores: 

Dennis Nieto Generoso RM563671

Giovanna Luiza Bento RM563203 

Mayene Moura da Silva RM564624 


