# Diagnóstico de diabetes por meio da análise de pacientes
Análise feita através da Biblioteca Pandas e Sqlite3 em Python

## Problema de Negócio :
Fonte dos dados: https://www.kaggle.com/uciml/pima-indians-diabetes-databaseData 

Descobrir atráves dos dados de pacientes se desenvolveram ou não diabetes para isso, precisamos gerar uma amostra de dados com os pacientes com mais de 50 anos e para cada um deles indicar em uma nova coluna se o paciente está normal (BMI menor que 30) ou obeso (BMI maior ou igual a 30).
 
## Estrátegias usadas para a solução do problema:

Passo 1: Instalando e Carregando os Pacotes

Passo 2: Definindo o Problema de Negócio

Passo 3: Copiando o dataframe para dentro do banco de dados como uma tabela

Passo 4: Consultando o número de linhas da tabela, através da biblioteca sqlite3

Passo 5: Consultando o número de registros de pacientes com idade maior ou igual a 50 anos

Passo 6: Criando tabela para Pacientes

Passo 7: Inserindo registros para a tabela de Pacientes apenas com registros de Pacientes acima de 50 anos

Passo 8: Alterando tabela de pacientes, adicionando a coluna de Perfil

Passo 9: Inserindo registros na coluna de Perfil

Passo 10: Coluna de Perfil de Pacientes 'Normal' com BMI até 30 e com idade maior que  50 anos

Passo 11: Coluna de Perfil de Pacientes 'Obeso' com BMI maior ou igual a 30 e com idade maior que 50 anos

Passo 12: Tabela de Pacientes atualizada para futuras análises de diabetes

Passo 13: Carregando dados no Pandas 

Passo 14: Salvando Tabela de Pacientes em CSV

## Conclusão:
Criada tabela para diagnosticar se os pacientes desenvolveram ou não diabetes usando Sqlite3 e salvando em CSV.
