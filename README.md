# projeto-sds3

App desenvolvido por mim na Semana Spring React
Evento promovido pela escola DevSuperior: https://devsuperior.com.br

Aprendizados:

Criar projetos backend e frontend
Salvar os projeto no Github em monorepo
Montar o visual estático do front end
Publicar o front end no Netlify
Modelo de domínio
Estruturar o back end no padrão camadas
Consulta paginada de vendas
Consultas agrupadas para gráficos
Implantação na nuvem
Integrar back end e front end
Três pilares do React
  Componentes
  Props
  Estado
React Hooks
  useState
  useEffect
Libs
  React Router DOM
  Axios

Instalaçôes das ferramentas:

JDK 11
STS
Postman
Postgresql 12 e pgAdmin
Heroku CLI
NPM
VS Code
Git

AULA 01:

Passo 1: criar projetos

Criar projeto ReactJS

Criar projeto Spring Boot com as seguintes dependências:
Web
JPA
H2
Postgres
Security

Passo 2: "limpar" o projeto ReactJS

Passo 3: adicionar Bootstrap e CSS ao projeto

Passo 4: adicionar componentes estáticos básicos
Navbar
Footer
DataTable

Passo 5: adicionar gráficos estáticos
Apex Charts
BarChart
DonutChart

Passo 6: implantação no Netlify
Deploy básico
Configurações adicionais

AULA 02

Passo 1: configuração de segurança

Passo 2: criar as entidades e o seed do banco

Passo 3: Estruturar o projeto em camadas
Criar repositories
Criar DTO's
Criar service
Criar controller

Passo 4: Busca paginada de vendas
Pageable
page, size, sort
Evitando interações repetidas ao banco de dados

Passo 5: Buscas agrupadas (GROUP BY)
Total de vendas por vendedor
Taxa de sucesso por vendedor

Passo 6: Validação no Postgres local
Criar três perfis de projeto: test, dev, prod
Gerar script SQL no perfil dev
Testar projeto no banco Postgres local

Passo 7: Implantação no Heroku
Criar app no Heroku
Provisionar banco Postgres
Definir variável APP_PROFILE=prod
Conectar ao banco via pgAdmin
Criar seed do banco

AULA 03

Passo 1: Rotas
Instalar React Router DOM
Criar páginas Home e Dashboard
Criar arquivo de rotas Routes.tsx

Passo 2: Página Home e navegações
Fazer um link na Home para Dashboard
Fazer um link na NavBar para Home

Passo 3: First request
Instalar Axios
Definir BASE_URL
Definir tipo SaleSum
Definir tipo local ChartData em DonutChart
Fazer a requisição e tratar os dados

Passo 4: DonutChart integration
Hook: useState
Hook: useEffect

Passo 5: BarChart integration
Definir função auxiliar round
Definir tipo SaleSuccess
Definir tipo local ChartData em BarChart

Passo 6: DataTable integration
Instalar date-fns ao projeto
Criar tipos Seller, Sale, SalePage
Criar função auxiliar formatLocalDate

Passo 7: Pagination
Props
Criar componente Pagination

Passo 8: Configuração da variável de ambiente no Netlify

