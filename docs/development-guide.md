# 开发规范

## 分支

- `main`：稳定、可运行的版本
- `develop`：日常功能的集成分支
- `feature/*`：单个功能的开发分支

## 提交信息

使用简化的 Conventional Commits：

- `feat:` 新功能
- `fix:` 修复问题
- `docs:` 文档变更
- `refactor:` 重构
- `test:` 测试变更
- `chore:` 工程或依赖变更

一次提交只处理一个明确目标，例如：

```text
docs: initialize project documentation
feat: add job list endpoint
fix: correct city filter behavior
```

## 开发流程

1. 明确需求和验收标准。
2. 从 `develop` 创建 `feature/*` 分支。
3. 设计数据结构和接口。
4. 完成功能及必要测试。
5. 本地验证并检查改动。
6. 使用清晰的提交信息提交。
7. 合并回 `develop`。

## 基本约定

- 不提交密码、令牌、数据库真实凭据或 `.env` 文件。
- Java 项目使用项目自带的 Maven Wrapper，不依赖全局 Maven。
- 前后端接口统一使用 JSON。
- 新增功能时同步更新相关文档。

