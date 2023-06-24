---
lab:
  title: 'Laboratório 1: Criar um produto'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Módulo 3: Conheça os Princípios básicos do Microsoft Dynamics 365 Supply Chain Management

## Laboratório 1: Criar um produto

## Objetivo

Em Contoso Entertainment System USA (USMF), é preciso criar um novo item para que uma nova configuração de gabinete seja comprada de fornecedores. 

## Configuração do Laboratório

   - **Tempo estimado**: 10 minutos

## Instruções

1.  Na página inicial **Finanças e Operações**, na parte superior direita, verifique se você está trabalhando com a empresa **USMF**. 

1.  Se necessário, selecione a empresa e, no menu, selecione **USMF**.

1.  No canto superior esquerdo, selecione o menu hambúrguer **Expandir o painel de navegação**. 

1.  No painel de navegação, no módulo **Gerenciamento de informações do produto**, selecione **Produtos** > **Produtos lançados**. 

1.  Na página **Detalhes do produto lançado**, selecione **+ New** no painel de ações. 

1.  No painel de **Novos produtos lançados**, para o campo  **Tipo de produto** , verifique se **Item** está selecionado. 

1.  No campo  **Subtipo do produto** , verifique se **Produto** está selecionado. 

1.  Selecione o menu  **Grupo de dimensões de rastreamento**  e insira ou selecione  `None` 

1.  Em **IDENTIFICAÇÃO**, para o **Número do produto**, insira `GTL007`

1.  Na caixa  **Nome do produto** , insira  `Cabinet 2`

1.  Em **GRUPOS DE REFERÊNCIA**, no campo  **Grupo de modelos de item** , insira ou selecione  `FIFO`, primeiro a entrar, primeiro a sair. 

1.  Para o campo **Grupo de itens**, insira ou selecione `TV&Video` 

1.  Para **Grupo de dimensões de armazenamento**, insira ou selecione `SiteWH` 

1.  Em **UNIDADES DE MEDIDA**, verifique se foram definidos os seguintes valores: 

    | **Configuração**    | **Valor** |
    | :------------- | :-------- |
    | Unidade de inventário | ea Cada   |
    | Unidade de compra  | ea Cada   |
    | Unidade de vendas     | ea Cada   |
    | Unidade BOM       | ea Cada   |

1.  Em **IMPOSTO SOBRE VENDAS**, para **Grupo de impostos sobre vendas de itens**, insira ou selecione  `ALL` 

1.  Em **IMPOSTO SOBRE COMPRAS**, para **Grupo de impostos sobre vendas de itens**, insira ou selecione  `ALL` 

1.  Em **PREÇOS**, no campo **Preço da compra** , insira  `30.00`

1.  No campo  **Preço de vendas** , insira  `30.00`

1.  Verifique se o novo **produto lançado** tem esta aparência: 

    ![Imagem de tela mostrando o formulário do novo produto liberado preenchido](./media/lp1-m2-new-release-product.png)

1.  Selecione  **OK**. 

1.  Para garantir que o produto seja finalizado, no painel de ações, em **Manter**, selecione a ação **Validar**. 

    ![Imagem de tela mostrando a barra de faixa de opções com a opção Validar em destaque](./media/lp1-m2-validate-ribbon-bar.png)

1.  Verifique se você recebeu a notificação confirmando que todos os valores de campo obrigatórios foram validados. 

    ![Imagem de tela com a notificação da informação de que todos os campos exigidos foram validados](./media/lp1-m2-confirmation-of-validation.png)

1.  Selecione **Salvar** e **feche** todas as páginas e retorne à página inicial. 

