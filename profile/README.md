
# 📱 Defesa Civil App

![Defesa Civil Logo](https://github.com/CAD-MED/Projeto-de-extensao-CAD-MED/raw/main/imagesReadme/logoo.png) <!-- Substitua pelo link do logo se houver -->

### Acesso rápido

- [Projeto extensão CAD MED 2025](https://github.com/CAD-MED/Projeto-de-extensao-CAD-MED-2025)

---

O **CADMED App** é uma aplicação móvel desenvolvida na plataforma Flutter, projetada para melhorar e digitalizar o processo de registro e gerenciamento dos atendimentos realizados nos postos da Defesa Civil. Sua principal meta é assegurar eficiência e segurança, trocando formulários em papel por um sistema digital robusto que possibilita o monitoramento constante e atualizado de todas as atividades e cidadãos assistidos.

O aplicativo funciona de maneira autônoma e confiável, mesmo em regiões sem conexão à internet, devido ao seu armazenamento local de dados. A interface foi projetada para ser simples e ágil, reduzindo ao máximo o tempo de treinamento.

A digitalização desse processo busca:

- **Acelerar o atendimento:** Reduzir o tempo de registro pra que a equipe foque em oferecer assistência imediata e de qualidade. Acabar com a papelada torna o processo mais suave e menos propenso a erros  
- **Otimizar a gestão de dados:** construir um histórico digital seguro, permitindo o acompanhamento contínuo de indivíduos e famílias e evitando duplicações de trabalho.  
- **Preservar a informação:** garantir que os dados permaneçam disponíveis e protegidos mesmo sem conexão com a internet, por meio do armazenamento local em **SQLite**.  

Facilitar análise e planejamento é importantíssimo, fornecendo um banco de dados bem organizado para análise posterior, assim ajudando no planejamento das ações pra lidar com desastres. As informações que forem pegas podem ser usadas para ver os pontos fracos, mapear onde o perigo é maior e melhorar a forma de entregar os recursos, fazendo desses dados um instrumento estratégico vital para a Defesa Civil.

---

## 💡 Visão Geral

O **CADMED App** é um aplicativo móvel desenvolvido em **Flutter**, voltado à digitalização dos processos da Defesa Civil.  
Com foco em **eficiência**, **segurança** e **usabilidade**, substitui formulários físicos por um sistema digital robusto e de fácil utilização — mesmo em locais com conectividade limitada.  

A interface é intuitiva e pensada para que qualquer agente possa operar o aplicativo com pouco ou nenhum treinamento.

---

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

---

## 🛠️ Tecnologias Utilizadas

- **Flutter:** SDK de código aberto para o desenvolvimento de aplicativos móveis nativos, proporcionando uma experiência de usuário fluida e intuitiva.
- **Dart:** Linguagem de programação que suporta o Flutter, facilitando a criação de uma interface de usuário responsiva e eficiente.
- **SQLite:** Banco de dados embutido utilizado para armazenamento local dos registros, permitindo acesso offline aos dados.
- **Node.js:** Plataforma utilizada para o desenvolvimento do backend, responsável por receber e processar os dados exportados do aplicativo.
- **API REST:** Interface de comunicação entre o aplicativo móvel e o servidor, utilizando métodos HTTP para gerenciamento de dados.

