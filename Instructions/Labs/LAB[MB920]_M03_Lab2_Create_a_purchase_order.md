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

Neste laboratório, você se familiarizará com a interface do usuário e os diferentes campos disponíveis no formulário de ordem de compra. Você também aprenderá a criar uma ordem de compra.


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

O campo **Local** e o campo **Armazém** especificam onde os bens ou serviços adquiridos precisam ser entregues. O endereço de entrega padrão é o local.  Ambos os campos podem ser preenchidos com os valores configurados para o fornecedor selecionado ou você pode especificá-los manualmente.

8. Em **DATAS**, o campo **Data de entrega** é usado para especificar quando os bens e serviços adquiridos precisam ser entregues.

    Você pode especificar uma única data de entrega para o pedido ou as linhas de pedido individuais podem receber datas de entrega exclusivas. Se a data de entrega especificada aqui não puder ser atendida para produtos ou serviços específicos porque eles têm prazos de entrega mais longos, essas linhas serão criadas com uma data de entrega posterior.

9. Expanda a seção **Administração**. A caixa do **Solicitante** pode ser usada para especificar quem está fazendo o pedido.

    Convém compartilhar isso com o fornecedor, caso ele precise entrar em contato com essa pessoa. O valor pode ser atribuído automaticamente quando a conta de usuário atual está associada a um nome na página **Usuários**.

10. Selecione **OK**.

O cabeçalho do pedido foi criado. Quando você trabalha com linhas de pedido de compra, apenas um resumo das informações do cabeçalho é mostrado. Se precisar exibir o restante das informações, selecione **Cabeçalho**.

![A captura de tela mostra o cabeçalho do pedido em que o resumo das informações do pedido é mostrado. A palavra Cabeçalho é realçada.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-17.png)

11. Em **Linhas de ordem de compra**, no menu, selecione **Linha de ordem de compra**.

![A captura de tela mostra as linhas de ordem de compra.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-18.png)

12. Em **Exibir**, selecione **Dimensões**.

    Os produtos podem ter modelos que variam por dimensões, cor, tamanho ou estilo. Os produtos também podem ser configurados para usar as dimensões de armazenamento, como o local e o depósito.  Também há dimensões de acompanhamento opcionais, como o lote e os números de série.  Para melhorar a eficiência da entrada de pedidos, você pode adicionar os campos de dimensão que costuma usar diretamente à grade do pedido.

13.  No painel **Exibição de dimensões**, em **DIMENSÕES DO PRODUTO**, marque a caixa de seleção **Cor**.

Opcional: ao pressionar o botão de alternância **Salvar configuração**, as dimensões escolhidas também serão mostradas na grade da linha do pedido na próxima vez em que a página da ordem de compra for aberta.

14. Selecione **OK**.

15. Clique no menu suspenso da célula **Número do item** e selecione **T0004**.

Lembre-se de que você também pode digitar na caixa de filtro em vez de rolar pela lista.

As linhas de pedido são criadas para produtos e serviços especificando um número de item ou como despesas especificando uma categoria de compras.

A categoria de compras é usada para adicionar linhas em que os itens adquiridos são custeados diretamente, em vez de entrar no estoque. Isso significa que, se você precisar fazer uma compra, poderá fazer isso criando uma linha de ordem de compra que especifica uma categoria de aquisição, em vez de criar uma linha com um número de item. Os itens também podem ser associados a uma categoria de compras e, nesse caso, a categoria de compras é mostrada apenas como informativa.

16. Clique no menu suspenso **Cor**, examine as opções disponíveis e selecione uma das cores ou combinações de cores.

17. Normalmente, **Local** e **Armazém** são preenchidos com os valores do cabeçalho do pedido, mas é possível substituir os campos para entregar algumas linhas a locais diferentes.

18. Na caixa **Quantidade**, digite **10**.

    A **Quantidade** é preenchida automaticamente com a quantidade mínima de pedido do produto, quando configurada, ou com o valor **1**.

19. Algumas informações adicionais:

- **Unidade**: indica a unidade de medida para a quantidade pedida. Normalmente, a unidade é fornecida automaticamente na unidade de compra nos dados mestre do produto.

- **Preço unitário**: contém um valor oriundo de um contrato de compra ou de um acordo comercial. É possível alterar o preço unitário em linhas de pedido individuais. Por exemplo, se um preço diferenciado for negociado com o fornecedor.

- **Desconto**: representa uma quantia com desconto por unidade. Sendo assim, esse desconto reduz o preço unitário pelo desconto. Esse desconto é normalmente fornecido automaticamente nos contratos de compra ou acordos comerciais, mas é possível substituir em linhas individuais se descontos diferenciados tiverem sido negociados com o fornecedor.

- **Percentual de desconto**: quando informado, reduz a quantia líquida da linha respectiva. O percentual de desconto é geralmente fornecido automaticamente a partir de contratos de compra ou acordos comerciais, mas é possível substituir em linhas individuais se uma porcentagem de desconto diferenciada tiver sido negociada com o fornecedor.

- **Valor líquido**: calculado a partir de outros campos na linha, incluindo a quantidade, o preço unitário, o desconto e a porcentagem de desconto. É possível alterar o valor líquido, mas os campos Preço Unitário, Desconto e Percentual de desconto estão em branco. Quando você postar em direção à linha, o valor postado será proporcional ao valor líquido. O campo “Valor líquido” é usado apenas para exibir o valor líquido da linha.

20. Nas linhas de ordem de compra, na parte inferior da página, selecione **Detalhes da linha**.

21. Selecione a guia **Entrega**.

    É possível atribuir uma data de entrega exclusiva para cada linha de pedido. A data é herdada do campo no cabeçalho da ordem de compra, mas isso pode ser alterado.

22. Feche a página **Linha de ordem de compra**.

23. Na página **Todas as ordens de compra**, use o recurso de Filtro e localize a nova ordem de compra.

24. Ao concluir, feche a página **Todas as ordens de compra** e retorne à página inicial.

