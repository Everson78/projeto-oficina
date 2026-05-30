# projeto-oficina
Projeto conceitual de banco de dados para uma oficina mecânica, desenvolvido no MySQL Workbench com base na narrativa proposta pela DIO. 
# Projeto Conceitual – Oficina Mecânica

## Descrição

Este projeto apresenta a modelagem conceitual de um sistema de controle e gerenciamento de Ordens de Serviço (OS) para uma oficina mecânica.

O modelo foi desenvolvido com base na narrativa proposta no desafio da DIO, contemplando clientes, veículos, equipes de mecânicos, serviços, peças e ordens de serviço.

## Entidades Principais

* Cliente
* Veículo
* Ordem de Serviço (OS)
* Equipe
* Mecânico
* Serviço
* Peça

## Relacionamentos

* Um cliente pode possuir vários veículos.
* Um veículo pode possuir várias ordens de serviço.
* Uma equipe é responsável pela avaliação e execução das ordens de serviço.
* Uma equipe pode possuir vários mecânicos.
* Uma ordem de serviço pode conter vários serviços.
* Um serviço pode estar presente em várias ordens de serviço.
* Uma ordem de serviço pode utilizar várias peças.
* Uma peça pode ser utilizada em várias ordens de serviço.

## Observações

Alguns atributos complementares foram adicionados com base no contexto do problema para tornar o modelo mais completo e coerente com um sistema real de oficina mecânica.

## Ferramenta Utilizada

* MySQL Workbench
