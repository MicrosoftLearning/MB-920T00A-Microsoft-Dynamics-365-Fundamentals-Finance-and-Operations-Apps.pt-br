---
lab:
  title: 'Laboratório 2.1: Criar uma conta principal'
  module: 'Learning Path 2: Learn the fundamentals of Microsoft Dynamics 365 Finance'
---

# Roteiro de aprendizagem 2: aprender os conceitos básicos do Microsoft Dynamics 365 Finance
# Módulo 2: Descrever contabilidades

## Laboratório 2.1: Criar uma conta principal

## Configuração do Laboratório

   - **Tempo estimado**: 5 minutos

## Objetivo

Nesse laboratório, você executará as seguintes atividades:

1. Criar uma entidade legal.

2. Criar um calendário fiscal.

3. Criar um plano de contas.

4. Criar as contas principais necessárias no plano de contas.

5. Criar uma unidade operacional do tipo departamento e centro de custo.

6. Criar uma estrutura de contabilidade usando os centros de custo e as contas principais.

7. Configurar o razão.

# Etapas do laboratório

## Criar uma entidade legal

1. No painel de navegação esquerdo do Dynamics 365 Finance, selecione **Módulos****&gt;****Administração de organização****&gt; Organizações &gt; Entidades legais**.

2. Na página **Entidades legais**, selecione o botão **Novo** no painel de ações para criar uma nova entidade legal e insira as seguintes informações:

    - Nome: **Sistemas de Demonstração da Contoso**

    - Empresa: **CDS**

    - País/região: **EUA**

3. Selecione **OK** na parte inferior.

## Criar um calendário fiscal

1. No painel de navegação esquerdo do Dynamics 365 Finance, selecione **Módulos****&gt;****Contabilidade****&gt; Calendários &gt; Calendários fiscais**. 

2. Na página **Calendário fiscal**, selecione o botão **Novo calendário** no painel de ações para criar um novo calendário fiscal e insira as seguintes informações:

    - Calendário: **CDS**

    - Descrição: **Calendário de sistemas de demonstração**

    - Início do ano fiscal: **01/10/2023**

    - Fim do ano fiscal: **30/09/2023**

    - Nome do ano fiscal: **2023-24**

    - Duração do período: **1**

    - Unidade: **Meses**

3. Selecione o botão **Criar**.

O sistema gerará 14 períodos, incluindo um período de abertura e um período de fechamento e 12 períodos por 12 meses.

## Criar um plano de contas

1. No painel de navegação esquerdo do Dynamics 365 Finance, selecione **Módulos** > **Contabilidade****&gt;****Plano de contas****&gt; Contas &gt; Plano de contas**.

2. Na página **Plano de contas**, selecione o botão **Novo** no painel de ações para criar um novo plano de contas e insira as seguintes informações:

    - **Planos de contas**: Sistemas de demonstração

    - **Descrição**: sistemas de demonstração da Contoso

3. Selecione o botão **Novo** na FastTab **Contas principais** para criar contas principais com os seguintes valores:

    - Conta principal: **1000**

    - Nome: **Pagamento à vista**

    - Tipo de despesa principal: **Balanço patrimonial**

    - Categoria de conta principal: **CASH**

    - Padrão de DB/CR: **Débito**

4. Crie outra conta principal:

    - Conta principal: **3000**

    - Nome: **Receita**

    - Tipo de despesa principal: **Receita**

    - Categoria da conta principal: **REV**

    - Padrão de BD/CR: **Crédito**

5. Crie outra conta principal:

    - Conta principal: **6000**

    - Nome: **Despesa de viagens**

    - Tipo de despesa principal: **Despesa**

    - Categoria da conta principal: **EXP**

    - Padrão de DB/CR: **Débito**

##  Criar uma unidade operacional

1. Navegue para **Módulos****&gt;****Administração de organização****&gt; Organizações &gt; Unidades operacionais**.

2. No painel de ações, selecione o botão **Novo** seguido do tipo de unidade ** Departamento em operação** e insira o seguinte valor:

    - Nome: **CDS_Training**

