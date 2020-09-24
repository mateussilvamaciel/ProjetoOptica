# ProjetoOptica
Sistema para controle de estoque e gestão de uma óptica

obs: Esse é meu primeiro projeto, toda sugestão e melhorias para o código é bem-vinda.

A primeira parte do projeto foi pensar no designer dos formularios, e através de videos no youtube conseguir criar o menu principal. Estou em busca de um designer melhor para
o formulario de produtos, clientes e receita.

Vou trabalhar com o banco de dados Postgres por indicação de uma amigo. A modelagem do banco ainda estou fazendo. Neste caso vou ter entidades, que são: Produto, Cliente, Receita e
Laboratório.

O projeto será um programa que ira gerenciar uma óptica, desde da venda até o recebimento do produto vindo do laboratório. 

Passo-a-passo:
1- Cliente chega com a receita para comprar um óculos de acordo com sua necessidade.
2- A atendente fica com a receita e envia para para o laboratório com a armação do óculos.
3- o laboratório envia o óculos pronto.
4- O atendente liga para o cliente vim busca o seu óculos

Pontos importantes que devo automatizar: Controle de estoque dos produtos, manter o histórico de data e hora das receitas que são enviadas para o laboratório, manter os dados 
do cliente armazenados para o caso de novo pedido, controle de vendas.

Fazer o CRUD é a próxima tarefa antes da finalizção do banco de dados. Entender a mecânica da conexão entre o Postgres e o C# para logo depois de finalizada a modelagem, 
poder aplicar o banco corretamente.
