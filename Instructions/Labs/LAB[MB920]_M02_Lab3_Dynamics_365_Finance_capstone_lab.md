---
lab:
  title: 'Laboratório 3: Laboratório de conclusão do Dynamics 365 Finance'
  module: 'Module 2: Learn the Fundamentals of Microsoft Dynamics 365 Finance'
ms.openlocfilehash: c6f655349c360df83fb064fe716cd712ff61c2aa
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909394"
---
## <a name="lab-3---dynamics-365-finance-capstone-lab"></a>Laboratório 3 – Laboratório de conclusão do Dynamics 365 Finance

## <a name="objective"></a>Objetivo

Durante este laboratório, você vai explorar os principais recursos do Microsoft Dynamics 365 Finance. Você vai explorar a contabilidade criando uma nova pessoa jurídica, adicionando uma nova conta e valores de dimensão e executando um balancete. Você vai explorar ainda contas a pagar criando um novo fornecedor, ordem de compra e fatura e, em seguida, liquidará a fatura. Por fim, você explorará contas a receber criando um novo cliente, uma fatura e um relatório de classificação por vencimento e, em seguida, aplicará o pagamento do cliente.

## <a name="lab-setup"></a>Configuração do Laboratório

   - **Tempo estimado**: 45 minutos

## <a name="exercise-1-explore-the-general-ledger"></a>Exercício 1: Explorar a contabilidade geral

### <a name="create-a-new-legal-entity"></a>Criar uma pessoa jurídica

1. Usando o painel de navegação, selecione **Módulos** > **Administração da organização** > **Organizações** > **Pessoas jurídicas**.

1. No Painel de Ações, selecione **+Novo** para criar uma pessoa jurídica.

1. No painel **Nova pessoa jurídica**, crie uma entidade usando as informações a seguir e depois selecione **OK**:

    | **Configuração** | **Valor** |
    | :--- | :--- |
    | Nome | Treinamento da Contoso EUA |
    | Empresa | USTR |
    | País/Região | EUA |

1. Na página Pessoas jurídicas, selecione a FastTab **Endereços** e **Editar**.

1. Na caixa fato, insira as seguintes atualizações e, em seguida, selecione **OK**:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | CEP/Código postal| 98052|
    | Street| 123 Main Street|
    | Primário para país/região | Verifique se **Sim** está selecionado |

1. Selecione a FastTab **Informações de contato**.

1. Selecione **+Adicionar** e insira as seguintes informações de contato:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | Descrição| Escritório Principal|
    | Número/endereço do contato| 888-555-1234|
    | Primário| Marque a caixa de seleção |

1. Selecione a FastTab **Registro de impostos**.

1. Na caixa **Número de registro de impostos**, digite **88-1234567**.

1. No Painel de Ações, selecione **Salvar**.

1. No painel de navegação, selecione **Página Inicial**.

### <a name="create-a-new-account-in-an-existing-chart-of-accounts"></a>Criar uma conta em um plano de contas existente

1. Na página inicial, no canto superior direito, verifique se a empresa **USMF** está selecionada.  
    Se não estiver, selecione a empresa atualmente listada e altere-a para **USMF**.

1. Usando o painel de navegação, selecione **Módulos** > **Contabilidade** > **Plano de contas** > **Contas** > **Contas principais**.

1. No Painel de Ações, selecione **+Novo** para criar uma conta de receita.

1. Na página Contas principais, insira as seguintes atualizações:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | Conta principal| 401500|
    | Nome| Receita de treinamento|
    | Tipo de conta principal| Receita |

1. No Painel de Ações, selecione **Salvar**.

### <a name="add-a-new-dimension-value"></a>Adicionar um valor de dimensão

1. Usando o painel de navegação, selecione **Módulos** > **Contabilidade** > **Plano de contas** > **Dimensões** > **Dimensões financeiras**.

1. Na lista de navegação, selecione **ServiceLine**.  
    Você também pode usar a caixa **Filtro** para pesquisar **ServiceLine**.

