# Sistema de Cadastro Dinâmico em C

## Descrição do Problema
Este projeto é um sistema simples de cadastro implementado em C utilizando alocação dinâmica de memória e ponteiros. Ele permite armazenar as informações de até 100 pessoas, oferecendo funcionalidades de:

1. Adicionar novos cadastros.
2. Listar todos os cadastros armazenados.
3. Deletar um cadastro específico pelo índice.
4. Encerrar o programa liberando toda a memória alocada.

Os dados armazenados para cada pessoa são:
- Nome (até 50 caracteres)
- Idade (inteiro positivo)
- CPF (exatamente 11 caracteres)

A aplicação possui um menu interativo e valida as entradas para garantir que os dados sejam armazenados corretamente.

---

## Como Compilar e Executar
### Pré-requisitos:
- Um compilador C 
- Um terminal ou ambiente de desenvolvimento compatível com execução de código em C.

1. **Compile o código:**
   Abra o terminal e execute o seguinte comando:
   ```bash
   gcc sistema_cadastro.c -o sistema_cadastro
   
Execute o programa: Após a compilação, execute o programa com o comando:

bash
Copiar código
./sistema_cadastro
Use o menu do programa: Escolha as opções para adicionar, listar ou deletar cadastros interativamente.
