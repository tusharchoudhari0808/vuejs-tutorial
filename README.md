# vue-new-project

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Customize configuration

See [Vite Configuration Reference](https://vite.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

# Introduction
## What is Vue js ?
###  Vue.js is a progressive JavaScript framework for building user interfaces and single-page applications (SPAs).

It uses a component-based architecture and supports reactive data binding for dynamic UI updates.

Vue is easy to learn, combining HTML, CSS, and JavaScript in single-file .vue components.

It provides built-in features like directives (v-if, v-for, v-model) and tools like Vue CLI, Vue Router, and Vuex.

Vue is lightweight, flexible, and backed by a strong community with excellent documentation.



# Vue 3 Project Folder Structure

my-vue-app/
│
├── node_modules/         # Installed npm packages
├── public/               # Public files (index.html, favicon, etc.)
│   └── index.html        # HTML template
│
├── src/                  # Main source code
│   ├── assets/           # Static assets (images, icons, etc.)
│   ├── components/       # Vue components (.vue files)
│   ├── views/            # Pages or views (for routing)
│   ├── router/           # Vue Router configuration (optional)
│   ├── store/            # Vuex store or Pinia (optional)
│   ├── App.vue           # Root component
│   └── main.js / main.ts # App entry point (JS or TS)
│
├── .gitignore            # Files to ignore in Git
├── package.json          # Project dependencies and scripts
├── vite.config.js        # Vite configuration (if using Vite)
├── babel.config.js       # Babel config (if using Vue CLI)
└── README.md             # Project documentation

# Vue.js Components (5 Key Points)

##What are Components?
Components are reusable and independent blocks of UI in Vue (e.g., buttons, cards, headers), defined in .vue files with <template>, <script>, and <style>.

Types of Components

Global components: Registered using app.component() and used anywhere.

Local components: Imported and registered inside other components.

##Props (Data Passing)
Components receive external data from parent via props, allowing dynamic rendering.

Emits (Event Handling)
Child components can send data back to the parent using the emit function (e.g., emit('clicked')).

##Component Communication

Parent to Child → via props

Child to Parent → via emit

Sibling components → use global state (Vuex/Pinia) or event bus

