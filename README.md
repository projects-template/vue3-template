# vue-template

这个项目集成了eslint、prettier、commitlint、husky、lint-staged 可以规范代码格式和提交规范

eslint 和 prettier 可以规范代码格式
commitlint 规范提交信息
husky 在提交或推送时，自动化执行脚本检查。
lint-staged 规范暂存区代码

## 使用方法

```
pnpm install
pnpm dev
```

## 提交规范

```
git add .
git commit -m "feat: 添加新功能"
```

相应的commit规范在commitlint.config.cjs中
