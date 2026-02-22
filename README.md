🌅 Ceará Horizonte Viagens

Aplicação Web Full-Stack desenvolvida para uma agência de turismo chamada Ceará Horizonte Viagens, com foco em captação de leads, apresentação estratégica de destinos e autonomia administrativa.

O sistema atua como:

🌍 Portal turístico interativo

🧭 Landing Page comercial otimizada

🛠️ Mini CMS com edição em tempo real

📈 Plataforma de geração de oportunidades comerciais

📌 Sobre o Projeto

O Ceará Horizonte Viagens é uma aplicação web moderna voltada para a promoção estratégica dos destinos turísticos do estado do Ceará.

O projeto combina:

Experiência rica e imersiva para visitantes

Sistema administrativo com edição dinâmica

Arquitetura Full-Stack leve, escalável e performática

🎯 Objetivos do Projeto
💼 Comercial

Captar leads qualificados

Facilitar contato com consultores

Estimular solicitações de roteiros personalizados

Converter visitantes em potenciais clientes

📚 Informativo

Apresentar a cultura cearense

Organizar praias por região (Litoral Leste e Oeste)

Exibir roteiros turísticos sugeridos

Oferecer dicas de viagem

Integrar visualização de localização via mapa

🔓 Autonomia Administrativa

O sistema permite que o proprietário:

Edite textos diretamente na interface

Atualize títulos e conteúdos institucionais

Substitua imagens via URL ou upload

Publique alterações em tempo real

Gerencie o conteúdo sem depender de desenvolvedor

👤 Funcionalidades
🧳 Para o Usuário/Turista

Exploração de destinos turísticos

Filtro dinâmico de praias por região

Visualização de roteiros sugeridos

Alternância entre modo claro e escuro

Mapa interativo de localização

Contato direto com consultores

Layout 100% responsivo

🔐 Para o Administrador

Área administrativa protegida por autenticação

Ativação do “Modo de Edição” visual

Edição direta de textos, títulos e imagens

Upload de imagens via Multer

Persistência de dados em arquivo JSON

Atualização instantânea do conteúdo público

🏗️ Arquitetura do Projeto

A aplicação segue uma arquitetura Full-Stack, separando responsabilidades entre Front-End e Back-End.

🎨 Front-End

Responsável pela interface e interações do usuário.

Tecnologias:

HTML5

CSS3

JavaScript (Vanilla)

Bootstrap 5

Vite

⚙️ Back-End

Responsável por autenticação, rotas da API e persistência de dados.

Tecnologias:

Node.js

Express.js

TypeScript

Multer

Sistema de Arquivos (FS)

🧠 Diferencial Técnico

Em vez de utilizar banco de dados relacional ou NoSQL, o sistema utiliza um arquivo de configuração:

site-config.json

Esse arquivo armazena:

Textos editáveis

Links de imagens

Configurações visuais

Essa abordagem proporciona:

⚡ Maior leveza

🚀 Melhor performance em projetos pequenos/médios

🧩 Simplicidade de manutenção

📦 Facilidade de deploy

📂 Estrutura do Projeto
📁 client
 ├── index.html
 ├── style.css
 ├── main.js

📁 server
 ├── server.ts
 ├── uploads/
 ├── site-config.json

📄 package.json
📄 vite.config.ts
🚀 Como Executar o Projeto
1️⃣ Clonar o repositório
git clone <URL_DO_REPOSITORIO>
2️⃣ Instalar dependências
npm install
3️⃣ Executar ambiente de desenvolvimento
npm run dev

O projeto iniciará o servidor Express juntamente com o ambiente Vite.

🛠️ Tecnologias Utilizadas

Vite

Bootstrap 5

Node.js

Express.js

TypeScript

Multer

HTML5

CSS3

JavaScript

📈 Possíveis Evoluções

Integração com banco de dados (PostgreSQL ou MongoDB)

Implementação de autenticação JWT

Sistema completo de reservas online

Integração com gateway de pagamento

Painel administrativo avançado

Deploy em ambiente cloud (Vercel, Render, Railway)
