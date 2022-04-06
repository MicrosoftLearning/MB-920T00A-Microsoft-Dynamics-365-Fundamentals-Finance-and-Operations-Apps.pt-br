---
lab:
  title: 'Laboratório 8: Laboratório de conclusão do gerenciamento da cadeia de fornecedores do Dynamics 365'
  module: 'Module 1: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
ms.openlocfilehash: 05fc7cf7a81164c2cabf3637e307dcae2ca5d3f7
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909381"
---
## <a name="lab-8---dynamics-365-supply-chain-management-capstone-lab"></a>Laboratório 8 – Laboratório de conclusão do gerenciamento da cadeia de fornecedores do Dynamics 365

## <a name="objective"></a>Objetivo

Durante este laboratório, você vai explorar a criação e a manutenção de preços do produto. Você também vai revisar os principais processos de negócios de cadeias de fornecimento, como gerenciamento de estoque, aquisição e suprimento.

## <a name="lab-setup"></a>Configuração do Laboratório

- **Tempo estimado**: 45 minutos 

## <a name="exercise-1-explore-product-management"></a>Exercício 1: Explorar o gerenciamento de produto

### <a name="create-a-product"></a>Crie um produto

No Contoso Entertainment System USA (USMF), é preciso criar um novo item para um compartimento de alto-falante recém-configurado a ser comprado de fornecedores.

1. Na página inicial, no canto superior direito, verifique se a empresa **USMF** está selecionada.

1. Se não estiver, selecione a empresa atualmente listada e altere-a para **USMF**.

1. Usando o painel de navegação, selecione **Módulos** > **Gerenciamento de informações do produto** > **Produtos** > **Produtos lançados**.

1. Na página Detalhes do produto lançado, no Painel de Ações, selecione **+ Novo**.

1. No painel de **Novos produtos lançados**, no menu **Tipo de produto**, verifique se o **Item** está selecionado.

1. No menu **Subtipo de produto**, verifique se **Produto** está selecionado.

1. Selecione o menu **Grupo de dimensões de rastreamento** e depois selecione **Nenhum**.

1. Em **IDENTIFICAÇÃO**, na caixa **Número do produto**, digite **GTL201**.

1. Na caixa **Nome do produto**, insira **Compartimento de alto-falante**.

1. Em **TRIBUTAÇÃO SOBRE AS VENDAS**, selecione o menu **Grupo de impostos do item** e selecione **TODOS**.

1. Em **TRIBUTAÇÃO DE COMPRA**, selecione o menu **Grupo de impostos do item** e selecione **TODOS**.

1. Em **PREÇOS**, na caixa **Preço da compra**, insira **30,00**.

1. Na caixa **Preço de vendas**, insira **30,00**.

1. Em **GRUPOS DE REFERÊNCIA**, selecione o menu **Grupo de modelos de item** e depois **FIFO First In-First Out**.

1. Selecione o menu **Grupo do item** e depois **CarAudio**.

1. Selecione o menu **Grupo de dimensões de armazenamento** e depois **SiteWH**.

1. Em **UNIDADES DE MEDIDA**, verifique se foram definidos os seguintes valores:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | Unidade de inventário| ea|
    | Unidade de compra| ea|
    | Unidade de vendas| ea|
    | Unidade BOM| ea|

1. Selecione **OK**.

1. Para confirmar que o produto foi finalizado, no Painel de Ações, selecione **Produto** e em **Manter**, selecione **Validar**.

1. Verifique se você recebeu a mensagem com a informação confirmando que todos os valores dos campos obrigatórios foram validados.

1. Feche todas as páginas e volte para a Home page.

## <a name="exercise-2-explore-warehouse-management"></a>Exercício 2: Explorar o gerenciamento de estoque

### <a name="create-a-warehouse"></a>Criar um depósito

1. Usando o painel de navegação, selecione **Módulos** > **Gerenciamento de estoque** > **Configuração** > **Detalhamento de estoque** > **Depósitos**.

1. Na página Depósitos, no Painel de Ações, selecione **Novo**.

1. Na caixa **Depósitos**, digite **150**.

1. Na caixa **Nome**, digite **Depósito de posto avançado**.

1. Selecione o menu **Local** e depois **1 Home speakers production**.

1. Selecione a FastTab **Nomes de localização**.

