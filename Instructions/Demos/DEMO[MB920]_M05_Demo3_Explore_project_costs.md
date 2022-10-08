---
demo:
  title: 'Demonstração 3: Explorar os custos do projeto'
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
---

## <a name="demo-3---explore-project-costs"></a>Demonstração 3 – Explorar os custos do projeto

Nesta demonstração, veremos a criação de uma entrada de tempo e despesa que será cobrada no projeto da Contoso Consulting. Vamos explorar as entradas em formatos otimizados para apresentação móvel e na Web, e veremos como um fluxo de trabalho é usado para gerenciar o processo de aprovação.

1. No **Dynamics 365 for Finance and Operations**, no painel de navegação, selecione **Módulos > Gerenciamento de projetos e contabilidade > Folhas de ponto > Minhas folhas de ponto (otimizadas para dispositivo móvel)** .  
    Para começar, embora eu não esteja em um dispositivo móvel no momento, você reconhecerá os formulários como amigáveis para dispositivos móveis depois de selecionarmos a opção **Minhas folhas de ponto (otimizadas para dispositivo móvel)** .

    ![Uma captura de tela do menu gerenciamento de projetos e contabilidade com minhas folhas de ponto (otimizadas para dispositivo móvel) realçado.](./media/projops_costs_1_select_my_timesheets.png)  

    Essa otimização é um importante diferencial para os aplicativos de negócios da Microsoft e ajuda a garantir que haja uma curva de aprendizado mínima entre a Web e o uso móvel.

1. No seletor superior direito da empresa, verifique se a pessoa jurídica à qual você está conectado é **USSI**. Se não for, altere-a para **USSI**.

1. Na página **Minhas folhas de ponto**, selecione **Novo**.  
    Agora, vamos criar uma nova folha de ponto que será baseada nas configurações definidas.

1. No painel **Nova folha de ponto**, aponte para a caixa **Data**.  
    A data inserida determinará o período da folha de ponto.

1. Aponte para **Criar a partir de favoritos**.  
    Se você tiver favoritos salvos, poderá optar por criar a partir deles para poupar tempo.

1. Quando concluir, selecione **OK**.

1. Na página **Detalhes das minhas folhas de ponto**, selecione o ícone **Novo +** .

1. No painel **Nova linha da folha de ponto**, aponte para a caixa **Pessoa jurídica**.  
    A nova linha da folha de ponto será aberta, com detalhes como o cliente, o projeto, a categoria, as propriedades da linha e os parâmetros de imposto. Também é possível selecionar uma pessoa jurídica diferente se a entrada de tempo estiver em nome de outra empresa em sua organização.

1. Selecione o menu **ID do projeto**.

1. Selecione um dos projetos disponíveis, como o projeto **Contoso Consulting**.

1. Quando concluir, selecione **OK**.  
    A tela otimizada para dispositivos móveis para a entrada de tempo será aberta e você poderá começar a agendar suas horas diárias para o projeto e a categoria, nesse caso, **Serviço**.

1. Na página **Entrada de tempo**, na caixa **Seg**, digite **8**.  
    Isso representa a entrada das horas de um único dia.

    ![Uma captura de tela da página de Entrada de tempo.](./media/projops_costs_2_mon_box.png)

1. Na caixa **Comentário interno**, adicione um comentário. Por exemplo: **Talvez bater um papo sobre novas bicicletas**.  
    Também é possível inserir comentários internos e externos em relação ao projeto para garantir que todas as partes compreendam a natureza das horas que estão sendo registradas.

1. Na caixa **Comentário externo**, adicione um comentário. Por exemplo: **Ajustou as correntes e alinhou as rodas dianteiras da frota**.

1. Na barra de navegação, selecione **Salvar**.

1. No menu de navegação esquerdo, em **Folhas de ponto**, selecione **Minhas folhas de tempo**.

1. Na página **Minhas folhas de ponto**, selecione a entrada de tempo criada anteriormente.

1. Na guia **Folha de ponto**, aponte para a coluna Categoria.  
    Agora, suponha que tenhamos retornado a um computador e que revisamos nosso tempo no formulário da folha de ponto na Web. Ainda podemos ver as mesmas informações, como a categoria e as horas.

