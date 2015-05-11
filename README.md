# projeto-coopera
Projeto de sistema para análise de gráficos voltados ao desenvolvimento pedagógico. Este projeto está voltado para o consumo por parte da Cooperativa do Saber.

# Features
Inicialmente o sistema deve contar com as seguintes features:

#1 Cadastro de alunos
#2 Remocao de alunos
#3 Alimentação de notas individual
#4 Alimentação de notas em massa
#5 Exibição de gráfico individual
#6 Exibição de gráfico em massa

# Como funciona
A Cooperativa possui uma hierarquia de dados bem-definida.
Um aluno é vinculado a uma turma, que é vinculada à Cooperativa por inteiro.
Cada aluno estuda por volta de 10 disciplinas, que são avaliadas em 6 ciclos de simulados.
Cada disciplina é ligada a uma área do conhecimento: Humanas, Exatas e Biológicas.
Cada ciclo possui 3 provas divididas entre as disciplinas em questão, simulando assim o processo
de vestibular da Unicamp.
Para cada uma destas provas é atribuída ao aluno notas que refletem seu desempenho tanto em questões dissertativas, que variam de 0 a 10, quanto em questões objetivas, que são o número de questões acertadas pelo aluno.
Cada uma dessas notas podem ter pesos diferentes de acordo com o gosto do professor que avalia.

Tendo pelo menos um ciclo de simulados, a análise de gráficos podem seguir critérios bem específicos. Os critérios base podem ser considerados: por disciplina, por área.
1. Comparação de notas do aluno atráves dos ciclos.
2. Comparação de notas do aluno com a turma.
3. Comparação de notas do aluno com toda a Cooperativa.
4. Comparação de notas da turma com outra turma.
5. Análise de notas de toda a Cooperativa.

Ou seja, temos que fazer com que as informações possam ser ligadas de forma que um mesmo tipo de gráfico possua vários filtros. Por exemplo, um gráfico de comparação por tempo (line-temporal) pode ter todos os filtros possível para um gráfico temporal.
Um gráfico que analise quantidade (pie-temporal) deve ter filtros que condizem a um gráfico de torta.
Mais filtros podem ser adicionados com o tempo, e cada filtro deve ser estacável de forma a abranger toda a hierarquia da Cooperativa.