1. As opções nesta seção definem o formato padrão para nomes de localização.

1. Defina as opções **Incluir corredor** e **Incluir rack** como **Sim**.

1. Defina a opção **Incluir prateleira** como **Sim**.

1. Na caixa **Formato**, para a prateleira, insira **-##** .

1. No Painel de Ações, selecione **Depósito**.

1. Em **Manter**, selecione **Assistente de Localização**.

1. Na página inicial, revise as informações e, no canto inferior direito, selecione **Próximo**.

1. Desmarque as caixas de seleção **Plataformas de entrada** e **Locais em massa**.

1. Selecione **Avançar** e revise as informações.

1. Continue em cada página e ao terminar, selecione **Concluir**.

1. Feche a página e retorne à página inicial.

### <a name="create-a-trade-agreement-for-sales-price"></a>Criar um acordo comercial para o preço de vendas

1. Usando o painel de navegação, selecione **Módulos** > **Gerenciamento de informações do produto** > **Produtos** > **Produtos lançados**.

1. Na página Detalhes dos produtos lançados, pesquise o número do produto **GTL201**.

1. À esquerda de **GTL201**, marque a caixa de seleção **Selecionar ou desmarcar linha**.

1. No Painel de Ações, selecione **Vender** e em **ACORDOS COMERCIAIS**, selecione **Criar acordos comerciais**.

1. No painel Ação, selecione **+ Novo**.

1. Selecione a coluna **Nome**, selecione o menu e depois **S_Price**.

1. No Painel de Ações, selecione **Linhas**.

1. Na página Linhas de diário, acordo comercial, na coluna **Relação de item**, selecione o menu e, em seguida, **GTL201**.

1. Esse é o número do item do produto que você criou.

1. Na coluna **Depósito**, selecione o menu e depois **150**.

1. Talvez seja preciso rolar para a direita para ver a coluna.

1. Na coluna **Valor em moeda**, na caixa, insira **100,00**.

1. Na seção Detalhes, na caixa **Da data**, insira a primeira data do ano atual.

1. No Painel de Ações, selecione **Validar** > **Validar todas as linhas.**

1. No painel de lançamento **Diário de preço/desconto**, selecione **OK**.

1. Verifique se não há erros.

1. No Painel de Ações, selecione **Postar**.

1. No painel de lançamento **Diário de preço/desconto**, selecione **OK**.

1. Verifique se a operação foi concluída.

1. Feche a página.

1. Na página Detalhes do produto lançado, no Painel de Ações em **Vender** > **ACORDOS COMERCIAIS**, selecione **Exibir acordos comerciais**.

1. O acordo comercial deve ser postado. Revise a linha para observar as informações de preço.

1. Feche as páginas e volte para a Página inicial.

## <a name="exercise-3-explore-production-management"></a>Exercício 3: Explorar o gerenciamento da produção

### <a name="create-a-production-order-for-a-product"></a>Criar um pedido de produção para um produto

1. Usando o painel de navegação, selecione **Módulos** > **Controle de produção** > **Pedidos de produção** > **Todos os pedidos de produção**.

1. No Painel de Ações, selecione **Novo pedido de produção**.

1. No painel **Criar pedido de produção**, em **IDENTIFICAÇÃO**, na caixa **Número do item**, insira **D0004** e selecione o item identificado.

1. Em **PRODUÇÃO**, na caixa **Entrega**, selecione uma data de um mês a partir da data de hoje.

1. A data de entrega indica quando o pedido de produção deve terminar para ser entregue no prazo. Essa data pode ser usada no processo de agendamento. Por exemplo, você pode agendar retroativamente o pedido a partir da data de entrega.

1. Na caixa **Quantidade**, insira **30**

1. Selecione **Criar**.

1. Feche todas as páginas e volte para a Home page.

## <a name="exercise-4-explore-inventory-management"></a>Exercício 4: Explorar o gerenciamento de inventário

### <a name="create-a-count-journal-with-the-product-for-the-created-warehouse"></a>Criar um diário de contagem com o produto para o depósito criado

1. Usando o painel de navegação, selecione **Módulos** > **Gerenciamento de estoque** > **Entradas de diário** > **Contagem de itens > Contagem**.

1. No Painel de Ações, selecione **+ Novo**.

