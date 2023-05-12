<h1>Projeto de Transformação e Agregação de Dados de Cervejarias</h1>

<p>Este projeto consiste em uma pipeline de transformação e agregação de dados de cervejarias, que visa processar e organizar os dados em diferentes camadas.</p>

<h2>Camada Bronze</h2>
<p>A camada Bronze contém os dados brutos e não tratados. Nessa etapa, os dados são adquiridos a partir da API <a href="https://www.openbrewerydb.org/">OpenBreweryDB</a> e persistidos em seu formato nativo.</p>

<h2>Camada Silver</h2>
<p>Na camada Silver, os dados da camada Bronze são transformados e armazenados em um formato de armazenamento colunar, como Parquet ou Delta. Além disso, eles são particionados com base na localização da cervejaria. Essa transformação visa otimizar o desempenho e a eficiência do acesso aos dados.</p>

<h2>Camada Gold</h2>
<p>A camada Gold é responsável por criar uma visualização agregada dos dados. Nessa etapa, é gerada uma visualização que apresenta a quantidade de lojas de cervejarias por tipo e localização. Essa agregação fornece uma visão sumarizada e mais intuitiva dos dados.</p>

<p>Essa pipeline de transformação e agregação de dados de cervejarias possibilita uma análise mais eficiente e facilita a obtenção de informações relevantes sobre as cervejarias em diferentes níveis de granularidade.</p>

<h2>Tecnologias Utilizadas</h2>

<ul>
  <li>Apache Airflow: Framework utilizado para construir e gerenciar a pipeline de transformação e agregação de dados.</li>
  <li>Docker: Plataforma de virtualização que permite executar aplicativos em contêineres isolados.</li>
  <li>HTML: Utilizado para aplicar formatação especial ao README.md.</li>
  <li>API: <a href="https://www.openbrewerydb.org/">OpenBreweryDB API</a>: API utilizada para obter informações sobre cervejarias.</li>
</ul>

