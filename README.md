# 🍩 Divino Donuts

<p align="left">
  <img src="img/logo/1.png" alt="Divino Donuts" height="72" />
</p>

> E-commerce de donuts desenvolvido em PHP com catálogo dinâmico (JSON), autenticação de usuários, carrinho persistente e fluxo completo de checkout.

![PHP](https://img.shields.io/badge/PHP-8%2B-777BB4?logo=php&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=000)
![JSON](https://img.shields.io/badge/JSON-000000?logo=json&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-Design-F24E1E?logo=figma&logoColor=white)

---

## 📑 Sumário

- [Demonstração](#demo)
- [Sobre o Projeto](#sobre)
- [Tecnologias Utilizadas](#tecnologias)
- [Instalação e Execução](#instalacao)
- [Configuração](#config)
- [Estrutura de Pastas](#estrutura)
- [Funcionalidades](#funcionalidades)
- [Testes](#testes)
- [Melhorias Futuras](#melhorias)
- [Contribuição](#contribuicao)
- [Licença](#licenca)
- [Autor](#autor)

---

<a id="demo"></a>
## :rocket: Demonstração

- Local (exemplo): http://localhost/Divino_Donuts/pages/home.php
- Preview do protótipo:

### Desktop

![Protótipo Desktop](protótipo/Pc.png)

### Mobile

![Protótipo Mobile](protótipo/Mobile.png)

### Assets

![Protótipo Assets](protótipo/Assets.png)

### Screenshots do sistema

<p align="left">
  <img src="img/banners/home.png" alt="Tela Home" width="32%" />
  <img src="img/banners/login.png" alt="Tela Login" width="32%" />
  <img src="img/banners/cadastro.png" alt="Tela Cadastro" width="32%" />
</p>

---

<a id="sobre"></a>
## 📖 Sobre o Projeto

O Divino Donuts é um e-commerce com páginas dinâmicas em PHP, convertido de uma base estática (HTML/CSS/JS) para um fluxo completo de navegação e compra. O objetivo é demonstrar uma aplicação web funcional com autenticação, catálogo, carrinho e finalização de pedido, utilizando arquivos JSON como persistência.

---

<a id="tecnologias"></a>
## 🛠️ Tecnologias Utilizadas

- PHP
- HTML5
- CSS3
- JavaScript (ES6)
- JSON (persistência de dados)
- Font Awesome e Google Fonts
- Figma (prototipagem) e Canva (logo)

---

<a id="instalacao"></a>
## ⚙️ Instalação e Execução

Pré-requisitos: ambiente de servidor local (XAMPP, WAMP ou MAMP).

```bash
# Clone o repositório
git clone https://github.com/helen2411/Divino_Donuts.git
```

- Copie a pasta do projeto para o diretório do servidor (ex.: htdocs no XAMPP)
- Inicie o Apache
- Abra:
  - http://localhost/Divino_Donuts/pages/home.php

---

<a id="config"></a>
## 🔑 Configuração

- Este projeto não usa arquivo `.env`
- Para cadastro e pedidos funcionarem corretamente, os arquivos JSON em `pages/` precisam estar com permissão de escrita:
  - `pages/usuario.json`
  - `pages/pedidos.json`

---

<a id="estrutura"></a>
## 📂 Estrutura de Pastas

```bash
Divino_Donuts/
 ├── pages/
 ├── scripts/
 ├── styles/
 ├── img/
 ├── protótipo/
 ├── LICENSE
 └── README.md
```

---

<a id="funcionalidades"></a>
## 📌 Funcionalidades

- Autenticação de usuários (cadastro, login, logout) com sessão e hashing de senha
- Catálogo dinâmico de produtos via JSON
- Filtro e busca por categoria/nome
- Carrinho persistente via sessão (adicionar, remover, alterar quantidade)
- Checkout com pagamento e confirmação do pedido
- Histórico de pedidos salvo em JSON
- Layout responsivo e página de acessibilidade

---

<a id="testes"></a>
## 🧪 Testes

Este projeto ainda não possui suíte de testes automatizados. A validação é feita por testes manuais do fluxo:

- Cadastro → Login → Produtos → Carrinho → Pagamento → Confirmação

---

<a id="melhorias"></a>
## 📈 Melhorias Futuras

- Migrar JSON para um banco SQL (MySQL/MariaDB)
- Criar página “Minha conta” com histórico e dados do usuário
- Implementar painel administrativo para produtos
- Integrar gateway de pagamento (Mercado Pago/PagSeguro/Stripe)

---

<a id="contribuicao"></a>
## 🤝 Contribuição

```bash
git checkout -b minha-feature
git commit -m "feat: minha nova feature"
git push origin minha-feature
```

---

<a id="licenca"></a>
## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

<a id="autor"></a>
## 👨‍💻 Autor

Feito por Helen.

- GitHub: https://github.com/helen2411
- LinkedIn: https://linkedin.com/in/seu-perfil

