---
lab:
  title: 'Laboratório 2: Criar uma ordem de compra'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>Módulo 3: Conheça os Princípios básicos do Microsoft Dynamics 365 Supply Chain Management

## <a name="lab-2---create-a-purchase-order"></a>Laboratório 2: Criar uma ordem de compra

## <a name="objectives"></a>Objetivos

It's more typical for purchase orders to be created automatically as result of master planning, direct delivery, and other processes. When created manually, a purchase order is usually created by a purchasing agent. Create a purchase order using the the USMF company.

## <a name="lab-setup"></a>Configuração do Laboratório

   - **Tempo estimado**: 10 minutos

## <a name="instructions"></a>Instruções

1. Na home page do Finance and Operations, na parte superior direita, verifique se você está trabalhando com a empresa USMF.

1. Se necessário, selecione a empresa e, no menu, selecione **USMF**.

1. No canto superior esquerdo, selecione o menu hambúrguer **Expandir o painel de navegação**.

1. Selecione **Módulos** > **Compras e suprimentos** > **Ordens de compra** > **Todas as ordens de compra**.

1. Na página Todas as ordens de compra, no menu superior, selecione **+ Novo**.

1. No painel Criar ordem de compra, selecione o menu **Conta do fornecedor** e selecione **US-101**.

1. When you select a vendor, details from the vendor record, such as address, invoice account, delivery terms, and delivery mode, will be copied as default values into the order header. You can change these values at any time.

1. Expanda a seção **Geral**.

1. Em **DIMENSÕES DE ARMAZENAMENTO**, selecione o menu **Local** e examine a lista de locais.

1. The Site field, together with the Warehouse field, specifies where the procured goods or services must be delivered. The default delivery address is the site. Both fields can be populated with values set up for the selected vendor, or you can specify them manually.

1. Em **DATAS**, o campo Data de entrega é usado para especificar quando produtos e serviços adquiridos precisam ser entregues.

1. You can specify a single delivery date for the order, or the individual order lines can be given unique delivery dates. If the delivery date specified here cannot be met for specific products or services because they have longer lead times, then those lines will be created with a later delivery date to accommodate for this.

1. Expand the <bpt id="p1">**</bpt>Administration<ept id="p1">**</ept> section. The <bpt id="p1">**</bpt>Orderer<ept id="p1">**</ept> box can be used to specify who is placing the order.

1. É mais comum que ordens de compra sejam criadas automaticamente como resultado de um planejamento mestre, entrega direta e outros processos.

1. Selecione **OK**.

1. Quando criada manualmente, uma ordem de compra geralmente é criada por um agente de compra.

    ![Imagem da tela exibindo o local do menu Cabeçalho](./media/lp1-m3-purchase-order-header-option.png)

1. Em **Linhas de ordem de compra**, no menu, selecione **Linha de ordem de compra**.

    ![Imagem da tela mostrando o local da opção do menu da linha da ordem de compra](./media/lp1-m3-purchase-order-purchase-order-line-menu.png)

1. Em **Exibir**, selecione **Dimensões**.

1. Crie uma ordem de compra usando a empresa USMF.

1. No painel de exibição Dimensões, em **DIMENSÕES DO PRODUTO**, marque a caixa de seleção **Cor**.

1. Opcional: se você selecionar o botão de alternância Salvar configuração, as dimensões escolhidas também serão mostradas na grade da linha do pedido na próxima vez que abrir a página ordem de compra.

1. Selecione **OK**.

1. Selecione o menu de célula **Número do item** e depois **T0004**.

1. Lembre-se de que você também pode digitar na caixa de filtro em vez de rolar pela lista.

1. As linhas de pedido são criadas para produtos e serviços especificando um número de item ou como despesas especificando uma categoria de compras.

1. Procurement category is used for adding lines where procured items are expensed directly, rather than going into inventory. This means that if you need to expense a purchase, you can do this by creating a purchase order line that specifies a procurement category, rather than creating a line with an item number. Items can also be associated with a procurement category and in this case, the procurement category is shown as informational only.

1. Selecione o menu **Cor**, examine as opções disponíveis e selecione uma das cores ou combinações de cores.

1. O local e o depósito são normalmente preenchidos com valores do cabeçalho do pedido, mas é possível substituir os campos se algumas linhas precisarem ser entregues a locais diferentes.

1. Na caixa **Quantidade**, digite **10**.

1. A Quantidade é preenchida automaticamente com a quantidade mínima de pedido do produto se estiver configurada ou com o valor de 1.

1. Algumas informações adicionais:

    - <bpt id="p1">**</bpt>Unit<ept id="p1">**</ept>: Indicates the unit of measure for the ordered quantity. Normally, the unit is automatically provided from the purchasing unit on the product master data.

    - <bpt id="p1">**</bpt>Unit price<ept id="p1">**</ept>: Contains a value from either a purchase agreement or a trade agreement. It is possible to change the unit price on individual order lines—for example, if a unique price is negotiated with the vendor.

    - <bpt id="p1">**</bpt>Discount<ept id="p1">**</ept>: Represents a discount amount per unit. This discount therefore reduces the unit price by the discount. This discount is commonly supplied automatically from purchase agreements or trade agreements, but it is possible to override on individual lines if unique discounts have been negotiated with the vendor.

    - <bpt id="p1">**</bpt>Discount percentage<ept id="p1">**</ept>: When entered, this reduces the net amount for the line accordingly. The discount percent is often supplied automatically from purchase agreements or trade agreements, but it is possible to override on individual lines if a unique discount percentage has been negotiated with the vendor.

    - <bpt id="p1">**</bpt>Net amount<ept id="p1">**</ept>: Calculated from other fields on the line, including quantity, unit price, discount, and discount percent. It is possible to change the Net amount, but then the Unit Price, Discount, and Discount percent fields will be blank, and when you post toward the line, the amount posted will be proportional to the net amount. Generally, the Net Amount field is only used for displaying the net amount of the line.

1. Nas linhas de ordem de compra, na parte inferior da página, selecione **Detalhes da linha**.

1. Selecione a guia **Entrega**.

1. A unique delivery date can be assigned to each order line. The date is inherited from the field on the purchase order header, but you can change this.

1. Feche a página de linha da ordem de compra.

1. Na página Todas as ordens de compra, use o recurso de Filtro e localize sua nova ordem de compra.

1. Ao concluir, feche a página Todas as ordens de compra e retorne à Página inicial.
