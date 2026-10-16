# Audit Agent

Audit Agent 多人协作开发仓库，目前处于项目初始化阶段。

## 获取项目

```bash
git clone https://github.com/lackjava-creator/Audit-Agent.git
cd Audit-Agent
```

## 协作流程

1. 通过 Issues 讨论任务、需求和问题。
2. 开发前同步 main，并创建自己的功能分支：

   ```bash
   git switch main
   git pull --ff-only origin main
   git switch -c feat/your-feature
   ```

3. 完成修改后提交并推送分支：

   ```bash
   git add <需要提交的文件>
   git commit -m "Describe your change"
   git push -u origin feat/your-feature
   ```

4. 发起 Pull Request，说明修改内容和验证方式，经团队评审后合并到 main。

## 参与方式

- 本仓库公开，任何人都可以查看、克隆，并通过 Fork 和 Pull Request 贡献修改。
- 需要直接推送分支的团队成员，由仓库管理员在 Settings → Collaborators 中邀请；接受邀请后获得写入权限。
- 分支与评审流程是团队协作约定，当前未设置强制分支保护。
- 请勿提交 API 密钥、密码、个人隐私信息或真实审计数据；示例数据应先脱敏。
