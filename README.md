# Gerenciador de Tarefas em C 

Um sistema de gerenciamento de tarefas (*To-Do List*) desenvolvido em linguagem C para rodar diretamente no terminal. Este projeto foi idealizado para consolidar e praticar conceitos fundamentais de estrutura de dados, lógica de programação e manipulação de fluxos.

# Funcionalidades
* **Listar Tarefas**: Exibe de forma organizada todas as tarefas cadastradas, indicando claramente o status de cada uma com um `[X]` para concluídas e `[ ]` para pendentes.
* **Adicionar Nova Tarefa**: Permite a inserção dinâmica de novas atividades (com limite configurado para até 10 tarefas).
* **Concluir Tarefa**: Altera o status de uma tarefa específica informando apenas o seu número correspondente.

# Conceitos e Estruturas Aplicadas
* **Estruturas de Dados Personalizadas**: Uso de `struct` e `typedef` para modelar o objeto tarefa.
* **Manipulação de Vetores**: Armazenamento e gerenciamento de um array de estruturas.
* **Controle de Fluxo e Loops**: Aplicação de estruturas relacionais e de repetição (`do-while`, `switch-case` e `for`).
* **Tratamento de Strings**: Uso avançado de funções nativas como `strcpy()` e `fgets()` com limpeza de buffer do teclado.

# Como Executar o Projeto

Caso queira testar ou rodar o sistema localmente em uma máquina com um compilador C (como o GCC) instalado, utilize os seguintes comandos no terminal:

```bash
# 1. Compilar o arquivo principal
gcc main.c -o gerenciador

# 2. Executar o programa gerado
./gerenciador
