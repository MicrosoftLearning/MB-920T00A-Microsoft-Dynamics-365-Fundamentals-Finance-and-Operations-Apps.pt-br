---
lab:
  title: 'Laboratório 2: Criar uma ordem de compra'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>Módulo 3: Conheça os Princípios básicos do Microsoft Dynamics 365 Supply Chain Management

## <a name="lab-2---create-a-purchase-order"></a>Laboratório 2: Criar uma ordem de compra

## <a name="objectives"></a>Objetivos

É mais comum que ordens de compra sejam criadas automaticamente como resultado de um planejamento mestre, entrega direta e outros processos. Quando criada manualmente, uma ordem de compra geralmente é criada por um agente de compra. Crie uma ordem de compra usando a empresa USMF.

## <a name="lab-setup"></a>Configuração do Laboratório

   - **Tempo estimado**: 10 minutos

## <a name="instructions"></a>Instruções

1. Na home page do Finance and Operations, na parte superior direita, verifique se você está trabalhando com a empresa USMF.

1. Se necessário, selecione a empresa e, no menu, selecione **USMF**.

1. No canto superior esquerdo, selecione o menu hambúrguer **Expandir o painel de navegação**.

1. Selecione **Módulos** > **Compras e suprimentos** > **Ordens de compra** > **Todas as ordens de compra**.

1. Na página Todas as ordens de compra, no menu superior, selecione **+ Novo**.

1. No painel Criar ordem de compra, selecione o menu **Conta do fornecedor** e selecione **US-101**.

1. Quando um fornecedor é selecionado, os detalhes do registro do fornecedor, como endereço, conta de faturamento, termos de entrega e modo de entrega, serão copiados como valores padrão no cabeçalho do pedido. Esses valores podem ser alterados a qualquer momento.

1. Expanda a seção **Geral**.

1. Em **DIMENSÕES DE ARMAZENAMENTO**, selecione o menu **Local** e examine a lista de locais.

1. O campo Local, junto com o campo Depósito, especifica onde os bens ou serviços adquiridos devem ser entregues. O endereço de entrega padrão é o local. Ambos os campos podem ser preenchidos com os valores configurados para o fornecedor selecionado ou você pode especificá-los manualmente.

1. Em **DATAS**, o campo Data de entrega é usado para especificar quando produtos e serviços adquiridos precisam ser entregues.

1. Você pode especificar uma única data de entrega para o pedido ou as linhas de pedido individuais podem receber datas de entrega exclusivas. Se a data de entrega especificada aqui não puder ser atendida para produtos ou serviços específicos porque eles têm prazos de entrega mais longos, essas linhas serão criadas com uma data de entrega posterior para dar conta disso.

1. Expanda a seção **Administração**. A caixa do **Solicitante** pode ser usada para especificar quem está fazendo o pedido.

1. Convém compartilhar isso com o fornecedor, caso ele precise entrar em contato com essa pessoa. O valor pode ser atribuído automaticamente se a conta de usuário atual estiver associada a um nome na página Usuários.

1. Selecione **OK**.

1. O cabeçalho do pedido foi criado. Quando você trabalha com linhas de pedido de compra, apenas um resumo das informações do cabeçalho é mostrado. Se precisar exibir o restante das informações, selecione **Cabeçalho**.

    ![Imagem da tela exibindo o local do menu Cabeçalho](./media/lp1-m3-purchase-order-header-option.png)

1. Em **Linhas de ordem de compra**, no menu, selecione **Linha de ordem de compra**.

    ![Imagem da tela mostrando o local da opção do menu da linha da ordem de compra](./media/lp1-m3-purchase-order-purchase-order-line-menu.png)

1. Em **Exibir**, selecione **Dimensões**.

1. Os produtos podem ter modelos que variam por dimensões, cor, tamanho ou estilo. Os produtos também podem ser configurados para usar as dimensões de armazenamento, como o local e o depósito. Também há dimensões de acompanhamento opcionais, como o lote e os números de série. Para melhorar a eficiência da entrada de pedidos, você pode adicionar os campos de dimensão que costuma usar diretamente à grade do pedido.

1. No painel de exibição Dimensões, em **DIMENSÕES DO PRODUTO**, marque a caixa de seleção **Cor**.

1. Opcional: se você selecionar o botão de alternância Salvar configuração, as dimensões escolhidas também serão mostradas na grade da linha do pedido na próxima vez que abrir a página ordem de compra.

1. Selecione **OK**.

1. Selecione o menu de célula **Número do item** e depois **T0004**.

1. Lembre-se de que você também pode digitar na caixa de filtro em vez de rolar pela lista.

1. As linhas de pedido são criadas para produtos e serviços especificando um número de item ou como despesas especificando uma categoria de compras.

1. A categoria de compras é usada para adicionar linhas em que os itens adquiridos são custeados diretamente, em vez de entrar no estoque. Isso significa que se você precisar custear uma compra, isso pode ser feito criando uma linha de ordem de compra que especifica uma categoria de compras, em vez de criar uma linha com um número de item. Os itens também podem ser associados a uma categoria de compras e, nesse caso, a categoria de compras é mostrada apenas como informativa.

1. Selecione o menu **Cor**, examine as opções disponíveis e selecione uma das cores ou combinações de cores.

1. O local e o depósito são normalmente preenchidos com valores do cabeçalho do pedido, mas é possível substituir os campos se algumas linhas precisarem ser entregues a locais diferentes.

1. Na caixa **Quantidade**, digite **10**.

1. A Quantidade é preenchida automaticamente com a quantidade mínima de pedido do produto se estiver configurada ou com o valor de 1.

1. Algumas informações adicionais:

    - **Unidade**: indica a unidade de medida para a quantidade pedida. Normalmente, a unidade é fornecida automaticamente na unidade de compra nos dados mestre do produto.

    - **Preço unitário**: contém um valor oriundo de um contrato de compra ou de um acordo comercial. É possível alterar o preço unitário em linhas de pedido individuais. Por exemplo, se um preço diferenciado for negociado com o fornecedor.

    - **Desconto**: representa uma quantia com desconto por unidade. Sendo assim, esse desconto reduz o preço unitário pelo desconto. Esse desconto é normalmente fornecido automaticamente nos contratos de compra ou acordos comerciais, mas é possível substituir em linhas individuais se descontos diferenciados tiverem sido negociados com o fornecedor.

    - **Percentual de desconto**: quando informado, reduz a quantia líquida da linha respectiva. A porcentagem de desconto é geralmente fornecida automaticamente a partir de contratos de compra ou acordos comerciais, mas é possível substituir em linhas individuais se uma porcentagem de desconto diferenciada tiver sido negociada com o fornecedor.

    - **Valor líquido**: calculado a partir de outros campos na linha, incluindo a quantidade, o preço unitário, o desconto e a porcentagem de desconto. É possível alterar o Valor líquido, mas os campos Preço unitário, Desconto e Porcentagem de desconto ficarão em branco e, quando você lançar na linha, a quantidade lançada será proporcional ao valor líquido. Em geral, o campo Valor líquido é usado apenas para exibir o valor líquido da linha.

1. Nas linhas de ordem de compra, na parte inferior da página, selecione **Detalhes da linha**.

1. Selecione a guia **Entrega**.

1. É possível atribuir uma data de entrega exclusiva para cada linha de pedido. A data é herdada do campo no cabeçalho da ordem de compra, mas isso pode ser alterado.

1. Feche a página de linha da ordem de compra.

1. Na página Todas as ordens de compra, use o recurso de Filtro e localize sua nova ordem de compra.

1. Ao concluir, feche a página Todas as ordens de compra e retorne à Página inicial.