3. No painel de ações, selecione o botão Novo seguido do tipo de unidade operacional Centro de custo e insira o seguinte valor:

    - Nome: **CDS_Purchase**

4. Adicione mais dois centros de custo: **CDS_IT** e **CDS_Admin**.

## Criar uma estrutura de contabilidade

1. Na página inicial **Finanças e Operações**, na parte superior direita, verifique se você está trabalhando com a empresa **CDS**.

2. Se necessário, selecione a empresa e, no menu, selecione **CDS**.

3. No painel de navegação esquerdo do Dynamics 365 Finance, selecione **Módulos** > **Contabilidade****&gt;****Plano de contas &gt; Estruturas &gt; Configurar estruturas de contas**.

4. No painel de ações, selecione o botão **Novo** para criar uma nova estrutura de conta com os seguintes valores:

    - Estrutura da conta: **CDS_BS**

    - Descrição: **Balanço CDS**

    - Adicionar conta principal: **SIM**

5. Selecione o botão **Criar**.

6. Na FastTab **Segmentos e valores permitidos**, selecione o botão **Adicionar** para adicionar o **Intervalo da conta principal 1000..2999**.

7. Selecione o botão **Ativar** no painel de ações seguido pelo botão **Ativar** na caixa de diálogo de processamento em lotes.

8. No painel de ações da página **Estruturas de conta**, selecione o botão **Novo** para criar outra estrutura de conta com os seguintes valores:

    - Estrutura da conta: **CDS_Revenue**

    - Descrição: **Receita CDS**

    - Adicionar conta principal: **SIM**

9. Selecione o botão **Criar**.

10. Na FastTab **Segmentos e valores permitidos**, selecione o botão **Adicionar** para adicionar o **Intervalo da conta principal 3000..5999**.

11. Selecione o botão **Ativar** no painel de ações seguido pelo botão **Ativar** na caixa de diálogo de processamento em lotes.

12. No painel de ações da página **Estruturas de contas**, selecione o botão **Novo** para criar outra estrutura de conta com os seguintes valores:

    - Estrutura da conta: **CDS_Expense**

    - Descrição: **Despesa CDS**

    - Adicionar conta principal: **SIM**

13. Selecione o botão **Criar**.

14. Na FastTab **Segmentos e valores permitidos**, selecione o botão **Adicionar** para adicionar o **Intervalo da conta principal 6000..9999**.

15. Selecione o botão **Segmento** na FastTab **Segmentos e valores permitidos**

16. Na caixa de diálogo **Adicionar segmento**, selecione **CostCenter** seguido pelo botão **Adicionar segmento**.

17. No campo **CostCenter**, insira **253..255**. 

18. Selecione o botão **Ativar** no painel de ações seguido pelo botão **Ativar** na caixa de diálogo de processamento em lotes.

## Configurar o razão

1. Na página inicial **Finanças e Operações**, na parte superior direita, verifique se você está trabalhando com a empresa **CDS**.

2. Se necessário, selecione a empresa e, no menu, selecione **CDS**.

3. No painel de navegação esquerdo do Dynamics 365 Finance, selecione a página **Módulos** > **Contabilidade &gt; Configuração &gt; Razão** e configure o seguinte:

    - Plano de contas: **Sistemas de demonstração**

    - Calendário fiscal: **CDS**

    - Moeda contábil: **USD**

    - Moeda de relatório: **USD**

    - Tipo de taxa de câmbio de moeda contábil: **Padrão**

    - Tipo de taxa de câmbio de orçamento: **Orçamento**

4. Na FastTab **Estrutura de conta**, selecione o botão **Adicionar** para adicionar a estrutura da conta **CDS_BS**.

5. Adicione mais duas estruturas de conta: **CDS_Revenue** e **CDS_Expense**.

Isso conclui a configuração básica do módulo Contabilidade. Você pode planejar sua configuração de diário agora para postar diários. 

 
