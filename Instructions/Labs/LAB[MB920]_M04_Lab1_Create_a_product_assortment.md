---
lab:
  title: 'Laboratório 1: Criar uma variedade de produto'
  module: 'Module 4: Learn the Fundamentals of Microsoft Dynamics 365 Commerce'
---

# Módulo 4: Conheça os princípios básicos do Microsoft Dynamics 365 Commerce

## Laboratório 1: Criar uma variedade de produto

## Objetivo

Você precisa criar uma variedade de produtos relacionados atribuídos a um canal de comércio específico que será disponibilizado em uma data futura. 

## Configuração do Laboratório

   - **Tempo estimado**: 10 minutos

## Instruções

1.  Na página inicial de “Finanças e operações”, na parte superior esquerda, selecione o menu de opções **Expandir o painel de navegação**.

2.  No painel de navegação, selecione **Varejo e Comércio** > **Catálogos e sortimentos** > **Sortimentos**.

3.  Aguarde o carregamento da página.

4.  Na página **Sortimentos**, selecione **+ Novo**.

5.  No painel **Novo registro**, expanda **Geral**.

6.  Selecione a caixa **Data efetiva** e, em seguida, selecione uma data no futuro.

7.  Na caixa **Nome do sortimento**, insira um nome para o novo sortimento. Por exemplo, **Nova temporada de primavera**.

8.  Defina a **Data de validade** como **Nunca**.

    A data de vencimento pode ser usada para desativar automaticamente um sortimento publicado.

9.  Expanda **Canais de comércio**.

10. No menu **Canais de comércio**, selecione **+ Adicionar linha**.

11. Em **Escolher nós da organização**, clique no menu **Hierarquia da organização** e, em seguida, em **Lojas de varejo por tipo (Fabrikam)**.

12. Na lista **NÓS DA ORGANIZAÇÃO DISPONÍVEIS**, selecione **Online** e selecione o ícone **Adicionar** ![Figura 15](./media/04-learn-the-fundamentals-of-dynamics-365-commerce-17.png) para adicioná-lo a **NÓS DA ORGANIZAÇÃO SELECIONADOS**.

    Isso adiciona o nó pai e todos os nós filho.

13. Adicione o nó pai **Mall** e, em seguida, selecione **OK**.

14. Verifique se os dois nós foram adicionados aos canais de comércio.

15. Expanda **Produtos**.

16. No menu **Produtos**, selecione **+ Adicionar linha**.

17. Clique no menu **Categoria**, selecione **Esportes em equipe** e, em seguida, **OK**.

    Isso adiciona todos os itens filho da categoria pai.

18. Revise a última coluna chamada **Tipo de linha**. Por padrão, todos os itens são incluídos.

19. Selecione **+ Adicionar linha**, selecione o menu **Categoria**, expanda **Esportes em equipe**, selecione **Basebol** e, em seguida, **selecione OK**.

20. Para excluir um item de uma categoria maior já incluída, neste caso, **Esportes em equipe**, na coluna **Tipo de linha**, altere o valor para **Excluir**.

21. Usando a linha da categoria **Basebol**, clique no menu **Produtos**.

22. Quando os produtos de uma categoria são definidos, você pode selecionar um produto específico para incluir ou excluir. Selecione **AdultBaseballInfield**.

23. Para remover um produto adicionado, exclua o conteúdo da caixa do produto e pressione a tecla **Tab** no teclado ou selecione outra área da página.

24. No menu superior, selecione **Salvar**.

25. No menu superior, selecione **Publicar**.

26. Revise as informações na caixa de diálogo e selecione **Sim**.

    O sortimento de produto recém-criado fica disponível na data de início de vigência.

