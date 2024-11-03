# Construindo-um-Esquema-Conceitual-para-BD_Oficina-Mecanica

## Desafio: 
Construir um diagrama entidade relacionamento a partir de um projeto conceitual segundo a narrativa fornecida. Desse maneira, criar todas as entidades, relacionamentos e atributos utilizando a ferramenta do MySQL WorkBench.

## Narrativa:
- Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica;
  - Clientes levam veículos (um ou mais) à oficina mecânica para serem consertados ou para passarem por revisões periódicas;
  - Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma Ordem de Serviço (OS) com data de entrega;
  - A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra;
  - O valor de cada peça também irá compor a OS do cliente que autoriza a execução dos serviços;
  - A mesma equipe avalia e executa os serviços;
  - Os mecânicos possuem código, nome, endereço e especialidade;
  - Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.

## Resultado:
<img src="https://github.com/user-attachments/assets/38a2ad7d-ef68-4504-849f-ad58deb743f3">
