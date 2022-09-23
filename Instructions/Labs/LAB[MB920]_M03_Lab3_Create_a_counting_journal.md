---
lab:
  title: 'Laboratório 3: Criar um diário de contagem'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>Módulo 3: Conheça os Princípios básicos do Microsoft Dynamics 365 Supply Chain Management

## <a name="lab-3---create-a-counting-journal"></a>Laboratório 3: Criar um diário de contagem

1. On the Finance and Operations home page, in the top right, verify you are working with the <bpt id="p1">**</bpt>USMF<ept id="p1">**</ept> company. If necessary, select the company, and from the drop down, select <bpt id="p1">**</bpt>USMF<ept id="p1">**</ept>.

2. No painel de navegação esquerdo, clique em **Módulos** > **Gerenciamento de estoque** > **Entradas do diário** > **Contagem de itens** > **Contagem**.

3. Select the <bpt id="p1">**</bpt>+New<ept id="p1">**</ept> button in the action pane. The <bpt id="p1">**</bpt>Create inventory journal<ept id="p1">**</ept> dialog form will appear with the <bpt id="p2">**</bpt>OK<ept id="p2">**</ept> button in the bottom. Select the <bpt id="p1">**</bpt>OK<ept id="p1">**</ept> button.

4. O formulário do diário de contagem de estoque será exibido com cabeçalho e informações detalhadas

![Captura de tela do formulário do diário de contagem de estoque com o cabeçalho e as informações detalhadas preenchidos.](../media/lp-scm-m-002-warehouse-inventory-mgmt-06.png)

5. Clique em **Criar linhas –&gt; Online** no painel de ação.

6. No painel de diálogo **Criar diário de contagem de itens disponíveis**, defina os campos **Warehouse**, **Status do estoque**, Localização e **Placa de licença** como **Sim**. 

![Captura de tela do painel de diálogo Criar diário de contagem de itens disponíveis com os campos definidos conforme descrito.](../media/lp-scm-m-002-warehouse-inventory-mgmt-07.png)

7. Expand the <bpt id="p1">**</bpt>Record to include<ept id="p1">**</ept> section and select the <bpt id="p2">**</bpt>Filter<ept id="p2">**</ept> link. In the <bpt id="p1">**</bpt>Item number<ept id="p1">**</ept> field, select <bpt id="p2">**</bpt>A0001<ept id="p2">**</ept>, and then select <bpt id="p3">**</bpt>OK<ept id="p3">**</ept>.

8. Na parte inferior do formulário de diálogo **Criar diário de contagem de itens disponíveis**, clique em **OK**.

A quantidade disponível do item A0001 será exibida na seção **Linhas do diário** com informações detalhadas sobre Site, Warehouse, Localização e Placa de Licença.

9. In the <bpt id="p1">**</bpt>Counted<ept id="p1">**</ept> column of the <bpt id="p2">**</bpt>Journal line<ept id="p2">**</ept> section, enter the numbers counted in each Site/Warehouse/Location/License plate. Note the following:

    - Se a quantidade **Disponível** for igual à quantidade da **Contagem**, o campo **Quantidade** ficará em branco.

    - Se o valor do campo **Contagem** for maior que o valor do campo **Disponível**, o campo **Quantidade** conterá um valor positivo.

    - Se o valor do campo **Contagem** for menor que o valor do campo **Disponível**, o campo **Quantidade** conterá um valor negativo.

10. Pressione o botão **Validar** no painel de ação e, em seguida, o botão **Postar**.

11. Feche a página e retorne à página inicial.
