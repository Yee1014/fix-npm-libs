# fix npm libs

使用 `patch-package` 修复npm包

## 使用方法

1. 修改 `package.json` 中的 `scripts`，添加 `postinstall` 脚本

```json
"scripts": {
  "postinstall": "patch-package"
}
```

2. 安装 `patch-package`

```bash
npm install patch-package --save-dev
```
