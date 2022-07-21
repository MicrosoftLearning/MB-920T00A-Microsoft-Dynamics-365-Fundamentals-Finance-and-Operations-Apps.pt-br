---
lab:
  title: 'Laboratório 3: Criar um diário de contagem'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
ms.openlocfilehash: 5e61646d33f284bb7e30b6f63a7db4778f58b47c
ms.sourcegitcommit: 8e5a278c6e08abdcc3fb719796f79842e868606b
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/14/2022
ms.locfileid: "147116240"
---
# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>Módulo 3: Conheça os Princípios básicos do Microsoft Dynamics 365 Supply Chain Management

## <a name="lab-3---create-a-counting-journal"></a>Laboratório 3: Criar um diário de contagem

1. Na página inicial do Finance and Operations, na parte superior direita, verifique se você está trabalhando com a empresa **USMF**. Se necessário, selecione a empresa e, no menu suspenso, clique em **USMF**.

2. No painel de navegação esquerdo, clique em **Módulos** > **Gerenciamento de estoque** > **Entradas do diário** > **Contagem de itens** > **Contagem**.

3. Pressione o botão **+ Novo** no painel de ação. O formulário de diálogo **Criar diário de estoque** será exibido com o botão **OK** na parte inferior. Selecione o botão **OK**.

4. O formulário do diário de contagem de estoque será exibido com cabeçalho e informações detalhadas

![Captura de tela do formulário do diário de contagem de estoque com o cabeçalho e as informações detalhadas preenchidos.](../media/lp-scm-m-002-warehouse-inventory-mgmt-06.png)

5. Clique em **Criar linhas –&gt; Online** no painel de ação.

6. No painel de diálogo **Criar diário de contagem de itens disponíveis**, defina os campos **Warehouse**, **Status do estoque**, Localização e **Placa de licença** como **Sim**. 

![Captura de tela do painel de diálogo Criar diário de contagem de itens disponíveis com os campos definidos conforme descrito.](../media/lp-scm-m-002-warehouse-inventory-mgmt-07.png)

7. Expanda a seção **Registro a incluir** e clique no link de **Filtrar**. No campo **Número do Item**, clique em **A0001** e, em seguida, em **OK**.

8. Na parte inferior do formulário de diálogo **Criar diário de contagem de itens disponíveis**, clique em **OK**.

A quantidade disponível do item A0001 será exibida na seção **Linhas do diário** com informações detalhadas sobre Site, Warehouse, Localização e Placa de Licença.

9. Na coluna **Contagem** da seção **Linha do diário**, insira os números contados em cada Site/Warehouse/Local/Placa de licença. Observe o seguinte:

    - Se a quantidade **Disponível** for igual à quantidade da **Contagem**, o campo **Quantidade** ficará em branco.

    - Se o valor do campo **Contagem** for maior que o valor do campo **Disponível**, o campo **Quantidade** conterá um valor positivo.

    - Se o valor do campo **Contagem** for menor que o valor do campo **Disponível**, o campo **Quantidade** conterá um valor negativo.

10. Pressione o botão **Validar** no painel de ação e, em seguida, o botão **Postar**.

11. Feche a página e retorne à página inicial.
