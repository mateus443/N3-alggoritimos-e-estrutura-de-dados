# Sistema de Cadastro Dinâmico em C

## Descrição do Problema
Este projeto implementa um sistema básico de cadastro em linguagem C, utilizando conceitos fundamentais como **alocação dinâmica de memória** e **ponteiros**. O sistema permite realizar o gerenciamento de até 100 cadastros, contemplando as seguintes funcionalidades:

1. **Adicionar Cadastro**: Insere um novo cadastro contendo Nome, Idade e CPF.
2. **Listar Cadastros**: Exibe todos os cadastros registrados.
3. **Deletar Cadastro**: Remove um cadastro específico pelo índice informado.
4. **Sair**: Encerra o programa, liberando toda a memória alocada.

### Estrutura do Sistema
Cada cadastro contém:
- **Nome**: String com até 50 caracteres.
- **Idade**: Inteiro positivo representando a idade.
- **CPF**: String contendo exatamente 11 caracteres numéricos.

O programa é interativo e apresenta um menu amigável ao usuário para facilitar a navegação entre as funcionalidades.

### Funcionalidades
- **Adicionar Cadastro**: O programa aloca dinamicamente um novo espaço de memória para um cadastro e permite ao usuário inserir os dados de uma nova pessoa.
- **Listar Cadastros**: Exibe os cadastros armazenados até o momento. O programa percorre o array dinâmico e imprime as informações de cada pessoa.
- **Deletar Cadastro**: Remove um cadastro específico pelo índice e libera a memória alocada para esse cadastro com a função `free()`.
- **Gerenciamento de Memória**: O programa utiliza alocação dinâmica (usando `malloc` e `realloc`) para armazenar os cadastros e garante que a memória seja liberada corretamente ao deletar ou ao encerrar o programa.

---

## Como Compilar e Executar

### Passo a Passo

1. **Compilação Local**
   - Navegue até o diretório onde está o código e compile o programa com um compilador C:
     
2. **Executando o Programa**
   - Após compilar, execute o programa:
  
3. **Interaja com o Menu**
   - O programa exibirá um menu com as opções de adicionar, listar, deletar cadastros ou sair. Use os números para navegar pelas opções.

### Exemplo de Execução
Abaixo está um exemplo visual do funcionamento do programa:

**Menu Inicial**:
=== Sistema de Cadastro ===

Adicionar Cadastro
Listar Cadastros
Deletar Cadastro
Sair Escolha uma opcao: 1
markdown
Copiar código

**Adicionar Cadastro**:
Informe o nome, exemplo: João Silva Informe a idade: 25 Informe o CPF (apenas números, 11 dígitos): 12345678901 Cadastro adicionado com sucesso!

**Listar Cadastros**:
=== Lista de Cadastros ===

Nome: João Silva, Idade: 25, CPF: 12345678901

**Deletar Cadastro**:
Informe o índice do cadastro a deletar: 1 Cadastro removido com sucesso!
