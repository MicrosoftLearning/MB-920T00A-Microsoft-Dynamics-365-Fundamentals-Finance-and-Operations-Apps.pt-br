---
demo:
  title: 'Demonstração 3: Explorar os custos do projeto'
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
---

## <a name="demo-3---explore-project-costs"></a>Demonstração 3 – Explorar os custos do projeto

In this demo, we will walk through the creation of a time and expense entry that will be charged to the Contoso Consulting project. We'll explore the entries in formats optimized for web and mobile presentation, and we'll see how a workflow is used to manage the approval process.

1. No **Dynamics 365 for Finance and Operations**, no painel de navegação, selecione **Módulos > Gerenciamento de projetos e contabilidade > Folhas de ponto > Minhas folhas de ponto (otimizadas para dispositivo móvel)** .  
    Para começar, embora eu não esteja em um dispositivo móvel no momento, você reconhecerá os formulários como amigáveis para dispositivos móveis depois de selecionarmos a opção **Minhas folhas de ponto (otimizadas para dispositivo móvel)** .

    ![Uma captura de tela do menu gerenciamento de projetos e contabilidade com minhas folhas de ponto (otimizadas para dispositivo móvel) realçado.](./media/projops_costs_1_select_my_timesheets.png)  

    Essa otimização é um importante diferencial para os aplicativos de negócios da Microsoft e ajuda a garantir que haja uma curva de aprendizado mínima entre a Web e o uso móvel.

1. In the top right company picker, verify the legal entity you are connecting to is <bpt id="p1">**</bpt>USSI<ept id="p1">**</ept>. If it's not, change the legal entity to <bpt id="p1">**</bpt>USSI<ept id="p1">**</ept>.

1. Na página **Minhas folhas de ponto**, selecione **Novo**.  
    Agora, vamos criar uma nova folha de ponto que será baseada nas configurações definidas.

1. No painel **Nova folha de ponto**, aponte para a caixa **Data**.  
    A data inserida determinará o período da folha de ponto.

1. Aponte para **Criar a partir de favoritos**.  
    Se você tiver favoritos salvos, poderá optar por criar a partir deles para poupar tempo.

1. Quando concluir, selecione **OK**.

1. Na página **Detalhes das minhas folhas de ponto**, selecione o ícone **Novo +** .

1. No painel **Nova linha da folha de ponto**, aponte para a caixa **Pessoa jurídica**.  
    The new timesheet line will be opened, with details such as the customer, the project, the category, the line properties, and tax parameters. You can also select a different legal entity if the time entry is on behalf of another company within your organization.

1. Selecione o menu **ID do projeto**.

1. Selecione um dos projetos disponíveis, como o projeto **Contoso Consulting**.

1. Quando concluir, selecione **OK**.  
    A tela otimizada para dispositivos móveis para a entrada de tempo será aberta e você poderá começar a agendar suas horas diárias para o projeto e a categoria, nesse caso, **Serviço**.

1. Na página **Entrada de tempo**, na caixa **Seg**, digite **8**.  
    Isso representa a entrada das horas de um único dia.

    ![Uma captura de tela da página de Entrada de tempo.](./media/projops_costs_2_mon_box.png)

1. Nesta demonstração, veremos a criação de uma entrada de tempo e despesa que será cobrada no projeto da Contoso Consulting.  
    Também é possível inserir comentários internos e externos em relação ao projeto para garantir que todas as partes compreendam a natureza das horas que estão sendo registradas.

1. Vamos explorar as entradas em formatos otimizados para apresentação móvel e na Web, e veremos como um fluxo de trabalho é usado para gerenciar o processo de aprovação.

1. Na barra de navegação, selecione **Salvar**.

1. No menu de navegação esquerdo, em **Folhas de ponto**, selecione **Minhas folhas de tempo**.

1. Na página **Minhas folhas de ponto**, selecione a entrada de tempo criada anteriormente.

1. Na guia **Folha de ponto**, aponte para a coluna Categoria.  
    Now assume we've returned to a computer and are reviewing our time from within the web timesheet form. We can still see the same information, such as the category and the hours.

1. Em **Detalhes da linha**, aponte para **Comentário interno** e **Comentário externo**.  
    We can also review the comments we entered earlier. The information is there, but the layout format is just a bit different. This format is often used for final review because it can be easier for people to review and validate their time, especially when someone is assigned to multiple projects or categories.

1. Na barra de navegação, selecione a guia **Fluxo de trabalho**.  
    If we're satisfied with the timesheet, we can submit it. The approvals required will be determined by each organization during the implementation phase based on their own company policies.

1. No painel **Examinar fluxo de trabalho da folha de ponto**, selecione **Enviar**.

1. No painel **Examinar fluxo de trabalho da folha de ponto – Enviar**, adicione outros comentários.

1. Selecione **Enviar**.

1. Browse to the <bpt id="p1">**</bpt>Hour transactions<ept id="p1">**</ept> page. If the <bpt id="p1">**</bpt>Hour transactions<ept id="p1">**</ept> tab is grayed out, browse to the <bpt id="p2">**</bpt>My timesheets page<ept id="p2">**</ept>, and select the previously created timesheet.

1. Na página **Transações de horas**, examine a página.  
    Upon approval, the results will be posted and will be visible in the Hour transactions page. We can see all the relevant information, such as the legal entity, project, category, hours, and in this case, even a view of the cost price and the sales price.  

Em seguida, podemos fazer uma busca detalhada das Transações de comprovante.

1. Na barra de navegação, selecione **Comprovante**.

1. Na página **Transações de comprovante**, aponte para as seções **Conta contábil** e **Nome da conta**.  
    Nessas seções, podemos ver o impacto na contabilidade geral, bem como as contas que serão usadas.  

Agora, vamos criar uma entrada de despesa para o mesmo projeto de consultoria da Contoso.

1. No painel de navegação, selecione **Módulos > Gerenciamento de despesas > Minhas despesas > Relatórios de despesas**.

1. Na página **Gerenciamento de despesas**, na guia **Relatórios**, selecione **+Novo relatório de despesas**.

1. No seletor superior direito da empresa, verifique se a pessoa jurídica à qual você está conectado é **USSI**.

1. Selecione **OK**.

1. Na página **Despesas**, selecione **+Nova despesa**.  
Uma nova linha de despesa será exibida.

1. Na coluna **Categoria de despesas**, selecione **Combustível** no menu suspenso **Categoria**.  
Aqui podemos inserir a nova despesa com os respectivos detalhes.

1. Na coluna **Valor da transação**, insira **25,00**.

1. Na coluna **Moeda**, selecione **USD**.

1. Se não for, altere-a para **USSI**.  
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
    At this time, travel policies and expense approval flow will be activated. The costs have been posted and applied to the Contoso Consulting project and will be available later for invoicing if chargeable.

In this demo, we have processed a time and expense entry that was charged to the Contoso Consulting project. We saw samples in web and mobile formats and were able to see how workflows are used to manage the approvals required by the USSI organization.
