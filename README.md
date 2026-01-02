# 🏀 NBA TEAMS

![GitHub top language](https://img.shields.io/github/languages/top/Wereouts/nbateams2?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/Wereouts/nbateams2?style=for-the-badge)
![GitHub code size](https://img.shields.io/github/languages/code-size/Wereouts/nbateams2?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/Wereouts/nbateams2?style=for-the-badge)
![GitHub license](https://img.shields.io/github/license/Wereouts/nbateams2?style=for-the-badge)

O **NBA TEAMS** é uma aplicação web interativa desenvolvida em React para entusiastas do basquete. O projeto permite a organização e visualização de jogadores das principais franquias da NBA, possibilitando a gestão personalizada de cards de atletas e a criação de novos times dentro da plataforma.

Diferente de versões anteriores ou templates genéricos, este projeto foca na experiência do usuário ao permitir a personalização dinâmica de cores e a gestão de "favoritos", tudo em uma interface moderna e responsiva.

## 🚧 Status do Projeto

✅ **Concluído / Estável**

## ✨ Funcionalidades Principais

*   **Gestão de Jogadores:** Adicione novos jogadores informando nome, posição (cargo) e link da imagem.
*   **Organização por Times:** Visualização segmentada por franquias (Lakers, Celtics, Bulls, Warriors, etc.).
*   **Criação de Times:** Formulário dedicado para cadastrar novos times com nome e cor de identificação.
*   **Personalização Dinâmica:** Alteração de cores dos times em tempo real através de um seletor de cores (color picker).
*   **Sistema de Favoritos:** Marque ou desmarque jogadores como favoritos com um simples clique no ícone de coração.
*   **Remoção de Cards:** Exclua jogadores da lista de forma instantânea.
*   **Persistência de Dados Local:** Utilização de estados do React para gerenciar a lista de colaboradores e times.

## 🛠️ Tecnologias Utilizadas

O projeto foi construído utilizando as melhores práticas de desenvolvimento com React:

*   **[React.js](https://reactjs.org/):** Biblioteca principal para construção da interface.
*   **[JavaScript (ES6+)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript):** Lógica de programação e manipulação de estados.
*   **[CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS):** Estilização modularizada por componentes.
*   **[UUID](https://www.npmjs.com/package/uuid):** Geração de identificadores únicos para cada card e time.
*   **[React Icons](https://react-icons.github.io/react-icons/):** Biblioteca de ícones para ações de favoritar e deletar.
*   **[Hex-to-RGBA](https://www.npmjs.com/package/hex-to-rgba):** Manipulação de opacidade de cores dinâmicas.

## 📂 Estrutura do Projeto

Abaixo, os destaques da organização de diretórios:

```text
src/
├── componentes/         # Componentes reutilizáveis da interface
│   ├── Banner/          # Cabeçalho principal
│   ├── Botao/           # Botões customizados
│   ├── Campo/           # Inputs de texto e cor
│   ├── Colaborador/     # Cards individuais dos jogadores
│   ├── Formulario/      # Lógica de cadastro de jogadores/times
│   ├── ListaSuspensa/   # Seleção de times
│   ├── Rodape/          # Rodapé com redes sociais
│   └── Time/            # Container de seção por time
├── App.js               # Componente pai e gerenciamento de estado global
└── index.js             # Ponto de entrada da aplicação
```

## 📋 Pré-requisitos

Antes de começar, você precisará ter instalado em sua máquina:
*   [Node.js](https://nodejs.org/en/) (versão 14 ou superior recomendada)
*   [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/)

## 🚀 Guia de Início Rápido

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/Wereouts/nbateams2.git
    ```

2.  **Acesse a pasta do projeto:**
    ```bash
    cd nbateams2
    ```

3.  **Instale as dependências:**
    ```bash
    npm install
    ```

4.  **Inicie a aplicação em modo de desenvolvimento:**
    ```bash
    npm start
    ```
    A aplicação abrirá automaticamente no seu navegador no endereço `http://localhost:3000`.

## 🤝 Como Contribuir

Contribuições são o que tornam a comunidade de código aberto um lugar incrível para aprender, inspirar e criar. Qualquer contribuição que você fizer será **muito apreciada**.

1.  Faça um **Fork** do projeto.
2.  Crie uma **Branch** para sua feature (`git checkout -b feature/IncrívelFeature`).
3.  Faça o **Commit** de suas alterações (`git commit -m 'Add: Alguma Feature Incrível'`).
4.  Faça o **Push** para a Branch (`git push origin feature/IncrívelFeature`).
5.  Abra um **Pull Request**.

Para bugs ou sugestões, utilize a seção de [Issues](https://github.com/Wereouts/nbateams2/issues).

## 📜 Licença

Este projeto está sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes (caso disponível no repositório).

## 👥 Autor

Desenvolvido por **Guilherme Costa**.

---
*Este projeto foi criado com fins educacionais para demonstrar o domínio de Hooks (useState), Props e composição de componentes em React.*