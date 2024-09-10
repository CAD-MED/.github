
# 📱 Defesa Civil App

![Defesa Civil Logo](https://github.com/CAD-MED/Projeto-de-extensao-CAD-MED/raw/main/imagesReadme/logoo.png) <!-- Substitua pelo link do logo se houver -->

### Acesso rápido

- [Projeto extensão CAD MED 2024](https://github.com/CAD-MED/Projeto-de-extensao-CAD-MED)


O **CADMED App** é uma aplicação móvel desenvolvida em Flutter, projetada para facilitar e agilizar o processo de registro e gerenciamento de pessoas atendidas nos postos da Defesa Civil. Com foco em eficiência e segurança, o aplicativo oferece um registro digital confiável dos cidadãos, permitindo um acompanhamento contínuo e atualizado de todas as atividades realizadas.

## 📋 Funcionalidades

- **Cadastro de Pessoas:**
  - Registre rapidamente informações essenciais das pessoas atendidas, incluindo nome (opcional), idade, gênero, endereço e situação de vulnerabilidade.
  - Todos os dados são armazenados localmente em um banco de dados SQLite, garantindo o funcionamento do aplicativo mesmo sem conexão com a internet.
  
- **Listagem de Atendimentos:**
  - Visualize uma lista detalhada de todas as pessoas cadastradas, incluindo a data e hora do atendimento.
  - Opção de buscar e filtrar registros específicos para uma gestão mais eficiente.
  
- **Edição de Registros:**
  - Edite as informações de um cadastro existente a qualquer momento, mantendo os dados sempre atualizados.
  - Possibilidade de remover registros obsoletos ou duplicados diretamente do banco de dados.

- **Configurações Internas do Aplicativo:**
  - Acesse as configurações para personalizar o funcionamento do app, incluindo preferências de usuário e ajustes de comunicação com o servidor.
  - Configure a integração com um servidor externo para exportação de dados via API, facilitando a centralização e análise de informações.

- **Exportação de Dados:**
  - Exporte os registros armazenados localmente para um servidor remoto usando Node.js, que então armazena os dados em um banco de dados SQL.
  - Utilização de requisições HTTP seguras para garantir a integridade e privacidade dos dados durante a transferência.

- **Tela "Sobre o App":**
  - Informações sobre o aplicativo, incluindo versão, desenvolvedores e informações de contato para suporte.

## 🛠️ Tecnologias Utilizadas

- **Flutter:** SDK de código aberto para o desenvolvimento de aplicativos móveis nativos, proporcionando uma experiência de usuário fluida e intuitiva.
- **Dart:** Linguagem de programação que suporta o Flutter, facilitando a criação de uma interface de usuário responsiva e eficiente.
- **SQLite:** Banco de dados embutido utilizado para armazenamento local dos registros, permitindo acesso offline aos dados.
- **Node.js:** Plataforma utilizada para o desenvolvimento do backend, responsável por receber e processar os dados exportados do aplicativo.
- **API REST:** Interface de comunicação entre o aplicativo móvel e o servidor, utilizando métodos HTTP para gerenciamento de dados.

