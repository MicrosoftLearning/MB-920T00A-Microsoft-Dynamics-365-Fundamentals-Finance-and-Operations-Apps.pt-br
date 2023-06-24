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

1.  Na página inicial **Finanças e Operações**, na parte superior direita, verifique se você está trabalhando com a empresa **USMF**. 

1.  Se necessário, selecione a empresa e, no menu, selecione **USMF**. 

1.  No painel de navegação esquerdo, no módulo **Varejo e Comércio**, selecione **Catálogos e variedades** > **Variedades**. 

1.  Na página **Sortimentos**, selecione **+ Novo**. 

1.  No formulário **Novo Registro**, se necessário, expanda a FastTab**Geral**. 

1.  Selecione o campo **Data de início de vigência** e, em seguida, selecione uma data no futuro.  

1.  No campo **Nome de variedade**, insira um nome para a nova variedade. Por exemplo, `New Spring Season`

    > **Nota:** a **Data de validade** pode ser usada para desativar automaticamente uma variedade publicada. 

1.  Expanda a FastTab **Canais de comércio**. 

1.  Na barra de ferramentas **Canais de comércio**, selecione **+ Adicionar linha**. 

1.  No painel **Escolher nós da organização**, para o campo **Hierarquia da organização**, selecione **Lojas de varejo por tipo (Fabrikam)** . 

1.  Na lista NÓS DA ORGANIZAÇÃO DISPONÍVEIS, selecione Online e, em seguida, adicione o ícone ![Seta para a direita](./media/d365-fo-add-org-node-icon.png) para adicioná-lo aos **NÓS DA ORGANIZAÇÃO SELECIONADA**.

    Isso adicionará o nó pai e todos os nós filho. 

1.  Adicione o nó pai **Mall** e, em seguida, selecione **OK**. 

1.  Verifique se os dois nós foram adicionados à FastTab **Canais de comércio**. 

1.  Expanda a FastTab **Produtos**. 

1.  Na barra de ferramentas **Produtos**, selecione **+Adicionar linha**. 

1.  Para o campo **Categoria**, expanda **Esportes em equipe (Esportes em equipe)** e **OK**.

    Isso adicionará todos os itens filho da categoria pai.

1.  Revise a última coluna chamada **Tipo de linha**. Por padrão, todos os itens serão incluídos.

1.  Selecione **+ Adicionar linha**, selecione o menu **Categoria**, expanda **Esportes em equipe**, selecione **Basebol** e, em seguida, **selecione OK**. 

1.  Para excluir um item de uma categoria maior já incluída, neste caso, Esportes em equipe, na coluna **Tipo de linha**, altere o valor para `Exclude` 

1.  Usando a linha Categoria de basebol, selecione o menu **Produtos**. 

1.  Quando os produtos dentro de uma categoria são definidos, você pode selecionar um produto específico para incluir ou excluir. Selecione **AdultBaseballInfield** ou insira `0013` 

    > **Nota:** para remover um produto adicionado, exclua o conteúdo do campo **Produto** e pressione Tab ou selecione outra área da página. 

1.  No painel de ações, selecione **Salvar** e selecione **Publicar**. 

1.  Escolha **Sim** no diálogo de confirmação. A variedade de produto recém-criada ficará disponível na **Data de início de vigência** selecionada. 

