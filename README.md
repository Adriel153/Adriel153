Você tem razão. O problema é que eu coloquei **blocos de código dentro de outro bloco de código**, então o Markdown fecha o bloco principal antes da hora.

Para você conseguir **copiar absolutamente tudo de uma vez**, o README inteiro precisa estar dentro de **um único bloco externo**, e os diagramas internos devem usar `~~~text` ou `~~~javascript` em vez de ```.

Aqui está a versão corrigida **do começo ao fim**, sem quebrar a partir de “Acredito que programação não é só escrever código”:

# 👋 Olá! Eu sou Adriel Felix da Silva

### 💻 Desenvolvedor em formação | Análise e Desenvolvimento de Sistemas

<p align="left">
  <a href="https://github.com/Adriel153">
    <img src="https://img.shields.io/badge/GitHub-Adriel153-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

## 🚀 Sobre mim

Sou estudante de **Análise e Desenvolvimento de Sistemas**, apaixonado por tecnologia, programação e desenvolvimento de soluções digitais.

Tenho como objetivo construir uma carreira sólida na área de desenvolvimento de software, sempre buscando transformar conhecimentos em **projetos reais, funcionais e úteis**.

Atualmente venho desenvolvendo projetos envolvendo **Frontend, Backend, APIs, bancos de dados, autenticação, integrações externas e deploy de aplicações**.

> 💡 **"Sempre em busca de melhorar e evoluir através da tecnologia."**

---

# 🧑💻 Minha jornada

Minha evolução como desenvolvedor acontece principalmente através de três pilares:

~~~text
                  💡 APRENDER
                      │
                      ▼
                📚 ESTUDAR
                      │
                      ▼
                💻 PRATICAR
                      │
                      ▼
                🔨 CONSTRUIR
                      │
                      ▼
                 🧪 TESTAR
                      │
                      ▼
                 🐛 CORRIGIR
                      │
                      ▼
                 🚀 MELHORAR
                      │
                      ▼
              👨💻 EVOLUIR

Acredito que programação não é apenas escrever código.

É necessário entender o problema, planejar uma solução, desenvolver, testar, corrigir e continuar melhorando.

---

# 🛠️ Tecnologias

## 🌐 Frontend

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
</p>

### Conhecimentos

* Desenvolvimento de interfaces responsivas
* Componentização
* JavaScript
* React
* Vite
* HTML semântico
* CSS
* Integração com APIs
* Experiência de usuário e interfaces modernas

---

# ⚙️ Backend

<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" />
</p>

### Conhecimentos

* Desenvolvimento de APIs
* Rotas e controllers
* Integração Frontend ↔ Backend
* Autenticação
* Autorização
* Validação de dados
* Upload de arquivos
* Integração com serviços externos
* Estruturação de aplicações web

---

# 🗄️ Banco de dados

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white" />
</p>

### Conhecimentos

* Modelagem de dados
* Relacionamentos
* Consultas
* Persistência de dados
* Migrations
* Integração com aplicações Node.js

---

# 🔧 Ferramentas

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/NPM-CB3837?style=for-the-badge&logo=npm&logoColor=white" />
</p>

Também tenho contato com:

* Git
* GitHub
* NPM
* Vite
* Node.js
* Deploy de aplicações
* Configuração de ambientes
* Variáveis de ambiente
* Integração de serviços externos

---

# 💈 Projeto em destaque — AQ BARBER

## 📱 Plataforma para barbearias e clientes

Um dos principais projetos que venho desenvolvendo é o **AQ BARBER**, uma plataforma criada para conectar **barbearias e clientes** através de recursos de publicação, comunicação e agendamento.

O projeto envolve tanto desenvolvimento de interface quanto desenvolvimento de backend, banco de dados e integrações externas.

---

## ✨ Funcionalidades do projeto

### 👤 Usuários

* Cadastro de usuários
* Login
* Autenticação
* Gerenciamento de perfil
* Foto de perfil
* Controle de permissões
* Diferentes tipos de usuários

### 💈 Barbearias

* Perfil da barbearia
* Informações do estabelecimento
* Publicações
* Conteúdo em imagem e vídeo
* Interação com clientes

### 📅 Agendamentos

Sistema de gerenciamento de agendamentos com diferentes estados:

```text
┌──────────────┐
│   PENDENTE   │
└──────┬───────┘
       │
       ▼
┌──────────────┐
│  CONFIRMADO  │
└──────┬───────┘
       │
       ▼
┌──────────────┐
│  CONCLUÍDO   │
└──────────────┘

       ou

┌──────────────┐
│   RECUSADO   │
└──────────────┘

       ou

