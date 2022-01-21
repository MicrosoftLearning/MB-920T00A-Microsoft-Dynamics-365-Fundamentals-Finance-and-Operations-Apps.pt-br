---
lab:
    title: 'Laboratório 8: Laboratório do trabalho de conclusão de curso do Dynamics 365 Supply Chain Management'
    module: 'Módulo 1: Conheça os Princípios básicos do Microsoft Dynamics 365 Supply Chain Management'
---

## Laboratório 8 - Laboratório do trabalho de conclusão de curso do Dynamics 365 Supply Chain Management

## Objetivo

Neste laboratório, você vai explorar a criação de produtos e a manutenção de preços. Também vai analisar os principais processos comerciais de cadeias de fornecimento, como gerenciamento de estoque, compras e fornecimento.

## Configuração do laboratório

- **Tempo estimado**: 45 minutos 

## Exercício 1: Explorar o gerenciamento de produtos

### Criar um produto

Na Contoso Entertainment System USA (USMF), você precisa criar um novo item para uma caixa de som recém-configurada a ser comprada dos fornecedores.

1. Na home page, na parte superior direita, verifique se a empresa **USMF** está selecionada.

1. Caso não esteja, selecione a empresa listada no momento e depois altere para **USMF**.

1. Usando o painel de navegação, selecione **Módulos** > **Gerenciamento de informações do produto** > **Produtos** > **Produtos liberados**.

1. Na página Detalhes do produto liberado, no painel de ações, selecione **+ Novo**.

1. No painel **Novo produto liberado**, no menu **Tipo de produto**, verifique se a opção **Item** está selecionada.

1. No menu **Subtipo do produto**, verifique se a opção **Produto** está selecionada.

1. Selecione o menu **Grupo de dimensões de rastreamento** e, em seguida, selecione **Nenhum**.

1. Em **IDENTIFICAÇÃO**, na caixa **Número do produto**, digite **GTL201**.

1. Na caixa **Nome do produto**, digite **Caixa de som**.

1. Em **TRIBUTAÇÃO SOBRE AS VENDAS**, selecione o menu **Grupo de impostos do item** e, em seguida, **TUDO**.

1. Em **TRIBUTAÇÃO DE COMPRA**, selecione o menu **Grupo de impostos do item** e, em seguida **TUDO**.

1. Em **PREÇOS**, na caixa **Preço de compra**, digite **30,00**.

1. Na caixa **Preço de vendas**, digite **30,00**.

1. Em **GRUPOS DE REFERÊNCIA**, selecione o menu **Grupo de modelo do item** e, em seguida, **FIFO Primeiro a entrar, primeiro a sair**.

1. Selecione o menu **Grupo de itens** e, em seguida, **CarAudio**.

1. Selecione o menu **Grupo de dimensões de armazenamento** e, em seguida, **SiteWH**.

1. Em **UNIDADES DE MEDIDAS**, verifique se os seguintes valores estão definidos:

    | **Configuração**| **Valor**|
    | :--- | :--- |
    | Unidade de estoque| cd|
    | Unidade de compra| cd|
    | Unidade de venda| cd|
    | Unidade de BOM| cd|

1. Selecione **OK**.

1. Para assegurar que o produto seja finalizado, no painel de ações, selecione **Produto** e, em seguida, em **Manter**, selecione **Validar**.

1. Verifique se é apresentada a faixa de informações confirmando que todos os valores de campo necessários foram validados.

1. Feche todas as páginas e volte para a home page.

## Exercício 2: Explorar o gerenciamento de depósito

### Criar um depósito

1. No painel de navegação, selecione **Módulos** > **Gerenciamento de estoque** > **Configuração** > **Divisão de estoque** > **Depósitos**.

1. Na página Depósitos, no painel de ações, selecione **Novo**.

1. Na caixa **Depósito**, digite **150**.

1. Na caixa **Nome**, digite **Outpost de depósito**.

1. Selecione o menu **Local** e, em seguida, **1 Produção de caixas de som para casa**.

