---
lab:
  title: 'Laboratório 2: Integração do Excel'
  module: 'Module 1: Explore the core capabilities of Dynamics 365 finance and operations apps'
---

# Módulo 1: Explorar as principais funcionalidades dos aplicativos de finanças e operações do Dynamics 365

## Laboratório 2: Integração do Excel

## Objetivo

Neste laboratório, você aprenderá a copiar dados de finanças e operações para o Excel usando o aplicativo de suplemento do Office Conector de Dados Dinâmicos. Você também saberá como o mesmo aplicativo pode ser usado para inserir dados no Dynamics 365 Finance and Operations. 

## Configuração do Laboratório

   - **Tempo estimado**: 5 minutos

## Instruções

Agora que você está familiarizado com os aplicativos de finanças e operações, explore o cenário de integração do Excel. 

1.  Na página inicial **Finanças e Operações**, na parte superior direita, verifique se você está trabalhando com a empresa **USMF**. 

2.  Acesse **Compras e fornecimento** > **Configuração** > **Fornecedores** > **Grupos de fornecedores**.

3.  No painel de ações, selecione **Abrir no Microsoft Office** e, **em Abrir no Excel**, selecione **Grupos de fornecedores (usmf)** .

4.  No painel **Abrir no Excel**, selecione **Baixar**. 

5.  O arquivo de modelo do Excel será baixado e salvo. **Abra** o arquivo de modelo do Excel baixado, ignore ou permita outros prompts de segurança padrão. Se necessário, feche a ativação e selecione **Habilitar Edição**. Selecione **Confie nesse suplemento** e entre (usando as mesmas credenciais, se solicitado). 

    Depois de entrar, o aplicativo Conector de Dados atualiza os dados existentes da tabela **Grupo de fornecedores** e é exibido na planilha do Excel. 

6.  Para criar um registro, insira `100` no campo **Grupo de fornecedores**, `Insurance vendor` no campo **Descrição** e `Net10` no campo **Termos de pagamento**. 

7.  Selecione o botão **Publicar** no painel de tarefas Conector de Dados Dinâmicos da Microsoft. 

8.  Atualize a lista **Grupos de fornecedores** no Dynamics 365 Finance e Operations para verificar se o novo registro foi adicionado com êxito. 

