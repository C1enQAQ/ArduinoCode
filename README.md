# NetLogo Language Support for CodeMirror 6

- Work in progress by Ruth Bagley (@rbagley), Haylie Wu (@wubbalubbadu), and John Chen (@CIVITAS-John).()Maybe还有我
- 为了配置环境 可用`npm install`.
- 你也许需要全局安装 `rollup`和`lezer-generator`
  - `npm install @lezer/generator --global`
  - `npm install rollup --global`
- 为构建语言,用· `lezer-generator ./src/lang/lang.grammar -o ./src/lang/lang.js`.
- 为构建项目,用 `rollup -c`.
- Funded by Northwestern SESP Venture Research Fund.