1. Selecione a guia rápida **Nomes de localização**.

1. As opções nessa seção definem o formato padrão para nomes de localização.

1. Defina as opções **Incluir corredor** e **Incluir rack** como **Sim**.

1. Selecione a opção **Incluir prateleira** como **Sim**.

1. Na caixa **Formatar**, para a prateleira, digite **-##**.

1. No painel de ações, selecione **Depósito**.

1. Em **Manter**, selecione **Assistente de Localização**.

1. Na página de boas-vindas, leia as informações e, em seguida, no canto inferior direito, selecione **Avançar**.

1. Desmarque as caixas de seleção **Docas de entrada** e **Locais de massa**.

1. Selecione **Avançar** e examine as informações.

1. Acesse cada página e, quando terminar, selecione **Concluir**.

1. Feche a página e volte para a home page.

### Criar um contrato comercial para preço de venda

1. Usando o painel de navegação, selecione **Módulos** > **Gerenciamento de informações do produto** > **Produtos** > **Produtos liberados**.

1. Na página Detalhes de produtos liberados, procure o número de produto **GTL201**.

1. À esquerda de **GTL201**, marque a caixa de seleção **Selecionar ou cancelar seleção da linha**.

1. No painel de ações, selecione **Vender** e, em seguida, em **CONTRATOS COMERCIAIS**, selecione **Criar contratos comerciais**.

1. No painel de ações, selecione **+Novo**.

1. Selecione a coluna **Nome**, selecione o menu e depois **Preço_S**.

1. No painel de ações, selecione **Linhas**.

1. Nas Linhas do diário, página de contrato comercial, na coluna **Relação de item**, selecione o menu e depois **GTL201**.

1. Esse é o número do item do produto que você criou.

1. Na coluna **Depósito**, selecione o menu e depois **150**.

1. Talvez seja necessário rolar a tela para a direita para ver a coluna.

1. Na coluna **Valor na moeda**, na caixa, digite **100,00**.

1. Na seção Detalhes, na caixa **De**, digite a primeira data do ano atual.

1. No painel de ações, selecione **Validar** > **Validar todas as linhas.**

1. No painel **Lançamento no diário de preço/desconto**, selecione **OK**.

1. Verifique se não há erros.

1. No painel de ações, selecione **Lançar**.

1. No painel **Lançamento no diário de preço/desconto**, selecione **OK**.

1. Verifique se a operação foi concluída.

1. Feche a página.

1. Na página Detalhes do produto liberado, no painel de ações, em **Vender** > **CONTRATOS COMERCIAIS**. selecione **Exibir contratos comerciais**.

1. O contrato comercial deve ser lançado. Examine a linha para observar as informações de preço.

1. Feche as páginas e volte para a home page.

## Exercício 3: Explorar o gerenciamento da produção

### Criar uma ordem de produção para um produto

1. No painel de navegação, selecione **Módulos** > **Controle de produção** > **Ordens de produção** > **Todas as ordens de produção**.

1. No painel de ações, selecione **Nova ordem de produção**.

1. No painel **Criar ordem de produção**, em **IDENTIFICAÇÃO**, na caixa **Número do item**, digite **D0004** e depois selecione o item identificado.

1. Em **PRODUÇÃO**, na caixa **Entrega**, selecione uma data a um mês da data de hoje.

1. A data de entrega indica quando a ordem de produção deve terminar para que a entrega seja feita a tempo. Essa data pode ser usada no processo de agendamento. Por exemplo, você pode agendar a ordem retroativa a partir da data de entrega.

1. Na caixa **Quantidade**, digite **30**.

1. Selecione **Criar**.

1. Feche todas as páginas e volte para a home page.

## Exercício 4: Explorar o gerenciamento de estoque

### Criar um diário de contagem com o produto para o depósito criado

1. Usando o painel de navegação, selecione **Módulos** > **Gerenciamento de estoque** > **Entradas de diário** > **Contagem de itens > Contagem**.

1. No painel de ações, selecione **+Novo**.

