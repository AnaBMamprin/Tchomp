# 🍔 TCHOMP - Guia Gastronômico Local

> **Visibilidade e inovação para a culinária local.**  
> Projeto de Conclusão de Curso (TCC) em Análise e Desenvolvimento de Sistemas (FATEC Guarulhos).

## 📖 Sobre o Projeto

O **TCHOMP** é uma aplicação web Full-Stack criada para funcionar como um guia gastronômico interativo. O principal objetivo do produto (MVP) é democratizar a visibilidade digital para pequenos e médios restaurantes da cidade de Guarulhos - SP, conectando clientes a novos sabores locais através de uma plataforma acessível e intuitiva.

Este projeto foi construído não apenas com foco na arquitetura de software, mas com uma forte **visão de produto e negócios**, buscando solucionar uma dor real de microempreendedores que não possuem recursos para grandes campanhas de marketing.

## 🚀 Funcionalidades (Features)

- **Catálogo de Restaurantes:** Listagem dinâmica dos estabelecimentos parceiros.
- **Geolocalização:** Integração com a API do Google Maps para exibir a localização exata dos restaurantes.
- **Autenticação Segura:** Sistema de login e controle de acesso protegido para usuários e administradores.
- **Interface Responsiva:** Navegação fluida adaptada para diferentes tamanhos de tela.

## 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

**Back-End:**
- Java 21
- Spring Boot
- Spring Security (Autenticação e Autorização)
- Maven (Gerenciamento de dependências)

**Front-End:**
- Thymeleaf (Template Engine)
- HTML5, CSS3 e JavaScript
- Bootstrap 5

**Banco de Dados & Integrações:**
- MySQL
- Google Maps API

## ⚙️ Como executar o projeto localmente

### Pré-requisitos
Antes de começar, você precisará ter instalado em sua máquina:
- [JDK 21](https://adoptium.net/)
- [MySQL](https://dev.mysql.com/downloads/)
- Uma IDE de sua preferência (recomendo IntelliJ IDEA ou VS Code)

### Passo a Passo

1. Faça o clone deste repositório:
   ```bash
   git clone https://github.com/AnaBMamprin/Tchomp.git
   ```

2. Configure o Banco de Dados:
   - Crie um banco de dados no MySQL chamado `db_app1`.
   - Acesse o arquivo `src/main/resources/application.properties` e atualize as credenciais do banco:
     ```properties
     spring.datasource.url=jdbc:mysql://localhost:3306/tchomp_db
     spring.datasource.username=SEU_USUARIO_DO_MYSQL
     spring.datasource.password=SUA_SENHA_DO_MYSQL
     ```

3. Configure a Chave da API do Google Maps:
   - No mesmo arquivo `application.properties` ou diretamente no Front-end (dependendo da sua implementação), insira a sua API Key do Google.

4. Execute a aplicação:
   - Rode o projeto pela sua IDE ou utilize o Maven pelo terminal:
     ```bash
     mvn spring-boot:run
     ```

5. Acesse no navegador:
   - A aplicação estará disponível em: `http://localhost:8080`

## 👩‍💻 Autora

**Ana Beatriz Mamprin**  
*Desenvolvedora Full-Stack & Analista de Negócios / TI*

- 💼 [LinkedIn] https://www.linkedin.com/in/ana-beatriz-mamprin/
- ✉️ Entre em contato para falarmos sobre tecnologia, produtos e novas oportunidades!
