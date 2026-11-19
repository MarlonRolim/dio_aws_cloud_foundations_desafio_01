# Anotações sobre aulas EC2, EBS e S3

> DIO - AWS CLOUD FOUNDATIONS
> Desafio 1

## EC2 - Elastic Compute Cloud

> Modelo de Negócio: IAAS

- Infraestrutura da AWS.
- Código, deploy, e restante é responsabilidade do usuário.
- Responsabilidade compartilhada.

## Amazon EBS - Elastic Block Store

> Storage altamente confíavel que pode ser anexado a qualquer instância EC2

Toda Instância de EC2 possui um volume de armazeamento, com a EBS conseguimos ter a capacidade de expansão.

- Funciona como se fosse um HD externo.

**Exemplo de Caso:**

[Diagrama EBS](./diagramas/exemplo%201%20-%20diagrama%20EBS.drawio)

![Diagrama EBS](./diagramas/imagens/diagrama%20EBS.png)

## S3 - Amazon Simple Storage Service

> Armazenamento de Documentos (Storage)

### Life Cicle

- Standard: < 90 dias
- Glacier - > 90 dias

**Exemplo de Caso:**

[Diagrama S3](./diagramas/exemplo%202%20-%20diagrama%20S3%20.drawio)

![Diagrama EBS](./diagramas/imagens/diagrama%20S3.png)

## Lambda

> Serviço que executa código em resposta a eventos.

### Exemplo de caso

Quando um arquivo é enviado para um bucket do S3, o Lambda pode ser acionado automaticamente para processar o arquivo, gerar uma miniatura, validar o conteúdo ou registrar os dados em um banco.


## Cenário Real

> Vida profissional

No momento disponho de infraestruturas baseadas em VPS, estudando fortemente implementação das aplicações utilizando AWS, onde não tinha nenhum conhecimento, mas agora já estou vislumbrando como seria uma aplicação totalmente arquitetada em AWS.

Obs.: Já havia visto por cima a ferramenta Drawio, porém não a esse nível de detalhe apresentada nesse desafio. Agradeço imensamente por isso, esse conhecimneto será bem utilizado.