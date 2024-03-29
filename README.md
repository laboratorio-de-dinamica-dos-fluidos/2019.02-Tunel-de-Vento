# 2019.02-Tunel-de-Vento
# 1.Início
## Tema: Experimentos em Túnel de Vento
### Integrantes:
Flávio Henrique de Almeida Feitoza Filho-17/0103145;

Gabriel Metre Resende-17/0120805;

Raiane Almeida Silva Vieira-17/0021220.
### 1.1 Objetivo:
 O presente trabalho tem por objetivo apresentar, bem como demonstrar por meio da realização de experimento em túnel de vento os efeitos do fluxo de ar sobre determinado corpo, permitindo-se assim obter resultados referentes a força de sustentação e de arrasto através da análise do comportamento estrutural. 
### 1.2 Escopo:
O estudo da Aerodinâmica consiste na verificação do comportamento do ar e sua interação com um objeto sólido. Assim, a verificação das forças de arrasto e sustentação, bem como os momentos sobre um corpo e a determinação do comportamento do escoamento correspondem aos objetivos das análises aerodinâmicas.

Tanto as forças quanto os momentos são provenientes da distribuição de pressão e da tensão de cisalhamento sobre a superfície do corpo.

Abaixo será apresentado um esquemático das forças e momentos em um perfil aerodinâmico.

![perfil de asa](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.02-Tunel-de-Vento/blob/master/perfil%20de%20asa.PNG)

**Figura 1**-Diagrama de forças aerodinâmicas.

- &alpha; - ângulo de ataque;

- L - sustentação;

- D - arrasto;

- R - força resultante;

- N - força normal;

- c - corda da asa; 

- A - força axial; 

- V&infin; - velocidade do vento. 

Tendo em vista, tais características para realização do experimento serão realizadas as seguintes etapas:
- Determinar a dimensão física do túnel de vento;
- Desenvolvimento de perfil aerodinâmico em impressora 3D a fim de verifiar os esforços e peso; 
- Monitoramento e medição das variáveis: força de sustentação e força de arrasto;
- Verificação do comportamento físico da parte estrutural;
- Simulação e verificação das linhas de emissão, as quais poderam ser visualizadas com a utilização de pedaços de plástico posicionados ao longo do perfil; 
- Aquisição dos dados obtidos através de equipamentos eletrônicos e análise via software;
- Comparação dos resultados obtidos experimelntalmente e simulados.
### 1.3 Viabilidade
Para realizar o experimento é preciso de um túnel de vento, uma balança aerodinâmica e perfis de asas. O laboratório de termofluídos do Campus Gama da Universidade de Brasília, possui um túnel de vento e uma balança aerodinâmica, a qual foi projetada e desenvolvida pelos alunos da disciplina de Projeto Integrador 1 no primeiro semestre de 2019, ambos atendem aos requisitos para a realização do experimento. Sabendo que já é de posse a maioria dos materiais a serem utilizados, os custos adicionais serão baixos e não será despendido muito tempo para montagem, assim conclui-se que é viável a execução do projeto. 

 # 2.Planejamento e preparação
 ## 2.1 Cronograma
 
![Planejamento e organização](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.02-Tunel-de-Vento/blob/master/Planejamento%20e%20Organiza%C3%A7%C3%A3o.jpg)
 **Figura 2** - Cronograma.
 
 As informações apresentadas acima são analisadas com determinados intervalos de tempo. Porém é necessário salientar que eventuais atrasos são possíveis, seja na aquisição dos materias, sua construção ou na organização do grupo.
 ## 2.2 Dados Medidos
 As informações apresentadas a seguir referem-se as fórmulas que os softwares XLFR5, bem como o desenvolvido pelos alunos da disciplina de Projeto integrador 1 no primeiro semestre de 2019 usam para apresentar os valores da sustentação e arrasto.
 
 Para realização do experimento deve-se inicialmente determinar a velocidade de escoamento do túnel de vento. Dessa maneira, é necessário utilizar as equações de Bernoulli e da continuidade, que serão apresentadas respectivamente a seguir:
 
 ![Eq.Bernoulli](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.02-Tunel-de-Vento/blob/master/Eq.Bernoulli.PNG)(Eq.1)
 
 ![Eq.Continuidade](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.02-Tunel-de-Vento/blob/master/Eq.Continuidade.PNG)(Eq.2)
 
 Consoante as equações apresentadas acima tem-se que V é a velocidade do vento, P é a pressão a qual o fluido está submetido, 𝜌 é
