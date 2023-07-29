---
lab:
  title: 'Laboratório 1: Criar um produto'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Módulo 3: Conheça os Princípios básicos do Microsoft Dynamics 365 Supply Chain Management

## Laboratório 1: Criar um produto

## Objetivo

Na USMF (Contoso Entertainment System USA), você planeja comprar uma nova configuração de um gabinete de um fornecedor.  Você precisa criar um item para representar a nova configuração.  Neste laboratório, você aprenderá a criar um item e configurações do item.

## Configuração do Laboratório

   - **Tempo estimado**: 10 minutos

## Instruções

Na USMF (Contoso Entertainment System USA), você planeja comprar uma nova configuração de um gabinete de um fornecedor.  Você precisa criar um item para representar a nova configuração. 

1.  Na página inicial Finanças e Operações, na parte superior direita, verifique se você está trabalhando com a empresa **USMF**. Se necessário, no menu suspenso da empresa, selecione **USMF**.

2.  No canto superior esquerdo, selecione o menu hambúrguer **Expandir o painel de navegação**.

3.  No painel de navegação, selecione **Módulos** e, em seguida, **Gerenciamento de informações do produto**. Depois, no menu **Produtos**, selecione **Produtos**.

4.  Na página **Produtos**, no menu superior, selecione **+ Novo**.

5.  Na página **Novo produto**, no campo **Tipo de produto**, verifique se **Item** está selecionado.

6.  No campo **Subtipo do produto**, verifique se **Produto** está selecionado.

7.  Em **IDENTIFICAÇÃO**, na caixa **Número do produto**, digite **GTL007**.

8.  Na caixa **Nome do produto**, digite **Gabinete 2**.

    ![A captura de tela mostra a exibição padrão da nova página de criação de produto.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-07.png)

9.  Selecione o botão **OK**.

10. No menu **Produto** no Painel de Ação, selecione **Grupos de dimensões** no grupo **Configurar**.

    ![A captura de tela mostra a opção configurar no menu do produto em que os diferentes detalhes do grupo de dimensões podem ser adicionados.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-08.png)

11. Clique no menu suspenso **Grupo de dimensões de armazenamento** e selecione **SiteWH**.

12. Selecione o menu suspenso **Grupo de dimensões de rastreamento** e selecione **Nenhum**.

13. Selecione o botão **OK**.

14. Selecione o botão **Lançar produtos** no Painel de Ação para lançar o produto em uma entidade legal.

15. Uma página é aberta exibindo a primeira etapa como **Selecionar produtos a serem lançados.**

    ![A captura de tela mostra a exibição padrão da página lançar produtos.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-09.png)

16. Selecione o botão **Avançar** na parte inferior da página

17. Na página **Selecionar empresas para as quais lançar**, selecione a entidade jurídica **USMF** em que o produto deve ser lançado.

18. Selecione o botão **Avançar** na parte inferior da página.

19. Na página **Confirmar seleção**, defina o valor de **Mostrar Infolog após falha** como **Sim** e **Executar como lote** como **Não**.

20. Clique no botão **Concluir** na parte inferior da página.

21. No painel de navegação, selecione Módulos e, em seguida, Gerenciamento de informações do produto. Depois, no menu Produtos, selecione **Lançados**.

22. Na página **Lançamentos** **produtos**, localize o novo item **GTL007** na grade. 

23. Selecione o link do produto e navegue até a página **Detalhes do produto**.

24. Na FastTab **Geral**, insira o seguinte:

    - **Grupo de modelos de item**: PEPS

25. Na FastTab **Comprar**, insira o seguinte:

    - **Unidade**: ea

    - **Grupo de impostos sobre vendas**: TODOS

    - **Preço**: 30

26. Na FastTab **Vender**, insira o seguinte:

    - **Unidade**: ea

    - **Grupo de impostos sobre vendas**: TODOS

    - **Preço**: 35

27. No FastTab **Gerenciar inventário**, insira o seguinte:

    - **Unidade**: ea

28. Na FastTab **Engenheiro**, insira o seguinte:

    - **Unidade BOM**: ea

29. Na FastTab **Gerenciar custos**, insira o seguinte:

    - **Grupo de itens**: áudio

30. Para concluir a configuração, selecione Produto no Painel de Ações. Selecione o botão Validar no grupo Manter

    ![A captura de tela mostra o grupo Manter no botão Produto no painel de ações. O botão Validar no grupo Manter está selecionado.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-10.png)

31. Verifique se você recebeu o anúncio em faixa com as informações que confirmam que todos os valores de campo exigidos foram validados.

    ![A captura de tela representa o anúncio em faixa com as informações que confirmam que todos os valores de campo exigidos foram validados. ](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-11.png)

32. Feche todas as páginas e volte para a Home page.
