---
lab:
    title: 'Laboratório 3: Laboratório do trabalho de conclusão de curso do Dynamics 365 Commerce'
    module: 'Módulo 3: Conheça os princípios básicos do Microsoft Dynamics 365 Commerce'
---

## Laboratório 3 - Laboratório do trabalho de conclusão de curso do Dynamics 365 Commerce

## Objetivo

Neste laboratório, vamos ver os fundamentos da configuração da matriz do Commerce. Os principais recursos incluem configuração do canal de varejo, criação de sortimento e configuração do desconto de varejo

## Configuração do laboratório

   - **Tempo estimado**: 30 minutos 

## Instruções

## Exercício 1: Explorar a sede do Commerce

### Criar uma nova loja

1. Na página de aterrissagem, na parte superior direita, verifique se a empresa **USRT** está selecionada.

1. Caso não esteja, selecione a empresa listada no momento e depois digite **USRT**.

1. Usando o painel de navegação, selecione **Módulos** > **Varejo e comércio** > **Canais** > **Lojas** > **Todas as lojas**.

1. No painel de ações, selecione **+Novo** para criar uma nova loja.

1. Na janela Novo registro, use as configurações na tabela a seguir para atualizar os valores:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | Nome| Loja Principal de Seattle|
    | Número da loja| 000098|
    | Depósito| Seattle|
    | Depósito de remessa| Seattle|
    | Fuso horário da loja| (GMT-08:00) Hora do Pacífico|
    | Perfil da funcionalidade| FN001|
    | Pesquisa de estoque| Sim|
    | Perfil de canal| Padrão|
    | Perfil offline| Padrão|
    | Grupo de impostos sobre vendas| WA|
    | Usar imposto baseado no destino| Sim|
    | Catálogo de endereços do cliente| RetailCust|
    | Catálogo de endereços do funcionário| Seattle|
    | Cliente padrão| 3002|

1. No painel de ações, selecione **Salvar**.

1. Selecione a guia rápida **Demonstrativo/fechamento** e insira as seguintes atualizações:

    | Configuração| Valor|
    | :--- | :--- |
    | Cálculo do valor do demonstrativo| Último|
    | Diferença máxima > Lançamento| 100,00|

1. Selecione a guia rápida **Dimensões financeiras** e depois insira as seguintes atualizações:

    | Configuração| Valor|
    | :--- | :--- |
    | BusinessUnit| 004|
    | RetailChannel| 000210|

1. Selecione a guia rápida **Layout da tela**.

1. Na caixa **ID do layout da tela**, digite **A2CP16:9C**.

1. No painel de ações, selecione **Salvar**.

1. No painel de ações, selecione **Configurar** e, em seguida, na guia **COPIAR**, selecione **Copiar tudo**.

1. No painel **Copiar tudo**, selecione o menu **Da loja** e, em seguida, **ANNAPOL**.

1. Se necessário, selecione o menu **Para a loja** e depois **00098**.

1. Selecione **OK**.

1. Verifique se a mensagem de sucesso é exibida e depois feche a página.

### Adicionar um grupo de produtos a um sortimento e publicar

1. Usando o painel de navegação, selecione **Módulos** > **Administração da organização** > **Organizações** > **Hierarquias da organização**.

1. Na lista de navegação, selecione **Lojas de Varejo por Região**.

1. No painel de ações, selecione **Exibir**.

1. Na página Designer da hierarquia, no painel de ações, selecione **Editar**.

1. No bloco **Oeste**, selecione o ícone de reticências (**...**).

1. Na página Designer da hierarquia, selecione **Inserir** > **Canal de varejo**.

1. No painel **Canal de varejo**, selecione **Loja Principal de Seattle** e, em seguida, **OK**.

1. No painel de ações, selecione **Salvar**.

1. Na caixa de diálogo, analise as informações e selecione **Fechar**.

1. No painel de ações, selecione **Publicar**.

1. No painel **Publicar alterações**, na caixa **Data de efetivação**, selecione o primeiro dia do mês atual.

1. Na caixa **Descrever alterações**, digite **Adição da Loja Principal de Seattle** e depois selecione **Publicar**.

