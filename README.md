2019.2 - Efeito Bernoulli


# Introdução

## Tema: Efeito Bernoulli

## Integrantes: 
* Ana Paula Ferreira Militão - 14/0129791
* Ana Paula Lopes Gonçalves - 15/0005342
* Vittória Gabriela Borges Costa - 16/0041830

## 1.3 Objetivos
   ### Objetivo geral:

Verificar experimentalmente a equação de Bernoulli.

   ### Objetivos específicos:

- Realizar um levantamento de informações teóricas básicas que formulam os princípios da equação de Bernoulli. 

- Construir um tubo de Venturi.

 - Construir um Tubo de Pitot.

- Analisar e caracterizar o escoamento de um fluído.

- Validar os resultados obtidos experimentalmente comparando-os a resultados já conhecidos através do referencial teórico. 

## Requisitos de solução

O Efeito de Bernoulli descreve o comportamento de um fluido movendo-se ao longo de uma linha de corrente e traduz para os fluidos o princípio da conservação da energia. Segundo a equação de Bernoulli (Figura 1), enquanto a pressão de um fluido diminui, sua velocidade aumenta.
 
![Equação de Bernoulli](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.2-EfeitoBernoulli/blob/master/Equa%C3%A7%C3%A3o%201.gif)
##### Equação 1

Assim, entende-se que um fluido escoando por um tubo tem sempre a mesma vazão independente da variação da área da seção tranversal do tubo. Ao assumir que a vazão é constante, concluí-se que a velocidade e a pressão do fluido dentro do tubo variam de acordo com a área da seção tranversal. Portanto, para verificar o princípio de Bernoulli, pode-se observar o comportamento de um fluído escoando por região de área de seção tranversal conhecida e realizar medições de pressão, velocidade e vazão volumétrica afim de comprovar os pressupostos citados anteriormente.

   Para esse fim, foi desenvolvido o Tubo de Venturi (Figura 2), um aparato que apresenta seções de áreas variadas para medir a velocidade e vazão de um fluido. E justamente através desse aparato que é possível verificar o efeito de Bernoulli, analisando o escoamento de um fluído através de um tubo de Venturi. Conhecendo a geometria do tubo, e a pressão inicial e final, é possível determinar a velocidade inicial e/ou final do escoamento.

