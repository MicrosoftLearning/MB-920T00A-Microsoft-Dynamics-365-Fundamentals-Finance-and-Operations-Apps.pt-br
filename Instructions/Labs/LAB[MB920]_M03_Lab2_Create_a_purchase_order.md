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

É mais comum que ordens de compra sejam criadas automaticamente como resultado de um planejamento mestre, entrega direta e outros processos. Quando criada manualmente, uma ordem de compra geralmente é criada por um agente de compra. Crie uma ordem de compra usando a empresa USMF. 

## Configuração do Laboratório

   - **Tempo estimado**: 10 minutos

## Instruções

1.  Na página inicial **Finanças e Operações**, na parte superior direita, verifique se você está trabalhando com a empresa **USMF**. 

1.  Se necessário, selecione a empresa e, no menu, selecione **USMF**. 

1.  No canto superior esquerdo, selecione o menu hambúrguer **Expandir o painel de navegação**. 

1.  No módulo **Aquisição e abastecimento**, selecione **Ordens de compra** > **Todas as ordens de compra**. 

1.  Na página **Todas as ordens de compra**, no painel de ações, selecione **+ Novo**. 

1.  No painel **Criar ordem de compra**, selecione o campo **Conta do fornecedor** e insira ou selecione `US-101`

1.  Quando um fornecedor é selecionado, os detalhes do registro do fornecedor, como endereço, conta de faturamento, termos de entrega e modo de entrega, serão copiados como valores padrão no cabeçalho da ordem de compra. Você pode alterar esses valores, se necessário. 

1.  Expanda a seção **Geral**. 

1.  Em **DIMENSÕES DE ARMAZENAMENTO**, selecione o menu **Local** e examine a lista de locais. 

    > **Nota:** o campo **Local** e o campo **Depósito** especificam onde os bens ou serviços adquiridos devem ser entregues. O endereço de entrega padrão é retirado do **Local**. Ambos os campos podem ser preenchidos com os valores configurados para o fornecedor selecionado ou você pode especificá-los manualmente. 

1.  Para **Depósito**, insira ou selecione `13`

1.  Em **DATAS**, o campo **Data de entrega** é usado para especificar quando os bens e serviços adquiridos precisam ser entregues.

    > **Nota:** você pode especificar uma única data de entrega para o pedido ou as linhas de pedido individuais podem receber datas de entrega exclusivas. Se a data de entrega especificada aqui não puder ser atendida para produtos ou serviços específicos porque eles têm prazos de entrega mais longos, essas linhas serão criadas com uma data de entrega posterior para dar conta disso.

1.  Expanda a seção **Administração**. O campo **Solicitante** pode ser usado para especificar quem está fazendo o pedido. 

    > **Note:** convém compartilhar isso com o fornecedor, caso ele precise entrar em contato com essa pessoa. O valor pode ser atribuído automaticamente quando a conta de usuário atual está associada a um registro de **Pessoa** na página **Usuários**. 

1.  Selecione **OK**. 

1.  O cabeçalho do pedido foi criado. Quando você trabalha com linhas de pedido de compra, apenas um resumo das informações do cabeçalho é mostrado.  Se precisar exibir o restante das informações, selecione a guia **Cabeçalho**. 

    ![Imagem da tela exibindo o local do menu Cabeçalho](./media/lp1-m3-purchase-order-header-option.png)

1.  Em **Linhas de ordem de compra**, na barra de ferramentas, selecione o menu **Linha de ordem de compra**. 

    ![Imagem da tela mostrando o local da opção do menu da linha da ordem de compra](./media/lp1-m3-purchase-order-purchase-order-line-menu.png)

1.  Em **Exibir**, selecione **Dimensões**. 

    > **Nota:** os produtos podem ter modelos que variam por dimensão, cor, tamanho ou estilo. Os produtos também podem ser configurados para usar as dimensões de armazenamento, como o local e o depósito.  Também há dimensões de acompanhamento opcionais, como o lote e os números de série.  Para melhorar a eficiência da entrada de pedidos, você pode adicionar os campos de dimensão que costuma usar diretamente à grade do pedido. 

