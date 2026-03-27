# Loja Drip (Frontend)

Aplicação frontend de e-commerce desenvolvida com React, com foco em performance, organização de código e experiência do usuário. O projeto simula uma loja virtual moderna, com gerenciamento de estado global e estrutura escalável para integração com serviços externos.

---

## Visão Geral

A Loja Drip é uma aplicação web que representa a interface de um e-commerce, permitindo navegação entre produtos, visualização de detalhes e gerenciamento de um carrinho de compras.

Este projeto foi desenvolvido com boas práticas de componentização, separação de responsabilidades e uso de Context API para gerenciamento de estado.

---

## Demonstração

A aplicação está disponível em produção:

🔗 https://loja-drip-jyy0vwa56-luans-projects-ccc678b8.vercel.app/

---

## Tecnologias Utilizadas

- React.js  
- JavaScript (ES6+)  
- Vite  
- Context API  
- CSS3  

---

src/
│
├── components/ # Componentes reutilizáveis
├── pages/ # Páginas da aplicação
├── contexts/ # Estado global (ex: carrinho)
├── assets/ # Imagens e arquivos estáticos
├── styles/ # Estilos globais (se houver)
└── App.jsx # Componente principal

## Arquitetura e Estrutura

O projeto segue uma arquitetura baseada em componentes reutilizáveis:


---

## Funcionalidades

- Listagem de produtos  
- Visualização de detalhes  
- Carrinho de compras  
- Gerenciamento de estado com Context API  
- Interface responsiva  

---

## Gerenciamento de Estado

O estado global é controlado utilizando a Context API do React, permitindo compartilhamento eficiente de dados entre componentes.

Exemplo:

- CartContext → responsável pelo carrinho de compras  

---

## Instalação e Execução

Clone o repositório:

```bash
git clone https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
```
```bash
cd SEU-REPOSITORIO
```bash
Instale as dependências:
```
```bash
npm install
```
```bash
Execute o projeto:
```
```bash
npm run dev
```

Acesse no navegador:

http://localhost:5173
Build e Produção

Gerar build:

npm run build

Visualizar build:

npm run preview
Boas Práticas Aplicadas
Componentização
Reutilização de código
Separação de responsabilidades
Estrutura escalável
Gerenciamento global com Context API
Limitações Atuais
Sem backend integrado
Sem persistência de dados
Sem autenticação de usuários
Sem sistema de pagamento
Melhorias Futuras
Integração com API REST
Banco de dados
Autenticação (JWT)
Pagamentos (Stripe / Mercado Pago)
Filtros e busca
Painel administrativo





