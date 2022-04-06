---
demo:
  title: 'Demonstração 1: Preços de operações de projetos'
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
ms.openlocfilehash: bbe3de969557591700be5874c7c709b74d1d286a
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909236"
---
## <a name="demo-1---project-operations-pricing"></a>Demonstração 1 —Preços de Operações de Projetos

1. Navegue até o workspace **Gerenciamento de projetos**.  
    Nesta demonstração, vamos configurar os preços de custo e vendas nas operações de projetos. Veremos também como o custo e os preços são derivados de uma fatura lançada anteriormente.

1. No seletor da empresa no canto superior direito, verifique se a pessoa jurídica à qual você está conectado é **USSI**.  
    Se não for, altere a organização para **USSI**.

1. Na tabela **Projetos ativos**, selecione o projeto **00000093 Contoso Consulting**. Isso abre a exibição de detalhes do projeto.

    ![Uma captura de tela do workspace de gerenciamento do projeto com a Contoso Consulting realçada na tabela Projetos ativos.](./media/projops_prices_1_selecting_contoso_consulting.png)

1. Na página da **Contoso Consulting**, na barra de navegação, selecione a guia **Gerenciar**.

1. No menu **Gerenciar**, selecione **Diários de faturas**.  
    Aqui, localizamos uma fatura em que as horas foram aplicadas.

1. Em **Transações de fatura**, na coluna **Preço de venda**, aponte para **350,00**.  
    Podemos ver nesta exibição que o preço de vendas do recurso Aaron Con, um gerente de projetos para a USSI, tem uma taxa de cobrança de 350 dólares. Vamos examinar a configuração de preços para ver como essa taxa foi determinada.

    ![Uma captura de tela de um diário de faturas com o valor de 350 realçado na coluna preço de venda.](./media/projops_prices_2_point_to_350.png)  

    Embora possamos examinar os preços do projeto individual, vamos começar pelo workspace de **Gerenciamento de projetos** para vermos todos os preços configurados.

1. Navegue até o workspace **Gerenciamento de projetos**.

1. No lado direito da tela, na seção **Links**, no submenu **Configuração**, selecione **Preço de venda (hora)** .

1. Na página **Preço de venda – hora**, na coluna **Preço** da tabela, aponte para **350,00**.  
Nessa exibição, podemos ver onde foi configurado o preço de vendas de 350 dólares para Aaron Con.

1. Aponte para a primeira linha inteira.  
    Se examinarmos toda a linha, veremos que Aaron está configurado como um Gerente de projetos e, mais especificamente, que a taxa está associada a uma ID de projeto específica para a Contoso Consulting.

1. Na coluna **Recurso**, aponte para todas as outras linhas com recursos atribuídos.  
    Podemos ver nessa tabela que também há outros Gerentes de projetos configurados, mas eles não estão alocados especificamente para IDs de projeto e, portanto, as tarifas deles são específicas apenas para a categoria e os recursos atribuídos.

    ![Uma captura de tela da página Preço de venda —hora, com todas as linhas com recursos atribuídos realçadas na tabela.](./media/projops_prices_3_resources_table.png)  

    Essa matriz é flexível o suficiente para dar suporte ao nível de detalhes que vimos com a Contoso Consulting e Aaron Con, além de dar suporte a um modelo de preços mais genérico, como o preço de US$ 300 mostrado aqui.

1. Para o Projeto Contoso, navegue até a página **Diários de faturas**.  
    Voltando para a fatura lançada, examinaremos a mesma transação de horas lançadas e os custos associados a Aaron Con selecionando a ID da transação na linha de transação da fatura.

1. Na seção **Transações de fatura**, selecione a guia **Hora**. Na tabela que aparecerá, na coluna **ID da transação**, selecione a ID da transação.

    ![Uma captura de tela da página Diário de faturas com a coluna ID da transação realçada.](./media/projops_prices_4_select_a_transaction_id.png)

1. Na página **Transações de horas**, selecione a guia **Visão geral**. Na tabela que aparecerá, na coluna **Preço de custo**, aponte para **200,00**.  
    Na exibição de transações de horas, podemos ver a entrada de Aaron Con e o preço de custo associado de US$ 200. Vamos voltar e examinar a configuração de preço de custo para ver como essa taxa de custo foi derivada.

1. Navegue até o workspace **Gerenciamento de projetos**.

1. No lado direito da tela, na seção **Links**, no submenu **Configuração**, selecione **Preço de custo (hora)** .

1. Na página **Exibição padrão Preço de custo — hora**, na tabela, aponte para a linha com **01/01/2014** na coluna **Data de efetivação**, **GP** na coluna **Categoria**, **200,00** na coluna **Preço de custo** e nenhum valor nas outras colunas.  
    Nessa exibição, posso ver um preço de custo de US$ 200 que foi configurado especificamente para a categoria de GP, mas não há outras linhas específicas para Aaron ou para nosso projeto de consultoria da Contoso. Isso também é uma prática comum, pois muitas organizações de serviço aplicam taxas de custo padrão em várias categorias, nesse caso, identificadas aqui como uma função de projeto. Esse custo geralmente é uma taxa combinada em que a taxa de pagamento do recurso individual será armazenada somente no sistema de folha de pagamento ou de RH. A taxa de custo padrão será então ajustada periodicamente, pois os custos de folha de pagamento são analisados para garantir que eles sejam precisos e que as margens sejam atendidas.

    ![Uma captura de tela da tabela Preço de custo — hora com a linha do preço do GP realçada.](./media/projops_prices_5_cost_price_hour_table.png)

1. Navegue até o workspace **Gerenciamento de projetos**.

1. No lado direito da tela, na seção **Links**, no submenu **Configuração**, aponte para **Preço de custo (hora)** e **Preço de venda (hora)** .  

Nesta demonstração, exploramos como os preços de custo e as vendas padrão são configurados em operações de projeto. Revisamos seu impacto em relação a uma fatura lançada para entender como a configuração desses preços afeta diretamente a fatura de material e tempo apresentada.
