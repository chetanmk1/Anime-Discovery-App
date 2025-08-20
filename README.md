# Anime-Discovery-App
A web app to browse, search, and discover anime using an open API.


A Quasar Project

## Install the dependencies
```bash
yarn
# or
npm install
```

### Start the app in development mode (hot-code reloading, error reporting, etc.)
```bash
quasar dev
```


### Lint the files
```bash
yarn lint
# or
npm run lint
```


### Format the files
```bash
yarn format
# or
npm run format
```



### Build the app for production
```bash
quasar build
```

### Customize the configuration
```bash
See [Configuring quasar.config.js](https://v2.quasar.dev/quasar-cli-vite/quasar-config-js)
```

### you can check if there are any warnings or errors by just running ESLint without the --fix flag:
```bash
npx eslint "src/**/*.{js,vue}" or npx eslint --ext .js,.vue src  or
npx eslint src  or quasar lint

# Run ESLint with Auto-Fix Command
npx eslint --fix src

# Working commands in short (In package.json, under "scripts")
# To check warnings
npm run lint:fix

# Fix warnings autpmatically
npm run lint:fix
```


## 🎬 Anime Discovery App
```bash

A Vue 3 + Quasar + Pinia based web app to browse, search, and discover anime using the Jikan API (MyAnimeList unofficial API).
Users can view trending anime, search by title, see detailed information, and save favorites.

🚀 Features

    🔍 Search Anime by title with live API results.

    🎥 Anime Details Page with synopsis, genres, episodes, and trailers.

    ❤️ Favorites Management (Pinia + Local Storage).

    🌙 Dark/Light Mode toggle.

    📊 Trending, Top Rated, Upcoming categories.

    ⚡ Responsive UI with Quasar components.


🛠️ Tech Stack

    Vue 3
    – Frontend framework

    Quasar
    – UI components & layout system

    Pinia
    – State management

    Axios
    – API requests

    Jikan API
    – Anime data source

📂 Project Structure

    src/
    ├── components/    # Reusable UI components
    ├── pages/         # Home, Details, Favorites
    ├── store/         # Pinia store (favorites, user state)
    ├── services/      # API requests (Axios wrapper)
    ├── App.vue        # Root component
    └── main.js        # Entry point

```