a densidade do fluido, g é a aceleração da gravidade, z é a altura em que o fluido está, ademais considera-se as
variáveis com o número 1 referentes aos dados para a maior seção do túnel de vento e 2 se refere à
seção menor. Isola-se a velocidade 𝑉1 da equação (2) e substitui na equação (1), podendo-se obter assim, as velocidades 𝑉1 e 𝑉2.

 Ademais, para vizualizar as linhas de emissão para diferentes ângulos de ataque, em especial no ângulo de estol, no qual há uma perda total de sustentação da asa, já que ocorre uma variação da camada limite. Tais características serão vizualizadas, bem como simuladas no programa XLFR5.
 
 A Sustentação corresponde a uma força aerodinâmica produzida pela ação do vento relativo
em um aerofólio, influenciada por superfícies de controle. Um aerofólio que se move no ar produz a sustentação, pois exerce em sua
superfície inferior uma pressão maior do que na superfície, essa diferença de pressão se dá devido a característica estrutural do aerofólio. Da mesma maneira pode-se considerar pra a força de Arrasto, no entanto deve-se levar em conta que essa força fornece uma resistência às aeronaves e por conseguinte redução da velocidade. Ambas forças dependem do ângulo de ataque.(ASSY,2004)

![Eq.sustentaçao](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.02-Tunel-de-Vento/blob/master/Eq.sustenta%C3%A7ao.PNG)(Eq.3)

![Eq.Arrasto](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.02-Tunel-de-Vento/blob/master/Eq.arrasto.PNG)(Eq.4)

Com relação as fórmulas apresentadas acima tem-se que 𝜌 representa a densidade do fluido, 𝑐𝑙 é o coeficiente de sustentação e 𝑐𝑑 é o
coeficiente de arrasto, v é a velocidade, c é a corda do perfil, D é a força de Arrasto e L a força de Sustentação.

A visualização do escoamento em perfis aerodinâmicos é utilizada para aferir os resultados obtidos pelos métodos numéricos, normalmente, resultados obtidos em softwares
de simulação. A geração de um escoamento laminar é imprescindível para a visualização
das linhas de corrente que são linhas desenhadas no campo de escoamento de forma que
num dado instante, são tangentes à direção do escoamento em cada ponto do campo.
(FOX, 2001)

