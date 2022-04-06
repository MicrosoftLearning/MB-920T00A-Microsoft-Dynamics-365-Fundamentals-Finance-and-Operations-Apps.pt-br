---
lab:
  title: 'Laboratório 2: Criar um diário de pagamentos de fornecedor'
  module: 'Module 2: Learn the Fundamentals of Microsoft Dynamics 365 Finance'
ms.openlocfilehash: cc38bf9c77d8b5d45e8a27f0a8f766d7834e065a
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909390"
---
## <a name="lab-2---create-a-vendor-payment-journal"></a>Laboratório 2 — Criar um diário de pagamento do fornecedor

## <a name="objectives"></a>Objetivos

As organizações que pagam fornecedores em um agendamento recorrente agora podem automatizar o processo de geração de propostas de pagamento do fornecedor. As automações de proposta de pagamento do fornecedor definem os seguintes detalhes:

- Quando as propostas de pagamento são executados
- Quais critérios são usados para selecionar as faturas que devem ser pagas
- Em qual diário de pagamento do fornecedor os pagamentos resultantes são salvos

As automações de proposta de pagamento não postam automaticamente os pagamentos. Portanto, você pode continuar a usar todos os processos de validação e fluxo de trabalho que você usa atualmente para aprovar os pagamentos criados.

Crie uma nova entrada de diário de pagamento de fornecedor e uma proposta de pagamento.

## <a name="lab-setup"></a>Configuração do Laboratório

   - **Tempo estimado**: 10 minutos

## <a name="instructions"></a>Instruções

1. Na home page do Finance and Operations, na parte superior direita, verifique se você está trabalhando com a empresa USMF.

1. Se necessário, selecione a empresa e, no menu, selecione **USMF**.

1. No painel de navegação à esquerda, selecione **Módulos** > **Contas a pagar** > **Pagamentos** > **Diário de pagamentos do fornecedor**.

1. No menu superior, selecione **+ Novo**.

1. Observe o novo número do lote do Diário que foi criado.

1. Na caixa **Nome**, insira **Vend**  e selecione **VendPay** na lista filtrada.

1. No menu superior, selecione **Linhas**.

1. Na página Pagamentos do fornecedor, no menu superior, selecione **Proposta de pagamento** > **Criar proposta de pagamento**.  
    A proposta de pagamento é uma consulta usada para selecionar faturas para pagamento. Você pode editar a lista de faturas a pagar antes de criar ou gerar os pagamentos do fornecedor.

    ![Imagem da tela exibindo a página pagamento do fornecedor com a proposta de pagamento e criar proposta de pagamento realçadas](./media/lp2-m4-vendor-payment-proposal.png)

1. No painel Proposta de pagamento do fornecedor, em **CRITÉRIOS DE SELEÇÃO DA FATURA**, selecione o menu **Selecionar faturas por**, revise as opções disponíveis e, em seguida, selecione **Data de vencimento**.

1. Em **De data** e **Para data**, exclua qualquer valor existente. Para este exercício, esses intervalos de datas serão deixados em branco.

    >[!NOTE] Uma data mínima de pagamento pode ser usada como a data de pagamento. A data mínima de pagamento será a data mais antiga usada ao criar pagamentos. Por exemplo, se uma fatura tiver uma data de vencimento após a data mínima de pagamento, a data de vencimento se tornará a data de pagamento em vez da data mínima de pagamento para pagar a fatura na data mais recente possível.

1. Expanda **Registros para incluir** e, em seguida, revise as opções.  
    O filtro geralmente é usado para restringir as faturas selecionadas para pagamento por grupo de fornecedores ou forma de pagamento. Por exemplo, você pode adicionar um filtro para pagar apenas faturas por check-in nesta rodada de pagamento.

1. Expanda **Parâmetros avançados** e, em seguida, revise as opções disponíveis.  
    Os parâmetros adicionais podem ser usados para definir a moeda de pagamento ou para habilitar pagamentos centralizados para esse pagamento.

1. Selecione **OK**.  
    Depois de selecionar OK, os resultados da consulta serão exibidos. Se você não quiser visualizar a lista de faturas selecionadas para pagar, volte para a guia rápida Parâmetros e altere a configuração **Criar pagamentos sem visualização da fatura** para **Sim**.

1. Na janela Proposta de pagamento do fornecedor, selecione **Mostrar visão geral do pagamento** para exibir os pagamentos que serão criados para o fornecedor na fatura selecionada.

    ![Imagem da tela exibindo a proposta de pagamento do fornecedor com o menu Mostrar visão geral do pagamento realçado](./media/lp2-m4-vendor-payment-proposal-complete-query.png)

1. No menu, selecione **Ocultar visão geral do pagamento** para ocultar os pagamentos.

1. Selecione o ícone de marca de seleção à esquerda do título da coluna **Nome do fornecedor** para selecionar todas as faturas.

    ![Imagem da tela exibindo todas as faturas selecionadas](./media/lp2-m4-vendor-payment-proposal-select-all.png)

1. Desmarque a caixa de seleção das três primeiras faturas e, em seguida, no menu, selecione **Remover** para remover todas as outras faturas.

    ![Captura de tela exibindo a página Proposta de pagamento do fornecedor com itens selecionados e a opção de menu Remover realçada](./media/lp2-m4-vendor-payment-proposal-remove-selected-invoices.png)

1. Na caixa de diálogo, selecione **Sim**.

1. Revise as três faturas restantes.

1. Para exportar a lista de faturas para o Excel, clique com o botão direito do mouse na grade e selecione uma opção de exportação.

1. No canto inferior direito, selecione **Criar pagamentos** para criar os pagamentos do fornecedor no diário de pagamento.

1. Revise a lista de pagamentos do fornecedor.
