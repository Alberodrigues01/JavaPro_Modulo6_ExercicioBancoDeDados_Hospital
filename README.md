# JavaPro_Modulo6_ExercicioBancoDeDados_Hospital
Mentorama_JavaPro, exercício do Módulo 6 para a criação de um banco de dados de um hospital
O exercício utilizou o Database PostgreSQL em conjunto com o SQL Client DBeaver
O exercício envolve a criação de três tabelas representando entidades de um hospital: pacientes, profissionais e histórico de internações.
A tabela de pacientes tem como chave primária o id do paciente, a tabela de profissionais a matrícula do mesmo e a tabela de internações possuem duas chaves primárias
(id internação e id paciente) e como chave estrangeira a matrícula do profssional responsável pela internação.
Após a criação das tabelas é feito a inserção de conteúdos nas tabelas obedecendo o tipo de cada campo da tabela em questão.
Foram criadas duas consultas. A primeira apresenta a quantidade de internações de cada paciente em ordem decrescente de quantidade. A segunda consulta apresenta a 
quantidade de médicos (cargo 'médico') por departamento do hospital.