1. No painel **Criar diário de estoque** em **Contagem por**, selecione o botão de alternância de **Depósito** para defini-lo como **Sim**.

1. Selecione **OK**.

1. Na página Diário de contagem de estoque, na FastTab **Detalhes do cabeçalho do diário**, em **Linhas do diário** na barra de ferramentas, selecione **+ Novo**.

1. Na coluna **Número do item**, selecione o menu e depois **GTL201**.

1. Na coluna **Depósito**, selecione o menu e depois **150**.

1. Na caixa **Contado**, digite **100,00**.

1. Isso especificará o número de itens estocados no depósito para este produto.

1. No Painel de Ações, selecione **Validar**.

1. No painel **Verificar diário**, selecione **OK**.

1. No Painel de Ações, selecione **Postar**.

1. No painel **Postar diário**, selecione **OK**.

1. Feche todas as páginas e volte para a Home page.

### <a name="check-on-hand-inventory-for-the-product"></a>Verificar o estoque disponível para o produto

1. Usando o painel de navegação, selecione **Módulos** > **Gerenciamento de estoque** > **Consultas e relatórios** > **Lista de disponibilidade**.

1. No Painel de Ações, selecione **Dimensões**.

1. No painel **Exibição da dimensão**, em **DIMENSÕES DE ARMAZENAMENTO**, marque as caixas de seleção **Local** e **Depósito** e depois **OK**.

1. No painel **Filtros**, selecione **Aplicar**.

1. Localize e examine o estoque disponível para **GTL201**.

1. Feche todas as páginas e volte para a Home page.

## <a name="exercise-5-explore-procurement-and-sourcing"></a>Exercício 5: Explorar a aquisição e o fornecimento

### <a name="create-a-purchase-order-with-a-product"></a>Criar um pedido de compra com um produto

1. Usando o painel de navegação, selecione **Módulos** > **Compras e suprimento** > **Ordens de compra** > **Todas as ordens de compra**.

1. Na página Todas as ordens de compra, no Painel de Ações, selecione **+ Novo**.

1. No painel **Criar pedido de compra**, selecione o menu **Conta do fornecedor** e depois selecione **US-101**.

1. Quando um fornecedor é selecionado, os detalhes do registro do fornecedor, como endereço, conta de faturamento, termos de entrega e modo de entrega, serão copiados como valores padrão no cabeçalho do pedido. Esses valores podem ser alterados a qualquer momento.

1. Na seção **Geral**, em **DIMENSÕES DE ARMAZENAMENTO**, selecione o menu **Local** e depois selecione **1 produção de alto-falantes domésticos**.

1. Em **DATAS**, selecione uma **Data de entrega** para uma semana a partir da data de hoje.

1. Selecione **Administração**.

1. Selecione o menu **Solicitante** e **Lars Giusti** para especificar quem está fazendo o pedido.

1. No painel **Criar ordem de compra**, selecione **OK**.

1. Na barra de ferramentas, selecione **Linha de ordem de compra**.

1. Em **Exibir**, selecione **Dimensões**.

1. No painel **Exibição de dimensões**, em **DIMENSÕES DO PRODUTO**, marque a caixa de seleção **Cor**.

1. Selecione **OK**.

1. Na coluna **Número do item**, selecione o menu e depois **T0005**.

1. Na coluna **Número do modelo**, selecione o menu e uma das cores.

1. Na caixa **Quantidade**, digite **15**.

1. Nas **linhas da ordem de compra**, na parte inferior da página, selecione a FastTab **Detalhes da linha**.

1. Esta guia já pode estar expandida.

1. Selecione a guia **Entrega** e, na caixa **Data de entrega**, use a data atribuída no momento ou insira uma data futura.  
    É possível atribuir uma data de entrega exclusiva para cada linha de pedido. A data é herdada do campo no cabeçalho da ordem de compra, mas isso pode ser alterado.

1. Anote o número do pedido de compra. Você precisará dessas informações posteriormente.

1. No Painel de Ação, selecione **Salvar**.

1. Feche a página de linha da ordem de compra.

1. Na página Todos os pedidos de compra, use o recurso **Filtro** para localizar o novo pedido de compra.

1. Ao concluir, feche a página Todas as ordens de compra e retorne à Página inicial.
