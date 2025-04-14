>[!NOTE]
>Projeto desenvolvido como parte das atividades da NI da matéria de **Programação Mobile** do terceiro semestre do curso de Análise e Desenvolvimento de Sistemas.

# Questão 4 - NI

<details>
  <summary>Enunciado</summary>
  
Desenvolvimento de App Android para o Registro de Pedidos de uma Lanchonete **(Lanche Fácil)**. A lanchonete Lanche Fácil, cujo domínio é *www.lanchefacil.com.br*, deseja criar um aplicativo para registro de pedidos de clientes em eventos e lojas físicas. O aplicativo será utilizado para capturar o pedido básico do cliente, permitindo que ele selecione o `tipo de lanche` e insira o `nome` para o pedido. Após o registro, o cliente visualizará seu pedido e nome, com a possibilidade de retornar à tela inicial para fazer novos pedidos. O fluxo de navegação será:
  
- **Activity 1** *(Tela de Boas-Vindas)*: Uma tela inicial com a logomarca da lanchonete e um botão que levará o cliente para o registro do pedido.
- **Activity 2** *(Formulário de Pedido)*: Tela onde o cliente seleciona o tipo de lanche através de botões ou uma lista e insere seu nome utilizando um campo de texto. Ao clicar no botão de confirmação, o app redireciona para a tela de resumo.
- **Activity 3** *(Resumo do Pedido)*: Exibe o nome do cliente e o lanche escolhido em um TextView. Há também uma imagem decorativa e um botão para voltar à tela inicial.
  
## REQUISITO DO PROJETO:

- **Navegação entre Activities:** O aplicativo deve conter *3 activities* com navegação via botões. A primeira activity exibe a logomarca da lanchonete e o botão para iniciar o pedido. A segunda activity permite selecionar o lanche e inserir o nome. A terceira activity exibe o resumo do pedido.
- **Formulário com TextInputLayout:** A segunda activity deve conter um campo de texto para o cliente inserir seu nome e botões para escolher o lanche desejado.
- **Exibição de Texto Dinâmico:** A terceira activity deve exibir o nome do cliente e o lanche escolhido utilizando um TextView dinâmico.
- **Uso de ImageView:**
  - *Activity 1:* Imagem da logomarca da lanchonete.
  - *Activity 2:* Uma imagem ilustrativa relacionada ao cardápio de lanches.
  - *Activity 3:* Uma imagem decorativa de "Pedido Concluído".
- **Botão de Retorno:** A terceira activity deve conter um botão para retornar à primeira activity, permitindo que novos pedidos sejam feitos.

</details>


## 👤Informações: 

- **Nome:** Felipe Oluwaseun Santos Ojo
- **RA:** 24026245
- **Disciplina:** Programação Mobile


## Clonando o repositório:

Para ter acesso ao repositório na sua máquina, basta digitar o seguinte comando dentro do **terminal**:

```
git clone https://github.com/lipeoe/QuestaoQuatroNI
```

