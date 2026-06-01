<div align="center">

<br>

⋆˙⟡ ·˚ ⋆ ·˚ ⟡˙⋆ ·˚ ⋆ ·˚ ⟡˙⋆

<br>

# metalog

*sistema web de gestão para empresas metalúrgicas*

<br>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

<br>

</div>

---

### ⟡ sobre o projeto

A **Metalog** é uma plataforma web voltada para empresas que trabalham com produtos metalúrgicos.
O sistema centraliza o controle de estoque, movimentações, lotes, projetos e financeiro em um só lugar.

---

### ˚✦ funcionalidades

```
⋆  gestão de produtos     →  cadastro, edição e controle de itens metalúrgicos
⋆  controle de estoque    →  entradas, saídas e movimentações em tempo real
⋆  gestão de lotes        →  rastreamento e organização por lote
⋆  controle financeiro    →  acompanhamento de receitas e despesas
⋆  gestão de projetos     →  criação e acompanhamento de projetos internos
⋆  autenticação           →  login, cadastro e área do usuário via Firebase
⋆  planos e assinaturas   →  integração com Mercado Pago
```

---

### ⟡ tecnologias utilizadas

| camada | tecnologia |
|--------|-----------|
| estrutura | HTML5 |
| estilização | CSS3 (modular por página) |
| interatividade | JavaScript (Vanilla) |
| autenticação | Firebase Auth |
| banco de dados | Firebase Firestore |
| pagamentos | Mercado Pago SDK |

---

### ˚✦ como rodar o projeto

**1. clone ou extraia o repositório**
```bash
git clone https://github.com/seu-usuario/metalog.git
cd metalog/projeto
```

**2. abra no navegador**

> O projeto é estático — basta abrir o arquivo `index.html` diretamente no navegador.

```bash
# ou via extensão Live Server no VS Code
# clique com botão direito em index.html → "Open with Live Server"
```

**3. configure o Firebase** *(opcional para funcionalidades completas)*

Edite o arquivo `static/js/auth.js` com as credenciais do seu projeto Firebase:

```js
const firebaseConfig = {
  apiKey: "sua-api-key",
  authDomain: "seu-projeto.firebaseapp.com",
  projectId: "seu-projeto",
  ...
};
```

---

### ⟡ estrutura de arquivos

```
metalog/
├── index.html               ⋆ página inicial
├── login.html               ⋆ autenticação
├── cadastro.html            ⋆ criação de conta
├── produtos.html            ⋆ gestão de produtos
├── armazenamento.html       ⋆ controle de estoque
├── movimentacoes.html       ⋆ movimentações
├── lotes.html               ⋆ gestão de lotes
├── controle-financeiro.html ⋆ financeiro
├── gestao-de-projetos.html  ⋆ projetos
├── planos.html              ⋆ planos e assinatura
├── assets/                  ⋆ imagens e logo
└── static/
    ├── css/                 ⋆ estilos por módulo
    └── js/                  ⋆ scripts por funcionalidade
```

---

<div align="center">

⋆˙⟡ ·˚ ⋆ ·˚ ⟡˙⋆ ·˚ ⋆ ·˚ ⟡˙⋆

*feito com cuidado ˚*

</div>
