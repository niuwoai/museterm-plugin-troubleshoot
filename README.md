# museterm-plugin-troubleshoot

MuseTerm 的一个示例插件。宿主不读这个仓库，读的是索引仓库里的编译结果。

- 包名见 `package.json`。
- 索引：https://github.com/niuwoai/museterm-plugins-manifest
- `npm run build` 用本机的 TypeScript 7.0.2 编译出 `dist/index.js`。编译产物也提交，方便和索引对照。
- 没有 `preinstall`、`install`、`postinstall`、`prepare`，也没有 `file:` 或 git 依赖。
- 许可证：LicenseRef-MuseTerm-Proprietary。
