---
lab:
    title: 'Laboratório 3: Laboratório do trabalho de conclusão de curso do Dynamics 365 Finance'
    module: 'Módulo 2: Conheça os princípios básicos do Microsoft Dynamics 365 Finance'
---

## Laboratório 3 - Laboratório do trabalho de conclusão de curso do Dynamics 365 Finance

## Objetivo

Neste laboratório, vamos ver os principais recursos do Microsoft Dynamics 365 Finance. Você vai descobrir a Contabilidade criando uma nova entidade, adicionando uma nova conta e valores de dimensão, e executando um balancete. Também vai conhecer as contas a pagar criando um novo fornecedor, ordem de compra e fatura, e depois definindo a fatura. Por fim, você vai explorar as contas a receber criando um novo cliente, uma fatura e um relatório de classificação por vencimento, e depois aplicar o pagamento de cliente.

## Configuração do laboratório

   - **Tempo estimado**: 45 minutos

## Exercício 1: Explorar a Contabilidade

### Criar uma nova entidade legal

1. Usando o painel de navegação, selecione **Módulos** > **Administração da organização** > **Organizações** > **Entidades legais**.

1. No painel de ações, selecione **+Novo** para criar uma nova entidade legal.

1. No painel **Nova entidade**, crie uma nova entidade usando as seguintes informações e depois selecione **OK**:

    | **Configuração** | **Valor** |
    | :--- | :--- |
    | Nome | Contoso Training USA |
    | Empresa | USTR |
    | País/região | EUA |

1. Na página Entidades legais, selecione a guia rápida **Endereços** e depois **Editar**.

1. Na caixa de fato, insira as seguintes atualizações e selecione **OK**:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | CEP/Código postal| 98052|
    | Rua| 123 Main Street|
    | Principal para país/região | Verifique se a opção **Sim** está selecionada |

1. Selecione a guia rápida **Informações de contato**.

1. Selecione **+Adicionar** e depois insira as seguintes informações de contato:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | Descrição| Escritório Principal|
    | Número de contato/endereço| 888-555-1234|
    | Principal| Marque a caixa de seleção |

1. Selecione a guia rápida **Registro de impostos**.

1. Na caixa **Número de inscrição de imposto**, digite **88-1234567**.

1. No painel de ações, selecione **Salvar**.

1. No painel de navegação, selecione **Página inicial**.

### Crie uma nova conta em um plano de contas existente

1. Na home page, na parte superior direita, verifique se a empresa **USMF** está selecionada.  
    Caso não esteja, selecione a empresa listada no momento e depois altere para **USMF**.

1. Usando o painel de navegação, selecione **Módulos** > **Contabilidade** > **Plano de contas** > **Contas** > **Contas principais**.

1. No painel de ações, selecione **+Novo** para criar uma nova conta de receita.

1. Na página Contas principais, insira as seguintes atualizações:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | Conta Principal| 401500|
    | Nome| Receita de Treinamento|
    | Tipo de conta principal| Receita |

1. No painel de ações, selecione **Salvar**.

### Adicionar um novo valor de dimensão

1. Usando o painel de navegação, selecione **Módulos** > **Contabilidade** > **Plano de contas** > **Dimensões** > **Dimensões financeiras**.

1. Na lista de navegação, selecione **ServiceLine**.  
    Também é possível usar a caixa **Filtro** para procurar **ServiceLine**.

1. No painel de ações, selecione **Valores de dimensão**.

1. No painel de ações, selecione **+Novo**.

1. Nas caixas **Valor da dimensão** e **Descrição**, digite **Serviços de Treinamento**.

1. No painel de ações, selecione **Salvar**.

### Use um valor de conta e de dimensão em um diário geral

1. Usando o painel de navegação, selecione **Módulos** > **Contabilidade** > **Entradas de diário** > **Diários gerais**.

1. No painel de ações, selecione **+Novo**.

1. Na primeira linha da lista, na coluna **Nome**, selecione o menu e depois **Diário Geral**.

1. No painel de ações, selecione **Linhas**.

1. Na lista, na coluna **Data**, selecione o ícone de calendário e depois altere a data para o primeiro dia do mês.

1. Na coluna **Conta**, selecione o menu e depois insira as seguintes atualizações:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | MainAccount| 601200|
    | BusinessUnit| 004|
    | Departamento| 025|
    | CostCenter| 009|
    | ItemGroup| Serviços|

1. Na caixa **Descrição**,digite **Reclassificação de despesa**.

1. Na caixa **Débito**, digite **1000,00**.

1. Role a tela para a direita e, na coluna **Contrapartida**, selecione o menu e depois insira as seguintes atualizações:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | MainAccount| 602200|
    | BusinessUnit| 004|
    | Departamento| 025|
    | CostCenter| 009|
    | ItemGroup| Serviços|

