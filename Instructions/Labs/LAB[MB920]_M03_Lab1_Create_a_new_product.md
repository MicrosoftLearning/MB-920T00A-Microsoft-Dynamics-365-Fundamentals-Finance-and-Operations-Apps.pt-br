---
lab:
  title: 'Laboratório 3.1: Criar um produto'
  module: 'Learning Path 3: Learn the fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Roteiro de aprendizagem 3: aprender os conceitos básicos do Microsoft Dynamics 365 Supply Chain Management
# Módulo 2: Descrever os processos de vendas e compras

## Laboratório 3.1: Criar um produto

Em sua organização, você planeja criar um novo item, que é uma camisa. A camisa terá cores e tamanhos diferentes. Neste laboratório, você aprenderá a criar um novo item com várias variantes e liberá-lo na entidade legal USMF.

## Etapas do laboratório

1. No painel de navegação do Dynamics 365 Supply Chain Management, selecione **Módulos** e, em seguida, selecione **Gerenciamento de informações de produtos** > **Configuração** > **Grupos de variante e dimensão**. Abra a página **Grupos de cores** e crie um novo registro.

    - Grupo de cores: **ShirtColor**

    - Descrição: **Cor da camisa**

2. Na FastTab **Linhas do grupo de cores**, insira os três registros a seguir:

    | **Cor** | **Nome da cor** |
    |-----------|----------------|
    | Azul      | Azul           |
    | Branca     | Branco          |
    | Preto     | Preto          |


3. Salve os registros.

4. Selecione **Gerenciamento de informações do produto** > **Configuração** > **Grupos de variante e dimensão**. Abra a página **Grupos de tamanhos** e crie um novo registro.

    - Grupo de tamanhos: **ShirtSize**

    - Descrição: **Tamanho da camisa**

5. Na FastTab **Linhas do grupo de tamanhos**, insira os três registros a seguir

    | **Tamanho** | **Nome do tamanho** |
    |----------|---------------|
    | S        | Pequeno         |
    | M        | Médio        |
    | L        | Grande         |


6. Salve os registros

7. No painel de navegação do Dynamics 365 Supply Chain Management, selecione **Módulos** e, em seguida, selecione **Gerenciamento de informações do produto**. Depois, no menu **Produtos**, selecione **Produtos mestres**.

8. Na página **Produtos mestres**, no menu superior, selecione **+ Novo**.

9. Na página **Novo produto**, no campo **Tipo de produto**, verifique se **Item** está selecionado.

10. No campo **Subtipo do produto**, verifique se **Produto****mestre** está selecionado.

11. Na guia **Identificação**, na caixa **Número do produto**, insira **SH001**.

12. No campo **Nome do produto**, insira **Camisa**.

13. No campo **Grupo de dimensões do produto**, selecione **ColorSize**.

14. Selecione o botão **OK**.

15. No menu **Produto** no painel de ações, selecione **Grupos de dimensões** no grupo **Configurar**.

16. Clique na lista suspensa **Grupo de dimensões de armazenamento** e selecione **SiteWH**.

17. Na lista suspensa **Grupo de dimensões de rastreamento**, selecione **Nenhum**.

18. Selecione o botão **OK**.

19. Selecione **ShirtColor** na lista de **grupos de cores**.

20. Selecione **ShirtSize** na lista de **Grupos de tamanhos**.

21. No painel de ações, selecione o botão **Grades de produtos**.

22. Na página **Grades de produtos**, selecione o botão **Sugestões de grade** no painel de ações.

23. Selecione o botão **Sugerir tudo** na página **Sugestões de grade**.

24. Selecione as variantes sugeridas selecionando o botão **Selecionar tudo** seguido pelo botão **Criar**.

As variantes serão criadas na página Variantes do produto.

25. Selecione o botão **Lançar produtos** no painel de ações para lançar o produto em uma entidade legal.

26. Uma página é aberta exibindo a primeira etapa como **Selecionar produtos a serem lançados.**

27. Selecione o botão **Avançar** na parte inferior da página.

28. Selecione as variantes que você deseja liberar na entidade legal e selecione o botão **Avançar**.

29. Na página **Selecionar empresas para o lançamento**, selecione a entidade jurídica **USMF** em que o produto deve ser lançado.

30. Selecione o botão **Avançar** na parte inferior da página.

31. Na página **Confirmar seleção**, defina o valor de **Mostrar log de informações após a falha** como **Sim** e **Executar como lote** como **Não**.

32. Clique no botão **Concluir** na parte inferior da página.

16. No painel de navegação, selecione **Módulos** e, depois, **Gerenciamento de informações do produto**. No menu **Produtos**, selecione **Produtos liberados**.

33. Na página **Lançar produtos**, localize o novo item **SH001** na grade.

34. Selecione o link do produto e navegue até a página **Detalhes do produto**.

35. Na FastTab **Geral**, insira o seguinte:

    - Grupo de modelos de item: **PEPS**

36. Na FastTab **Comprar**, insira o seguinte:

    - Unidade: **ea**

    - Grupo de impostos do item: **TODOS**

    - Preço: **30**

37. Na FastTab **Vender**, insira o seguinte:

    - Unidade: **ea**

    - Grupo de impostos do item: **TODOS**

    - Preço: **35**

38. No FastTab **Gerenciar inventário**, insira o seguinte:

    - Unidade: **ea**

39. Na FastTab **Engenheiro**, insira o seguinte:

    - Unidade BOM: **ea**

40. Na FastTab **Gerenciar custos**, insira o seguinte:

    - Grupo de itens: **áudio**

41. Para concluir a configuração, selecione **Produto** no Painel de Ações. Selecione o botão **Validar** no grupo **Manter**.

42. Feche todas as páginas e volte para a **Página inicial**.

 
