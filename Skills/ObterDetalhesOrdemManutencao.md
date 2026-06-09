# Pré Requisito - Criar Conta Trial

## 1 - Primeiro passo será criar uma conta trial com validade de 30 dias.

Link Trial SAP Build: <https://www.sap.com/products/technology-platform/build/trial.html>

![Alt Text](../Images/Imagem1.png)


Irá receber usuário e palavra-chave no corpo do Email

Remetente: [webmaster@sap.com](mailto:webmaster@sap.com)

![Alt Text](../Images/Imagem2.png) 

## 2 - No e-mail recebido será informado usuário e senha a ser utilizado para logarmos no SAP Build e no Joule Studio.

Link SAP Build: <https://sap-build-us10-trial-3-t67lhj9w.us10.build.cloud.sap/lobby>

## 3 - Iniciar o processo de criação de um projeto. Clicar no botão 'Criar' e escolher 'Criar um agente e habilidade' do Joule

![Alt Text](../Images/Imagem3.png)

<B>Nome:</B> Agente de validacao do estoque da manutencao -#SEUUSUARIO (GE323288)

<B>Descrição:</B> Este projeto contém um agente Joule e habilidades usadas para validar ordens de manutenção com base na disponibilidade de materiais.

## 4 - Acessar o agente criado, após ir no botão ‘Criar’ e ‘Habilidade do Joule’

 
![Alt Text](../Images/Imagem4.png)
## 5 - Preencher os campos conforme abaixo e pressionar em ‘Criar’
<B>Nome:</B> ObterDetalhesOrdemManutencao

<B>Descrição:</B> Exibir informações da ordem de manutenção, como status, prioridade, localização e datas.
Criar habilidade.
 Ao ser criada, acessar a opção ‘Painel de habilidades’
 
![Alt Text](../Images/Imagem5.png)

Acessar a aba parâmetros e clicar no símbolo + na sessão ‘Entrada da habilidade’
 
![Alt Text](../Images/Imagem6.png)
![Alt Text](../Images/Imagem7.png)

## 6 - Preencher os campos com os seguintes conteúdos e pressionar ‘Aplicar’.
<B>Nome:</B> ID Ordem manutencao

<B>Descrição:</B> ID da ordem de manutenção para obter informações sobre a manutenção
Obrigatório: Sim

Clicar em ‘Salvar’

## 7 - Na aba parâmetros, clicar no símbolo + na sessão ‘Saídas da habilidade’
 
![Alt Text](../Images/Imagem8.png)

<B>Nome:</B> Detalhes ordem de manutencao

<B>Descrição:</B> Detalhes ordem de manutenção

<B>Tipo:</B> Any 

<B>Obrigatório:</B> Sim
 
![Alt Text](../Images/Imagem9.png)

## 8 - Clicar no botão ‘Adicionar etapa’ e escolher a opção ‘Call Action’ e ‘Browse All Actions’

 
![Alt Text](../Images/Imagem10.png)

Na biblioteca ‘Mostrar filtros’

<B>Projeto:</B> Maintenance Fulfillment Agent API

![Alt Text](../Images/Imagem11.png)

<B>Nome:</B> Get maintenance order details

![Alt Text](../Images/Imagem12.png)

## 9 - Após adicionar, necessário criar uma ‘Variável de destino’
 
![Alt Text](../Images/Imagem13.png)

<B>Identificador:</B> AgenteDeAtendimento

<B>Descrição:</B> Destination do agente de atendimento da manutenção

 ![Alt Text](../Images/Imagem14.png)

## 10 - Definir as entradas e as saídas.
 
![Alt Text](../Images/Imagem15.png) 

![Alt Text](../Images/Imagem16.png)

# [Voltar](../README.md)


