---
lab:
  title: 'Laboratório 3: Laboratório de conclusão do Dynamics 365 Commerce'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Commerce'
ms.openlocfilehash: c498966dc4b2bba78b4e0d27077c4b346666323f
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909218"
---
## <a name="lab-3---dynamics-365-commerce-capstone-lab"></a>Laboratório 3 – Laboratório de conclusão do Dynamics 365 Commerce

## <a name="objective"></a>Objetivo

Durante este laboratório, você vai explorar os conceitos básicos da configuração de Sede comercial. Os principais recursos incluem configuração de canal de varejo, criação de sortimento e configuração de desconto de varejo.

## <a name="lab-setup"></a>Configuração do Laboratório

   - **Tempo estimado**: 30 minutos 

## <a name="instructions"></a>Instruções

## <a name="exercise-1-explore-commerce-headquarters"></a>Exercício 1: Explorar as sedes comerciais

### <a name="create-a-new-store"></a>Criar uma nova loja

1. Na página de aterrissagem, no canto superior direito, verifique se a empresa **USRT** está selecionada.

1. Se não estiver, selecione a empresa listada no momento e, em seguida, insira **USRT**.

1. Usando o painel de navegação, selecione **Módulos** > **Varejo e Comércio** > **Canais** > **Lojas** > **Todas as lojas**.

1. No Painel de Ações, selecione **+Novo** para criar uma nova loja.

1. Na janela Novo registro, use as configurações na tabela a seguir para atualizar os valores:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | Nome| Loja Modelo de Seattle|
    | Número da loja| 000098|
    | Warehouse| Seattle|
    | Depósito de expedição| Seattle|
    | Fuso horário da loja| (GMT-08:00) Hora do Pacífico|
    | Perfil de funcionalidade| PF001|
    | Pesquisa de inventário| Sim|
    | Perfil de canal| Padrão|
    | Perfil offline| Padrão|
    | Grupo de impostos sobre vendas| WA|
    | Usar imposto baseado em destino| Sim|
    | Catálogo de endereços do cliente| RetailCust|
    | Catálogo de endereços do funcionário| Seattle|
    | Cliente padrão| 3002|

1. No Painel de Ações, selecione **Salvar**.

1. Selecione a FastTab **Demonstrativo/fechamento** e depois insira as seguintes atualizações:

    | Configuração| Valor|
    | :--- | :--- |
    | Cálculo do valor do demonstrativo| Último|
    | Diferença máxima > Lançamento| 100,00|

1. Selecione a FastTab **Dimensões financeiras** e depois insira as seguintes atualizações:

    | Configuração| Valor|
    | :--- | :--- |
    | BusinessUnit| 004|
    | RetailChannel| 000210|

1. Selecione a FastTab **Layout da tela**.

1. Na caixa **ID de layout da tela**, digite  **A2CP16:9C**.

1. No Painel de Ações, selecione **Salvar**.

1. No Painel de Ações, selecione  **Configurar** e, na guia **COPIAR**, selecione **Copiar tudo**.

1. No painel **Copiar tudo**, selecione o menu **Da loja** e, em seguida, selecione **ANNAPOL**.

1. Se necessário, selecione o menu **Para a loja** e, em seguida, selecione **00098**.

1. Selecione  **OK**.

1. Verifique se a mensagem de êxito é exibida e feche a página.

### <a name="add-a-group-of-products-to-an-assortment-and-publish"></a>Adicionar um grupo de produtos a um sortimento e publicar

1. Usando o painel de navegação, selecione  **Módulos** > **Administração da organização** > **Organizações** > **Hierarquias da organização**.

1. Na lista de navegação, selecione **Lojas de varejo por região**.

1. No Painel de Ações, selecione  **Exibir**.

1. Na página designer de Hierarquia, no Painel de Ações, selecione **Editar**.

1. No bloco **Oeste**, selecione o ícone de reticências ( **...** ).

1. Na página designer de Hierarquia, selecione  **Inserir** > **Canal de varejo**.

1. No painel **Canal de varejo**, selecione **Loja Modelo de Seattle** e, em seguida, selecione **OK**.

1. No Painel de Ações, selecione **Salvar**.

1. Na caixa de diálogo, analise as informações e selecione **Fechar**.

1. No Painel de Ações, selecione  **Publicar**.

1. No painel **Publicar alterações**, na caixa **Data de efetivação**, selecione o primeiro dia do mês atual.

