# Desafio AWS CloudFormation - DIO

## Introdução

Este repositório foi criado como parte do desafio da DIO para consolidar os conhecimentos em **AWS CloudFormation**.  
O objetivo foi implementar minha primeira **Stack** com CloudFormation, aplicando os conceitos vistos em aula e documentando a experiência como material de apoio para estudos futuros.

## Sobre o AWS CloudFormation

O **AWS CloudFormation** é um serviço que auxilia na automação da criação de recursos AWS por meio de templates em **JSON** ou **YAML**.  

Esses templates podem ser utilizados quantas vezes forem necessárias, a cobrança é feita por Stack criada. **Stack** é um conjunto de recursos AWS (como EC2, S3, RDS entre outros).  

Além de automatizar a infraestrutura, o CloudFormation permite versionar templates, possibilitando a criação desde recursos simples até arquiteturas mais robustas.  
Em resumo, ele fornece uma maneira prática e organizada de construir templates que são utilizados para criar e gerenciar recursos na AWS.

## Implementação da Stack

Durante a prática, foram realizados os seguintes passos:

- Criação de recursos diretamente a partir de código, permitindo subir máquinas e serviços na nuvem.  
- Configuração de uma instância **Amazon EC2** simples.  
- Instalação do **Servidor Apache** na instância.  
- Definição e configuração de um **Security Group** para controle de acesso.  

Essa implementação demonstrou como o CloudFormation simplifica o processo de provisionamento, garantindo maior organização e escalabilidade.

## Conclusão

Com essa prática, foi possível entender como o **AWS CloudFormation** facilita a criação e o gerenciamento de recursos na nuvem de forma automatizada.  

A partir de um template, conseguimos provisionar uma infraestrutura completa, incluindo EC2, Security Group, S3 e IAM de maneira rápida, organizada e reproduzível.  

Essa experiência mostrou na prática a importância de estruturar a nuvem de forma organizada, trazendo mais controle, consistência e escalabilidade para futuros projetos.
