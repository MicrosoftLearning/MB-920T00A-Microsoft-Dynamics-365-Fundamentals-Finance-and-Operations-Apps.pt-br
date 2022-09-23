---
lab:
  title: '‘Laboratório 4: Criar uma ordem de produção'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

## <a name="lab-4---create-a-production-order"></a>Laboratório 4: Criar uma ordem de produção

## <a name="objectives"></a>Objetivos

The production order contains information about what will be produced, the quantity to produce, and the planned finish date. It also contains information about which materials to consume and which process to follow to produce the item.

Você deve criar uma nova ordem de produção para sua empresa.

## <a name="lab-setup"></a>Configuração do Laboratório

   - **Tempo estimado**: 5 minutos

## <a name="instructions"></a>Instruções

1. Na home page do Finance and Operations, na parte superior direita, verifique se você está trabalhando com a empresa USMF.

1. Se necessário, selecione a empresa e, no menu, selecione **USMF**.

1. No painel de navegação à esquerda, selecione **Módulos** > **Controle de produção** > **Pedidos de produção** > **Todos os pedidos de produção**.

1. No menu superior, selecione **Nova ordem de produção**.

1. Em **IDENTIFICAÇÃO**, na caixa **Número do item**, digite **D0001** e, em seguida, selecione o item identificado.

1. Em **PRODUÇÃO**, na caixa **Entrega**, selecione uma data de um mês a partir da data de hoje.  
    The delivery date indicates when the production order should end in order to deliver on time. This date can be used in the scheduling process. For example, you can schedule the order backward from the delivery date.

1. Na caixa **Quantidade**, digite **20**.

1. Under <bpt id="p1">**</bpt>BOM/ROUTE<ept id="p1">**</ept>, the BOM number field automatically displays the number of any active BOM for the current item, but you can change the BOM for the production order by selecting an active BOM from the list of approved BOM versions. The Route number field automatically displays the number of any active Route for the current item, but you can change the Route for the production order by selecting an active Route from the list of approved Route versions.

    ![Imagem da tela exibindo o painel completo Criar ordem de produção](./media/lp1-m4-new-production-order-pane.png)

1. Selecione **Criar**.
