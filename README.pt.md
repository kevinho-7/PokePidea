# PokePedia

<img src="https://flagcdn.com/20x15/us.png" width="25"> [**`English Version`**](./README.md)

> Projeto acadêmico desenvolvido para a disciplina de **Web Front-end Development II** na BYU–Idaho como parte do curso de Desenvolvimento de Software.

PokePedia é uma aplicação web interativa de Pokédex que permite aos usuários explorar Pokémon por geração, pesquisar Pokémon específicos e montar sua própria “PokéBox” capturando e armazenando Pokémon favoritos utilizando o LocalStorage do navegador.

O projeto demonstra conhecimentos em desenvolvimento front-end moderno, integração assíncrona com APIs, manipulação dinâmica do DOM e princípios de design responsivo.

---

## 🚀 Funcionalidades

- Navegação por gerações de Pokémon (Gen I até Gen IX)
- Pesquisa de Pokémon por nome
- Visualização de cards detalhados com arte oficial e tipos do Pokémon
- Captura de Pokémon e armazenamento em uma PokéBox local
- Liberação de Pokémon da PokéBox com modal de confirmação
- Persistência de dados utilizando LocalStorage
- Layout totalmente responsivo para diferentes tamanhos de tela
- Ajustes dinâmicos de footer e header com base no viewport
- Conselhos aleatórios do Professor Oak a cada captura

---

## 🛠️ Tecnologias Utilizadas

### Frontend
- HTML5
- CSS3
- JavaScript (ES6+)
- Bootstrap 5
- Vite (ferramenta de build)

### APIs & Serviços
- [PokéAPI](https://pokeapi.co/) - Dados dos Pokémon
- [Advice Slip API](https://api.adviceslip.dev/) - Conselhos aleatórios do Professor Oak

### Ferramentas & Ambiente
- Git & GitHub
- Netlify (Hospedagem)
- ESLint
- Chrome DevTools

---

## 📂 Estrutura do Projeto

```text
src/
├── scripts/
│   ├── main.js           # Ponto de entrada e lógica de roteamento
│   ├── API-data.js       # Chamadas para PokéAPI e Advice API
│   ├── utils.js          # Helpers de LocalStorage, renderização e modais
│   └── dinamic-styles.js # Ajustes responsivos de estilo
├── styles/
│   └── style.css         # Estilos customizados e grids
public/
├── images/               # Assets estáticos (logos, GIFs e hero image)
pages/
├── pokebox.html          # Template da página da PokéBox
index.html                # Página principal da Pokédex
vite.config.js            # Configuração multi-page do Vite
```

## 📚 Conceitos Praticados

- JavaScript assíncrono (async/await e Fetch API)
- Manipulação do DOM e renderização dinâmica de conteúdo
- Clonagem de templates para componentes reutilizáveis
- Delegação de eventos e MutationObserver para elementos dinâmicos
- LocalStorage para persistência de dados no cliente
- Componentes do Bootstrap 5 (modais, dropdowns, navbar e grid)
- Design responsivo com CSS Grid e Flexbox
- Configuração de aplicação multi-page com Vite
- Manipulação de parâmetros de URL e roteamento
- Modais utilizando Bootstrap JS

---

## 🎯 Objetivo do Projeto

Este projeto foi desenvolvido como trabalho final da disciplina de Web Front-end Development II na BYU–Idaho. Os principais objetivos foram:

- Demonstrar domínio de JavaScript puro sem frameworks pesados
- Integrar APIs REST de terceiros de forma eficiente
- Construir uma aplicação web totalmente responsiva
- Implementar interações complexas de interface (captura, liberação e pesquisa)
- Praticar organização de código limpa e arquitetura modular

---

## 👨‍💻 Autor

**Kevin G. Ferreira**  
Estudante de Desenvolvimento de Software na BYU–Idaho

---

## 📄 Licença

Este projeto foi desenvolvido para fins acadêmicos. Pokémon e seus respectivos assets pertencem à Nintendo, Game Freak e The Pokémon Company.
