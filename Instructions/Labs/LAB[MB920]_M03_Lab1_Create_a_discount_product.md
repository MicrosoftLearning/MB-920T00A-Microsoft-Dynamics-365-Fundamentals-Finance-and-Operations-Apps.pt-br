---
lab:
    title: 'Laboratório 1: Criar um produto com desconto'
    module: 'Módulo 3: Conheça os princípios básicos do Microsoft Dynamics 365 Commerce'
---

## Laboratório 1 - Criar um produto com desconto

## Objetivos

A loja de Boston da sua empresa está pronta para direcionar as vendas de alguns produtos que precisam ser vendidos para fazer espaço para a nova linha. Você precisa criar e ativar um novo desconto de produto.

## Configuração do laboratório

   - **Tempo estimado**: 10 minutos

## Instruções

1. Na página do Finance and Operations, na parte superior esquerda, selecione o menu de hambúrguer **Expandir o painel de navegação**.

1. No painel de navegação, selecione **Espaços de trabalho** > **Gerenciamento de preços e descontos**.

1. Na página Gerenciamento de preços e descontos, examine os **Descontos ativos**.

1. No menu, selecione **Novo**, examine as opções disponíveis e depois selecione **Desconto**.

1. Na página Descontos, na caixa **Nome**, digite um nome para o desconto. Por exemplo, 20% de Ano Novo.

1. Na guia Geral, verifique se o Status está definido como **Desabilitado**.

1. O desconto só pode ser editado quando está definido como desabilitado.

1. Selecione o menu **Modo de simultaneidade de desconto**, examine as opções disponíveis e depois selecione **Melhor preço**.

    >[!OBSERVAÇÃO] Ao escolher entre as opções de modo de simultaneidade, tenha em mente o seguinte:
    >
    >  - Quando vários descontos compostos são aplicáveis, o desconto mais alto sempre será calculado primeiro.  Em seguida, o próximo desconto mais alto é calculado sobre o valor restante.  Essa hierarquia de cálculos continuará até que todos os descontos compostos tenham sido aplicados.  
    >    **Correto**: 40% de desconto + 20% de desconto = 52% de desconto  
    >      - (40% de desconto sobre US$ 100 = US$ 40. Restante = US$ 60.  20% de desconto sobre US$ 60 = 12. Restante = US$ 48)  
    >
    >    **Incorreto**: 40% de desconto + 20% de desconto = 60% de desconto
    >
    >  - Descontos exclusivos sempre serão aplicados a um Melhor preço ou Desconto composto, mesmo que esse seja o percentual de desconto mais baixo.
    >    - Quando mais de um desconto exclusivo for aplicável, o mais alto será usado.
    >  - Quanto tanto o Melhor preço quanto o Desconto composto forem aplicáveis ou vários itens da mesma opção, o desconto mais alto será usado.

1. Selecione o menu **Conta de desconto** e examine a lista.

1. Na caixa Conta de desconto, digite **desconto**.

1. A lista será filtrada automaticamente.

1. Nos resultados, selecione o Número da conta de desconto **403200**.

1. Examine as outras opções e depois expanda **Detalhes**.

1. Na caixa **Descrição**, digite uma descrição para o desconto. Por exemplo, Oferta de desconto de ano novo: 20%.

1. Expanda **Preço/desconto**.

1. Na caixa Percentual de desconto, digite **20,00**.

1. Expanda **Período de validação**.

1. Defina a **Data de efetivação** e a **Data de vencimento** do desconto.

1. Não se esqueça de definir a data de vencimento no futuro, caso contrário, o desconto não aparecerá na lista de descontos ativos.

1. Expanda **Linhas**.

1. No menu, selecione **+ Adicionar.**

1. Selecione o menu **Categoria** e depois selecione **Moda (Moda)**.

1. O desconto será aplicado a todos os produtos na categoria Moda.

1. Expanda **Detalhes da linha** e, em seguida, na caixa **Descrição**, digite uma descrição para as linhas de produto. Por exemplo, Todos os produtos na categoria Moda serão incluídos no desconto.

1. Na parte superior da página, no menu, selecione **Grupos de preços**.

1. Na página Grupos de preços, selecione o menu **Grupo de preços**.

1. Examine os grupos de preços disponíveis, selecione **Grupo de preços de Boston** e depois selecione **Salvar**.

1. Na parte superior direita da página Grupos de preços, selecione o ícone **Fechar**.

1. Na página Descontos, na guia Detalhes, selecione o menu **Status** e depois **Habilitado**.

1. Observe que as configurações de desconto não podem mais ser editadas.

1. Salve suas alterações e depois feche a página Desconto.

1. Na página Gerenciamento de preços e descontos, examine a guia Descontos ativos e verifique se os descontos recém-adicionados são mostrados na parte inferior da lista.

1. Se necessário, na parte superior direita, selecione o ícone **Atualizar** para atualizar a lista de descontos.
