# Análise do risco de inadimplência dos mutuários
Sou aluno da TripleTen no curso de Ciência de Dados, estou divulgando projetos que desenvolvi para meu portifólio. Este é o segundo projeto.

Neste projeto prepararei um relatório para a divisão de empréstimos de um banco. Descobri se o estado civil de um cliente e o número de filhos têm impacto sobre a inadimplência de um empréstimo. O banco já tem alguns dados sobre a capacidade de crédito dos clientes.
Devo criar uma pontuação de crédito de um cliente em potencial. Uma pontuação de crédito é usada para avaliar a capacidade de um devedor em potencial de pagar seu empréstimo.

**Perguntas Respondidas no Projeto**
1. Existe alguma relação entre ter filhos e pagar um empréstimo em dia?
2. Existe alguma relação entre o estado civil e o pagamento de um empréstimo no prazo estipulado?
3. Existe uma relação entre o nível de renda e o pagamento de um empréstimo no prazo?
4. Como as diferentes finalidades do empréstimo afetam o pagamento pontual do empréstimo?

**Descrição das Colunas**
* children : o número de crianças na família
* days_employed : quanto tempo o cliente trabalhou
* dob_years : a idade do cliente
* education : o nível de educação do cliente
* education_id : identificador da educação do cliente
* family_status : estado civil do cliente
* family_status_id : identificador do estado civil do cliente
* gender : o sexo do cliente
* income_type : o tipo de renda do cliente
* debt : se o cliente já deixou de pagar um empréstimo
* total_income : renda mensal
* purpose : motivo para fazer um empréstimo

**Conclusões** 

Depois de analisar os dados, conclui que:

1. Ter filhos não parece ser um fator que aumente a taxa de inadimplência, pois mesmo que tenha aumentado 2% de 0 filhos para 1, é pouco e com 3 filhos a taxa cai, ficando similar a 0 filhos.
2. Parece que pessoas que não passaram por um casamento com outra pessoa tem mais tendência a ser inadimplente, mesmo com união civil tendem a ser mais.
3. O grupo de renda da pessoa também parece não influenciar muito, porém os mais rico tem menor a taxa, seguidos pelos mais pobres. Fazendo com que os grupos do 'meio' sejam os mais inadimplentes.
4. O motivo pelo crédito não é conclusivo, e sim algo pessoal.

**Conclusão Geral**

Pessoas mais ricas que ja passaram ou estão em um casamento com nenhum filho ou mais de dois tendem a pagar mais seus empréstimos.
