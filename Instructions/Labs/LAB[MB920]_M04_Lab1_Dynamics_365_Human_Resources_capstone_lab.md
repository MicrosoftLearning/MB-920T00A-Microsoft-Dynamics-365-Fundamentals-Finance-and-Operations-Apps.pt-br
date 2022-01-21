---
lab:
    title: 'Laboratório 1: Laboratório do trabalho de conclusão de curso do Dynamics 365 Human Resource'
    module: 'Módulo 4: Conheça os princípios básicos do Microsoft Dynamics 365 Human Resources'
---

## Laboratório 1 - Laboratório do trabalho de conclusão de curso do Dynamics 365 Human Resource

## Objetivo

Neste laboratório, vamos explorar o processo de integração de um novo funcionário, incluindo a criação de um registro de funcionário. Você também vai ver o processo de análise de desempenho envolvendo a definição de metas e a classificação do desempenho. Além disso, você vai usar os recursos de autoatendimento para enviar um relatório de despesas.

## Configuração do laboratório

- **Tempo estimado**: 20 minutos 

## Exercício 1: Descobrir o Human Resources

### Criar um novo registro de contratação

1. Usando o painel de navegação, selecione **Módulos** > **Recursos humanos** > **Posições** > **Posições**.

1. No painel de ações, selecione **+Novo** para criar uma nova posição.

1. Na caixa de diálogo **Criar nova posição**, selecione o menu **Trabalho** e depois **Gerente da loja**.

1. Selecione **Criar posição**.

1. Usando o painel de navegação, selecione **Módulos** > **Trabalhadores** > **Funcionários**.

1. No painel de ações, selecione **+Novo** para criar um novo funcionário.

1. No painel **Contratar novo trabalhador**, insira as atualizações a seguir e depois selecione **Contratar e adicionar detalhes**.

    | **Configuração** | **Valor** |
    | :--- | :---- |
    | Nome | Bill |
    | Sobrenome | Smith |
    | Data de Início do funcionário | Selecionar a data atual|

### Criar uma meta para o novo contratado

1. No painel de ações, selecione **Trabalhador**.

1. Na guia **DESENVOLVIMENTO**, selecione **Metas**.

1. Talvez seja necessário rolar a tela para a direita para ver a guia.

1. No painel de ações, selecione **+Novo** para criar uma nova meta.

1. Na guia rápida **Geral**, especifique as seguintes atualizações:

    | **Configuração** | **Valor** |
    | :--- | :---- |
    | Nome | Meta de vendas trimestrais |
    | Visão geral | Ajude a equipe da loja a atingir a meta de vendas trimestral. |
    | Categoria da meta | Vendas |
    | Data de início | Selecione uma data uma semana depois da data atual |
    | Data de término | Selecione uma data 2 semanas depois da data de início |

1. No painel de ações, selecione **Salvar**.

1. Feche a página Meta de Vendas Trimestral.

1. Fechar as metas | Página de Bill.

### Atribua cursos de aprendizado ao novo contratado

1. Na página Funcionários de Bill, no painel de ações, selecione **Trabalhador**.

1. Na guia **COMPETÊNCIAS**, selecione **Cursos**.

1. Talvez seja necessário rolar a tela para a direita para ver a guia.

1. No painel de ações, selecione **+Novo** para criar um novo curso.

1. Na visualização de grade, na coluna **ID do curso**, selecione o menu e, em seguida **00004**.

1. Na caixa de diálogo **Transferir dados do curso**, selecione **Sim**.

1. Na coluna **Data de início**, selecione o ícone de calendário e selecione a data de hoje.

1. Na coluna **Data de término**, selecione o ícone de calendário e selecione a data duas semanas depois da data de hoje.

1. No painel de ações, selecione **Salvar**.

1. Fechar os cursos | Página de Bill.

### Criar um relatório de despesas

1. Usando o painel de navegação, selecione **Módulos** > **Recursos Humanos** > **Espaços de Trabalho** > **Autoatendimento para funcionários**.

1. Na seção **Informações da minha carreira**, no bloco **Despesas**, selecione **Novo Relatório**.

1. No painel **Novo relatório de despesa**, selecione o menu **Objetivo**, **Treinamento** e depois **OK**.

1. Na grade **Despesas**, na linha da nova despesa, digite as seguintes atualizações:

    | **Configuração** | **Valor** |
    | :--- | :---- |
    | Data da transação | Selecione a data de hoje |
    | Categoria da despesa | Aluguel de carro |
    | Comerciante | LitWare Travel |
    | Valor da transação | 150,00 |

1. Usando a máquina virtual do laboratório, abra o **Bloco de Notas**.

1. No corpo do bloco de notas, digite **Recibo da LitWare Travel**.

1. Salve o arquivo na área de trabalho como **Recibo.txt** e depois feche o Bloco de Notas.

1. Você usará esse arquivo para representar um recibo a ser anexado a um relatório de despesas.

1. Volte para a guia do navegador do Microsoft Dynamics 365 Finance & Operations.

1. No painel de ações, selecione **Recebimentos de cabeçalho**.

1. No painel **Recebimentos de cabeçalho**, selecione **Carregar e anexar novo recibo**.

1. Selecione **Browse** (Procurar).

1. Selecione o arquivo **Recibo.txt** que você criou antes e depois selecione **Abrir**.

1. Na caixa **Anotações**, digite **Aluguel de carro** e selecione **Carregar**.

1. Marque a caixa de seleção **Recebimento** e depois selecione **Selecionar linhas**.

1. No painel **Anexar recibos à linha**, marque a caixa de seleção **150,00 LitWare Travel** e depois selecione **OK**.

1. Selecione **Fechar**.

1. No painel de ações, clique em **Fluxo de trabalho** e depois selecione **Enviar**.

1. No painel **Relatório de despesas - USMF - Enviar**, na caixa **Comentários**, digite **Favor examinar meu relatório de despesas**.

1. Selecione **Enviar**.

### Registrar um diário de desempenho

1. Usando o painel de navegação, selecione **Módulos** > **Recursos humanos** > **Desempenho** > **Diário de desempenho**

1. No painel de ações, selecione **+Novo**.

1. Na página **Novo diário**, especifique as atualizações a seguir.


    | **Configuração** | **Valor** |
    | :--- | :---- |
    | Título | Participação em treinamento |
    | Descrição | Treinamento comercial completo para gerente de loja |
    | Pessoa | Bill Smith |
    | Data da conclusão | A data de hoje. |

1. No painel de ações, selecione **Salvar**.

1. No painel de ações, selecione **Adicionar à meta**.

1. Selecione **Meta de Vendas Trimestral** e depois selecione **OK**.

1. Feche a página Diário de desempenho.
