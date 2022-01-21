---
lab:
    title: 'Laboratório 2: Criar um sortimento de produto'
    module: 'Módulo 3: Conheça os princípios básicos do Microsoft Dynamics 365 Commerce'
---

## Laboratório 2 - Criar um sortimento de produto

## Objetivos

Você precisa criar um sortimento de produtos relacionados atribuídos a um determinado canal do Commerce que serão disponibilizados em uma data futura.

## Configuração do laboratório

   - **Tempo estimado**: 10 minutos

## Instruções

1. Na página do Finance and Operations, na parte superior esquerda, selecione o menu de hambúrguer **Expandir o painel de navegação**.

1. No painel de navegação, selecione **Varejo e comércio** > **Catálogos e classificações** > **Sortimentos**.

1. Aguarde o carregamento da página.

1. Na página Sortimentos, selecione **+ Novo**.

1. No painel Novo registro, expanda **Geral**.

1. Marque a caixa **Data de efetivação** e selecione uma data no futuro.

1. Na caixa **Nome do sortimento**, digite um nome para o novo sortimento. Por exemplo, **Nova temporada de primavera**.

1. Defina a **Data de vencimento** como **Nunca**.

1. A data de vencimento pode ser usada para desativar automaticamente um sortimento publicado.

1. Expanda **Canais comerciais**.

1. No menu Canais comerciais, selecione **+ Adicionar linha**.

1. Em Escolha os nós da organização, selecione o menu **Hierarquia da organização** e depois **Lojas de varejo por tipo (Fabrikam)**.

1. Na lista NÓS ORGANIZACIONAIS DISPONÍVEIS, selecione Online e depois o ícone Adicionar ![ícone de seta para a direita](./media/d365-fo-add-org-node-icon.png) para adicioná-la aos **NÓS DA ORGANIZAÇÃO SELECIONADOS**.  
  Isso adicionará o nó pai e todos os nós filho.

1. Adicione o nó pai **Shopping** e depois selecione **OK**.

1. Verifique se os dois nós foram adicionados aos Canais comerciais.

1. Expanda **Produtos**.

1. No menu Produtos, selecione **+ Adicionar linha**.

1. Selecione o menu **Categoria**, selecione **Esportes em Equipe (Esportes em Equipe)** e selecione **OK**.

1. Isso adicionará todos os itens filho da categoria pai.

1. Revise a última coluna chamada **Tipo de linha**. Por padrão, todos os itens serão incluídos.

1. Selecione **+ Adicionar linha**, selecione o menu **Categoria**, expanda **Esportes em Equipe (Esportes em Equipe)**, selecione **Beisebol** e **OK**.

1. Para excluir um item de uma categoria maior já incluída, nesse caso, Esportes em Equipe, na coluna Tipo de linha, altere o valor para **Excluir**.

1. Usando a linha de categoria Beisebol, selecione o menu **Produtos**.

1. Quando os produtos em uma categoria estiverem definidos, você poderá selecionar um produto específico para incluir ou excluir. Selecione **AdultBaseballInfield**.

1. Para remover um produto adicionado, exclua o conteúdo da caixa de produto e pressione a tecla Tab no teclado ou selecione outra área da página.

1. No menu superior, selecione **Salvar**.

1. No menu superior, selecione **Publicar**.

1. Examine as informações na caixa de diálogo e selecione **Sim**.

1. O sortimento de produto recém-criado ficará disponível na data de efetivação.
