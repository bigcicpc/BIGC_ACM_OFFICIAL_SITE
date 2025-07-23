# 贡献指南（CONTRIBUTING）

感谢你有意为本项目做出贡献！为了让协作更加高效、规范，请遵循以下约定：

## 1. 约定式提交（Conventional Commits）

请按照 [Conventional Commits](https://www.conventionalcommits.org/zh-hans/v1.0.0/) 规范进行提交，格式如下：

```
<type>(<scope>): <subject>
```

- `type`：提交类型，如 feat（新功能）、fix（修复）、docs（文档）、style（格式）、refactor（重构）、test（测试）、chore（杂项）等。
- `scope`：可选，影响范围（如模块名、文件名）。
- `subject`：简要描述本次提交的目的。

示例：
```
feat(core): 新增用户登录功能
fix(ui): 修复按钮样式错位
```

## 2. Pull Request（PR）规范

- **分支管理**：请从 `main` 分支拉取新分支进行开发，分支命名建议为 `feature/xxx`、`fix/xxx`、`docs/xxx` 等。
- **PR 标题**：建议与提交信息保持一致，简明扼要。
- **PR 描述**：请详细描述本次变更的内容、动机及影响范围，必要时附上截图或相关 issue 链接。
- **自检清单**：
  - [ ] 代码已本地测试通过
  - [ ] 无明显语法/逻辑错误
  - [ ] 文件目录结构清晰，符合项目规范
  - [ ] `mkdocs.yml` 已同步更新
  - [ ] 相关 issue 已关联（如适用）

## 3. 代码风格

- 遵循项目现有的代码风格。

## 4. 其他建议

- 提交前请确保合并主分支最新代码，避免冲突。
- 如有疑问或建议，欢迎在微信群讨论或联系主要贡献者。

---

感谢你的贡献！