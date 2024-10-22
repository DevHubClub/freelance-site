# Projeto site Free-lance 

Este projeto é um site de Freelance desenvolvido para conectar freelancers com empregadores que procuram contratar talentos em várias áreas. O site oferece funcionalidades de busca de empregos, cadastro de usuários e gerenciamento de perfis, proporcionando uma plataforma eficiente e intuitiva para ambos os lados do mercado de trabalho freelance.
#### Link de visualização do projeto
[Em breve]()

## Funcionalidades

**Cadastro e Login de Usuários:** Sistema de autenticação seguro para freelancers e empregadores.

**Busca e Aplicação para Vagas:** Ferramenta de pesquisa para encontrar e aplicar para trabalhos freelance.

**Gerenciamento de Perfis:** Interface amigável para atualização de informações de perfil e portfólio.

**Administração de Vagas:** Empregadores podem postar novas vagas e gerenciar aplicações recebidas.

## Stack utilizada

**Frontend**: HTML, CSS, JavaScript

**Backend**: Node.js, Express

**Banco de Dados**: MongoDB

## Como Executar

#### Como Executar o Back-End

1 - Navegue até a pasta backend pelo terminal cmd ou no próprio terminal no VS CODE:

```
cd backend
```
2 - Depois instale as dependências:
```
EM BREVE
```
3 - Logo após a instalação, configure as variáveis de ambiente criando um arquivo .env na raiz da pasta backend com as seguintes informações:
```
EM BREVE
```
3 - Depois de ter feito isso, inicie o servidor:
```
EM BREVE
```

## Como Executar o Frontend:

#### Navegue até a pasta frontend e inicie um servidor local:
Para um setup simples, você pode usa a extensão "Live Server" do VS Code ou:
```
npm install -g http-server
http-server
```

## Explicação dos Diretórios e Arquivos(Estrutura das Pastas e Arquivos)
**Backend:**
O diretório backend contém todo o código relacionado ao servidor e à lógica de negócios do lado do servidor da aplicação.

**Controllers:** Contém os controladores que definem a lógica de manipulação de dados para diferentes entidades da aplicação, como autenticação (authController.js), manipulação de vagas de emprego (jobController.js), e usuários (userController.js).

**Models:** Aqui estão definidos os modelos de dados da aplicação, utilizando geralmente o padrão MVC (Model-View-Controller). Por exemplo, Job.js e User.js definem a estrutura e comportamento dos objetos Job e User, respectivamente.

**Routes:** Define as rotas da API da aplicação, que mapeiam os endpoints HTTP para as funções nos controladores. Por exemplo, authRoutes.js define as rotas para autenticação, jobRoutes.js para operações relacionadas a vagas de emprego, e assim por diante.

**Config:** Contém arquivos de configuração da aplicação, como db.js que configura a conexão com o banco de dados.

**Middleware:** Middleware são funções que têm acesso ao objeto de requisição (request), objeto de resposta (response) e à próxima função de middleware no ciclo de requisição-resposta do aplicativo. Aqui você pode ter middlewares como authMiddleware.js para autenticar usuários em rotas específicas.

**App.js e Server.js:** Arquivos principais que inicializam e configuram o servidor Express, onde app.js normalmente configura e exporta o aplicativo Express, e server.js inicia o servidor HTTP.

**Frontend**
O diretório frontend contém todos os arquivos relacionados à interface do usuário, que são renderizados no navegador do usuário final.

**Assets:** Contém recursos estáticos utilizados pela interface, como imagens (images) e estilos (styles). Por exemplo, main.css contém os estilos principais aplicados em todo o site.

**Js:** Contém arquivos JavaScript utilizados na interação do usuário com a página. Por exemplo, main.js pode conter lógica JavaScript para carregar dinamicamente conteúdo na página principal (index.html), ou interações como validação de formulários.

**Pages:** Contém os arquivos HTML individuais para cada página do site. Por exemplo, index.html é a página inicial, about.html contém informações sobre a empresa, jobs.html lista as vagas de emprego disponíveis, e contact.html fornece formas de contato.


#### Outros Arquivos
**.gitignore:** Arquivo que especifica quais arquivos e diretórios devem ser ignorados pelo Git durante o controle de versão.

**package.json:** Arquivo de manifesto do Node.js que armazena metadados relevantes para o projeto. Pode incluir dependências, scripts de execução e outras informações úteis.

**README.md:** Documentação do projeto, normalmente contendo uma descrição detalhada, instruções de instalação, uso e contribuição.

**Conclusão:**

Esta organização divide de forma clara o trabalho entre a parte visível para os usuários (frontend) e o sistema que processa os dados (backend), seguindo práticas recomendadas de desenvolvimento de software. Cada diretório e arquivo tem um papel definido que contribui para o funcionamento eficiente da aplicação, facilitando sua organização e manutenção ao longo do tempo que agente for desenvolvendo.
## 👩‍💻🧑‍💻 Nossa Equipe de Desenvolvedores
Conheça a equipe por trás do projeto NOME DO projeto! Nosso time é composto por desenvolvedores(as) apaixonados(as) por criar soluções inovadoras para conectar freelancers e empregadores.


#### Nome Aqui
breve descrição sobre você

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)]()

[![Github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)]()
 
 
