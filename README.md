## Descrição de Cenários dos Casos de Uso:

### Caso de Uso: Cadastro de Pessoa Física

#### Cenário Principal:
1. O atendente seleciona a opção de cadastrar uma nova pessoa física.
2. O sistema exibe o formulário de cadastro.
3. O atendente preenche os dados da pessoa física.
4. O atendente confirma o cadastro.
5. O sistema armazena os dados da pessoa física.

#### Cenário Alternativo 1: Dados Inválidos:
- 3a. Os dados fornecidos não estão válidos.
- 3b. O sistema exibe uma mensagem de erro e solicita que o atendente corrija os dados.
- 3c. O atendente corrige os dados.
- [Retorna ao passo 4].

#### Cenário Alternativo 2: Cancelamento do Cadastro:
- 4a. O atendente decide cancelar o cadastro.
- 4b. O sistema retorna ao menu principal sem salvar os dados.

#### Pré-condição:
O atendente possui acesso ao sistema de gestão escolar.

#### Pós-condição:
Os dados da pessoa física são armazenados no sistema.

### Caso de Uso: Cadastro de Pessoa Jurídica (semelhante ao Cadastro de Pessoa Física)

Descrição semelhante ao Caso de Uso de Cadastro de Pessoa Física

### Caso de Uso: Cadastro de Professor (semelhante ao Cadastro de Pessoa Física)

Descrição semelhante ao Caso de Uso de Cadastro de Pessoa Física

### Caso de Uso: Cadastro de Fornecedor (semelhante ao Cadastro de Pessoa Física)

Descrição semelhante ao Caso de Uso de Cadastro de Pessoa Física

### Caso de Uso: Cadastro de Aluno (semelhante ao Cadastro de Pessoa Física)

Descrição semelhante ao Caso de Uso de Cadastro de Pessoa Física

## Diagrama de Classe:

### Classes:
- Pessoa
- Pessoa Física
- Pessoa Jurídica
- Professor
- Fornecedor
- Aluno

### Relacionamentos:
- Herança: Pessoa Física e Pessoa Jurídica herdam de Pessoa.
- Associação: Aluno possui associação com Professor e Fornecedor.

