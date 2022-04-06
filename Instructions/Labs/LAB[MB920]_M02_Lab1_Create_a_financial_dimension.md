---
lab:
  title: 'Laboratório 1: Criar uma dimensão financeira'
  module: 'Module 2: Learn the Fundamentals of Microsoft Dynamics 365 Finance'
ms.openlocfilehash: 9bbc1a92cb719b988ddfa6a08e1e3b2d8c69976e
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909380"
---
## <a name="lab-1---create-a-financial-dimension"></a>Laboratório 1 — Criar uma dimensão financeira

## <a name="objectives"></a>Objetivos

Use a página Dimensões financeiras para criar dimensões financeiras que você pode usar como segmentos de contas em planos de contas. Há dois tipos de dimensões financeiras: as dimensões personalizadas e as dimensões apoiadas por entidades. As dimensões personalizadas são compartilhadas entre entidades legais e os valores são inseridos e mantidos pelos usuários. Para dimensões com suporte de entidade, os valores são definidos em algum outro lugar no sistema, como nas entidades Clientes ou Lojas. Algumas dimensões com suporte de entidade são compartilhadas entre entidades legais, enquanto outras dimensões com suporte de entidade são específicas da empresa.

Você deve criar uma dimensão financeira personalizada que será usada por sua empresa.

## <a name="lab-setup"></a>Configuração do Laboratório

   - **Tempo estimado**: 5 minutos

## <a name="instructions"></a>Instruções

1. Na home page do Finance and Operations, na parte superior direita, verifique se você está trabalhando com a empresa USMF.

1. Se necessário, selecione a empresa e, no menu, selecione **USMF**.

1. No painel de navegação à esquerda, selecione **Módulos** > **Contabilidade** > **Plano de contas** > **Dimensões** > **Dimensões financeiras**.

1. No menu superior, selecione **+ Novo**.

1. Na página dimensões financeiras, selecione o menu **Usar valores de** e, em seguida, selecione **< Dimensão personalizada >** .

1. Na caixa de nome da **Dimensão**, digite **Affliate_Revenue**.

1. Na caixa **Nome da coluna do relatório**, digite **Afflt**.

1. No menu superior, selecione **Ativar**.

    ![Captura de tela exibindo a nova dimensão financeira personalizada com o menu Usar valores de, Nome da dimensão, Nome da coluna de relatório e Ativar realçado](./media/lp2-m3-new-financial-dimension.png)

1. Revise as informações na caixa de diálogo e selecione **Fechar**.

1. Examine a faixa de notificação de aviso.

    ![Captura de tela exibindo faixa de informações de aviso referenciando o requisito de modo de manutenção para ativar uma nova dimensão.](./media/lp2-m3-activation-warning-banner.png)

    >[!NOTE] O modo de manutenção pode ser ativado e desativado diretamente por meio de serviços de ciclo de vida (LCS) em seus ambientes de área de teste e de produção. Mais informações sobre como gerenciar serviços de ciclo de vida podem ser encontradas em [https://docs.microsoft.com/en-us/dynamics365/fin-ops-core/dev-itpro/deployment/maintenanceoperationsguide-newinfrastructure](https://docs.microsoft.com/en-us/dynamics365/fin-ops-core/dev-itpro/deployment/maintenanceoperationsguide-newinfrastructure) .