┌──────────────┐
│  CANCELADO   │
└──────────────┘
```

### 🔔 Notificações

O sistema possui estrutura para comunicação de eventos importantes, como:

* Novos agendamentos
* Confirmações
* Recusas
* Atualizações de agendamento
* Avisos para usuários

### 💬 Comunicação

* Sistema de mensagens
* Comunicação entre usuários
* Estrutura de chat
* Recursos de segurança para comunicação

### 📸 Publicações

* Publicações de imagens
* Publicações de vídeos
* Feed de conteúdo
* Perfil das barbearias
* Interação com publicações

### 💳 Pagamentos

Integração com sistema de pagamentos para gerenciamento de assinaturas e planos.

O projeto trabalha com diferentes formas de pagamento e integração com serviços externos.

---

# 🏗️ Arquitetura do AQ BARBER

```text
                         AQ BARBER
                             │
              ┌──────────────┴──────────────┐
              │                             │
              ▼                             ▼
        ┌─────────────┐              ┌─────────────┐
        │   FRONTEND  │              │   BACKEND   │
        │             │              │             │
        │ React       │◄────────────►│ Node.js     │
        │ Vite        │     API      │ Express     │
        └──────┬──────┘              └──────┬──────┘
               │                            │
               │                            ▼
               │                     ┌─────────────┐
               │                     │  DATABASE   │
               │                     │ PostgreSQL  │
               │                     └─────────────┘
               │
               ▼
        ┌──────────────────┐
        │ Serviços externos│
        │                  │
        │ Pagamentos       │
        │ E-mail           │
        │ Armazenamento    │
        └──────────────────┘
```

---

# 📱 Experiência de usuário

Um dos focos do projeto é tornar a experiência simples e intuitiva.

A interface do feed foi pensada para apresentar o conteúdo das barbearias de maneira visual, com inspiração em plataformas modernas de conteúdo vertical.

```text
┌─────────────────────────────┐
│                             │
│        🎥 PUBLICAÇÃO        │
│                             │
│                             │
│        BARBEARIA            │
│                             │
│                  ❤️         │
│                  💬         │
│                  ↗️         │
│                             │
│                             │
├─────────────────────────────┤
│ 🏠  🔍  💬  🔔  👤         │
└─────────────────────────────┘
```

O objetivo é proporcionar uma experiência moderna e adaptada principalmente para dispositivos móveis.

---

# 🔐 Segurança

Durante o desenvolvimento dos projetos também venho trabalhando com conceitos relacionados a segurança, como:

* Autenticação de usuários
* Controle de acesso
* Validação de dados
* Verificação de informações
* Códigos de segurança
* Tokens temporários
* Variáveis de ambiente
* Proteção de informações sensíveis

---

# 🔌 Integrações

Também venho trabalhando com integração entre aplicações e serviços externos.

```text
             ┌─────────────────┐
             │    APLICAÇÃO    │
             └────────┬────────┘
                      │
        ┌─────────────┼─────────────┐
        │             │             │
        ▼             ▼             ▼
   📧 E-mail      💳 Pagamento   🗄️ Banco
        │             │             │
        ▼             ▼             ▼
    Serviço       Gateway       PostgreSQL
    externo       externo
```

Essa experiência me ajuda a entender como diferentes sistemas podem trabalhar juntos.

---

# 📊 GitHub — Estatísticas

<p align="center">
  <img
    height="180"
    src="https://github-readme-stats.vercel.app/api?username=Adriel153&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true"
    alt="Estatísticas do GitHub"
  />

<img
 height="180"
 src="https://github-readme-stats.vercel.app/api/top-langs/?username=Adriel153&layout=compact&langs_count=8&theme=tokyonight&hide_border=true"
 alt="Linguagens mais utilizadas"
/>

</p>

---

# 🔥 Sequência de contribuições

<p align="center">
  <img
    src="https://streak-stats.demolab.com?user=Adriel153&theme=tokyonight&hide_border=true"
    alt="GitHub Streak"
  />
</p>

---

# 📈 Atividade no GitHub

<p align="center">
  <img
    src="https://github-readme-activity-graph.vercel.app/graph?username=Adriel153&theme=tokyo-night&hide_border=true&area=true"
    alt="Gráfico de atividade do GitHub"
  />
</p>

---

# 📚 Conhecimentos

## 💻 Programação

* JavaScript
* Java
* Lógica de programação
* Programação Orientada a Objetos

## 🌐 Web

* HTML5
* CSS3
* JavaScript
* React
* Vite
* Node.js
* Express

## 🗄️ Dados

* PostgreSQL
* SQLite
* Modelagem de banco de dados
* Migrations

## 🔧 Desenvolvimento

* Git
* GitHub
* APIs REST
* Autenticação
* Integração de sistemas
* Deploy
* Variáveis de ambiente

---

# 🎓 Formação

## Análise e Desenvolvimento de Sistemas

🎓 **Curso:** Superior de Tecnologia em Análise e Desenvolvimento de Sistemas

Durante minha formação venho desenvolvendo conhecimentos em:

* Desenvolvimento de software
* Lógica de programação
* Banco de dados
* Programação Orientada a Objetos
* Desenvolvimento web
* Engenharia de software
* Análise de sistemas
* Estruturação de aplicações

---

# 🧠 Como desenvolvo meus projetos

```text
                  💡 IDEIA
                    │
                    ▼
             🔎 ANÁLISE DO PROBLEMA
                    │
                    ▼
              📝 PLANEJAMENTO
                    │
                    ▼
             🏗️ DESENVOLVIMENTO
                    │
                    ▼
                🧪 TESTES
                    │
                    ▼
             🐛 CORREÇÕES
                    │
                    ▼
              🚀 DEPLOY
                    │
                    ▼
             📈 MELHORIAS