1. Na caixa de diálogo, analise as informações e selecione **Fechar**.

1. No painel de ações, selecione **Salvar**.

1. Na caixa de diálogo, analise as informações e selecione **Fechar**.

1. Feche a página.

1. Usando o painel de navegação, selecione **Módulos** > **Varejo e comércio** > **Catálogos e sortimentos** > **Sortimentos**.

1. Na página Sortimentos, selecione **AW-Outlet**.

1. No painel de ações, selecione **Editar**.

1. Na caixa de diálogo, selecione **Sim** para confirmar a seleção de edição.

1. Na página AW-Outlet, selecione a guia rápida **Canal comercial**.

1. Na barra de ferramentas, selecione **+ Adicionar linha**.

1. No painel  **Escolha os nós da organização**, selecione o menu **Hierarquia da organização** e depois **Lojas de varejo por região**.

1. Em **NÓS ORGANIZACIONAIS DISPONÍVEIS**, selecione **Loja Principal de Seattle** e depois o ícone de seta para a direita **Adicionar** para adicioná-lo a **NÓS ORGANIZACIONAIS SELECIONADOS**.

1. Selecione **OK**.

1. No painel de ações, selecione **Publicar**.

1. Na caixa de diálogo, analise as informações e depois selecione **Sim**.

1. No painel de ações, selecione **Editar**.

1. Na caixa de diálogo de **confirmação**, selecione **Sim**.

1. Na página AW-Outlet, selecione a guia **Produtos**.

1. Na página AW-Outlet, selecione **+ Adicionar linha**.

1. Selecione o menu **Categoria**, selecione **Esportes em Equipe** e selecione **OK**.

1. No painel de ações, selecione **Publicar**.  

### Executar o trabalho de agendador do retail para produtos

1. Usando o painel de navegação, selecione **Módulos** > **Varejo e comércio** > **TI de varejo e comércio** > **Agenda de distribuição**.

1. Na lista de navegação, selecione **1040 (Produtos)**.

1. No painel de ações, selecione **Executar agora**.

1. No painel **Sincronização incremental com cronograma '1040'**, examine as informações e depois selecione **OK**.

### Criar um novo desconto de produto

1. Usando o painel de navegação, selecione **Módulos** > **Varejo e comércio** > **Preços e descontos** > **Todos os descontos**.

1. No painel de ações, selecione **Novo** > **Desconto**.

1. Na página Descontos, na caixa **Nome**, digite **Abertura da loja**.

1. Na guia rápida **Detalhes**, na caixa **Descrição**, digite **Desconto de 20% de abertura da loja**.

1. Na guia rápida **Preço/desconto**, na caixa **Percentual de desconto**, digite **20,00**.

1. Na guia rápida **Período de validação**, na caixa **Data de efetivação**, digite uma data do mês anterior.

1. Na caixa **Data de vencimento**, digite uma data uma semana depois da data atual.

1. Na guia rápida **Linhas**, na barra de ferramentas, selecione **+ Adicionar**.

1. Na coluna **Categoria**, selecione o menu, selecione **Esportes em Equipe** e **OK**.

1. No painel de ações, selecione **Salvar**.

1. No painel de ações, selecione **Grupos de preços**.

1. Na página Grupos de preços, selecione o menu **Grupos de preços** e depois **Oeste**.

1. No painel de ações, selecione **Salvar**.

1. Usando o painel de navegação, selecione **Módulos** > **Varejo e comércio** > **Preços e descontos** > **Todos os descontos**.

1. Na lista de navegação, selecione **ST100101**.

1. Na guia rápida **Geral**, selecione o menu **Status** e depois **Habilitado**.

1. No painel de ações, selecione **Salvar**.

1. Feche o formulário.

1. Usando o painel de navegação, selecione **Módulos** > **Varejo e comércio** > **TI de varejo e comércio** > **Agenda de distribuição**.

1. Na lista de navegação, selecione **1020 (Produtos)**.

1. No painel de ações, selecione **Executar agora**.

1. No painel **Sincronização incremental com cronograma '1020'**, examine as informações e selecione **OK**.