1. No painel **Criar diário do estoque**, em **Contagem por**, selecione o botão de alternância **Depósito** para configurá-lo como **Sim**.

1. Selecione **OK**.

1. Na página Diário de contagem de estoque, na guia rápida **Detalhes do cabeçalho do diário**, em **Linhas do diário** na barra de ferramentas, selecione **+Novo**.

1. Na coluna **Número do item**, selecione o menu e depois **GTL201**.

1. Na coluna **Depósito**, selecione o menu e depois **150**.

1. Na caixa **Contado**, digite **100,00**.

1. Isso especificará o número de itens armazenados no depósito para esse produto.

1. No painel de ações, selecione **Validar**.

1. No painel **Verificar diário**, selecione **OK**.

1. No painel de ações, selecione **Lançar**.

1. No painel **Diário de lançamentos**, selecione **OK**.

1. Feche todas as páginas e volte para a home page.

### Verifique o estoque disponível do produto

1. Usando o painel de navegação, selecione **Módulos** > **Gerenciamento de estoque** > **Consultas e relatórios** > **Lista disponível**.

1. No painel de ações, selecione **Dimensões**.

1. No painel **Mostrar dimensões**, em **DIMENSÕES DE ARMAZENAMENTO**, marque as caixas de seleção **Local** e **Depósito** e depois selecione **OK**.

1. No painel **Filtros**, selecione **Aplicar**.

1. Localize e examine o estoque disponível para **GTL201**.

1. Feche todas as páginas e volte para a home page.

## Exercício 5: Explorar as compras e o fornecimento

### Criar uma ordem de compra com um produto

1. Usando o painel de navegação, selecione **Módulos** > **Compras e fornecimento** > **Ordens de compra** > **Todas as ordens de compra**.

1. Na página Todas as ordens de compra, no painel de ações, selecione **+ Nova**.

1. No painel **Criar ordem de compra**, selecione o menu **Conta de fornecedor** e, em seguida, **US-101**.

1. Quando você seleciona um fornecedor, os detalhes de registro de fornecedor, como endereço, conta de fatura, condições de entrega e modo de entrega, são copiados como valores padrão para o cabeçalho da ordem. Você pode alterar esses valores a qualquer momento.

1. Na seção **Geral**, em **DIMENSÕES DE ARMAZENAMENTO**, selecione o menu **Local** e, em seguida, selecione **1 Produção de caixas de som para casa**.

1. Em **DATAS**, selecione uma **Data de entrega** para uma semana a partir de hoje.

1. Selecione **Administração**.

1. Selecione o menu **Autor da ordem** e depois **Lars Giusti** para especificar quem está fazendo o pedido.

1. No painel **Criar ordem de compra**, selecione **OK**.

1. Na barra de ferramentas, selecione **Linha de ordem de compra**.

1. Em **EXIBIR**, selecione **Dimensões**.

1. No painel **Mostrar dimensões**, em **DIMENSÕES DO PRODUTO**, marque a caixa de seleção **Cor**.

1. Selecione **OK**.

1. Na coluna **Número do item**, selecione o menu e depois **T0005**.

1. Na coluna **Número da grade**, selecione o menu e depois uma das cores.

1. No campo **Quantidade**, digite **15**.

1. Nas **Linhas da ordem de compra**, na parte inferior da página, selecione a guia rápida **Detalhes da linha**.

1. Talvez essa guia já esteja expandida.

1. Selecione a guia **Entrega** e, na caixa **Data de entrega**, use a data atribuída no momento ou digite uma data futura.  
    Uma data de entrega única pode ser atribuída a cada linha da ordem. A data é herdada do campo no cabeçalho da ordem de compra, mas você pode mudar isso.

1. Anote o número da sua ordem de compra. Você precisará fazer isso depois.

1. No painel de ações, selecione **Salvar**.

1. Feche a página Linha da ordem de compra.

1. Na página Todas as ordens de compra, use o recurso **Filtro** para procurar sua nova ordem de compra.

1. Quando terminar, feche a página Todas as ordens de compra e volte para a home page.
