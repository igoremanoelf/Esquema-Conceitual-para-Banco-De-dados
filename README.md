# Sistema de Controle de Ordens de Serviço para Oficina Mecânica

Este projeto apresenta o esquema conceitual para o gerenciamento de ordens de serviço em uma oficina mecânica. O objetivo do sistema é organizar e otimizar as informações relacionadas aos clientes, veículos, ordens de serviço, equipes, mecânicos, serviços e peças.

## Descrição do Contexto

Os clientes levam seus veículos à oficina para reparos ou revisões periódicas. Os veículos são designados a uma equipe de mecânicos que preenche a ordem de serviço (OS) com os dados necessários, incluindo a data de entrega e os serviços identificados. O sistema também calcula o valor total da OS com base nos serviços realizados e nas peças utilizadas, consultando uma tabela de referência de mão-de-obra.

### Principais Funcionalidades do Sistema
- Cadastro de clientes e veículos.
- Criação e gerenciamento de ordens de serviço (OS).
- Cálculo automático do valor total da OS (mão de obra + peças).
- Organização das equipes de mecânicos e seus serviços.
- Controle do estoque de peças utilizadas nos serviços.

## Esquema Conceitual

O modelo conceitual foi desenvolvido com base nos requisitos fornecidos e inclui as seguintes entidades: Cliente, Veículo, Ordem de Serviço, Serviço, Peça, Equipe e Mecânico. 

O sistema utiliza relacionamentos para garantir a integridade das informações e otimizar o processo de controle de ordens de serviço.

### Observações

- Caso surjam requisitos adicionais ou cenários específicos não contemplados no esquema inicial, ajustes serão documentados e implementados.
- Este esquema serve como base para a implementação de um sistema físico utilizando banco de dados relacional.

---

Contribuições e melhorias são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.