1.  No painel **Exibição de dimensões**, em **DIMENSÕES DO PRODUTO**, selecione **Cor**. 

1.  *Opcional:* ao pressionar o botão de alternância **Salvar configuração**, as dimensões escolhidas também serão mostradas na grade da linha do pedido na próxima vez em que a página da ordem de compra for aberta. 

1.  Selecione **OK**. 

1.  Em **Linhas de ordem de compra**, selecione o campo **Número do item** e selecione **T0004**. 

    > **Nota:** lembre-se de que você também pode inserir `T0004` no **filtro** em vez de rolar pela lista. 

    > **Nota:** as linhas de pedido são criadas para produtos e serviços especificando um **número de item** ou como despesas especificando uma **Categoria de aquisição**.
    > 
    > A **categoria de aquisição** é usada para adicionar linhas em que os itens adquiridos são custeados diretamente, em vez de entrar no inventário. Isso significa que, se você precisar custear uma compra, poderá fazer isso criando uma linha de ordem de compra que especifica uma **Categoria de aquisição**, em vez de criar uma linha com um **número de item**. Os itens também podem ser associados a uma categoria de compras e, nesse caso, a categoria de compras é mostrada apenas como informativa. 

1.  Selecione o menu **Cor**, examine as opções disponíveis e selecione uma das cores ou combinações de cores. 

    > **Nota:** **Local** e **Depósito** são normalmente preenchidos com valores do cabeçalho a ordem de compra, mas será possível substituir os campos se algumas linhas precisarem ser entregues em locais diferentes. 

1.  No campo **Quantidade**, insira `10` 

    > **Nota:** a **Quantidade** é preenchida automaticamente com a **quantidade mínima de pedido** do **produto**, quando configurada, ou com um valor de **1**. 

    > **Nota:** outros campos de detalhes de linha disponíveis: 
    >
    >    - **Unidade**: indica a unidade de medida para a quantidade pedida. Normalmente, a unidade é fornecida automaticamente na unidade de compra nos dados mestre do produto. 
    >
    >    - **Preço unitário**: contém um valor oriundo de um contrato de compra ou de um acordo comercial. É possível alterar o preço unitário em linhas de pedido individuais. Por exemplo, se um preço diferenciado for negociado com o fornecedor. 
    >
    >    - **Desconto**: representa uma quantia com desconto por unidade. Sendo assim, esse desconto reduz o preço unitário pelo desconto. Esse desconto é normalmente fornecido automaticamente nos contratos de compra ou acordos comerciais, mas é possível substituir em linhas individuais se descontos diferenciados tiverem sido negociados com o fornecedor. 
    >
    >    - **Percentual de desconto**: quando informado, reduz a quantia líquida da linha respectiva. A porcentagem de desconto é geralmente fornecida automaticamente a partir de contratos de compra ou acordos comerciais, mas é possível substituir em linhas individuais se uma porcentagem de desconto diferenciada tiver sido negociada com o fornecedor. 
    >
    >    - **Valor líquido**: calculado a partir de outros campos na linha, incluindo a quantidade, o preço unitário, o desconto e a porcentagem de desconto. É possível alterar o Valor líquido, mas os campos Preço unitário, Desconto e Porcentagem de desconto ficarão em branco e, quando você lançar na linha, a quantidade lançada será proporcional ao valor líquido. Em geral, o campo Valor líquido é usado apenas para exibir o valor líquido da linha. 

1.  Na FastTab **Detalhes de linha**, expanda se necessário e selecione a guia **Entrega**. 

    > **Nota:** é possível atribuir uma **Data de entrega** exclusiva para cada linha de pedido. A data é herdada do campo **Data de entrega** no cabeçalho da ordem de compra, mas isso pode ser alterado aqui. 

1.  Anote o **número da ordem de compra** e **feche** a página. 

1.  Na exibição de lista **Todas as ordens de compra**, use o **Filtro** para encontrar sua nova ordem de compra. 

1.  Ao concluir, **feche** a página **Todas as ordens de compra** e retorne à Página inicial. 