## 2.3 Resultados Esperados
 O experimento visa validar os gráficos "cl versus ângulo de ataque" e "cd versus ângulo de ataque" simulados via software. Bem como, mostrar o efeito dinâmico sobre o escoamento ao se analisar determinado ângulo de ataque no aerofólio.
 
 # 3 Execução
 ## 3.1 Divisão das Tarefas
 Não houve mudanças. A divisão das tarefas permanece a mesma do tópico "2.1 Cronograma". 
 ## 3.2 Foto do Experimento Montado
 ![Foto Experimento Montado e Aerofólio](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.02-Tunel-de-Vento/blob/master/Foto%20Experimento%20Montado%20e%20Aerof%C3%B3lio.jpeg)
 
 **Figura 3**-Foto do Experimento Montado com um dos aerofólios
 
 ![Foto Experimento Montado](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.02-Tunel-de-Vento/blob/master/Foto%20Experimento%20Montado.jpeg)
 
 **Figura 4**-Foto do Experimento Montado.
 
 ## 3.3 Procedimentos realizados
 Inicialmente, foi realizado a calibração da balança aerodinâmica acoplada ao túnel de vento. Posteriormente, determinou-se a velocidade no túnel de vento com auxílio de um anemômetro. Posicionou-se os perfis a serem analisados, observando-se as linhas de corrente, bem como os valores apresentados no software da balança para o coeficiente de sustentação e de arrasto em diferentes inclinações.
 
 # 4 Análise e Conclusão
 ## 4.1 Resultados Obtidos
  Por meio da utilização de um anemômetro verificou-se o seguinte valor da velocidade no túnel de vento. Conforme figura a seguir:
  
  ![anemometro](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.02-Tunel-de-Vento/blob/master/anemometro.jpeg)
  
  **Figura 5** - Resultado da velocidade medida experimentalmente no túnel de vento.
  
  Adotou-se a densidade d= 1,225 kg/m^3, a velocidade do anenômetro, corda (d)= 0,08 m.
  
  Os resultados do coeficiente de sustentação obtidos para o perfil em análise (NACA0012), variando-se o ângulo de ataque, será apresentado a seguir:
  
  ![cl.alpha.experimental.obtido](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.02-Tunel-de-Vento/blob/master/cl.alpha.experimental.obtido.png)
  
  **Figura 6** - Valores do coeficiente de sustentação (cl) para diferentes ângulos de ataque.
  
  Obteve-se os seguintes valores para as forças por unidade de comprimento (L e D) a diferentes inclinações. Conforme seguinte figura:
  
  ![alpha.L.D.experimentais](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.02-Tunel-de-Vento/blob/master/alfa.L.D.experimentais.png)
  
  **Figura 7** - Valores das forças de Sutentação e Arrasto nas inclinações analisadas.
  
  Referente a simulação tem-se o seguinte resultado obtido:
  
   ![SimulaçãoXFLR5.png](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.02-Tunel-de-Vento/blob/master/Simula%C3%A7%C3%A3oXFLR5.png)
   
 **Figura 8** - Simulação do aerofólio NACA 0012 no software XFLR5.
 
 Tanto o software associado a balança, quanto o programa XFLR5 utilizaram como base as equações 3 e 4, para determinação do coeficiente de sustentação e arrasto (cl, cd), bem como das forças de sustentação e arrasto (L, D).
  
   [![linha.de.corrente](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.02-Tunel-de-Vento/blob/master/linhas%20de%20corrente.jpg)](https://www.youtube.com/watch?v=iBikIiG30e4)
   
   **Video 1** - Exemplificação das linhas de corrente.
   
   (Clique na imagem para assistir o video da simulção de linhas de corrente)
  ![coleta.de.dados](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.02-Tunel-de-Vento/blob/master/processo%20de%20coleta%20de%20dados.jpeg)
  
  **Figura 9** - Coleta de dados do aerofólio NACA0012.
  
 ## 4.2 Considerações finais
 
 A partir dos resultados obtidos experimentalmente e apresentados nas figuras 6 e 7 e comparando-os com os valores determinados por meio da simulação no XFLR5 ilustrada na figura 8, por meio de gráficos os quais apresentam os valores de cl e cd para diferentes ângulos de ataque, realizou-se um gráfico comparativo, a fim de mostrar os valores do experimento e simulação conjuntamente.

![Comparação.Experimental.Simulação.png](https://github.com/laboratorio-de-dinamica-dos-fluidos/2019.02-Tunel-de-Vento/blob/master/Compara%C3%A7%C3%A3o.Experimental.Simula%C3%A7%C3%A3o.png)
 
 **Figura 10** - Comparação gráfica entre os resultados experimentais e simulados para verificação de erros.
 
 Por meio do gráfico acima percebe-se que a diferença entre os valores de cl para a simulação e experimento é pequena e deve-se provavelmente a algumas simplificações realizadas pelo programa XFLR5, já que esse considera um escoamento muito próximo ao ideal, porém na prática tem algumas variações. Outras considerações serão apresentadas a seguir:
- Pode ter ocorrido vibrações na bancada onde encontra-se o túnel de vento, bem como erros de calibração da balança aerodinâmica utilizada. 
- Mesmo a superfície interna do túnel de vento estando próxima ao ideal, há rugosidades. 
-A estrutura do túnel não estava em boas condições de encaixe na junção dos tubos. 
-Quanto a alteração manual do perfil para cada angulação, pode não ter sido tão precisa. 
- Pode haver erro associado à diferença de valores padrões (utilizados nas fórmulas e simulações) e de valores reais.

 Apesar de tais valores distinguirem entre os testes físicos e os da balança, pode-se considerar tais medidas aceitáveis, tendo em vista que o erro é de cerca de algumas casas decimais, tal erro acaba por influenciar no valor um pouco distinto da força de sustentação e de arrasto (S, L, respectivamente).

 Dessarte, pode-se dizer que as propostas inicialmente realizadas foram cumpridas, ou seja, obteve-se valores próximos experimentais e simulados para o coeficiente de sustentação e arrasto, bem como verificou-se a presença de linhas de corrente, por meio do vídeo 1 apresentado nos resultados obtidos.


 # Referências
 ASSY, T. Mecânica dos Fluidos - Fundamentos e Aplicações. Editora LTC. 2a Ed. Rio de Janeiro, 2004.
 
 FOX, R. Introdução à Mecânica dos Fluidos. LTC, Rio de Janeiro, 2001.

