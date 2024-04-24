Autenticação de Login para API em Spring
============================================================================================================
Descrição
============================================================================================================
Este projeto é uma implementação de autenticação de login para uma API desenvolvida em Spring. A autenticação é um processo fundamental em sistemas de computador que verifica a identidade de um usuário ou sistema, garantindo que apenas usuários autorizados tenham acesso aos recursos protegidos.

A autenticação é frequentemente realizada por meio de credenciais, como nome de usuário e senha, tokens de acesso, certificados digitais, entre outros métodos. Neste projeto, utilizamos o método de autenticação baseado em tokens JWT (JSON Web Tokens).

Tecnologias Utilizadas
============================================================================================================
- Java
- Spring Boot
- Spring Security
- JWT (JSON Web Tokens)

Funcionalidades
============================================================================================================
- Registro de usuários
- Autenticação de usuários
- Geração de token JWT para usuários autenticados
- Proteção de endpoints da API com autenticação JWT

Como Utilizar
============================================================================================================
Clone este repositório:
git clone https://github.com/MMoreira1305/login-auth-api.git
Navegue até o diretório do projeto:
cd login-auth-api
Execute o projeto utilizando Maven:
mvn spring-boot:run
Acesse a API através do endpoint fornecido pelo Spring Boot.
Endpoints
POST /api/register: Registra um novo usuário.
POST /api/login: Autentica um usuário e gera um token JWT.
Outros endpoints da API estão protegidos e requerem o token JWT no cabeçalho da requisição.

Contribuição
============================================================================================================
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

Licença
Este projeto está licenciado sob a MIT License.