![Tubo de Venturi](http://1.bp.blogspot.com/-lchp2UI4fHo/VSl2spb5SDI/AAAAAAAAC04/arjO0FR3PKw/s1600/Capturar1F.PNG)

**Figura 1:** Modelo clássico de um tubo de Venturi. 

O Efeito Bernoulli pode ser observado em diversas situações bastante simples, como fazer uma bola de pingue-pongue flutuar com o fluxo de ar de um secador e fazer fitas paralelas se aproximarem ao aumentar a velocidade do fluxo de ar entre elas, ou situações mais complexas, como criando sustentação na asa das aeronaves durante o voo. Devido às limitações de tempo e materiais, decidiu-se que o experimento deveria ser simples, mas, por questões didáticas e para melhor compreensão da teoria envolvida, deveria apresentar mais explicitamente as dimensões das grandezas responsáveis. Portanto, para atender os requisitos do problema, o grupo propõe a construção de um Tubo de Venturi caseiro, com o qual poderão ser realizadas as medidas necessárias com auxílio de um Tubo de Pitot para analisar o princípio de Bernoulli.  


   
## Escopo

   O experimento proposto pelo grupo consistirá nas seguintes etapas:
 1. Fabricar um modelo caseiro de tubo de Venturi acoplado a um tudo de Pitot. Materiais: garrafas PET e uma mangueira transparente;
 3. Testar a estrutura do tubo para verificar possíveis defeitos como deformações e/ou furos que podem prejudicar a continuidade do fluxo;
 4. Realizar o experimento, provocando mudança no fluxo de ar com um secador de cabelo, e obter os dados de dimensão do tudo e velocidade do escoamento para posterior análise;
 5. Calcular e analisar os dados obtidos em relação à mudança de velocidade e pressão do escoamento;
 6. Comprovar as hipóteses do princípio de Bernoulli pelos cálculos de vazão;
 7. Em paralelo, durante toda a concepção e realização do projeto,  será realizada a concepção da documentação e produção do relatório na plataforma do GitHub. 
   
   Todos os membros do grupo participarão de todas as etapas e a distribuição de tarefas será realizada em consenso geral de acordo com as pendências a serem cumpridas. 
   
  
## Avaliação de viabilidade
   De acordo com pesquisas realizadas pelo grupo, a fabricação do tubo de Venturi caseiro é simples e requer materiais de baixo custo e de fácil acess, com utilização de materiais reutilizáveis (garrafas PET). Uma vez construído o tubo, a obtenção dos dados no experimento também não requer instrumentos de medição complexos, para isso será usado o tubo de Pitot, também facilmente construido. Assim, o custo final de materiais e equipamentos será baixo. Além disso, o tempo necessário para realização do projeto é uma vantagem, pois os aparato pode ser montado em uma tarde. A interpretação dos dados é simples e possuí uma vasta quantidade de referencial bibliográfico para auxílio dos cálculos e deduções necessários. Dessa forma, concluí-se que o experimento proposto é perfeitamente viável e satisfatório. 



# Planejamento e Preparação

 ## Teoria do Experimento
   A Equação de Bernoulli traduz o princípio de conservação de energia numa mesma linha de corrente num escoamento suposto estacionário, com volume constante, invíscido, sujeito adicionalmente a forças de campo (gravidade). 
   A principal aproximação na dedução da equação de Bernoulli é que os efeitos viscosos são desprezivelmente pequenos quando comparados aos efeitos da inércia, da gravidade e da pressão. Como todos os fluidos têm viscosidade (não existe um “fluido não viscoso”), essa aproximação não é válida para o todo de um campo de escoamento de interesse prático. Apesar de sua simplicidade e suas restrições, esta provou ser uma ferramenta muito poderosa na mecânica de fluidos. 
   Para deduzir a equação de Bernoulli aplica-se o teorema trabalho-energia ao fluido em uma seção de um tubo de escoamento como indica a Figura 2. 

![Fluido escoando em um tubo](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.2-EfeitoBernoulli/blob/master/Escoamento%20do%20flu%C3%ADdo.jpeg)

**Figura 2:** Representação do fluido em um tubo de escoamento.


   Considera-se um elemento do fluido que esrava inicialmente entre duas seções retas _a_ e _c_. Durante um pequeno intervalo de rempo _dt_, o fluido em _a_ se desloca para _b_ percorrendo uma distância _ds_. Adotando a hipótese de fluido incompressível, a equação da continuidade determina que o volume _dV_ do fluido é constante em qualquer seção reta do tubo.

   ![Equação 2](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.2-EfeitoBernoulli/blob/master/Equa%C3%A7%C3%A3o%202.gif)**(Equação 2)**


   O trabalho total _dW_ realizado pelo fluido nas vizinhanças sobre o elemento de fluido durante este deslocamento é:

   ![Equação 3](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.2-EfeitoBernoulli/blob/master/Equa%C3%A7%C3%A3o%203.gif)**(Equação 3)**


   O segundo termo possui sinal negativo porque a força sobre _c_ se opõe ao deslocamento do fluido.
   O trabalho _dW_ é realizado por outras forças, além da força conservativa da gravidade, de modo que ele é igual à variação da energia mecânica do sistema, associada ao elemento do fluido.
   A energia mecânica para os trchos _b_ e _c_ não varia, portanto, a energia cinética durante _dt_ é: 

   ![Equação 4](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.2-EfeitoBernoulli/blob/master/Equa%C3%A7%C3%A3o%204.gif)**(Equação 4])**


   Para a energia gravitacional, a variação total da energia potencial _dU_ durante _dt_ é:

   ![Equação 5](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.2-EfeitoBernoulli/blob/master/Equa%C3%A7%C3%A3o%205.gif)**(Equação 5)**


   Como, 

   ![Equação 6](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.2-EfeitoBernoulli/blob/master/Equa%C3%A7%C3%A3o%206.gif)**(Equação 6)**