1. No Painel de Ações, selecione **Valores de dimensão**.

1. No Painel de Ações, selecione **+ Novo**.

1. Nas caixas **Valor de dimensão** e **Descrição**, insira **Serviços de treinamento**.

1. No Painel de Ações, selecione **Salvar**.

### <a name="use-an-account-and-dimension-value-in-a-general-journal"></a>Usar um valor de conta e dimensão em um diário geral

1. Usando o painel de navegação, selecione **Módulos** > **Contabilidade** > **Entradas de diário** > **Diários gerais**.

1. No Painel de Ações, selecione **+ Novo**.

1. Na primeira linha da lista, na coluna **Nome**, selecione o menu e, em seguida, selecione **Diário geral**.

1. No Painel de Ações, selecione **Linhas**.

1. Na lista, na coluna **Data**, selecione o ícone calendário e altere a data para o 1º dia do mês.

1. Na coluna **Conta**, selecione o menu e insira as seguintes atualizações:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | MainAccount| 601200|
    | BusinessUnit| 004|
    | department| 025|
    | CostCenter| 009|
    | ItemGroup| Serviços|

1. Na caixa **Descrição**, digite **Reclassificação de despesa**.

1. Na caixa **Débito**, digite **1.000,00**.

1. Role para a direita e, na coluna **Contrapartida**, selecione o menu e insira as seguintes atualizações:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | MainAccount| 602200|
    | BusinessUnit| 004|
    | department| 025|
    | CostCenter| 009|
    | ItemGroup| Serviços|

1. No Painel de Ações, selecione **Salvar**.

1. No Painel de Ações, selecione **Validar** > **Validar**.  
    Aguarde a conclusão da validação do diário.

1. Revise a faixa de aviso.  
    Essa mensagem de aviso pode ser ignorada para este laboratório.

1. No Painel de Ações, selecione **Postar**.

### <a name="run-a-trial-balance-using-a-dimension-set"></a>Executar um balancete usando um conjunto de dimensões

1. Usando o painel de navegação, selecione **Módulos** > **Contabilidade** > **Consultas e relatórios** > **Balancete**.

1. Na página Balancete, selecione **Calcular saldos**.

1. O botão **Calcular saldos** está localizado nas configurações **DADOS A INCLUIR**.

1. Na tabela, revise os resultados.

1. Na página Balancete, em **Exibição Padrão**, expanda **Parâmetros**.

1. Em **DADOS A INCLUIR**, selecione o menu **Conjunto de dimensões financeiras** e depois **MA-BU-DEPT-CC**.

1. Selecione **Calcular saldos** para exibir as dimensões usadas no diário.

1. Feche a página.

## <a name="exercise-2-explore-accounts-payable"></a>Exercício 2: Explorar o contas a pagar

### <a name="create-a-vendor"></a>Criar um fornecedor

1. Usando o painel de navegação, selecione **Módulos** > **Contas a pagar** > **Fornecedores** > **Todos os fornecedores**.

1. No Painel de Ações, selecione **+Novo** para criar um fornecedor.

1. Na página Novo Registro, crie um fornecedor usando as seguintes informações:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | Conta do fornecedor| F00001|
    | Nome| ABC Training, Inc|
    | Grupo| 20|

1. No Painel de Ações, selecione **Salvar**.

1. Selecione a FastTab **Endereços** e **+Adicionar**.

1. No painel Novo endereço, insira as seguintes atualizações e selecione **OK**:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | Nome ou descrição| Escritório Principal|
    | CEP/Código postal| 98052|
    | Street| 123 Front Street|

1. No Painel de Ações, selecione **Salvar**.

1. Selecione a FastTab **Pagamento.**

1. Selecione o menu **Método de pagamento** e, em seguida, **selecione VERIFICAR**.

