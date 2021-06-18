1. Crie as seguintes tabelas:
    • Animal: id, nome, raca (nome não pode ser nulo e a raça é
    chave estrangeira da tabela especie).
    • Especie: id, nome (nome não pode ser nulo).
    • Dono: id, nome, cpf, fone (cpf não repetir e nome não pode
    ser nulo).
file: Atividade_21_06_2021_Migration_v0_.sql

2. A partir das tabelas criadas, efetue as seguintes
    alterações nelas:
    • Altere 'Animal' adicionando a coluna dono como chave
    estrangeira.
    • Altere a tabela chamada 'Espécie' para 'raça'.
    • Altere a expressão 'Dono' para 'Tutor'.
file: Atividade_21_06_2021_Migration_v1_.sql

3. Adicionar registros nas tabelas Animal, Dono e Raça conforme slide.
file: Atividade_21_06_2021_Seed_v0_.sql

4. A partir das tabelas criadas, efetue as seguintes
    alterações nos registros:
    • Altere o nome do cachorro 'Brutus' para 'Rex’.
    • Excluir o cachorro com nome 'toto' que seja da raça
    'poodle’.
    • Alterar o dono da cachorra 'Lica' para o dono 'Maria'.
file: Atividade_21_06_2021_Seed_v1_.sql  

5. Adicione a seguinte tabela ao esquema:
    • Consulta: id, data, animal
file: Atividade_21_06_2021_Migration_v2_.sql

6. Altere a tabela 'consulta' modificando o campo
    'data'. Esse campo deve ser do tipo 'timestamp'.
file: Atividade_21_06_2021_Migration_v3_.sql

7. Adicionar registros na tabela Consulta
file: Atividade_21_06_2021_Seed_v2_.sql  

8. A partir da criação da tabela 'consulta', efetue as seguintes manipulações nos registros:
    • Excluir a consulta do dia '12/01/07' para o animal de 'id'
    igual 1.
    • Alterar a data da consulta do animal de 'id' igual 3, de
    '12/01/07' para '13/01/07'
file: Atividade_21_06_2021_Seed_v3_.sql  