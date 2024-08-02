---
lab:
  title: 'Laboratório 3.2: Criar uma ordem de produção'
  module: 'Learning Path 3: Learn the fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Roteiro de aprendizagem 3: aprender os conceitos básicos do Microsoft Dynamics 365 Supply Chain Management
# Módulo 4: Descrever o processo de fabricação

## Laboratório 3.2: Criar uma ordem de produção

## Objetivo

As ordens de produção ajudam a iniciar o processo de produção no Supply Chain Management. Neste laboratório, você se familiarizará com a interface do usuário e a funcionalidade do Formulário de ordem de produção. Você também aprenderá a criar e processar uma ordem de produção até o fim do exercício.

## Etapas do laboratório

1. Na página inicial do ** Supply Chain Management** do Dynamics 365, no canto superior direito, verifique se você está trabalhando com a empresa **USMF**.

2. Se necessário, selecione a empresa e, no menu, selecione **USMF**.

3. No painel de navegação à esquerda, selecione **Módulos** > **Controle de produção** > **Pedidos de produção** > **Todos os pedidos de produção**.

4. No menu superior, selecione **Nova ordem de produção** e insira os dados a seguir.

    - Número de item: **D0002**

    - Quantidade: **10**

    - Local: **1**

    - Depósito: **11**

    - Entrega: [selecione uma data de um mês a partir da data de hoje]

    - Número BOM: **D0002BOM**

    - Número da rota: **000004**

5. Selecione o botão **Criar**.

Uma nova ordem de produção é criada para 10 quantidades do item D0002.

6. Selecione **Ordem de produção (menu do painel de ações) &gt; Processar &gt; estimativa.**

7. Na caixa de diálogo **Estimativa**, selecione **Padrão** no campo **configuração de lucro**, selecione o **campo Referências** e selecione o botão **OK**.

O **Status** da ordem de produção será alterado para **Estimado**.

8. Selecione **Agendar (menu do painel de ações) &gt; Ordem de produção &gt; Agendar operações.**

9. Na caixa de diálogo **Agendamento de operações**, selecione **Avançar a partir de hoje** no campo **Direção do agendamento** e selecione o botão **OK**.

10. Selecione **Exibir (menu do painel de ações) &gt; Informações relacionadas &gt; Reserva de capacidade**.

11. Verifique os novos registros criados na página **Reserva de capacidade**.

12. Navegue de volta para a página **Todas as ordens de produção**. Observe que o **Status** da ordem de produção é alterado para **Agendado**.

13. Selecione **Ordem de produção (menu do painel de ações) &gt; Processo &gt; Liberação**.

14. Na caixa de diálogo **Liberação**, selecione o **campo Referências** e selecione o botão **OK**.

15. O **Status** da ordem de produção nunca será alterado para **Liberado**.

16. Selecione **Ordem de produção (menu do painel de ações) &gt; Processo &gt; Início**.

17. Na caixa de diálogo **Iniciar**, selecione a guia **Geral**.

18. Na guia **Geral**, insira os seguintes detalhes.

    - Data: **Data de hoje**

    - Quantidade: **10**

    - Iniciar produção: **SIM**

    - Postar cartão de roteiro agora: **NÃO**

    - Postar a lista de separação agora: **NÃO**

19. Selecione o botão **OK**.

O **Status** da ordem de produção é alterado para **Iniciado**.

20. Selecione **Exibir (menu do painel de ações) &gt; Diários &gt; Lista de separação**.

Um novo diário de lista de separação é criado com três linhas.

21. Publique o diário da lista de separação.

22. Navegue de volta para a página **Todas as ordens de produção** e selecione **Exibir (menu do painel de ações) &gt; Diários &gt; Cartão de roteiro**.

Um novo diário de cartão de roteiro é criado com três linhas.

23. Selecione o campo **Operação concluída** em todas as três linhas e poste o diário do cartão de roteiro.

24. Navegue de volta para a página **Todas as ordens de produção** e selecione **Ordens de produção (menu do painel de ações) &gt; Processo &gt; Relatar como concluído**.

25. Na caixa de diálogo **Relatar como concluído**, insira **10** no campo **Quantidade boa**. Selecione o campo **Encerrar o trabalho** e selecione **OK.**

O **Status** da ordem de produção nunca será alterado para **Encerrado**. O estoque do item **D0002** aumenta em 10 no local 1 e no depósito 11.

26. Selecione **Gerenciar custos (menu do painel de ações) &gt; Cálculos &gt; Exibir detalhes do cálculo**.

Observe a avaliação de custo final do item fabricado na guia **Avaliação de custo de visão geral**.

 
