---
lab:
  title: 'Laboratório 1: Criar um produto com desconto'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Commerce'
ms.openlocfilehash: 2d3a61398c6184a9b43e2fd0da9d28cb55f55ee5
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909376"
---
## <a name="lab-1---create-a-discount-product"></a>Laboratório 1 — Criar um produto com desconto

## <a name="objectives"></a>Objetivos

A loja de Boston da sua empresa está pronta para impulsionar as vendas de alguns produtos que precisam ser vendidos para liberar espaço para a nova linha. Você precisa criar e ativar um novo desconto de produto.

## <a name="lab-setup"></a>Configuração do Laboratório

   - **Tempo estimado**: 10 minutos

## <a name="instructions"></a>Instruções

1. Na página Finanças e operações, na parte superior esquerda, selecione o menu de opções **Expandir o painel de navegação**.

1. No painel de navegação, selecione **Espaços de trabalho** > **Gerenciamento de descontos e preços**.

1. Na página Gerenciamento de preços e descontos, examine os **Descontos ativos** exibidos no momento.

1. No menu, selecione **Novo**, examine as opções disponíveis e selecione **Desconto**.

1. Na página descontos, na caixa **Nome**, insira um nome para o desconto. Por exemplo, Ano novo, 20%.

1. Na guia geral, verifique se o status está definido como **Desabilitado**.

1. O desconto só poderá ser editado quando estiver definido como desabilitado.

1. Selecione o menu **Modo de simultaneidade de desconto**, examine as opções disponíveis e, em seguida, selecione **Melhor preço**.

    >[!NOTE] Ao escolher entre as opções do modo de simultaneidade, tenha em mente:
    >
    >  - Quando vários descontos compostos são aplicáveis, o desconto mais alto sempre será calculado primeiro.  O próximo desconto mais alto é então calculado sobre o valor restante.  Essa hierarquia de cálculo continuará até que todos os descontos compostos aplicáveis tenham sido aplicados.  
    >    **Correto**: desconto de 40% + desconto de 20% = desconto de 52%  
    >      - (desconto de 40% sobre $100 = $40. Restante = $60.  desconto de 20% sobre $60 = 12. Restante = $48)  
    >
    >    **Incorreto**: desconto de 40% + desconto de 20% = desconto de 60%
    >
    >  - Os descontos exclusivos sempre se aplicarão a um melhor preço ou um desconto composto, mesmo se for a porcentagem de desconto mais baixa.
    >    - Quando mais de um desconto exclusivo for aplicável, o maior será usado.
    >  - Quando o melhor preço e os compostos forem aplicáveis ou se vários dos mesmos forem aplicáveis, o desconto mais alto será usado.

1. Selecione o menu **Conta de desconto** e examine a lista.

1. Na caixa conta de desconto, insira **desconto**.

1. A lista será filtrada automaticamente.

1. Nos resultados, selecione o número da conta de desconto **403200**.

1. Examine as outras opções e, em seguida, expanda **Detalhes**.

1. Na caixa **Descrição**, insira uma descrição para o desconto. Por exemplo, desconto de ano novo que oferece 20%.

1. Expanda **Preço/desconto**.

1. Na caixa percentual de desconto, digite **20,00**.

1. Expanda **Período de validação**.

1. Defina a **Data de validade** e a **Data de vencimento** do desconto.

1. Defina a data de validade no futuro, caso contrário, o desconto não será mostrado na lista de descontos ativos.

1. Expanda **Linhas**.

1. No menu, selecione **+ Adicionar.**

1. Selecione o menu **Categoria** e, em seguida, selecione **Moda (Moda)** .

1. Isso aplicará o desconto a todos os produtos da categoria Moda.

1. Expanda **Detalhes da linha** e, na caixa **Descrição**, insira uma descrição para as linhas de produto. Por exemplo, todos os produtos da categoria Moda serão incluídos no desconto.

1. Na parte superior da página, no menu, selecione **Grupos de preços**.

1. Na página Grupos de preços, selecione o menu **Grupo de preços**.

1. Examine os grupos de preços disponíveis, selecione **Grupo de preços de Boston** e, em seguida, selecione **Salvar**.

1. No canto superior direito da página Grupos de preços, selecione o ícone **Fechar**.

1. Na página Descontos, na guia Detalhes, selecione o menu **Status** e, em seguida, selecione **Habilitado**.

1. Observe que as configurações de desconto não podem mais ser editadas.

1. Salve as alterações e feche a página de desconto.

1. Na página Gerenciamento de preços e descontos, examine a guia Descontos ativos e verifique se o seu desconto recém-adicionado é mostrado na parte inferior da lista.

1. Se necessário, no canto superior direito, selecione o ícone de **Atualização** para atualizar a lista de descontos.
