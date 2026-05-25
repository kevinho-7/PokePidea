# PokePedia

<img src="https://flagcdn.com/64x48/br.png" width="25"> [**`Portuguese Version`**](./README.pt.md)

> Academic project developed for the **Web Front-end Development II** course at BYU–Idaho as part of my Software Development degree program.

PokePedia is an interactive Pokédex web application that allows users to explore Pokémon by generation, search for specific Pokémon, and build their own personal "PokéBox" by catching and storing favorite Pokémon using browser local storage.

The project demonstrates proficiency in modern front-end development, asynchronous API integration, dynamic DOM manipulation, and responsive design principles.

---

## 🚀 Features

- Browse Pokémon by generation (Gen I through Gen IX)
- Search for specific Pokémon by name
- View detailed Pokémon cards with official artwork and type information
- Catch Pokémon and store them in a local PokéBox
- Release Pokémon from the PokéBox with confirmation modal
- Persistent storage using browser LocalStorage
- Fully responsive layout that adapts to different screen sizes
- Dynamic footer and header adjustments based on viewport
- Professor Oak's random advice on each catch

---

## 🛠️ Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript (ES6+)
- Bootstrap 5
- Vite (Build tool)

### APIs & Services
- [PokéAPI](https://pokeapi.co/) - Pokémon data
- [Advice Slip API](https://api.advice slip.dev/) - Professor Oak's random advice

### Tools & Environment
- Git & GitHub
- Netlify (Hosting)
- ESLint
- Chrome DevTools

---

## 📂 Project Structure

```text
src/
├── scripts/
│   ├── main.js           # Entry point, page routing logic
│   ├── API-data.js       # API calls to PokéAPI and Advice API
│   ├── utils.js          # LocalStorage helpers, card rendering, modals
│   └── dinamic-styles.js # Responsive style adjustments
├── styles/
│   └── style.css         # Custom styles and grid layouts
public/
├── images/               # Static assets (logos, GIFs, hero image)
pages/
├── pokebox.html          # PokéBox page template
index.html                # Main PokéDex page
vite.config.js            # Vite multi-page configuration
```

## 📚 Concepts Practiced

- Asynchronous JavaScript (async/await, fetch API)
- DOM manipulation and dynamic content rendering
- Template cloning for reusable card components
- Event delegation and MutationObserver for dynamically added elements
- LocalStorage for client-side data persistence
- Bootstrap 5 components (modals, dropdowns, navbar, grid)
- Responsive design with CSS Grid and Flexbox
- Vite multi-page application setup
- URL parameter handling and routing
- Modal dialogs with Bootstrap JS

---

## 🎯 Purpose of the Project

This project was created as the final assignment for the Web Front-end Development II course at BYU–Idaho. The main objectives were to:

- Demonstrate proficiency in vanilla JavaScript without heavy frameworks
- Integrate third-party REST APIs effectively
- Build a fully responsive, mobile-friendly web application
- Implement complex UI interactions (catching, releasing, searching)
- Practice clean code organization and modular architecture

---

## 👨‍💻 Author

**Kevin G. Ferreira**  
Software Development student at BYU–Idaho

---

## 📄 License

This project was developed for academic purposes. Pokémon and related assets are property of Nintendo, Game Freak, and The Pokémon Company.
