# vue2-lint

## Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

See [yorkie](https://github.com/yyx990803/yorkie)

See [husky](https://typicode.github.io/husky/)

See [commitlint](https://github.com/conventional-changelog/commitlint)

See [lint-staged](https://github.com/okonet/lint-staged)

See [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0-beta.2/#why-use-conventional-commits)

See [stylelint.docschina](http://stylelint.docschina.org)

See [stylelint](https://stylelint.io)

See [stylelint-config-standard](https://github.com/stylelint/stylelint-config-standard)

See [stylelint-config-standard-vue](https://github.com/ota-meshi/stylelint-config-standard-vue)

See [stylelint-config-standard-less](https://github.com/stylelint-less/stylelint-config-standard-less)

See [stylelint-config-standard-scss](https://github.com/stylelint-scss/stylelint-config-standard-scss)

See [stylelint-order](https://github.com/hudochenkov/stylelint-order)

See [stylelint-config-recess-order](https://github.com/stormwarning/stylelint-config-recess-order)

See [stylelint-config-recommended](https://github.com/stylelint/stylelint-config-recommended)

See [stylelint-config-recommended-vue](https://github.com/ota-meshi/stylelint-config-recommended-vue)

See [stylelint-config-recommended-less](https://github.com/ssivanatarajan/stylelint-config-recommended-less)

See [stylelint-config-recommended-scss](https://github.com/stylelint-scss/stylelint-config-recommended-scss)

See [stylelint-config-html](https://github.com/ota-meshi/stylelint-config-html)

> standard 会引入 recommended 因此安装 standard 时会自动安装相应 recommended
> recommended 会引入 stylelint 和 postcss 因此 安装 recommended 时会自动安装相应的 stylelint 和 postcss

### Conventional Commits

| Type     | 作用                                                                                   |
| -------- | -------------------------------------------------------------------------------------- |
| feat     | 新增特性 (feature)                                                                     |
| fix      | 修复 Bug(bug fix)                                                                      |
| docs     | 修改文档 (documentation)                                                               |
| style    | 代码格式修改(white-space, formatting, missing semi colons, etc)                        |
| refactor | 代码重构(refactor)                                                                     |
| perf     | 改善性能(A code change that improves performance)                                      |
| test     | 测试(when adding missing tests)                                                        |
| build    | 变更项目构建或外部依赖（例如 scopes: webpack、gulp、npm 等）                           |
| ci       | 更改持续集成软件的配置文件和 package 中的 scripts 命令，例如 scopes: Travis, Circle 等 |
| chore    | 变更构建流程或辅助工具(比如更改测试环境)                                               |
| revert   | 代码回退                                                                               |

### CSS 的书写顺序

1. 优先级第一定位属性
2. 优先级第二自身属性
3. 优先级第三文字样式
4. 优先级第四文本属性
5. 优先级第五 css3 中新增属性

### 绕过校验

```
git commit --no-verify -m "xxxxxx"
```

### blog

https://juejin.cn/post/7103889661465985038

https://juejin.cn/post/7119428188991651848
