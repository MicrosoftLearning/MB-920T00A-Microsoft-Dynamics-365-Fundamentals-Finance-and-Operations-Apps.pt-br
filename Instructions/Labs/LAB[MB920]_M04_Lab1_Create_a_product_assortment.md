---
lab:
  title: 'Laboratório 1: Criar uma variedade de produto'
  module: 'Module 4: Learn the Fundamentals of Microsoft Dynamics 365 Commerce'
---

## <a name="lab-1---create-a-product-assortment"></a>Laboratório 1: Criar uma variedade de produtos

## <a name="objectives"></a>Objetivos

Você precisa criar uma variedade de produtos relacionados atribuídos a um canal de comércio específico que será disponibilizado em uma data futura.

## <a name="lab-setup"></a>Configuração do Laboratório

   - **Tempo estimado**: 10 minutos

## <a name="instructions"></a>Instruções

1. Na página Finanças e operações, na parte superior esquerda, selecione o menu de opções **Expandir o painel de navegação**.

1. No painel de navegação, selecione **Varejo e Comércio** > **Catálogos e sortimentos** > **Sortimentos**.

1. Aguarde até que a página seja carregada.

1. Na página Sortimentos, selecione **+ Novo**.

1. No painel Novo Registro, expanda **Geral**.

1. Selecione a caixa **Data efetiva** e, em seguida, selecione uma data no futuro.

1. In the <bpt id="p1">**</bpt>Assortment name<ept id="p1">**</ept> box, enter a name for the new assortment. For example, <bpt id="p1">**</bpt>New Spring Season<ept id="p1">**</ept>.

1. Defina a **Data de validade** como **Nunca**.

1. A data de validade pode ser usada para desativar automaticamente um sortimento publicado.

1. Expanda **Canais de comércio**.

1. No menu Canais de comércio, selecione **+ Adicionar linha**.

1. Em Escolher nós da organização, selecione o menu **Hierarquia da organização** e depois **Lojas de varejo por tipo (Fabrikam)** .

1. Na lista NÓS DA ORGANIZAÇÃO DISPONÍVEIS, selecione Online e, em seguida, adicione o ícone ![Seta para a direita](./media/d365-fo-add-org-node-icon.png) para adicioná-lo aos **NÓS DA ORGANIZAÇÃO SELECIONADA**.  
  Isso adicionará o nó pai e todos os nós filho.

1. Adicione o nó pai **Mall** e, em seguida, selecione **OK**.

1. Verifique se os dois nós foram adicionados aos canais de Comércio.

1. Expanda **Produtos**.

1. No menu Produtos, selecione **+ Adicionar linha**.

1. Selecione o menu **Categoria**, selecione **Esportes em equipe** e depois **OK**.

1. Isso adicionará todos os itens filho da categoria pai.

1. Review the last column named <bpt id="p1">**</bpt>Line type<ept id="p1">**</ept>. By default, all items will be included.

1. Selecione **+ Adicionar linha**, selecione o menu **Categoria**, expanda **Esportes em equipe**, selecione **Basebol** e, em seguida, **selecione OK**.

1. Para excluir um item de uma categoria maior já incluída, nesse caso, Esportes em equipe, na coluna Tipo de linha, altere o valor para **Excluir**.

1. Usando a linha Categoria de basebol, selecione o menu **Produtos**.

1. When products within a category are defined, you can select a specific product to include or exclude. Select <bpt id="p1">**</bpt>AdultBaseballInfield<ept id="p1">**</ept>.

1. Para remover um produto adicionado, exclua o conteúdo da caixa do produto e pressione a tecla Tab no teclado ou selecione outra área da página.

1. No menu superior, selecione **Salvar**.

1. No menu superior, selecione **Publicar**.

1. Revise as informações na caixa de diálogo e selecione **Sim**.

1. O sortimento de produto recém-criado ficará disponível na data de vigência.