1. Em **Detalhes da linha**, aponte para **Comentário interno** e **Comentário externo**.  
    Também podemos examinar os comentários que inserimos anteriormente. As informações estão lá, mas o formato de layout é apenas um pouco diferente. Esse formato é geralmente usado para análise final porque pode ser mais fácil para as pessoas revisarem e validarem seus horários, especialmente quando alguém recebe atribuição de vários projetos ou categorias.

1. Na barra de navegação, selecione a guia **Fluxo de trabalho**.  
    Se estivermos satisfeitos com a folha de ponto, poderemos enviá-la. As aprovações necessárias serão determinadas por cada organização durante a fase de implementação com base nas próprias políticas internas.

1. No painel **Examinar fluxo de trabalho da folha de ponto**, selecione **Enviar**.

1. No painel **Examinar fluxo de trabalho da folha de ponto – Enviar**, adicione outros comentários.

1. Selecione **Enviar**.

1. Navegue até a página **Transações de horas**. Se a guia **Transações de horas** estiver esmaecida, navegue até a página **Minhas folhas de ponto** e selecione a folha de ponto criada antes.

1. Na página **Transações de horas**, examine a página.  
    Após a aprovação, os resultados serão postados e ficarão visíveis na página Transações de horas. Podemos ver todas as informações relevantes, como a pessoa jurídica, o projeto, a categoria, as horas e, nesse caso, até mesmo uma exibição do preço de custo e do preço de venda.  

Em seguida, podemos fazer uma busca detalhada das Transações de comprovante.

1. Na barra de navegação, selecione **Comprovante**.

1. Na página **Transações de comprovante**, aponte para as seções **Conta contábil** e **Nome da conta**.  
    Nessas seções, podemos ver o impacto na contabilidade geral, bem como as contas que serão usadas.  

Agora, vamos criar uma entrada de despesa para o mesmo projeto de consultoria da Contoso.

1. No painel de navegação, selecione **Módulos > Gerenciamento de despesas > Minhas despesas > Relatórios de despesas**.

1. Na página **Gerenciamento de despesas**, na guia **Relatórios**, selecione **+Novo relatório de despesas**.

1. No painel **Novo relatório de despesas**, na **Caixa finalidade**, insira um título. Por exemplo, **Contoso – Fev2021**.

1. Selecione **OK**.

1. Na página **Despesas**, selecione **+Nova despesa**.  
Uma nova linha de despesa será exibida.

1. Na coluna **Categoria de despesas**, selecione **Combustível** no menu suspenso **Categoria**.  
Aqui podemos inserir a nova despesa com os respectivos detalhes.

1. Na coluna **Valor da transação**, insira **25,00**.

1. Na coluna **Moeda**, selecione **USD**.

1. Na coluna **Data da transação**, selecione uma data. Por exemplo, **01/02/2021**.  
    Depois de inserir todos os detalhes, você pode salvar a despesa.

1. Selecione **Salvar**.

1. No menu de navegação esquerdo, em **Workspaces**, selecione **Gerenciamento de despesas**.

1. Na página **Gerenciamento de despesas**, selecione o relatório de despesas que você acabou de criar.

1. Na página **Relatório de despesas**, selecione a caixa **ID do projeto** e, em seguida, selecione **00000093 Contoso Consulting**.  

Em seguida, podemos indicar que o combustível será cobrado no projeto Contoso Consulting, bem como informações adicionais sobre a despesa.

1. Aponte para a caixa **Informações Adicionais**.

1. No lado inferior direito da tela, selecione **Salvar e continuar**.

1. No lado direito da tela, selecione **Enviar**.

1. Na caixa **Comentário**, adicione comentários extras.

1. Selecione **Enviar**.

1. Na página **Gerenciamento de despesas**, aponte para a coluna **Status de aprovação**.  
    Neste momento, as políticas de viagem e o fluxo de aprovação de despesas serão ativados. Os custos foram lançados e aplicados ao projeto Contoso Consulting e estarão disponíveis posteriormente para faturamento, se forem passíveis de cobrança.

Nesta demonstração, processamos uma entrada de hora e despesa que foi cobrada no projeto Contoso Consulting. Vimos amostras nos formatos Web e móvel e pudemos ver como os fluxos de trabalho são usados para gerenciar as aprovações exigidas pela organização USSI.