1. Selecione a FastTab **Imposto 1099** e insira as seguintes atualizações:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | Relatório 1099| Sim|
    | ID de imposto federal| 82-1234567|
    | Tipo de ID de imposto| Número de identificação do empregador|
    | Caixa 1099| DIVERSOS-03|

1. No Painel de Ações, selecione **Salvar**.

1. Feche o formulário.

### <a name="create-a-purchase-order-for-the-new-vendor"></a>Criar um pedido de compra para o novo fornecedor

1. Na página F00001: ABC Training, Inc, no Painel de Ações, selecione **Aquisição**.

1. No Painel de Ações, na guia **NOVO**, selecione **Ordem de compra**.

1. Na página Ordem de compra, em **Linhas de ordem de compra**, insira as seguintes atualizações:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | Número do item| S0001|
    | Quantidade| 2|

    >[!NOTE] Será preciso rolar para a direita para ver a coluna **Quantidade.**

1. No Painel de Ações, selecione **Salvar**.

1. No Painel de Ações, selecione **Comprar** e, na guia **AÇÕES**, selecione **Confirmar**.

### <a name="record-vendor-invoice-for-the-purchase-order"></a>Registrar a fatura do fornecedor para a ordem de compra

1. No Painel de Ações, selecione **Fatura**.

1. Na guia **GERAR**, selecione **Fatura**.

1. No Painel de Ações, selecione **Padrão de: quantidade de recebimento de produto**.

1. No menu **Quantidade padrão para linhas**, selecione **Quantidade ordenada** e **OK**.

1. Na página Fatura do fornecedor, insira as seguintes atualizações:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | Número| FAT001|
    | Descrição da fatura| Serviço de Instalação Inicial|
    | Data da fatura| *insira a data de hoje*|

1. No Painel de Ações, selecione **Salvar**.

1. No Painel de Ações, selecione **Atualizar status de conciliação**.

1. No Painel de Ações, selecione **Postar**.

### <a name="settling-the-vendor-invoice"></a>Liquidar a fatura do fornecedor

1. Usando o painel de navegação, selecione **Módulos** > **Contas a pagar** > **Pagamentos** > **Diário de pagamentos do fornecedor**.

1. No Painel de Ações, selecione **+ Novo**.

1. Na página Diário de pagamentos do fornecedor, na primeira linha, na coluna **Nome**, selecione o menu e depois **VendPay.**

1. No Painel de Ações, selecione **Linhas** para registrar um pagamento.

1. Na página Pagamentos do fornecedor, na caixa **Conta**, insira **F00001**.

1. Na barra de ferramentas, selecione **Liquidar transações**.

1. Na página Liquidar transações da ABC Training, Inc, na coluna **Marcar**, selecione a caixa de seleção.

1. No canto inferior direito, selecione **OK**.

1. No Painel de Ações, selecione **Gerar pagamentos**.

1. No painel **Gerar pagamentos**, insira as seguintes atualizações e selecione **OK**:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | Forma de pagamento| CHECK|
    | Conta bancária| USMF OPER|

1. No painel **Pagamento por cheque**, examine as informações e selecione **OK**.

    >[!ALERTA] Você verá um erro informando que **Não foi possível encontrar a impressora com o caminho**. Ignore isso. Não há impressoras instaladas no laboratório.

1. Role para a direita e, na coluna **Status do pagamento**, verifique se aparece **Enviado**.

1. No Painel de Ações, selecione **Validar** > **Validar**.

1. No Painel de Ações, selecione **Postar**.

## <a name="exercise-3-explore-accounts-receivable"></a>Exercício 3: Explorar o contas a receber

### <a name="create-a-customer"></a>Criar um cliente

1. Usando o painel de navegação, selecione **Módulos** > **Contas a receber** > **Clientes** > **Todos os clientes**.

1. No Painel de Ações, selecione **+Novo** para criar um cliente.

