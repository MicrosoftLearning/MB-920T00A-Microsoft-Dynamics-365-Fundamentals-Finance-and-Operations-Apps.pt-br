---
lab:
  title: 'Laboratório 1: Criar uma conta principal'
  module: 'Module 2: Learn the Fundamentals of Microsoft Dynamics 365 Finance'
---

# Módulo 2: Conheça os princípios básicos do Microsoft Dynamics 365 Finance

## Laboratório 1: Criar uma conta principal

## Configuração do Laboratório

   - **Tempo estimado**: 5 minutos

## Instruções


1.  Na página inicial **Finanças e Operações**, na parte superior direita, verifique se você está trabalhando com a empresa **USMF**.

2.  Se necessário, selecione a empresa e, no menu, selecione **USMF**.
3.  No painel de navegação esquerdo, selecione **Módulos > Contabilidade > Calendários > Calendários fiscais**.
4.  Selecione um calendário **fiscal**
5.  Se o ano civil atual já estiver criado, saia da página **Calendários fiscais**.
6. Se o ano civil atual não estiver criado, selecione o botão **Novo ano** no painel de ações e insira o ano atual, como aparece na captura de tela a seguir. Selecione o **botão Criar** para criar o ano civil atual.

![A captura de tela mostra como criar o novo ano no calendário fiscal](./media/lab-create-a-main-account-04.png)


4.  No painel de navegação esquerdo, clique em **Módulos** > **Contabilidade** > **Plano de contas** > **Contas** > **Contas principais**.

5.  No painel de ações, selecione **+ Novo**.

6.  Insira os seguintes valores na página **Conta principal**:

    - Conta principal: **601510**

    - Nome: **Despesa com chamadas internacionais**

    - Tipo de conta principal: **Despesa**

    - Categoria da conta principal: **TANDEEXP**

    - Padrão de DB/CR: **Débito**

    ![A captura de tela mostra contas principais – gráfico de contas: página compartilhada em que diferentes valores precisam ser adicionados.](./media/lab-create-a-main-account-01.png)

7.  Navegue até **Módulos &gt; Razão geral &gt; Entradas do diário &gt; Diários gerais.**

8.  No painel de ações, selecione **+ Novo**.

9.  Insira o seguinte valor na página **Diários gerais** e selecione **Linhas** no painel de ação:

    - Nome: GenJrn

10.  Insira os seguintes valores na página **Comprovante de diário**:

    - Tipo de conta: **Razão**

    - Conta principal: **601510**

    - Débito: **10.00** 

    - Tipo de conta de deslocamento: **Razão**

    - Número da conta de deslocamento: **110180** 

11. Pressione o botão **Salvar** no painel de ação.

12. Selecione **Validar &gt; Simular postagem**. 

13. Pressione o botão **Postar** no painel de ações. O diário deve ser postado.
