---
lab:
  title: 'Laboratório 6: Criar uma ordem de produção'
  module: 'Module 1: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
ms.openlocfilehash: 222c557f935bc0dcfaa4f2e96049774f141ea028
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909228"
---
## <a name="lab-6---create-a-production-order"></a>Laboratório 6 — Criar uma ordem de produção

## <a name="objectives"></a>Objetivos

A ordem de produção contém informações sobre o que será produzido, a quantidade a ser produzida e a data de término planejada. Ele também contém informações sobre quais materiais consumir e qual processo deve ser seguido para produzir o item.

Você deve criar uma nova ordem de produção para sua empresa.

## <a name="lab-setup"></a>Configuração do Laboratório

   - **Tempo estimado**: 5 minutos

## <a name="instructions"></a>Instruções

1. Na home page do Finance and Operations, na parte superior direita, verifique se você está trabalhando com a empresa USMF.

1. Se necessário, selecione a empresa e, no menu, selecione **USMF**.

1. No painel de navegação à esquerda, selecione **Módulos** > **Controle de produção** > **Pedidos de produção** > **Todos os pedidos de produção**.

1. No menu superior, selecione **Nova ordem de produção**.

1. Em **IDENTIFICAÇÃO**, na caixa **Número do item**, digite **D0001** e, em seguida, selecione o item identificado.

1. Em **PRODUÇÃO**, na caixa **Entrega**, selecione uma data de um mês a partir da data de hoje.  
    A data de entrega indica quando o pedido de produção deve terminar para ser entregue no prazo. Essa data pode ser usada no processo de agendamento. Por exemplo, você pode agendar retroativamente o pedido a partir da data de entrega.

1. Na caixa **Quantidade**, digite **20**.

1. Em **LISTA DE MATERIAIS/ROTA**, o campo número da lista de materiais exibe automaticamente o número de qualquer lista de materiais ativa para o item atual, mas você pode alterá-la para a ordem de produção selecionando uma lista ativa na lista de versões aprovadas. O campo número de rota exibe automaticamente o número de qualquer rota ativa para o item atual, mas você pode alterá-la para a ordem de produção selecionando uma rota ativa na lista de versões aprovadas.

    ![Imagem da tela exibindo o painel completo Criar ordem de produção](./media/lp1-m4-new-production-order-pane.png)

1. Selecione **Criar**.
