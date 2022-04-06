---
lab:
  title: 'Laboratório 5: Criar um depósito'
  module: 'Module 1: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
ms.openlocfilehash: 919ea602b0768683acd845dd184b3bf5a0364fd0
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909234"
---
# <a name="module-1-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>Módulo 1: Conheça os Princípios básicos do Microsoft Dynamics 365 Supply Chain Management

## <a name="lab-5---create-a-warehouse"></a>Laboratório 5 — Criar um estoque

## <a name="objectives"></a>Objetivos
O sistema de gerenciamento de depósitos no Supply Chain Management oferece maneiras flexíveis de definir o layout do seu depósito para atender às necessidades em constante mudança, para que você conquiste a máxima eficiência do depósito.

- Você pode estabelecer áreas de armazenamento de alta prioridade e de baixa prioridade para o posicionamento ideal de bens.
- Você pode dividir seu depósito em zonas para acomodar várias necessidades de armazenamento, como requisitos de temperatura ou várias taxas de giro para itens.
- Você pode especificar locais de depósito em qualquer nível (por exemplo, site, depósito, corredor, rack, prateleira e posição de compartimento).
- Você pode agrupar locais usando as configurações de restrição de capacidade física.
- Você pode controlar como os itens são armazenados e selecionados, com base nas regras definidas pela consulta.

Para usar o gerenciamento de depósito no Gerenciamento da cadeia de suprimentos, você deve criar um depósito e habilitá-lo para atividades de gerenciamento de depósito mais avançadas ou especializadas.

## <a name="lab-setup"></a>Configuração do Laboratório

   - **Tempo estimado**: 10 minutos

## <a name="instructions"></a>Instruções

1. Na home page do Finance and Operations, na parte superior direita, verifique se você está trabalhando com a empresa USMF.

1. Se necessário, selecione a empresa e, no menu, selecione **USMF**.

1. No painel de navegação à esquerda, selecione **Módulos** > **Gerenciamento de estoque** > **Configuração** > **Detalhamento de estoque** > **Depósitos**.

    ![Imagem da tela exibindo a navegação do módulo de depósitos](./media/lp1-m3-warehouses-module-navigation.png)

1. Na página Depósitos, no menu superior, selecione **Novo**.

1. No campo **Depósito**, insira **101**.

1. No campo **Nome**, insira **Depósito de estouro**.

1. Selecione o menu **Local** e depois **3 Espuma de produção caseira**.

1. Expanda **Nomes de local**.  
    As opções nesta seção definem o formato padrão para nomes de localização.

1. Defina as opções **Incluir corredor** e **Incluir rack** como **Sim**.

1. Na caixa **Formato**, para o rack, insira um valor.  
    Por exemplo, se o formato do nome do local do rack precisar conter OVFL, você deverá inserir esse valor na caixa Formato.

1. Em **NÍVEL**, defina a opção **Incluir prateleira** como **Sim**.

1. Na caixa **Formato**, para a prateleira, insira **-##** .

1. No menu superior, selecione **Depósito**.

    ![Imagem da tela exibindo a opção de menu do depósito realçada](./media/lp1-m3-warehouses-menu-option.png)

1. Em **Manter**, selecione **Assistente de Localização**.

1. Na página inicial, revise as informações e, no canto inferior direito, selecione **Próximo**.

1. Desmarque as caixas de seleção **Plataformas de saída** e **Locais em massa**.

1. Selecione **Avançar** e revise as informações.

1. Continue em cada página e, ao terminar, selecione **Concluir**.

1. Feche a página e retorne à página inicial.