a variação da energia mecânica fica:

   ![Equação 7](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.2-EfeitoBernoulli/blob/master/Equa%C3%A7%C3%A3o%207.gif)**(Equação 7)**


que simplificando se torna:

   ![Equação 8](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.2-EfeitoBernoulli/blob/master/Equa%C3%A7%C3%A3o%208.gif)**(Equação 8) _Equação de Bernoulli_**


   O significado físico deste Princípio será demonstrado de forma simples neste experimento. Como no tubo de Venturi o volume do fluido ao longo do tubo não varia com o tempo, logo percebe-se que a vazão do flúido é constante, e considerando também como desprezível os efeitos viscosos na parede do tubo e o escoamento como incompressível (devido à sua baixa velocidade) e irrotacional (devido ao seu fluxo laminar), pode-se aplicar a equação de Bernoulli para determinar a velocidade e a vazão do fluído em diferentes áreas do tubo. 

## Cronograma 
  Elaborou-se um cronograma de atividades de acordo com as exigências da disciplina.
  
  ![Cronograma](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.2-EfeitoBernoulli/blob/master/Cronograma%20Experimento%20Bernoulli-1.jpg)

**Figura 2:** Cronograma de atividades do grupo para a disciplina. 
  
   A construção do tubo de venturi e a realização do experimento será realizada em duas etapas, com duração de uma a duas horas. A primeira consiste na escolha, construção e validação da estrutura e a segunda na execução do experimento em questão. A aluna responsável por essas atividades será a Vittória e tais etapas serão efetuadas no dia 18/09 e 20/09, respectivamente.
      
   ## Medições e Resultados esperados
  Previamente ao início de qualquer experimento, é primordial saber as especificações e características dos materiais e equipamentos que serão usados. Desta forma, o fluído utilizado no tubo em "U", na parte inferior, é escolhido de forma conveniente, conhecendo sua densidade. No início, suas duas extremidades estão numa mesma altura (ambos submetidos a pressão ambiente). Contudo, alterando o fluxo de ar, nota-se que o fluido passará a apresentar uma diferença de altura, a qual será aferida. Além disso, deve-se medir as áreas A1 e A2 das seções transversais do tubo principal. 
  
  Com esses dados, espera-se comprovar a validade da equação de Bernoulli. Isto é, espera-se que para a área maior, tenha-se uma pressão maior e uma velocidade menor e vice-versa. Comprovando, também, a conservação da energia no sistema.
    
  ## Execução 
  
![Execucao1](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.2-EfeitoBernoulli/blob/master/WhatsApp%20Image%202019-09-20%20at%2016.46.22.jpeg)
**Figura 3:** Esquemático montado do tudo de venturi 

![Execucao2](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.2-EfeitoBernoulli/blob/master/WhatsApp%20Image%202019-09-20%20at%2016.46.24.jpeg)
**Figura 4:** Validação da estrutura 

![Execucao4](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.2-EfeitoBernoulli/blob/master/WhatsApp%20Image%202019-09-21%20at%2020.44.32.jpeg)

![Execucao5](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.2-EfeitoBernoulli/blob/master/WhatsApp%20Image%202019-09-21%20at%2020.44.33%20(1).jpeg)
**Figura 4:** Execução experimento

![Execucao3](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.2-EfeitoBernoulli/blob/master/WhatsApp%20Image%202019-09-20%20at%2016.46.25%20(1).jpeg)

   
## Referências

STEWART, W. L. E. B. R. 
Fenômenos de Transporte , Rio de Janeiro, 2017