1. No painel de ações, selecione **Salvar**.

1. No painel de ações, selecione **Validar** > **Validar**.  
    Aguarde até a conclusão da validação do diário.

1. Examine a faixa de aviso.  
    Esse aviso pode ser ignorado para este laboratório.

1. No painel de ações, selecione **Lançar**.

### Executar um balancete usando um conjunto de dimensões

1. Usando o painel de navegação, selecione **Módulos** > **Contabilidade** > **Consultas e relatórios** > **Balancete**.

1. Na página Balancete, selecione **Calcular saldos**.

1. O botão **Calcular saldos** fica nas configurações **DADOS A SEREM INCLUÍDOS**.

1. Examine os resultados na tabela.

1. Na página Balancete, em **Exibição Padrão**, expanda **Parâmetros**.

1. Em **DADOS A SEREM INCLUÍDOS**, selecione o menu **Conjunto de dimensões financeiras** e depois **MA-BU-DEPT-CC**.

1. Selecione **Calcular saldos** para visualizar as dimensões usadas no diário.

1. Feche a página.

## Exercício 2: Explorar as Contas a pagar

### Criar um fornecedor

1. Usando o painel de navegação, selecione **Módulos** > **Contas a Pagar** > **Fornecedores** > **Todos os fornecedores**.

1. No painel de ações, selecione **+Novo** para criar um fornecedor.

1. Na página Novo Registro, crie um novo fornecedor com as seguintes informações:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | Conta do fornecedor| V00001|
    | Nome| ABC Training, Inc|
    | Grupo| 20|

1. No painel de ações, selecione **Salvar**.

1. Selecione a guia rápida **Endereços** e depois **+Adicionar**.

1. No painel Novo endereço, digite as seguintes atualizações e selecione **OK**:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | Nome ou descrição| Escritório Principal|
    | CEP/Código postal| 98052|
    | Rua| 123 Front Street|

1. No painel de ações, selecione **Salvar**.

1. Selecione a guia rápida **Pagamento**.

1. Selecione o menu **Forma de pagamento** e, em seguida, selecione **CHEQUE**.

1. Selecione a guia rápida **Imposto 1099** e depois insira as seguintes atualizações:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | Relatório 1099| Sim|
    | ID de imposto federal| 82-1234567|
    | Tipo de ID do Imposto| Número de Identificação de Empregador|
    | Caixa 1099| MISC-03|

1. No painel de ações, selecione **Salvar**.

1. Feche o formulário.

### Criar uma ordem de compra para o novo fornecedor

1. Na página V00001 : ABC Training, Inc, no painel de ações, selecione **Compras.**

1. No painel de ações, na guia **NOVA**, selecione **Ordem de compra**.

1. Na página Ordem de compra, em **Linhas da ordem de compra**, digite as seguintes atualizações:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | Número do item| S0001|
    | Quantidade| 2|

    >[!OBSERVAÇÃO] Talvez seja preciso rolar a tela para a direita para ver a coluna **Quantidade**.

1. No painel de ações, selecione **Salvar**.

1. No painel de ações, selecione **Comprar** e depois, na guia **AÇÕES**, selecione **Confirmar**.

### Registrar a fatura do fornecedor para a ordem de compra

1. No painel de ações, selecione **Fatura**.

1. Na guia **GERAR**, selecione **Fatura**.

1. No painel de ações, selecione **Padrão de: Quantidade de recebimento de produtos**.

1. No menu **Quantidade padrão para linhas**, selecione **Quantidade encomendada** e depois **OK**.

1. Na página Fatura de fornecedor, insira as seguintes atualizações:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | Número| INV001|
    | Descrição da fatura| Serviço de instalação inicial|
    | Data da fatura| *insira a data de hoje*|

1. No painel de ações, selecione **Salvar**.

1. No painel de ações, selecione **Atualizar status de conciliação**.

1. No painel de ações, selecione **Lançar**.

### Liquidação da fatura do fornecedor

1. No painel de navegação à esquerda, selecione **Módulos** > **Contas a pagar** > **Pagamentos** > **Diário de pagamentos de fornecedor**.

1. No painel de ações, selecione **+Novo**.

1. Na página Diário de pagamentos do fornecedor, na primeira linha, na coluna **Nome**, selecione o menu e depois **VendPay**.

1. No painel de ações, selecione **Linhas** para registrar um pagamento.

1. Na página Pagamentos de fornecedor, na caixa **Conta**, digite **V00001**.

1. Na barra de ferramentas, selecione **Liquidar transações**.

1. Na página Liquidar transações para ABC Training, Inc, na coluna **Marcar**, marque a caixa de seleção.

1. No canto inferior direito, selecione **OK**.

