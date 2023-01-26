### INF0303_2022/2 - Semana 12 - Dia 25/01/2023 - Encontro 12 - Aulas 45a48 - Atividade Supervisionada

1. Considere o projeto "avaliacao_escolar" disponibilizado em aulas anteriores no SIGAA.
2. Considere os slides disponibilizados para a aula do dia 18/01/2023.
3. Pede-se:

  3.1 Elaborar o GFC do código do método avalia(), implementado na classe Avaliacao.java
  3.2 Identificar os casos de teste necessários para a cobertura do critério todos os caminhos, conforme descrito nos slides. Os casos de testes devem conter os valores da variáveis e indicar qual caminho está cobrindo. O caminho deve ser descrito através da sequencia de nós, por onde o fluxo passa.
### caso1 (base)
n1=6 n2=6 faltas=16 cargaHoraria=64 
9 -> 10 -> 11 -> 12.1 -> 12.2 -> 12.3 -> 12.4 -> 12.5 -> 12.6 -> 12.7 -> 17 -> 19 -> 21.1 -> 21.2 -> 22 -> 26
### caso2 
n1=-0.1 n2=6 faltas=16 cargaHoraria=64 
9 -> 10 -> 11 -> 12.1 -> 16
### caso2 
n1=10.1 n2=6 faltas=16 cargaHoraria=64 
9 -> 10 -> 11 -> 12.1 -> 12.2 -> 16
### caso3
n1=6 n2=-0.1 faltas=16 cargaHoraria=64 
9 -> 10 -> 11 -> 12.1 -> 12.2-> 12.3 -> 16
### caso4
n1=6 n2=10.1 faltas=16 cargaHoraria=64 
9 -> 10 -> 11 -> 12.1 -> 12.2-> 12.3 -> 12.4 -> 16
### caso5
n1=6 n2=6 faltas=-0.1 cargaHoraria=64 
9 -> 10 -> 11 -> 12.1 -> 12.2-> 12.3 -> 12.4 -> 12.5 -> 16
### caso6
n1=6 n2=6 faltas=17 cargaHoraria=64 
9 -> 10 -> 11 -> 12.1 -> 12.2-> 12.3 -> 12.4 -> 12.5 -> 16

  3.2 Calcular a complexidade ciclomática do código do método avalia, conforme fórmula constante dos slides citados.


INSTRUÇÕES:
1. Esta tarefa é individual;
2. Deve ser feita neste mesmo arquivo. Adicione aqui a imagem do GFC.
2. O prazo para entrega é as 23h59min do dia 25/01/2023.
