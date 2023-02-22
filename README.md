# 學習資源
* [Learn Git Branching](https://learngitbranching.js.org/?locale=zh_TW)
* [Git & GitHub 教學手冊](https://w3c.hexschool.com/git/cfdbd310)

# 環境
使用gitlab flow
- master:主版本，所有發布版本都會會以此版本為主
- production: 生產版本
- develop: 開發版本
- feature: 新功能

# 練習案例
## 建立部署分支
```bash
- git branch production # 建立生產分支
- git branch develop    # 建立測試分支
- git branch -a         # 列出所有分支
```


## 切換到開發分支，進行新功能分支開發
```bash
- git checkout develop  # 將專案切換到開發分支
- git checkout -b feature_a # 在測試分支進行開發feature_a。在 checkout 命令給定 -b 參數執行，可以同時建立分支和切換。
```

