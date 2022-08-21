### Visão Geral
O template **default** adiciona em uma stack a capacidade de provisionar o ambiente de desenvolvimento Wordpress com container Docker.

### Pré-requisitos
Para utilizar esse template você precisa utilizar o `CLI` do `StackSpot` que você pode baixar [**aqui**](https://stackspot.com/).

**Outras ferramentas necessárias:**
- Docker
- Docker Compose

### Inputs
Os inputs necessários para utilizar o template são:  

| **Campo**                     | **Valor**         | **Descrição**         |
| :---                          | :---              | :---                  |
| Project Name                  | ex.: MyWebSite    | Nome da aplicação     |
| Wordpress Server Port         | ex.: 81           | Porta do servidor web |
| Wordpress Database Name       | ex.: wp_stackspot | Nome do Banco de Dados |
| Wordpress Database Port       | ex.: 3306         | Porta do Banco de Dados|
| Wordpress Database UserName   | ex.: wp_stackspot | Usuário do Banco de Dados|
| Wordpress Database Password   | ex.: wp_stackspot | Senha do Banco de Dados|
| Wordpress Docker Image        | ex.: 6.0.1        | Versão da imagem do Docker|
