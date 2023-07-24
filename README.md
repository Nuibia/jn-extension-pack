# 前端插件包
## 插件内容
### 1. [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
    帮助我们检查单词拼写是否出现错误，检查的规则遵循 camelCase （驼峰拼写法）
    
    当在编写代码的过程中，变量未遵循驼峰拼写法的规则时，则会在其下发出现波浪线，这就证明该插件起作用了，如下图
![demo2](https://cdn.byai.com/static/oss-script/ded807cc35167a66dd074db6c96badba.gif)

    我们还可以将鼠标放置到有波浪线的字符上，改插件会进行推荐修改如下图：
![demo3](https://cdn.byai.com/static/oss-script/9dc1504cdb13feb0551dc7b836975132.gif)
    
    如果有时候出现了必须出现的特殊字段但是被识别警告了，可以选择加入到工作区或者个人词典下
---
### 2. [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

js代码检测工具，约束代码风格，以保证代码的一致性和避免错误，相关学习可以查看[ESLint官网](https://eslint.bootcss.com/)

----
### 3. [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

代码格式化，通常一般使用ESLint格式化代码，使用Prettier格式化代码,相关学习可以去查看[Prettier中文网](https://www.prettier.cn/)

---
### 4. [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
GitLens 可以增强 VSCode 内置 Git 的功能。例如 commits 搜索，历史记录和显示的代码作者身份具体功能可以查看 Feature List。如下图：
![demo4](https://cdn.byai.com/static/oss-script/0d2d9a58f23bd32743c7858792488955.gif)

---

### 5. [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
Path Intellisense 是一款自动完成文件名、文件路径的 VS Code 插件,可以让你像补全代码一样去补全文件名
![demo5](https://cdn.byai.com/static/oss-script/0c58a9947bb1a0a103fae0eb477889aa.gif)

----
### 6. [ES7 React/Redux/GraphQL/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)
代码片段插件，含有丰富的React代码片段，满足日常开发需要，如下图：
![demo6](https://cdn.byai.com/static/oss-script/bc18a5cd35b12b1d4a4fddd23b3b9d04.jpg)

> 未来如果有需要，可以搞一个自己的代码片段插件

---
### 7. [vscode-styled-components](https://marketplace.visualstudio.com/items?itemName=styled-components.vscode-styled-components)
使用styled-components一定要使用这个插件，下载了该插件，可以推断你想要输入的样式，如下图：
![demo7](https://cdn.byai.com/static/oss-script/0495612fc04b082657f59a4032400ac8.gif)

---
### 8. [Tabnine AI Autocomplete for Javascript, Python, Typescript, PHP, Go, Java, Ruby & more](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode)
一款利用机器学习补全代码的编辑器插件,十分智能的代码补全插件，如下图：
![demo8](https://cdn.byai.com/static/oss-script/bb479ed4e421844ed83ae01b57240cea.gif)

---
### 9. [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)
高亮TODO，如下图：
![demo9](https://cdn.byai.com/static/oss-script/179b34ebf12e5d6648836f356a328df6.png)
### 10. [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
EditorConfig包含一个用于定义代码格式的文件和一批编辑器插件，这些插件是让编辑器读取配置文件并以此来格式化代码。可以理解为编译器层面的代码格式工具

## 推荐vscode原生设置：
### 1. editor.linkedEditing
等同于[Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)，当重命名一个开始标签时，会自动改写结束标签
    (结合实际尝试了下，HTML文件生效，但是tsx文件不生效，所以还是推荐安装`Auto Rename Tag`插件)
![demo1](https://cdn.byai.com/static/oss-script/304d2802620974eeb369a6302f50cfc0.gif)
