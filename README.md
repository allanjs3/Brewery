# Projeto de Transformação e Agregação de Dados de Cervejarias

Este projeto consiste em uma pipeline de transformação e agregação de dados de cervejarias, que visa processar e organizar os dados em diferentes camadas. A camada Bronze contém os dados brutos e não tratados, a camada Silver armazena os dados transformados em um formato de armazenamento colunar, como Parquet ou Delta, particionados por localização da cervejaria, e a camada Gold cria uma visualização agregada com a quantidade de lojas por tipo e localização.

## Descrição

Uma descrição mais detalhada do projeto, incluindo o contexto e o objetivo do projeto.

## Funcionalidades

- Funcionalidade 1: Descrição breve da funcionalidade 1.
- Funcionalidade 2: Descrição breve da funcionalidade 2.
- ...

## Tecnologias Utilizadas

- Apache Airflow: Framework utilizado para construir e gerenciar fluxos de trabalho.
- HTML: Utilizado para aplicar formatação especial ao README.md.
- API: OpenBreweryDB API (https://www.openbrewerydb.org/): API utilizada para obter informações sobre cervejarias.

## Instalação

1. Clone o repositório: `git clone https://github.com/seu-usuario/nome-do-repositorio.git`
2. Entre no diretório do projeto: `cd nome-do-repositorio`
3. Instale as dependências: `pip install -r requirements.txt`

## Configuração

1. Faça uma cópia do arquivo `.env.example` e renomeie para `.env`.
2. Preencha as variáveis de ambiente necessárias no arquivo `.env`.

## Uso

1. Inicie o Apache Airflow: `airflow webserver -p 8080` (por exemplo).
2. Acesse o Airflow UI no navegador.
3. Configure e execute os fluxos de trabalho para obter informações da OpenBreweryDB API.
4. ...

## Contribuição

Se você quiser contribuir para este projeto, siga as etapas abaixo:

1. Faça um fork do repositório.
2. Crie um novo branch: `git checkout -b minha-branch`
3. Faça as modificações necessárias e commit: `git commit -am 'Adicionei uma nova funcionalidade'`
4. Envie as alterações para o branch: `git push origin minha-branch`
5. Crie um novo pull request.

## Licença

Este projeto está licenciado sob a [Licença XYZ](link-para-a-licenca).
