2019.2 - Efeito Bernoulli

### Integrantes: 
* Ana Paula Ferreira Militão - 14/0129791
* Ana Paula Lopes Gonçalves - 15/0005342
* Vittória Gabriela Borges Costa - 16/0041830

### Tema: Efeito Bernoulli



## Introdução

   O Efeito de Bernoulli descreve o comportamento de um fluido movendo-se ao longo de uma linha de corrente e traduz para os fluidos o princípio da conservação da energia. Segundo a equação de Bernoulli (Figura 1), enquanto a pressão de um fluido diminuiu, sua velocidade aumenta.
 
![Equação de Bernoulli](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.2-EfeitoBernoulli/blob/master/Equa%C3%A7%C3%A3o%201.gif)

**Equação 1**


   Com uso dessa relação, foi desenvolvido o Tubo de Venturi (Figura 2), um aparato que apresenta seções de áreas variadas para medir a velocidade e vazão de um fluido. E justamente através desse aparato que é possível verificar o efeito de Bernoulli, analisando o escoamento de um fluído através de um tubo de Venturi. Conhecendo a geometria do tubo, e a pressão inicial e final, é possível determinar a velocidade inicial e/ou final do escoamento.

![Tubo de Venturi](http://1.bp.blogspot.com/-lchp2UI4fHo/VSl2spb5SDI/AAAAAAAAC04/arjO0FR3PKw/s1600/Capturar1F.PNG)

**Figura 1:** Modelo clássico de um tubo de Venturi. 


## Objetivos
   ### Objetivo geral:
   
Verificar experimentalmente a equação de Bernoulli.

   ## Objetivos específicos:
   
- Realizar um levantamento de informações teóricas básicas que formulam os princípios da equação de Bernoulli. 

- Construir um tubo de Venturi.

- Analisar e caracterizar o escoamento de um fluído.

- Validar os resultados obtidos experimentalmente comparando-os a resultados já conhecidos através do referencial teórico. 

## Requisitos de solução
   O princípio de Bernoulli diz que um fluido escoando por um tubo tem sempre a mesma vazão independente da variação da áreaa da seção tranversal do tubo. Assumindo que a vazão é constante, concluí-se que a velocidade e a pressão do fluido dentro do tubo variam de acordo com a área da seção tranversal. Portanto, para verificar o princípio de Bernoulli, pode-se observar o comportamento de um fluído escoando por região de área de seção tranversal conhecida e realizar medições de pressão, velocidade e vazão volumétrica afim de comprovar os pressupostos citados anteriormente, 
   Portanto, para atender os requisitos do problema, o grupo propõe a construção de um Tubo de Venturi caseiro, com o qual poderão ser realizadas as medidas necessárias para analisar o princípio de Bernoulli.  

## Escopo
   O experimento proposto pelo grupo seguirá as seguintes etapas:
 1. Projeto da estrutura do tubo de Venturi. Incluindo a escolha dos materiais mais adequados ao experimento;
 2. Fabricação do tubo de Venturi;
 3. Testes com a estrutura do tubo para verificão de defeitos como deformações e ou furos que podem prejudicar a continuidade do fluxo;
 4. Realização do experimento e obtenção de dados;
 5. Calculos e análise dos dados obtidos;
 6. Em paralelo, durante toda a concepção e realização do projeto,  será realizada a concepção da documentação e produção do relatório na plataforma do GitHub. 
   
   Todos os membros do grupo participarão de todas as etapas e a distribuição de tarefas será realizada em consenso geral de acordo com as pendências a serem cumpridas. 
   
  
## Avaliação de viabilidade
   De acordo com pesquisas realizadas pelo grupo, a fabricação do tubo de Venturi caseiro é simples e requer materiais de baixo custo e de fácil acesso. Podendo até utilizar materiais recicláveis como garrafas PET. Uma vez construído o tubo, a obtenção dos dados no experimento também não requer instrumentos de medição complexos. A interpretação dos dados é simples e possuí uma vasta quantidade de referencial bibliográfico para auxílio dos cálculos e deduções necessários. Dessa forma, concluí-se que o experimento proposto é perfeitamente viável e satisfatório. 

## Planejamento e Preparação
   ### Referencial Teórico
   A Equação de Bernoulli traduz o princípio de conservação de energia numa mesma linha de corrente num escoamento suposto estacionário, com volume constante, invíscido, sujeito adicionalmente a forças de campo (gravidade). 
   A principal aproximação na dedução da equação de Bernoulli é que os efeitos viscosos são desprezivelmente pequenos quando comparados aos efeitos da inércia, da gravidade e da pressão. Como todos os fluidos têm viscosidade (não existe um “fluido não viscoso”), essa aproximação não é válida para o todo de um campo de escoamento de interesse prático. Apesar de sua simplicidade e suas restrições, esta provou ser uma ferramenta muito poderosa na mecânica de fluidos. 
   Para deduzir a equação de Bernoulli aplica-se o teorema trabalho-energia ao fluido em uma seção de um tubo de escoamento como indica a Figura 2. 
   
![Fluido escoando em um tubo](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.2-EfeitoBernoulli/blob/master/Escoamento%20do%20flu%C3%ADdo.jpeg)

**Figura 2:** Representação do fluido em um tubo de escoamento.
   
   
   Considera-se um elemento do fluido que esrava inicialmente entre duas seções retas _a_ e _c_. Durante um pequeno intervalo de rempo _dt_, o fluido em _a_ se desloca para _b_ percorrendo uma distância _ds_. Adotando a hipótese de fluido incompressível, a equação da continuidade determina que o volume _dV_ do fluido é constante em qualquer seção reta do tubo.
   
   ![Equação 2](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.2-EfeitoBernoulli/blob/master/Equa%C3%A7%C3%A3o%202.gif) 

**Equação 2**


   O trabalho total _dW_ realizado pelo fluido nas vizinhanças sobre o elemento de fluido durante este deslocamento é:
   
   ![Equação 3](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.2-EfeitoBernoulli/blob/master/Equa%C3%A7%C3%A3o%203.gif)
   
 **Equação 3**
 
 
   O segundo termo possui sinal negativo porque a força sobre _c_ se opõe ao deslocamento do fluido.
   O trabalho _dW_ é realizado por outras forças, além da força conservativa da gravidade, de modo que ele é igual à variação da energia mecânica do sistema, associada ao elemento do fluido.
   A energia mecânica para os trchos _b_ e _c_ não varia, portanto, a energia cinética durante _dt_ é: 

   ![Equação 4](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.2-EfeitoBernoulli/blob/master/Equa%C3%A7%C3%A3o%204.gif)
   
 **Equação 4**
 
 
   Para a energia gravitacional, a variação total da energia potencial _dU_ durante _dt_ é:
   
   ![Equação 5](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.2-EfeitoBernoulli/blob/master/Equa%C3%A7%C3%A3o%205.gif)
   
 **Equação 5**
 
 
   Como, 
     
   ![Equação 6](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.2-EfeitoBernoulli/blob/master/Equa%C3%A7%C3%A3o%206.gif)
   
 **Equação 6**
 
 
a variação da energia mecânica fica:
  
   ![Equação 7](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.2-EfeitoBernoulli/blob/master/Equa%C3%A7%C3%A3o%207.gif)
   
 **Equação 7**

que simplificando se torna:
  
   ![Equação 8](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.2-EfeitoBernoulli/blob/master/Equa%C3%A7%C3%A3o%208.gif)
   
 **Equação 8: _Equação de Bernoulli_**
 
 
 
## Referências

STEWART, W. L. E. B. R. 
Fenômenos de Transporte , Rio de Janeiro, 2017
