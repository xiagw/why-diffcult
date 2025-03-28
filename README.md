# why-diffcult
Is so difficult that even programmers struggle with it?

为什么程序员都屡屡犯错而觉得很难的 list：

| 技术难点 | 常见问题 | 解决方案建议 |
|---------|----------|------------|
| vi/vim | 命令模式复杂，退出困难 | 掌握基本命令(:wq, :q!), 使用 vimtutor 学习 |
| git/github/github PR | 分支管理混乱，冲突处理困难 | 遵循 Git Flow，经常 pull 和 rebase |
| ssh/ssh key | 密钥管理和权限设置 | 使用 ssh-keygen，注意权限设置为 600 |
| SSL | 证书配置和更新麻烦 | 使用 Let's Encrypt，自动化更新 |
| CA | 证书链配置复杂 | 使用可信 CA，保持证书更新 |
| RSA/ECC | 密钥长度和算法选择 | 根据安全需求选择合适的算法和密钥长度 |
| Private/Public key | 密钥对管理和安全存储 | 使用密钥管理系统，做好备份 |