# vue3-chat

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin) to make the TypeScript language service aware of `.vue` types.

If the standalone TypeScript plugin doesn't feel fast enough to you, Volar has also implemented a [Take Over Mode](https://github.com/johnsoncodehk/volar/discussions/471#discussioncomment-1361669) that is more performant. You can enable it by the following steps:

1. Disable the built-in TypeScript Extension
    1) Run `Extensions: Show Built-in Extensions` from VSCode's command palette
    2) Find `TypeScript and JavaScript Language Features`, right click and select `Disable (Workspace)`
2. Reload the VSCode window by running `Developer: Reload Window` from the command palette.

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Lint with [ESLint](https://eslint.org/)

[RULE](https://eslint.org/docs/latest/use/configure/rules)
[格式化](https://prettier.io/docs/en/options.html)

```sh
npm run lint
```

### vscode插件

Vue.volar ： Vue 3 官方推荐的 VS Code 开发插件；Vue.vscode-typescript-vue-plugin： Vue 3 TypeScript 语法辅助 VS Code 插件；dbaeumer.vscode-eslint ： ESLint 的 VS Code 插件；esbenp.prettier-vscode ：Prettier 的 VS Code 插件；rvest.vs-code-prettier-eslint：ESLint 联动 Prettier 的 VS Code 插件；

#### 关于 Vue 3 的项目代码规范配置理念，主要有三个要点：

* 编写代码规范，核心是用 TypeScript 这个强类型的语法，来减少 Vue 3 项目潜在的类型问题；
* 代码格式规范，基于 VS Code 编辑器，用 ESLint 和 Prettier，规范和限制开发代码时的代码风格格式化和质量检查；
* 代码质量检查，基于 ESLint 的 CLI 工具进行兜底检查，避免是用其它编辑器绕过 VS Code 的代码规范限制。

### 使用less

* npm install less less-loader（css）
* npm install moment(时间库)
* npm install -D stylus