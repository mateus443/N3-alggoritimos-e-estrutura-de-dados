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

---

## Como Compilar e Executar

### Passo a Passo
1. **Acesse o site Online GDB ou outro compilador em C:
  
2. **Cole o código**:
   - Copie o código fornecido abaixo e cole na área de edição do site.

3. **Compile e Execute**:
   - Clique no botão **"Run"** para compilar e executar o programa.

4. **Interaja com o Menu**:
   - Use os números do menu para navegar pelas opções e testar as funcionalidades do programa.

Exemplo de Execução
Abaixo está um exemplo visual do funcionamento do programa:

Menu Inicial:

=== Sistema de Cadastro ===
1. Adicionar Cadastro
2. Listar Cadastros
3. Deletar Cadastro
4. Sair
Escolha uma opcao: _

Adicionar Cadastro:

Informe o nome: João Silva
Informe a idade: 25
Informe o CPF (apenas números, 11 dígitos): 12345678901
Cadastro adicionado com sucesso!

Listar Cadastros:

=== Lista de Cadastros ===
1. Nome: João Silva, Idade: 25, CPF: 12345678901
   
Deletar Cadastro:

Informe o índice do cadastro a deletar: 1
Cadastro removido com sucesso!
