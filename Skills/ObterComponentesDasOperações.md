# Após finalizar o exercício 1.2. Salvar todo a trabalho realizado e retornar a tela inicial.

## 1 - Na tela inicial do Joule Studio

Acessar o projeto criado, após ir no botão ‘Criar’ e ‘Habilidade do Joule’
 
![Alt Text](/Images/ex3-1.png)

## Preencher os campos conforme abaixo e pressionar em ‘Criar’
<B>Nome:</B> ObterComponentesDasOperações

<B>Descrição:</B> Retorna a lista de materiais necessários para realizar uma operação de manutenção específica, com base no ID da operação fornecido. Útil para verificar a disponibilidade em estoque e garantir a prontidão para a execução.

Criar habilidade.
Ao ser criada, acessar a opção ‘Painel de habilidades’

![Alt Text](/Images/ex3-2.png)

## Acessar a aba parâmetros e clicar no símbolo + na sessão ‘Entrada da habilidade’

![Alt Text](/Images/ex3-3.png)


## Preencher os campos com os seguintes conteúdos e pressionar ‘Aplicar’.
Nome: ID Operacao
Descrição: ID da operação para verificar a disponibilidade de estoque e garantir a prontidão para execução.
Obrigatório: Sim

![Alt Text](/Images/ex3-4.png)

Clicar em ‘Aplicar’

## Na aba parâmetros, clicar no símbolo + na sessão ‘Saídas da habilidade’

![Alt Text](/Images/ex3-5.png)

<B>Saida 1</B>

<B>Nome:</B> Value

<B>Descrição:</B> Value

<B>Tipo:</B> Any

<B>Obrigatório:</B> Sim

<B>Lista:</B> Sim 

<B>Saida 2</B>

<B>Nome:</B> Count

<B>Descrição:</B> Count

<B>Tipo:</B> Number

<B>Obrigatório:</B> Sim

<B>Lista:</B> Não

![Alt Text](/Images/ex3-6.png)


## Clicar no botão ‘Adicionar etapa’ e escolher a opção ‘Call Action’ e ‘Browse All Actions’

![Alt Text](/Images/ex3-7.png)

## Na biblioteca ‘Mostrar filtros’ e selecionar ‘Get components for each operation’

Variável de destino: AgenteDeAtendimento

![Alt Text](/Images/ex3-8.png)


## Navegar até a aba de ‘Entradas’ e selecionar o ID.
<B>ID:</B> ID Operacao
 
![Alt Text](/Images/ex3-9.png)

## Selecionar o passo ‘Fim’ e definir os parâmetros de saída

![Alt Text](/Images/ex3-10.png)

# [Voltar](../README.md)