1. No painel **Criar cliente**, crie o cliente usando as informações a seguir e selecione **Salvar**:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | Conta do cliente| US-901|
    | Nome| Fabrikam Consulting Services|
    | Grupo de clientes| 30|
    | CEP/Código postal| 98052|
    | Street| 123 Middle Street|

1. Na página US-901 Fabrikam Consulting Services, selecione a FastTab **Padrões de pagamento**.

1. Selecione o menu **Método de pagamento** e, em seguida, **selecione VERIFICAR**.

1. Selecione a FastTab **Dimensões financeiras**.

1. Na caixa **BusinessUnit**, digite **004**.

1. No Painel de Ações, selecione **Salvar**.

### <a name="create-a-free-text-invoice-for-the-new-customer"></a>Criar uma fatura de texto livre para o novo cliente

1. No Painel de Ações, selecione **Fatura** e, na guia **NOVO**, selecione **Fatura de texto livre**.

1. Na página US-901 Fabrikam Consulting Services, no **cabeçalho** **Fatura de texto livre**, defina a data da **FATURA** como a data de hoje.

1. Em **Linhas da fatura**, faça as seguintes alterações:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | Descrição| Treinamento de serviço do consultor|
    | Conta principal| 401200|
    | Grupo de impostos sobre vendas| WA|
    | Quantidade| 1\.500,00|

1. No Painel de Ações, selecione **Imposto sobre vendas**.

1. Na página Transações de imposto sobre vendas, examine o registro e selecione **OK**.

1. No Painel de Ações, selecione **Postar**.

1. No painel **Postar fatura de teste gratuito**, em **OPÇÕES DE IMPRESSÃO**, defina **Imprimir fatura** como **Sim** e selecione **OK**.

1. No painel **Configurações de destino de impressão**, selecione **OK** para imprimir a fatura na tela.

1. Revise a fatura e, quando concluir, feche-a.

1. Feche o formulário.

### <a name="run-an-accounts-receivable-aging-report-to-check"></a>Executar um relatório de classificação por vencimento de contas a receber para verificar

1. Usando o painel de navegação, selecione **Módulos** > **Crédito e cobranças** > **Consultas e relatórios** > **Clientes** > **Relatório de classificação por vencimento de clientes**.

1. No painel **Relatório de classificação por vencimento de clientes**, insira as seguintes atualizações e selecione **OK**:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | Classificação por vencimento de| Data de hoje|
    | Definição do período de classificação por vencimento| 30_60_90_180|
    | Detalhes| Anos|

1. No Relatório de classificação por vencimento de clientes, selecione o ícone de seta para baixo da **Próxima página** e role até a última página.
    Examine a fatura que foi criada para o cliente US-901.

1. Feche o formulário.

### <a name="apply-customer-payment-for-the-free-text-invoice"></a>Aplicar pagamento de cliente para a fatura de texto livre

1. Usando o painel de navegação, selecione **Módulos** > **Contas a receber** > **Pagamentos** > **Diário de pagamentos do cliente**.

1. No Painel de Ações, selecione **+ Novo**.

1. Na página Diário de pagamentos do cliente, na coluna **Nome**, selecione o menu e depois **CustPay**.

1. No Painel de Ações, selecione **Inserir pagamentos do cliente**.

1. Na caixa **Cliente**, digite **US-901**.  
    Aguarde o carregamento dos dados e, na coluna **Marcar**, marque a caixa de seleção.

1. Acima da grade, na caixa **Valor**, digite **1.597,50**. O valor mostrado na caixa **Valor restante** deve ser alterado automaticamente de **1.597,50** para **0**.  
    Talvez seja necessário selecionar um espaço vazio para o valor ser calculado.

1. Na caixa **Referência de pagamento**, digite **Verificar 123**.

1. No Painel de Ações, selecione **Salvar no diário**.

1. Feche o formulário.

1. No Painel de Ações, selecione **Linhas**.

1. No Painel de Ações, selecione **Validar** > **Validar**.

1. No Painel de Ações, selecione **Postar**.
