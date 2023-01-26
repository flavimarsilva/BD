### INF0303_2022/2 - Semana 12 - Dia 25/01/2023 - Encontro 12 - Aulas 45a48 - Atividade Supervisionada

1. Considere o projeto "avaliacao_escolar" disponibilizado em aulas anteriores no SIGAA.
2. Considere os slides disponibilizados para a aula do dia 18/01/2023.
3. Pede-se:
  
  3.1 Elaborar o GFC do código do método avalia(), implementado na classe Avaliacao.java
  3.2 Identificar os casos de teste necessários para a cobertura do critério todos os caminhos, conforme descrito nos slides. Os casos de testes devem conter os valores da variáveis e indicar qual caminho está cobrindo. O caminho deve ser descrito através da sequencia de nós, por onde o fluxo passa.
  ## Resposta
  ### caminho1 (base)
  n1=6 n2=6 faltas=16 cargaHoraria=64 
  
  9 &rarr; 10 &rarr; 11 &rarr; 12.1 &rarr; 12.2 &rarr; 12.3 &rarr; 12.4 &rarr; 12.5 &rarr; 12.6 &rarr; 12.7 &rarr; 17 &rarr; 19 &rarr; 21 &rarr; 22 &rarr; 26
  ### caminho2 
  n1=-0.1 n2=6 faltas=16 cargaHoraria=64 
  
  9 &rarr; 10 &rarr; 11 &rarr; 12.1 &rarr; 16 &rarr; 26
  ### caminho3
  n1=10.1 n2=6 faltas=16 cargaHoraria=64 
 
  9 &rarr; 10 &rarr; 11 &rarr; 12.1 &rarr; 12.2 &rarr; 16 &rarr; 26
  ### caminho4
  n1=6 n2=-0.1 faltas=16 cargaHoraria=64 
  
  9 &rarr; 10 &rarr; 11 &rarr; 12.1 &rarr; 12.2&rarr; 12.3 &rarr; 16 &rarr; 26
  ### caminho5
  n1=6 n2=10.1 faltas=16 cargaHoraria=64 
  
  9 &rarr; 10 &rarr; 11 &rarr; 12.1 &rarr; 12.2&rarr; 12.3 &rarr; 12.4 &rarr; 16 &rarr; 26
  ### caminho6
  n1=6 n2=6 faltas=-0.1 cargaHoraria=64 
  
  9 &rarr; 10 &rarr; 11 &rarr; 12.1 &rarr; 12.2&rarr; 12.3 &rarr; 12.4 &rarr; 12.5 &rarr; 16 &rarr; 26
  ### caminho7
  n1=6 n2=6 faltas=16 cargaHoraria=15 
 
  9 &rarr; 10 &rarr; 11 &rarr; 12.1 &rarr; 12.2&rarr; 12.3 &rarr; 12.4 &rarr; 12.5 &rarr; 12.6 &rarr; 16 &rarr; 26
  ### caminho8
  n1=6 n2=6 faltas=16 cargaHoraria=-0.1
  
  9 &rarr; 10 &rarr; 11 &rarr; 12.1 &rarr; 12.2&rarr; 12.3 &rarr; 12.4 &rarr; 12.5 &rarr; 12.6 &rarr; 12.7 &rarr; 16 &rarr; 26
  ### caminho9
  n1=6 n2=6 faltas=17 cargaHoraria=-64
  
  9 &rarr; 10 &rarr; 11 &rarr; 12.1 &rarr; 12.2&rarr; 12.3 &rarr; 12.4 &rarr; 12.5 &rarr; 12.6 &rarr; 12.7 &rarr; 17 &rarr; 18 &rarr; 26
  ### caminho10
  n1=3 n2=2.9 faltas=16 cargaHoraria=-64
  
  9 &rarr; 10 &rarr; 11 &rarr; 12.1 &rarr; 12.2&rarr; 12.3 &rarr; 12.4 &rarr; 12.5 &rarr; 12.6 &rarr; 12.7 &rarr; 17 &rarr; 19 &rarr; 20 &rarr; 26
  ### caminho11
  n1=4.5 n2=4.5 faltas=16 cargaHoraria=-64
  
  9 &rarr; 10 &rarr; 11 &rarr; 12.1 &rarr; 12.2&rarr; 12.3 &rarr; 12.4 &rarr; 12.5 &rarr; 12.6 &rarr; 12.7 &rarr; 17 &rarr; 19 &rarr; 21 &rarr; 22 &rarr; 26

  3.2 Calcular a complexidade ciclomática do código do método avalia, conforme fórmula constante dos slides citados.
  
  ## Resposta
  ```
  c = 26 - 17 + 2
  c = 9 + 2
  c = 11
  ```
  ou
  ```
  c = p + 1
  c = 10 + 1
  c = 11
  ```
