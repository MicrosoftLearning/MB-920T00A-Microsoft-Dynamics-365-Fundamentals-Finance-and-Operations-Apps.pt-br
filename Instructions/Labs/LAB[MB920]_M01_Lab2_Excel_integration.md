---
lab:
  title: 'Laboratório 2: Integração do Excel'
  module: 'Module 1: Explore the core capabilities of Dynamics 365 finance and operations apps'
ms.openlocfilehash: e5929571477cfcdbb1b2e81c72ebc566a96c56a4
ms.sourcegitcommit: 8e5a278c6e08abdcc3fb719796f79842e868606b
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/14/2022
ms.locfileid: "147116237"
---
# <a name="module-1-explore-the-core-capabilities-of-dynamics-365-finance-and-operations-apps"></a>Módulo 1: Explorar as principais funcionalidades dos aplicativos de finanças e operações do Dynamics 365

## <a name="lab-2---excel-integration"></a>Laboratório 2: Integração do Excel

Agora que você está familiarizado com os aplicativos de finanças e operações, explore o cenário de integração do Excel.

### <a name="task-1-create-template"></a>Tarefa 1: Criar um modelo

1. Abra a página inicial do Finance and Operations. 

2. Acesse **Módulos** > **Comum** > **Comum** > **Integração do Office** > **Pasta de trabalho do Excel** **Designer**. Observe que a maior parte da navegação ocorre por meio de Módulos, portanto, isso normalmente não é especificado.

3. Pesquise **VendorGroup** no filtro.

4. Na lista de campos disponíveis, selecione os campos **Grupo de fornecedores**, **Descrição** e **Termos de pagamento** e mova-os para a caixa de campo selecionada clicando na seta para a direita.

5. No painel de ação, pressione o botão **Criar pasta de trabalho**.

6. À direita, no painel **Salvar em**, pressione o botão **Baixar**.

7. Baixe o arquivo clicando em **Salvar como** e armazene-o na pasta **Downloads**.

8. Acesse **Comum** > **Integração do Office** > **Documento** **Modelos**.

9. Selecione **Novo**.

10. No painel direito, na seção **Carregar modelo**, pressione o botão **Procurar** e selecione o arquivo baixado anteriormente (se o nome padrão tiver sido usado, será DynamicsWorkbook).

11. No campo **Nome do modelo**, insira **CustomVendorGroup**.

12. Selecione **OK** e, em seguida, **Salvar**.

### <a name="task-2-open-in-excel"></a>Tarefa 2: Abrir no Excel

1. Acesse **Compras e fornecimento** > **Configuração** > **Fornecedores** > **Grupos de fornecedores**.

2. Clique em **Abrir no Microsoft Office** > **Abrir no Excel** para encontrar o novo modelo, CustomVendorGroup, que foi carregado.

3. Selecione **CustomVendorGroup** e baixe o modelo do Excel.

4. Salve e abra o modelo do Excel baixado, forneça a permissão, se necessário, feche a ativação e clique em **Habilitar edição**. Torne o suplemento confiável e faça logon (com as mesmas credenciais, se solicitado).

Todos os dados existentes da tabela Grupo de fornecedores serão exibidos na planilha do Excel.

5. Crie um registro.

6. Insira **100** no campo **Grupo de fornecedores**, **Fornecedor de seguros** no campo **Descrição** e **Net10** no campo **Termos de pagamento**.

7. Pressione o botão **Publicar** no aplicativo Suplemento do Microsoft Dynamics Office.

8. Abra o formulário do **Grupo de fornecedores** e verifique se o novo registro foi adicionado.