1. Na caixa **Descrever alterações**, insira  **Adição da loja modelo de Seattle**  e depois selecione  **Publicar**.

1. Na caixa de diálogo, analise as informações e selecione **Fechar**.

1. No Painel de Ações, selecione **Salvar**.

1. Na caixa de diálogo, analise as informações e selecione **Fechar**.

1. Feche a página.

1. Usando o painel de navegação, selecione  **Módulos** > **Varejo e Comércio** > **Catálogos e sortimentos** > **Sortimentos**.

1. Na página Sortimentos, selecione **AW-Outlet**.

1. No painel Ação, selecione  **Editar**.

1. Na caixa de diálogo, selecione  **Sim**  para confirmar a seleção de edição.

1. Na página AW-Outlet, selecione a FastTab **Canal de comércio**.

1. Na barra de ferramentas, selecione  **+Adicionar linha**.

1. No painel **Escolher nós da organização**, selecione o menu **Hierarquia da organização** e depois  **Lojas de varejo por Região**.

1. Em **NÓS DISPONÍVEIS DA ORGANIZAÇÃO**, selecione  **Loja modelo de Seattle**  e depois selecione o ícone de seta direita **Adicionar** para adicioná-lo aos **NÓS DA ORGANIZAÇÃO SELECIONADOS**.

1. Selecione  **OK**.

1. No Painel de Ações, selecione  **Publicar**.

1. Na caixa de diálogo, analise as informações e selecione  **Sim**.

1. No Painel de Ações, selecione  **Editar**.

1. Na caixa de diálogo de **confirmação**, selecione **Sim**.

1. Na página AW-Outlet, selecione a guia **Produtos**.

1. Na página AW-Outlet, selecione **+Adicionar linha**.

1. Selecione o menu **Categoria**, selecione  **Esportes de equipe** e, em seguida,  **OK**.

1. No Painel de Ações, selecione  **Publicar**.  

### <a name="run-the-retail-scheduler-job-for-products"></a>Executar o trabalho de agendador do retail para produtos

1. Usando o painel de navegação, selecione  **Módulos** > **Varejo e Comércio** > **Varejo e Comércio TI** > **Agendamento de distribuição**.

1. Na lista de navegação, selecione  **1040 (Produtos)** .

1. No Painel de Ações, selecione  **Executar agora**.

1. No painel **Sincronização incremental com a agenda '1040'** , revise as informações e selecione  **OK**.

### <a name="create-a-new-product-discount"></a>Criar um novo desconto de produto

1. Usando o painel de navegação, selecione  **Módulos** > **Varejo e Comércio** > **Preços e descontos** > **Todos os descontos**.

1. No Painel de Ações, selecione  **Novo** > **Desconto**.

1. Na página Descontos, na caixa **Nome**, insira  **Abertura de loja**.

1. Na FastTab **Detalhes**, na caixa **Descrição**, insira  **20% de desconto na abertura de loja**.

1. Na FastTab **Preço/desconto**, na caixa **Percentual de desconto**, insira  **20,00**.

1. Na FastTab **Período de validação**, na caixa **Data de efetivação**, insira uma data do mês anterior.

1. Na caixa **Data de validade**, insira uma data de uma semana a partir da data atual.

1. Na FastTab **Linhas**, na barra de ferramentas, selecione **+ Adicionar**.

1. Na coluna **Categoria**, selecione o menu, selecione **Esportes em equipe** e depois **OK**.

1. No Painel de Ações, selecione **Salvar**.

1. No Painel de Ações, selecione  **Grupos de preços**.

1. Na página Grupos de preços, selecione o menu **Grupos de preços** e selecione  **Oeste**.

1. No Painel de Ações, selecione **Salvar**.

1. Usando o painel de navegação, selecione  **Módulos** > **Varejo e Comércio** > **Preços e descontos** > **Todos os descontos**.

1. Na lista de navegação, selecione  **ST100101**.

1. Na FastTab **Geral**, selecione o menu **Status** e, em seguida,  **Habilitado**.

1. No Painel de Ações, selecione **Salvar**.

1. Feche o formulário.

1. Usando o painel de navegação, selecione  **Módulos** > **Varejo e Comércio** > **Varejo e Comércio TI** > **Agendamento de distribuição**.

1. Na lista de navegação, selecione  **1020 (Produtos)** .

1. No Painel de Ações, selecione  **Executar agora**.

1. No painel **Sincronização incremental com a agenda '1020'** , revise as informações e selecione  **OK**.
