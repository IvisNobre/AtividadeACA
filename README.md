# Atividade de Análise Computacional da Aprendizagem

# Base de Dados:
A base de dados utilizada para essa atividade tem como título "dados-notas-versus-disciplina-versus-evasao" e se encontra disponível no link:
https://github.com/cristiancechinel/bookchapter/blob/master/dados-notas-versus-disciplina-versus-evasao.zip

Essa base de dados contém informações sobre o desempenho acadêmico de alunos em três disciplinas: Algoritmos, Cálculo I e Geometria Analítica, além da situação final de cada aluno.

Matricula: Identificador único para cada aluno.
Algoritmos: Nota do aluno na disciplina de Algoritmos.
CalculoI: Nota do aluno na disciplina de Cálculo I.
GeometriaAnalitica: Nota do aluno na disciplina de Geometria Analítica.
Situacao: Situação final do aluno, que pode ser "Evadido" ou "Formado". 

# Atividade de Associação

Com um suporte de 16% e uma confiança acima de 60%, temos 3 regras.

### Regras:

_Regra 1:_ Se Algoritmos ≤ 5.05" e Geometria Analítica ≤ 4.95, então Cálculo ≤ 4.75.

_Regra 2:_ Se Cálculo ≤ 4.75 e Geometria Analítica ≤ 4.95, então Algoritmos ≤ 5.05.

_Regra 3:_ Se Algoritmos ≤ 5.05 e Cálculo ≤ 4.75, então Geometria Analítica ≤ 4.95.


![image](https://github.com/user-attachments/assets/ff5ad36e-443b-4009-b3d2-60507daeab68)

Estas regras indicam que existe uma relação entre as classificações nas três disciplinas. Por exemplo, estudantes que apresentam resultados notas baixas em Algoritmos e Geometria Analítica costumam ter também notas baixas em Cálculo, e o contrário também acontece.

# Atividade de Agrupamento

Os resultados mostram que, com 13 clusters, o maior Silhouette Score é de 0.339. Esse valor indica a qualidade da separação entre os clusters, onde quanto mais próximo de 1, melhor a separação. Embora 13 clusters tenha o maior Silhouette Score, o valor não é tão alto, sugerindo que os clusters podem não estar bem separados.

![image](https://github.com/user-attachments/assets/662d9bdf-5e71-4936-98c0-00f5cd9a3467)
