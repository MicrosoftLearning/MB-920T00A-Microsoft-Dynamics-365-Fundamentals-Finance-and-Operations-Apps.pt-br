---
lab:
  title: 'Laboratório 2: Criar uma ordem de compra'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Módulo 3: Conheça os Princípios básicos do Microsoft Dynamics 365 Supply Chain Management

## Laboratório 2: Criar uma ordem de compra

## Configuração do Laboratório

   - **Tempo estimado**: 15 minutos

## Objetivo

Neste laboratório, você ficará familiarizado com a interface do usuário e os diversos campos disponíveis no formulário de ordem de compra. Você também aprenderá a criar uma ordem de compra.


## Configuração do Laboratório

   - **Tempo estimado**: 10 minutos

## Instruções

1. Na página inicial Finanças e Operações, na parte superior direita, verifique se você está trabalhando com a empresa **USMF**. Se necessário, selecione a empresa e, no menu suspenso, clique em **USMF**.

2. No canto superior esquerdo, selecione o menu hambúrguer **Expandir o painel de navegação**.

3. Selecione **Módulos** > **Compras e suprimentos** > **Ordens de compra** > **Todas as ordens de compra**.

4. Na página **Todas as ordens de compra**, no menu superior, selecione **+ Novo**.

5. No painel **Criar ordem de compra**, clique no menu suspenso **Conta de fornecedor** e selecione **US-101**.

> [!NOTE]
> Observação: quando um fornecedor é selecionado, os detalhes do registro do fornecedor, como endereço, conta de faturamento, termos de entrega e modo de entrega, são copiados como valores padrão no cabeçalho do pedido. Esses valores podem ser alterados a qualquer momento.

6. Expanda a seção **Geral**, se necessário.

7. Em **DIMENSÕES DE ARMAZENAMENTO**, clique no menu suspenso **Local** e examine a lista de locais.

O campo **Local** e o campo **Armazém** especificam onde os bens ou serviços adquiridos precisam ser entregues. O endereço de entrega padrão é o local. Os dois campos podem ser preenchidos com valores configurados para o fornecedor selecionado ou você pode especificá-los manualmente.

8. Em **DATAS**, o campo **Data de entrega** é usado para especificar quando os bens e serviços adquiridos precisam ser entregues.

    Você pode especificar uma única data de entrega para a ordem ou as linhas de ordem individuais podem receber datas de entrega exclusivas. Se a data de entrega especificada aqui não puder ser atendida para produtos ou serviços específicos porque eles têm prazos de entrega mais longos, essas linhas serão criadas com uma data de entrega posterior para acomodar isso.

9. Expanda a seção **Administração**. A caixa do **Solicitante** pode ser usada para especificar quem está fazendo o pedido.

    Talvez seja conveniente compartilhar com o fornecedor caso ele precise contatar a pessoa. O valor pode ser atribuído automaticamente quando a conta de usuário atual está associada a um nome na página **Usuários**.

10. Selecione **OK**.

O cabeçalho da ordem foi criado. Quando você trabalha com linhas da ordem de compra, apenas um resumo das informações do cabeçalho é exibido. Se precisar exibir o restante das informações, selecione **Cabeçalho**.

![A captura de tela mostra o cabeçalho do pedido em que o resumo das informações do pedido é mostrado. A palavra Cabeçalho é realçada.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-17.png)

11. Em **Linhas de ordem de compra**, no menu, selecione **Linha de ordem de compra**.

![A captura de tela mostra as linhas da ordem de compra.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-18.png)

12. Em **Exibir**, selecione **Dimensões**.

    Os produtos podem estar em variantes diferenciadas por dimensões, como cor, tamanho ou estilo. Os produtos também podem ser configurados para usar dimensões de armazenamento, como local e depósito. Também existem dimensões de rastreamento opcionais, como os números de lote e de série. Para aprimorar a eficiência da entrada de ordem, você pode adicionar os campos de dimensão que costuma usar diretamente à grade da ordem.

13. No painel **Exibição de dimensões**, em **DIMENSÕES DO PRODUTO**, marque a caixa de seleção **Cor**.

Opcional: ao pressionar o botão de alternância **Salvar configuração**, as dimensões escolhidas também serão mostradas na grade da linha do pedido na próxima vez em que a página da ordem de compra for aberta.

14. Selecione **OK**.

15. Clique no menu suspenso da célula **Número do item** e selecione **T0004**.

Lembre-se de que você também pode digitar na caixa de filtro em vez de rolar pela lista.

As linhas da ordem são criadas para produtos e serviços especificando um número de item ou como despesas especificando uma categoria de compras.

A categoria de compras é usada para adicionar linhas em que os itens comprados são gastos diretamente, em vez de entrar no estoque. Se precisar fazer uma compra, você poderá fazer isso criando uma linha de ordem de compra que especifique uma categoria de compra, em vez de criar uma linha com um número de item. Os itens também podem ser associados a uma categoria de compras e, nesse caso, a categoria de compras é mostrada somente como informativa.

16. Clique no menu suspenso **Cor**, examine as opções disponíveis e selecione uma das cores ou combinações de cores.

17. Normalmente, **Local** e **Armazém** são preenchidos com os valores do cabeçalho do pedido, mas é possível substituir os campos para entregar algumas linhas a locais diferentes.

18. Na caixa **Quantidade**, digite **10**.

    A **Quantidade** é preenchida automaticamente com a quantidade mínima de pedido do produto, quando configurada, ou com o valor **1**.

19. Algumas informações adicionais:

- **Unidade**: indica a unidade de medida para a quantidade pedida. Normalmente, a unidade é fornecida automaticamente da unidade de compra nos dados do produto mestre.

- **Preço unitário**: contém um valor oriundo de um contrato de compra ou de um acordo comercial. É possível alterar o preço unitário nas linhas de ordem individuais, por exemplo, se um preço exclusivo é negociado com o fornecedor.

- **Desconto**: representa uma quantia com desconto por unidade. Esse desconto, portanto, reduz o preço unitário pelo desconto. Em geral, esse desconto é fornecido automaticamente de contratos de compra ou contratos comerciais, mas é possível substituir em linhas individuais se os descontos exclusivos tiverem sido negociados com o fornecedor.

- **Percentual de desconto**: quando informado, reduz a quantia líquida da linha respectiva. A porcentagem de desconto geralmente é fornecida automaticamente de contratos de compra ou contratos comerciais, mas é possível substituir em linhas individuais se uma porcentagem de desconto exclusiva tiver sido negociada com o fornecedor.

- **Valor líquido**: calculado a partir de outros campos na linha, incluindo a quantidade, o preço unitário, o desconto e a porcentagem de desconto. É possível alterar o valor líquido, mas os campos Preço Unitário, Desconto e Porcentagem de desconto ficam em branco. Quando você lançar na linha, o valor lançado será proporcional ao valor líquido. O campo Valor Líquido é usado somente para exibir o valor líquido da linha.

20. Nas linhas de ordem de compra, na parte inferior da página, selecione **Detalhes da linha**.

21. Selecione a guia **Entrega**.

    Uma data de entrega exclusiva pode ser atribuída a cada linha da ordem. A data é herdada do campo no cabeçalho da ordem de compra, mas você pode alterar isso.

22. Feche a página **Linha de ordem de compra**.

23. Na página **Todas as ordens de compra**, use o recurso de Filtro e localize a nova ordem de compra.

24. Ao concluir, feche a página **Todas as ordens de compra** e retorne à página inicial.

