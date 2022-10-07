---
demo:
  title: 'Demonstração 2: Criar uma fatura'
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
---

## <a name="demo-2---create-an-invoice"></a>Demonstração 2 — Criar uma fatura

1. Navegue até o workspace  **Gerenciamento de projetos**.  
    Nesta demonstração, vamos examinar o processo de faturar um único projeto nas operações de projeto. Embora seja possível executar o faturamento em lote, para fins de demonstração, vamos nos concentrar apenas em um único projeto de material e tempo.Também veremos os resultados de lançamento e as informações financeiras no demonstrativo de projeto. Vamos começar com o faturamento do projeto. 

1. No seletor da empresa no canto superior direito, verifique se a pessoa jurídica à qual você está conectado é  **USSI**. Se não for, altere-a para  **USSI**.  
    No workspace  **Gerenciamento de projetos**, podemos ver todos os projetos ativos.Podemos pesquisar projetos usando o filtro ou, neste exemplo, selecionaremos uma ID de projeto conhecida. 

1. Na tabela  **Projetos ativos** , na coluna  **ID de Projeto** , selecione  **00000093 Contoso Consulting**.  

1. Em seguida, abra a página  **Propostas de fatura de projetos**  para exibir todas as faturas anteriores processadas para a Contoso Consulting. 

1. No painel de ações, na guia  **FATURA** , selecione  **Propostas de fatura de projetos**. 

1. Na página de  **Propostas de fatura de projetos** , na barra de navegação, selecione  **Novo** e  **Proposta de fatura**.  
    Essa é uma fatura de material e tempo simples, portanto, não precisamos selecionar a opção para proposta de fatura na regra de cobrança. 

    ![Uma captura de tela da página de propostas de fatura de projetos com a nova proposta de fatura realçada.](./media/projops_invoice_1_new_invoice_proposal.png)

1. No painel  **Criar proposta de fatura** , aponte para as caixas em  **Selecionar transações**.  
    Aqui, podemos selecionar opções como o método de faturamento, a data da fatura, a fonte de financiamento e o projeto.Também podemos optar por incluir subprojetos, assim como incorporar tipos de transação, as datas de início e de término das transações e quaisquer dimensões financeiras de que precisarmos. 

    ![Uma captura de tela do painel criar proposta de fatura com a seção selecionar transações realçada.](./media/projops_invoice_2_select_transactions.png)

1. Do menu suspenso **Projeto** , selecione  **00000093 Contoso Consulting**. 

1. Para este exemplo, verifique se a  **Data da fatura** está definida como  **01/02/21**, se a  **Data de início**  está definida como  **01/02/21** e se a data de término é a data de hoje.  
    Depois que as seleções forem feitas, selecione o botão Pesquisar para localizar as transações que atendem a esses parâmetros.

1. Selecione  **Pesquisar**.  
    Em seguida, para faturar todas as transações, selecione a opção Select all. Isso selecionará os itens que escolhemos para despesas e horas.

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
    Agora estamos prontos para criar uma visualização de impressão para garantir que todas as informações de faturamento sejam precisas. Algumas organizações usam a visualização durante as reuniões de revisão do projeto para garantir que todos concordem com os totais antes que a fatura seja finalizada. 

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
    Aqui vemos os resultados lançados na contabilidade. As contas contábeis são determinadas pela configuração da conta e pelas dimensões financeiras aplicadas a cada projeto.

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
    Depois que os dados são atualizados, um gerente de projeto pode optar por detalhar ainda mais os detalhes transacionais para tomar decisões de projeto ou fazer ajustes conforme necessário.Nesta demonstração, processamos uma fatura de tempo e material com uma transação de hora e de despesa. Analisamos isso em versão prévia, lançamos a fatura, revisamos o lançamento contábil e, por fim, revisamos o impacto financeiro por meio deste demonstrativo do projeto.
