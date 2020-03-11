#このプロジェクトが出来るまで

- vue-cliをグローバルにインストールする。2020-03-03時点ではVue CLIの v4.2.3がインストールされた。
```
npm i -g vue-cli
```

- プロジェクトディレクトリを作成したいディレクトリへ移動して、vue-cliで下記のコマンドを実行する。
```
vue create vuejs-sample
```

- 質問が出現するので次のように選択する。
```
Vue CLI v4.2.3
? Please pick a preset: Manually select features
? Check the features needed for your project: Babel, TS, PWA, Router, Vuex, CSS Pre-processors, Linter, Unit
? Use class-style component syntax? Yes
? Use Babel alongside TypeScript (required for modern mode, auto-detected polyfills, transpiling JSX)? Yes
? Use history mode for router? (Requires proper server setup for index fallback in production) Yes
? Pick a CSS pre-processor (PostCSS, Autoprefixer and CSS Modules are supported by default): Sass/SCSS (with dart-sass)
? Pick a linter / formatter config: Prettier
? Pick additional lint features: Lint on save, Lint and fix on commit
? Pick a unit testing solution: Jest
? Where do you prefer placing config for Babel, ESLint, etc.? In dedicated config files
? Save this as a preset for future projects? Yes
```