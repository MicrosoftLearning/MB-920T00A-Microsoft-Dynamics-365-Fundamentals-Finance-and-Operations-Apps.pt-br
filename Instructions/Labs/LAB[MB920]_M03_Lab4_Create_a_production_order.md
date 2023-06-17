---
lab:
  title: '‘Laboratório 4: Criar uma ordem de produção'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Módulo 3: Conheça os Princípios básicos do Microsoft Dynamics 365 Supply Chain Management

## ‘Laboratório 4: Criar uma ordem de produção

## Objetivo

A ordem de produção contém informações sobre o que será produzido, a quantidade a ser produzida e a data de término planejada. Ele também contém informações sobre quais materiais consumir e qual processo deve ser seguido para produzir o item.

Você deve criar uma nova ordem de produção para sua empresa.

## Configuração do Laboratório

   - **Tempo estimado**: 5 minutos

## Instruções

1.  Na página inicial **Finanças e Operações**, na parte superior direita, verifique se você está trabalhando com a empresa **USMF**. 

1.  Se necessário, selecione a empresa e, no menu, selecione **USMF**. 

1.  No painel de navegação esquerdo, no módulo **Controle de produção**, selecione **Pedidos de produção** > **Todos os pedidos de produção**. 

1.  No painel de ações, selecione **Novo pedido de produção**. 

1.  Em **IDENTIFICAÇÃO**, no campo **Número do item**, insira `D0001` e selecione o item **MidRangeSpeaker**. 

1.  Em **PRODUÇÃO**, no campo **Entrega**, selecione uma data de um mês a partir da data de hoje. 
   
    > **Observação:** a data de **entrega** indica quando o pedido de produção deve terminar para ser entregue no prazo. Essa data pode ser usada no processo de agendamento. Por exemplo, você pode agendar retroativamente o pedido a partir da data de entrega. 

1.  No campo **Quantidade**, insira `20.00` 

    > **Observação:** em **LISTA DE MATERIAIS/ROTA**, o campo **Número da lista de materiais** exibe automaticamente o número de qualquer lista de materiais ativa para o item atual, mas é possível alterá-lo para a ordem de produção selecionando uma lista de materiais ativa na lista de versões aprovadas. O campo **Número de rota** exibe automaticamente o número de qualquer rota ativa para o item atual, mas é possível alterá-lo para a ordem de produção selecionando uma rota ativa na lista de versões aprovadas. 

    ![Imagem da tela exibindo o painel completo Criar ordem de produção](./media/lp1-m4-new-production-order-pane.png)

1.  Selecione **Criar**. 

1.  **Feche** a página e retorne à página inicial. 