```

Procuro entender não apenas **como fazer algo funcionar**, mas também como estruturar uma solução que possa continuar evoluindo.

---

# 🎯 Objetivo profissional

Estou buscando minha primeira grande oportunidade profissional na área de desenvolvimento, especialmente em posições como:

* 💻 Desenvolvedor Júnior
* 🌐 Desenvolvedor Web Júnior
* ⚙️ Desenvolvedor Full Stack Júnior
* 🧑‍💻 Desenvolvedor de Sistemas

Meu objetivo é entrar em uma equipe onde eu possa:

* Aprender com profissionais experientes
* Trabalhar em projetos reais
* Desenvolver minhas habilidades
* Contribuir com soluções
* Aprender novas tecnologias
* Evoluir tecnicamente
* Crescer profissionalmente

---

# 🌱 Atualmente estudando

```text
JavaScript
    │
    ├── React
    │
    ├── Node.js
    │
    ├── APIs
    │
    └── Desenvolvimento Full Stack

Banco de Dados
    │
    └── PostgreSQL

Boas práticas
    │
    ├── Git
    ├── Arquitetura
    ├── Segurança
    └── Organização de código
```

---

# 📂 Projetos

## 💈 AQ BARBER

**Plataforma para barbearias e clientes**

Tecnologias:

`React` `Vite` `JavaScript` `Node.js` `Express` `PostgreSQL`

Principais conceitos trabalhados:

* Autenticação
* Perfis
* Agendamentos
* Notificações
* Mensagens
* Publicações
* Upload de arquivos
* APIs
* Banco de dados
* Pagamentos
* Deploy

---

## 🌐 Projetos Web

Desenvolvimento de interfaces e aplicações utilizando:

`HTML` `CSS` `JavaScript` `React`

Foco em:

* Responsividade
* Interfaces modernas
* Organização
* Experiência do usuário
* Integração com APIs

---

## 🎓 Projetos acadêmicos

Projetos desenvolvidos durante minha formação em **Análise e Desenvolvimento de Sistemas**.

Principais conceitos:

`Java` `POO` `Lógica` `Banco de Dados` `Desenvolvimento de Software`

---

# 📌 Filosofia

Acredito que um bom desenvolvedor nunca para de aprender.

Cada erro encontrado em um projeto é uma oportunidade para entender melhor o problema.

Cada funcionalidade desenvolvida é uma oportunidade para melhorar minhas habilidades.

E cada projeto é uma oportunidade para construir algo melhor que o anterior.

```javascript
const adriel = {
  objetivo: "Evoluir como desenvolvedor",

  foco: [
    "Desenvolvimento Web",
    "Full Stack",
    "Tecnologia",
    "Aprendizado contínuo"
  ],

  tecnologias: [
    "HTML",
    "CSS",
    "JavaScript",
    "React",
    "Node.js",
    "Express",
    "PostgreSQL"
  ],

  projetoPrincipal: "AQ BARBER",

  filosofia:
    "Sempre em busca de melhorar e evoluir através da tecnologia."
};

console.log("🚀 Construindo meu futuro através da tecnologia!");
```

---

# 📫 Contato

<p align="center">

<a href="https://github.com/Adriel153">
  <img src="https://img.shields.io/badge/GitHub-Adriel153-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

</p>

---

<p align="center">

### 🚀 Obrigado por visitar meu perfil!

**Sempre aprendendo.
Sempre desenvolvendo.
Sempre evoluindo.**

</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Adriel153&label=Visualizações%20do%20perfil&color=0e75b6&style=flat" alt="Visualizações do perfil" />
</p>
~~~
