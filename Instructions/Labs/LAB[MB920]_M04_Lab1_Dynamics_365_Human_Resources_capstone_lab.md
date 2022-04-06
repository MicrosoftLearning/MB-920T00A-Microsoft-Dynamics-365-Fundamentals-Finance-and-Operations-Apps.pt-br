---
lab:
  title: 'Laboratório 1: Laboratório do trabalho de conclusão de curso do Dynamics 365 Human Resources'
  module: 'Module 4: Learn the Fundamentals of Microsoft Dynamics 365 Human Resources'
ms.openlocfilehash: e1d0f9974a3c1d6f4b31bb62733153850e2c86b0
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909400"
---
## <a name="lab-1---dynamics-365-human-resources-capstone-lab"></a>Laboratório 1 — Laboratório do trabalho de conclusão de curso do Dynamics 365 Human Resources

## <a name="objective"></a>Objetivo

Durante este laboratório, você explorará o processo de integração de um novo funcionário, incluindo a criação de um registro de funcionário. Você também revisará o processo de revisão de desempenho que envolve a configuração de meta e a classificação de desempenho. Além disso, você usará recursos de autoatendimento para enviar um relatório de despesas.

## <a name="lab-setup"></a>Configuração do Laboratório

- **Tempo estimado**: 20 minutos 

## <a name="exercise-1-explore-human-resources"></a>Exercício 1: Explorar os recursos humanos

### <a name="create-a-new-hire-record"></a>Crie um novo registro de contratação

1. Usando o painel de navegação, selecione **Módulos** > **Recursos humanos** > **Posições** > **Posições**.

1. No Painel de Ações, selecione **+Novo** para criar uma nova posição.

1. Na caixa de diálogo **Criar nova posição**, selecione o menu **Trabalho** e, em seguida, selecione **Gerenciador da Loja**.

1. Selecione **Criar posição**.

1. Usando o painel de navegação, selecione **Módulos** > **Trabalhadores** > **Funcionários**.

1. No Painel de Ações, selecione **+Novo** para criar um novo funcionário.

1. No painel **Contratação de novo trabalhador**, insira as atualizações a seguir e, em seguida, selecione **Contratar e adicionar detalhes**.

    | **Configuração** | **Valor** |
    | :--- | :---- |
    | Nome | Bill |
    | Sobrenome | Smith |
    | Data de início do emprego | Selecionar a data atual|

### <a name="create-a-goal-for-the-new-hire"></a>Crie uma meta para o novo contratado

1. No Painel de Ações, selecione **Trabalhador**.

1. Na guia **DESENVOLVIMENTO**, selecione **Metas**.

1. Talvez você precise rolar a tela para a direita para ver a guia.

1. No Painel de Ações, selecione **+Novo** para criar uma nova meta.

1. Na FastTab **Geral**, insira as seguintes atualizações:

    | **Configuração** | **Valor** |
    | :--- | :---- |
    | Nome | Meta de vendas trimestral |
    | Visão geral | Ajude a equipe da loja a atingir a meta de vendas trimestral. |
    | Categoria da meta | Sales |
    | Data de início | Selecione uma data de uma semana a partir da data atual |
    | Data de término | Selecionar a data 2 semanas após a data de início |

1. No Painel de Ações, selecione **Salvar**.

1. Feche a página Meta de Vendas Trimestral.

1. Fechar as metas | Página de cobrança.

### <a name="assign-learning-course-to-the-new-hire"></a>Atribua cursos de aprendizado ao novo contratado

1. Na página Funcionários para Cobrança, no Painel de Ação, selecione **Trabalhador**

1. Na guia **COMPETÊNCIAS**, selecione **Cursos**.

1. Talvez você precise rolar a tela para a direita para ver a guia.

1. No Painel de Ações, selecione **+Novo** para criar um novo curso.

1. Na exibição de grade, na coluna **ID do** Curso, selecione o menu e, em seguida, selecione **00004**.

1. Na caixa de diálogo **Transferir dados do curso**, selecione **Sim**.

1. Na coluna **Data de início**, selecione o ícone de calendário e, em seguida, selecione a data de hoje.

1. Na coluna **Data de término**, selecione o ícone de calendário e, em seguida, selecione uma data de duas semanas a partir da data de hoje.

1. No Painel de Ações, selecione **Salvar**.

1. Feche a página Cursos | Cobrança.

### <a name="create-an-expense-report"></a>Crie um relatório de despesas

1. Usando o painel de navegação, selecione **Módulos** > **Recursos Humanos** > **Espaços de Trabalho** > **Autoatendimento de funcionário**.

1. Na seção **Informações da minha carreira**, no bloco **Despesas**, selecione **Novo Relatório**.

1. No painel **Novo relatório de despesas**, selecione o menu **Finalidade**, selecione **Treinamento** e, em seguida, selecione **OK**.

1. Na grade **Despesas**, na nova linha de despesas, insira as seguintes atualizações:

    | **Configuração** | **Valor** |
    | :--- | :---- |
    | Data da transação | Selecionar a data de hoje |
    | Categoria da despesa | Aluguel de carro |
    | Comerciante | LitWare Travel |
    | Valor da transação | 150,00 |

1. Usando a máquina virtual de laboratório, abra o **Bloco de notas**.

1. No corpo do bloco de notas, insira **Recibo da LitWare Travel**.

1. Salve o arquivo na Área de Trabalho como **Receipt.txt** e feche o Bloco de notas.

1. Você usará esse arquivo para representar um recibo para anexar a um relatório de despesas.

1. Retorne à guia do navegador Microsoft Dynamics 365 Finance & Operations.

1. No Painel de Ação, selecione **Recibos do cabeçalho**.

1. No painel **Recibos do cabeçalho**, selecione Carregar **e anexe o novo recibo**.

1. Selecione **Procurar**.

1. Selecione o arquivo **Receipt.txt** criado anteriormente e, em seguida, selecione **Abrir**.

1. Na caixa **Observações**, insira **Aluguel de carro** e selecione **Carregar**.

1. Marque a caixa de seleção **Recibo** e selecione **Selecionar linhas**.

1. No painel **Anexar recibos à linha**, marque a caixa de seleção **150,00 LitWare Travel** e, em seguida, selecione **OK**.

1. Selecione **Fechar**.

1. No Painel de Ação, selecione **Fluxo de trabalho** e, em seguida, selecione **Enviar**.

1. No painel **Relatório de despesas – USMF – Enviar**, na caixa **Comentários**, insira **Meu relatório de despesas**.

1. Selecione **Enviar**.

### <a name="record-performance-journal"></a>Registre um diário de desempenho

1. Usando o painel de navegação, selecione **Módulos** > **Recursos humanos** > **Desempenho** > **Diário de desempenho**

1. No Painel de Ações, selecione **+ Novo**.

1. Na página **Novo diário**, insira as atualizações a seguir.


    | **Configuração** | **Valor** |
    | :--- | :---- |
    | Título | Treinamento assistido |
    | Descrição | Concluído o treinamento de negócios para o Gerenciador de Lojas |
    | Pessoa | Bill Smith |
    | Data de conclusão | Data de hoje |

1. No Painel de Ações, selecione **Salvar**.

1. No Painel de Ações, selecione **Adicionar à meta**.

1. Selecione **Meta de Vendas Trimestral** e, em seguida, selecione **OK**.

1. Feche a página Diário de desempenho.
