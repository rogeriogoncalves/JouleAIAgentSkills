# Após finalizar o exercício 1.1. Salvar todo a trabalho realizado e retornar a tela inicial.

## 1 - Na tela inicial do Joule Studio
Acessar o agente criado, após ir no botão ‘Criar’ e ‘Habilidade do Joule’

 ![Alt Text](../Images/exe2-1.png)

Preencher os campos conforme abaixo e pressionar em ‘Criar’
Nome: ObterOperaçõesDaOrdem
Descrição: Listar operações sob uma ordem específica.
Criar habilidade.
Ao ser criada, acessar a opção ‘Painel de habilidades’
 2
Acessar a aba parâmetros e clicar no símbolo + na sessão ‘Entrada da habilidade’

 3
 4
Preencher os campos com os seguintes conteúdos e pressionar ‘Aplicar’.
Nome: ID Ordem manutencao
Descrição: ID da ordem de manutenção para obter informações sobre a manutenção
Obrigatório: Sim

Clicar em ‘Aplicar’
Na aba parâmetros, clicar no símbolo + na sessão ‘Saídas da habilidade’
 5

Saida 1
Nome: Value
Descrição: Value
Tipo: Any 
Obrigatório: Sim
Lista: Sim 

Saida 2
Nome: Count
Descrição: Count
Tipo: Number 
Obrigatório: Sim
Lista: Não
 6

Clicar no botão ‘Adicionar etapa’ e escolher a opção ‘Call Action’ e ‘Browse All Actions’
 
Na biblioteca ‘Mostrar filtros’ e selecionar ‘Get operations for maintenance order’
Variável de destino: AgenteDeAtendimento
 7

Navegar até a aba de ‘Entradas’ e selecionar o ID.
  8
Selecionar o passo ‘Fim’ e definir os parâmetros de saída
 9

 # [Voltar](../README.md)