1. No painel de ações, selecione **Gerar pagamentos**.

1. No painel **Gerar pagamentos**, insira as seguintes atualizações e selecione **OK**:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | Forma de pagamento| CHEQUE|
    | Conta bancária| OPER USMF|

1. No painel **Pagamento por cheque**, examine as informações e selecione **OK**.

    >[!ALERT] Você verá um erro que diz **Não é possível localizar a impressora com o caminho**. É só ignorá-lo. Não há impressoras instaladas no laboratório.

1. Role a tela para a direita e, na coluna **Status do pagamento**, verifique se a opção **Enviado** está exibida.

1. No painel de ações, selecione **Validar** > **Validar**.

1. No painel de ações, selecione **Lançar**.

## Exercício 3: Explorar as Contas a receber

### Criar um cliente

1. Usando o painel de navegação, selecione **Módulos** > **Contas a pagar** > **Clientes** > **Todos os clientes**.

1. No painel de ações, selecione **+Novo** para criar um cliente.

1. No painel **Criar cliente**, crie o novo cliente usando as seguintes informações e depois selecione **Salvar**:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | Conta de cliente| US-901|
    | Nome| Fabrikam Consulting Services|
    | Grupo de clientes| 30|
    | CEP/Código postal| 98052|
    | Rua| 123 Middle Street|

1. Na página US-901 Fabrikam Consulting Services, selecione a guia rápida **Padrões de pagamento**.

1. Selecione o menu **Forma de pagamento** e, em seguida, selecione **CHEQUE**.

1. Selecione a guia rápida **Dimensões financeiras**.

1. Na caixa **BusinessUnit**, digite **004**.

1. No painel de ações, selecione **Salvar**.

### Criar uma fatura de texto livre para o novo cliente

1. No painel de ações, selecione **Fatura** e, na guia **NOVO**, selecione **Fatura de texto livre**.

1. Na página US-901 Fabrikam Consulting Services, no **cabeçalho** **Fatura de texto livre**, defina a data da **FATURA** como a data de hoje.

1. Em **Linhas da fatura**, faça as seguintes alterações:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | Descrição| Consultant Service Training|
    | Conta principal| 401200|
    | Grupo de impostos sobre vendas| WA|
    | Valor| 1500,00|

1. No painel de ações, selecione **Imposto**

1. Na página Transações de imposto sobre vendas, examine o registro e selecione **OK**.

1. No painel de ações, selecione **Lançar**.

1. No painel **Lançar fatura de texto livre**, em **OPÇÕES DE IMPRESSÃO**, defina **Imprimir fatura** como **Sim** e depois selecione **OK**.

1. No painel **Configurações de destino de impressão**, selecione **OK** para imprimir a fatura para a tela.

1. Examine a fatura e, quando terminar, feche-a.

1. Feche o formulário.

### Executar um relatório de classificação por vencimento de contas a receber para cheque

1. Usando o painel de navegação, selecione **Módulos** > **Crédito e cobranças** > **Consultas e relatórios** > **Clientes** > **Relatório de classificação por vencimento de clientes**.

1. No painel **Relatório de classificação por vencimento de clientes**, digite as seguintes atualizações e selecione **OK**:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | Classificação por vencimento a partir de| A data de hoje|
    | Definição do período de classificação por vencimento| 30_60_90_180|
    | Detalhes| Anos|

1. No Relatório de classificação por vencimento de clientes, selecione o ícone de seta para baixo **Próxima Página** e depois role a tela para a última página.
    Examine a fatura que foi criada para o cliente US-901.

1. Feche o formulário.

### Aplicar pagamento de cliente para a fatura de texto livre

1. Usando o painel de navegação, selecione **Módulos** > **Contas a receber** > **Pagamentos** > **Diário de pagamentos de cliente**.

1. No painel de ações, selecione **+Novo**.

1. Na página Diário de pagamentos do cliente na coluna **Nome**, selecione o menu e depois **CustPay**.

1. No painel de ações, selecione **Inserir pagamentos de cliente**.

1. Na caixa **Cliente**, digite **US-901**.  
    Espere o carregamento dos dados e depois, na coluna **Marcar**, marque a caixa de seleção.

1. Acima da grade, na caixa **Valor**, digite **1597,50**. O valor mostrado na caixa **Valor restante** deve ser alterado automaticamente de **1.597,50** para **0**.  
    Talvez seja preciso selecionar um espaço vazio para o cálculo do valor.

1. Na caixa **Referência de pagamento**, digite **Cheque 123**.

1. No painel de ações, selecione **Salvar no diário**.

1. Feche o formulário.

1. No painel de ações, selecione **Linhas**.

1. No painel de ações, selecione **Validar** > **Validar**.

1. No painel de ações, selecione **Lançar**.
