# Sistema de Cadastro de Equipamentos

## Descrição
Programa desenvolvido em linguagem C para cadastrar e consultar equipamentos de um laboratório de informática, utilizando um arquivo de texto para armazenar os registros.

## Funcionalidades
- Cadastrar equipamentos.
- Informar nome, código de identificação e localização.
- Salvar os dados em `equipamentos.txt`.
- Listar os equipamentos cadastrados.
- Preservar os registros anteriores ao adicionar novos equipamentos.

## Tecnologias utilizadas
- Linguagem C.
- Manipulação de arquivos TXT.

## Funções utilizadas
- `fopen()`
- `fprintf()`
- `fgets()`
- `fclose()`

## Como executar
1. Compile o arquivo `cadastro.c` com um compilador C.
2. Execute o programa.
3. Escolha uma opção no menu.
4. Cadastre ou consulte os equipamentos.

## Testes realizados
- Cadastro de um equipamento.
- Listagem dos registros cadastrados.
- Cadastro de mais de um equipamento para verificar a preservação dos dados.
- Verificação do comportamento quando ainda não há registros.
- Verificação de opções inválidas no menu.
