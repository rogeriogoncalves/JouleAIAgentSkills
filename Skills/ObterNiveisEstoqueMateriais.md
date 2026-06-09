# Após finalizar o exercício 1.4. Salvar todo a trabalho realizado e retornar a tela inicial.

## 1 - Na tela inicial do Joule Studio
Acessar o agente criado, após ir no botão ‘Criar’ e ‘Habilidade do Joule’

![Alt Text](Images/ex5-1.png)

## 2 = Preencher os campos conforme abaixo e pressionar em ‘Criar’
<B>Nome:</B> ObterNiveisEstoqueMateriais

<B>Descrição:</B> Checar disponibilidade de estoque de um material.
Criar habilidade.
### 3 - Ao ser criada, acessar a opção ‘Painel de habilidades’

![Alt Text](Images/ex5-2.png)

### 4 - Acessar a aba parâmetros e clicar no símbolo + na sessão ‘Entrada da habilidade’

![Alt Text](Images/ex5-3.png)

### 5 - Preencher os campos com os seguintes conteúdos e pressionar ‘Aplicar’.

<B>Nome:</B> ID Material

<B>Descrição:</B> Nível de estoque ID do material.

<B>Obrigatório:</B> Sim

![Alt Text](Images/ex5-4.png)

Clicar em ‘Aplicar’

### 6 - Na aba parâmetros, clicar no símbolo + na sessão ‘Saídas da habilidade’

<B>Saida 1</B>

<B>Nome:</B> Value
<B>Descrição:</B> Material Stock level Value
<B>Tipo:</B> Any 
<B>Obrigatório:</B> Sim
<B>Lista:</B> Sim 

<B>Saida 2</B>

<B>Nome:</B> Count

<B>Descrição:</B> Count

<B>Tipo:</B> Number

<B>Obrigatório:</B> Sim

<B>Lista:</B> Não

 ![Alt Text](Images/ex5-5.png)

### 7 - Clicar no botão ‘Adicionar etapa’ e escolher a opção ‘Call Action’ e ‘Browse All Actions’

 ![Alt Text](Images/ex5-6.png)

### 8 - Na biblioteca ‘Mostrar filtros’ e selecionar ‘Get stock levels for material’

<B>Variável de destino:</B> AgenteDeAtendimento

![Alt Text](Images/ex5-7.png)

### 9 - Navegar até a aba de ‘Entradas’ e selecionar o ID.

<B>ID:</B> ID Material

![Alt Text](Images/ex5-8.png)

### 10 - Selecionar o passo ‘Fim’ e definir os parâmetros de saída

![Alt Text](Images/ex5-9.png)

# [Voltar](../README.md)

