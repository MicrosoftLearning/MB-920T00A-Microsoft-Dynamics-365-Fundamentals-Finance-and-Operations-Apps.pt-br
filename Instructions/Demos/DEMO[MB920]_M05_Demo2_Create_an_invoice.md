---
demo:
  title: 'Demonstração 2: Criar uma fatura'
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
---

## <a name="demo-2---create-an-invoice"></a>Demonstração 2 — Criar uma fatura

1. Navegue até o workspace  **Gerenciamento de projetos**.  
    In this demo, we'll go over the process of invoicing a single project within project operations. Although it's possible to perform mass invoicing, for demonstration purposes we will focus on just a single time and material project. We'll also see the posting results and financial insights within the project statement. Let's start with project invoicing. 

1. In the top-right company picker, verify the legal entity you are connected to is<bpt id="p1"> **</bpt>USSI<ept id="p1">**</ept>. If it's not, change the legal entity to<bpt id="p1"> **</bpt>USSI<ept id="p1">**</ept>.  
    From the<bpt id="p1"> **</bpt>Project management<ept id="p1">**</ept> workspace, we can see all the active projects. We can search for projects using the filter, or in this example, we will select a known Project ID. 

1. Na tabela  **Projetos ativos** , na coluna  **ID de Projeto** , selecione  **00000093 Contoso Consulting**.  

1. Em seguida, abra a página  **Propostas de fatura de projetos**  para exibir todas as faturas anteriores processadas para a Contoso Consulting. 

1. No painel de ações, na guia  **FATURA** , selecione  **Propostas de fatura de projetos**. 

1. Na página de  **Propostas de fatura de projetos** , na barra de navegação, selecione  **Novo** e  **Proposta de fatura**.  
    Essa é uma fatura de material e tempo simples, portanto, não precisamos selecionar a opção para proposta de fatura na regra de cobrança. 

    ![Uma captura de tela da página de propostas de fatura de projetos com a nova proposta de fatura realçada.](./media/projops_invoice_1_new_invoice_proposal.png)

1. No painel  **Criar proposta de fatura** , aponte para as caixas em  **Selecionar transações**.  
    From here, we can select things such as the invoicing method, the invoice date, the funding source, and the project. We can also choose to include sub projects, as well as incorporate transaction types, the start and end dates for transactions, and any financial dimensions we need. 

    ![Uma captura de tela do painel criar proposta de fatura com a seção selecionar transações realçada.](./media/projops_invoice_2_select_transactions.png)

1. Do menu suspenso **Projeto** , selecione  **00000093 Contoso Consulting**. 

1. Para este exemplo, verifique se a  **Data da fatura** está definida como  **01/02/21**, se a  **Data de início**  está definida como  **01/02/21** e se a data de término é a data de hoje.  
    Depois que as seleções forem feitas, selecione o botão Pesquisar para localizar as transações que atendem a esses parâmetros.

1. Selecione  **Pesquisar**.  
    Nesta demonstração, vamos examinar o processo de faturar um único projeto nas operações de projeto.

1. Na guia  **Transações de projeto** , selecione  **Selecionar todos**.

1. Selecione  **OK**. 

1. Na página  **Propostas de fatura** , aponte para a coluna  **Valor da linha de fatura** .  
    Aqui podemos ver o valor e o resumo da fatura, as transações por hora e as despesas.

    ![Uma captura de tela da página de proposta de fatura com a coluna valor da linha da fatura realçada.](./media/projops_invoice_3_invoice_line_amount_column.png)

1. Aponte para a guia  **Hora** . 

1. Aponte para a guia **Despesas**.  
    Também é possível alternar e examinar a transação de despesas.  
Em seguida, vejamos o botão totais para conferir como fica a fatura do ponto de vista do custo e da receita.

1. Na barra de navegação, selecione  **Totais**.

1. Na página  **Totais**, aponte para a coluna  **CONTABILIDADE**, a coluna  **CLIENTE**  e a  **coluna Desconto de linha**.  
    Na tela totais, podemos ver qual será o impacto na contabilidade, as informações do cliente, como limites de crédito, descontos, impostos sobre vendas e o impacto líquido da fatura. 

1. No lado direito da tela, selecione  **X** para fechar a página.  
    Embora seja possível executar o faturamento em lote, para fins de demonstração, vamos nos concentrar apenas em um único projeto de material e tempo. 

1. Na página  **Proposta de fatura** , na barra de navegação, selecione  **Visualização de impressão**. 

1. Na caixa de diálogo, selecione  **Visualização de impressão**.  
    Aqui você pode ver um exemplo de visualização de impressão para uma Fatura pro forma. 

1. Selecione **X** para fechar a página.  
    Quando validarmos todas as informações e estivermos satisfeitos com a Visualização de impressão da fatura, podemos lançar a proposta de fatura.

1. Na barra de navegação, selecione  **Publicar**.

1. Selecione a guia  **Parâmetros** .

1. Em  **PARÂMETROS**, defina  **Publicação** como **Sim**.

1. Em  **OPÇÕES DE IMPRESSÃO**, defina  **Imprimir fatura** como  **Sim**.

1. Selecione  **OK**.

1. Na página  **Fatura** , aponte para o número da  **Fatura**.  
    Agora temos um número de fatura que foi gerado.  
    Depois que a fatura tiver sido lançada, poderemos revisar as informações no diário de faturas e fazer uma busca detalhada nas transações do razão.

1. Navegue até o workspace  **Gerenciamento de projetos**.

1. Na tabela  **Ativar projetos** , selecione o projeto  **00000093** **Contoso Consulting**.

1. No painel de ações, na guia  **FATURA** , selecione  **Diários de fatura**.

1. Na página  **Diário de faturas** , na barra de ações, selecione  **Comprovante**.

1. Na página  **Transações de comprovante** , aponte para a coluna  **Conta contábil**.  
    Também veremos os resultados de lançamento e as informações financeiras no demonstrativo de projeto.

1. Navegue até o workspace  **Gerenciamento de projetos** . 

1. Na tabela  **Ativar projetos** , selecione o projeto  **00000093 Contoso Consulting**.

1. Na página  **Contoso Consulting** , na barra de navegação, selecione  **Controle**.  
    Aqui, podemos ver todos os detalhes do projeto.  
    Em seguida, vamos examinar as finanças do projeto em um demonstrativo de projeto.

1. Selecione  **Demonstrativos do projeto**.

1. Na página  **Demonstrativos do projeto** , aponte para a seção  **DATA DO PROJETO** .  
É possível criar um demonstrativo para qualquer intervalo de datas que desejar.

1. Selecione a caixa de data  **De** e digite  **1/2021**.
1. 
1. Selecione a caixa de data  **Até** e insira a data de hoje.

1. Ao concluir, selecione  **Calcular**.

    ![Uma captura de tela da página de demonstrativos do projeto com a opção calcular realçada.](./media/projops_invoice_4_calculate.png)

1. Aponte para  **Transações**.  
    Vamos começar com o faturamento do projeto.
