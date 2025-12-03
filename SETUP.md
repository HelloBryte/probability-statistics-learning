# 本地同步说明

完整的学习资料文件较大（约90KB），需要通过 Git 命令行推送。

## 推送步骤

```bash
cd /Users/mac/PycharmProjects/podcast/probability_statistics

# 配置 Git（如果还没配置）
git config user.name "HelloBryte"
git config user.email "你的邮箱"

# 添加 SSH 远程仓库（推荐）
git remote set-url origin git@github.com:HelloBryte/probability-statistics-learning.git

# 或使用 GitHub CLI 登录后推送
# brew install gh
# gh auth login
# git push -u origin main
```

## 文件列表

- `00_大纲与设计说明.md` - 课程大纲和设计理念
- `概率统计学习资料.md` - 完整学习内容（约90KB）
