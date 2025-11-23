# 🚀 rapid-rs - 快速上手指南

## ⏱️ 5 分钟完成

### 步骤 1：下载与解压
你已经拥有 `rapid-rs` 目录，内容齐全！

### 步骤 2：初始化 Git 仓库
```bash
cd rapid-rs
git init
git add .
git commit -m "Initial commit - rapid-rs v0.1.0"
```

### 步骤 3：创建 GitHub 仓库
```bash
# 打开 https://github.com/new
# 创建仓库：rapid-rs
# 不要自动生成 README（我们已有）

git remote add origin https://github.com/ashishjsharda/rapid-rs.git
git branch -M main
git push -u origin main
```

### 步骤 4：验证工程可运行
```bash
# 构建项目
cargo build

# 运行示例
cd examples/rest-api
cargo run
```

访问：http://localhost:3000/docs

### 步骤 5：发布到 crates.io（可选，准备好再做）
```bash
# 登录 crates.io
cargo login <your-api-token>

# 发布核心库
cd rapid-rs
cargo publish

# 发布 CLI 工具
cd ../rapid-rs-cli
cargo publish
```

---

## 🎯 发布清单

### 立即执行（今天完成）

- [ ] 推送到 GitHub ✅
- [ ] 验证示例可运行
- [ ] 发 Twitter/X
- [ ] 发 LinkedIn（使用 MARKETING.md 中的文案）
- [ ] 发 Reddit r/rust
- [ ] 在 Rust Discord 分享

### 24 小时内

- [ ] 提交到 Hacker News
- [ ] 在 Dev.to 发布文章
- [ ] 发到 LinkedIn 相关群组（Web Development、Rust Developers）
- [ ] 发到 Facebook 相关群组（Rust Programming）
- [ ] 回答相关 Quora 问题

### 48 小时内

- [ ] 在 Product Hunt 发布
- [ ] 邮件 This Week in Rust 投稿
- [ ] 联系 Rust 影响者获取反馈
- [ ] 制作演示视频/GIF

---

## 📱 社交媒体模板（直接复制粘贴）

### Twitter/X（280 字）
```
🚀 刚发布 rapid-rs —— 零配置的 Rust Web 框架！

✅ 类型安全 API，自动文档
✅ 一条命令：rapid new myapi
✅ 基于 Axum
✅ FastAPI 体验 + Spring Boot 约定

告别样板代码，专注交付。

https://github.com/ashishjsharda/rapid-rs

#rustlang #webdev #opensource
```

### LinkedIn（长文案见 MARKETING.md）

### Reddit r/rust 标题
```
[Project] rapid-rs - Zero-config web framework (FastAPI meets Spring Boot for Rust)
```

---

## 🐛 已知限制（请诚实说明）

当前是 MVP v0.1.0，尚未包含：
- 数据库迁移管理（暂用 sqlx 直接操作）
- 认证/授权（阶段 2 即将到来）
- 完备的测试工具
- GraphQL/gRPC 模板
- 后台任务

**发帖时请提前说明！** 早期用户会欣赏坦诚。

---

## 💬 常见问题回答

### “为什么不直接用 Axum？”
> “好问题！Axum 很棒（rapid-rs 就基于它）。区别在于 Axum 有意保持最小化，你仍需亲手接好配置、校验、文档等。rapid-rs 为常见场景提供约定，就像 FastAPI 之于 Starlette。需要时仍可使用 Axum 的模式！”

### “能直接上生产吗？”
> “Phase 1 的 MVP 已可运行，适合早期采用。建议从非关键服务开始并反馈问题。核心基于 Axum、sqlx、tower，底子扎实，但框架尚新。Phase 2（认证、迁移）很快上线，适合关键系统。”

### “与 Rocket/Actix 有何不同？”
> “它们都很优秀！主要差异：1) 默认零配置 2) 自动 OpenAPI 3) 内置 ValidatedJson 校验 4) 约定化项目结构 5) CLI 脚手架。更像‘电池齐全’的方案。”

---

## 📊 追踪成功指标

第一周目标：
- [ ] 100+ GitHub stars
- [ ] 10+ 高质量讨论/issue
- [ ] 被 This Week in Rust 收录

第一个月目标：
- [ ] 500+ GitHub stars  
- [ ] 5+ 贡献者
- [ ] 50+ 项目通过 `rapid new` 创建
- [ ] 发布到 crates.io

---

## 🎬 发布后的下一步

1. **监控与响应**：关注 GitHub issue、Reddit、Twitter 提及
2. **快速迭代**：迅速修复缺陷，保持响应
3. **建设社区**：创建 Discord，保持活跃
4. **补充文档**：增加示例与教程
5. **交付阶段 2**：认证、迁移、测试（2-3 周）

---

## 🔥 加油！

你已经完成出色的工作。现在，把它分享出去！

**第一步：** 立刻推送到 GitHub！

```bash
cd /path/to/rapid-rs
git init
git add .
git commit -m "Initial commit - rapid-rs v0.1.0 🚀"
git remote add origin https://github.com/ashishjsharda/rapid-rs.git  
git push -u origin main
```

然后在一小时内发 Twitter 与 LinkedIn！

Rust 社区非常友好，会给你宝贵反馈。

**你一定行！🚀**
