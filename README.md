# 🌿Cidades + Verdes

"Cidades + Verdes" é um projeto que visa conscientizar sobre a importância das florestas urbanas e promover ações para tornar as cidades mais sustentáveis. O site, inicialmente desenvolvido com HTML e CSS, foi aprimorado com JavaScript para incluir funcionalidades dinâmicas de gerenciamento de usuários, simulando uma aplicação web interativa. [cite: 1, 3]

## 🌳 Páginas do Projeto

O projeto é composto por quatro páginas principais:

  * **Página Inicial | index.html**: Apresenta a importância das florestas urbanas, seus benefícios, ações sustentáveis e exemplos de inspiração verde. Inclui também seções sobre a comunidade ativa, recursos e informações de contato.
  * **Página de Cadastro | cadastro.html**: Permite que novos usuários se cadastrem no site, solicitando nome completo, e-mail, senha, data de nascimento e cidade.
  * **Página de Login | login.html**: Permite que usuários existentes façam login com e-mail e senha.
  * **Página de Administração | admin.html**: Uma página de gerenciamento onde é possível cadastrar, visualizar, pesquisar e excluir usuários da aplicação. [cite: 9] As informações são salvas localmente no navegador. [cite: 8]

## 🌳 Estrutura do Projeto

O projeto está organizado da seguinte forma:

```
├── imgs/
│   ├── LogoComFundo.png
│   ├── LogoSemFundo.png
│   ├── ... (outras imagens)
├── fonts/
│   ├── nord.ttf
│   └── NewYork.otf
├── admin.css
├── admin.html
├── admin.js
├── cadastro.html
├── curriculo.html
├── index.html
├── login.html
├── style.css
└── styleCurriculo.css
```

## 🌳 Tecnologias Utilizadas

  * **HTML5**: Usado para a estrutura e conteúdo das páginas web.
  * **CSS3**: Usado para a estilização e design das páginas. [cite: 2]
  * **JavaScript (ES6+)**: Utilizado para adicionar interatividade e manipular os dados da aplicação. [cite: 3]
      * **DOM API**: Para manipulação dinâmica dos elementos da página. [cite: 17]
      * **Web Storage API (Local Storage)**: Para armazenamento de dados no navegador do usuário. [cite: 17]

## 🌳 Funcionalidades

### Funcionalidades Gerais

  * Navegação intuitiva entre as seções e páginas do site.
  * Formulários de cadastro e login para interação do usuário.
  * Design limpo e responsivo para uma boa experiência em diferentes dispositivos.

### Painel Administrativo (`admin.html`)

O desenvolvimento desta seção seguiu os requisitos do Projeto 2 da disciplina de Programação Web Front-End. 

  * **Cadastro de Usuários**: Formulário para adicionar novos usuários (nome e e-mail). 
  * **Armazenamento Local**: Os dados dos usuários são salvos no Local Storage do navegador em um único objeto JSON. 
  * **Listagem Dinâmica**: Os usuários cadastrados são exibidos em uma lista não ordenada logo abaixo do formulário, incluindo a data de envio. 
  * **Exclusão Individual**: Cada item da lista possui uma opção para ser excluído individualmente, removendo-o da tela e do Local Storage. 
  * **Exclusão Total**: Funcionalidade para apagar todos os usuários da lista e do Local Storage de uma só vez. 
  * **Pesquisa de Usuários**: Um campo de busca que permite filtrar a lista por nome ou e-mail em tempo real.
  * **Limpeza de Formulário**: Opção para limpar os campos de entrada de dados do formulário de cadastro. 

## Autor

**Douglas Nascimento de Matos**

  * **Email**: douglasnascimento@alunos.utfpr.edu.br
  * **LinkedIn**: [@douglasnascimentomatos](https://www.linkedin.com/in/douglasnascimentomatos)
  * **GitHub**: [douglasnascimento-dev](https://github.com/douglasnascimento-dev)
