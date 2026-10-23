# GitHub Token 获取教程（最简版）

> 5 步快速获取 GitHub Classic Token

---

## 🚀 5 步获取 GitHub Token

### 1️⃣ 打开 Token 设置页面

直接访问：**https://github.com/settings/tokens**

（需要先登录 GitHub）

---

### 2️⃣ 点击生成按钮

点击 **"Generate new token"** → 选择 **"Generate new token (classic)"**

---

### 3️⃣ 填写基本信息

**Note（名称）：** 随便起个名字，比如 `my-token`

**Expiration（过期时间）：** 建议选 `90 days`

---

### 4️⃣ 勾选权限

**最常用配置：** 只勾选这一个

- ✅ **repo** （勾选后会自动选中下面的所有子选项）

这个权限可以访问你所有的公开和私有仓库。

**其他可选权限：**
- `workflow` - 如果需要修改 GitHub Actions
- `gist` - 如果需要创建/修改 Gist
- `delete_repo` - 如果需要删除仓库

---

### 5️⃣ 生成并复制

1. 滚动到页面底部，点击绿色按钮 **"Generate token"**
2. **立即复制显示的 token！**（格式类似：`ghp_xxxxxxxxxxxx...`）
3. 保存到记事本或密码管理器

⚠️ **重要：这个 token 只显示一次，关闭页面后无法再看到！**

---

## 💡 使用 Token

### 方式1：Git 命令行（推荐）

```bash
# 克隆仓库时
git clone https://github.com/username/repo.git

# 第一次会提示输入：
# Username: 输入你的 GitHub 用户名
# Password: 粘贴刚才复制的 token（不是 GitHub 密码！）
```

**之后的操作（push、pull）会自动使用保存的 token。**

---

### 方式2：直接写在 URL 里

```bash
git clone https://YOUR_TOKEN@github.com/username/repo.git
```

将 `YOUR_TOKEN` 替换成你的 token

⚠️ **注意：** 这种方式会在历史记录中暴露 token，不推荐使用

---

## 📝 常见操作示例

### 克隆仓库
```bash
git clone https://github.com/username/repo.git
# 输入用户名和 token
```

### 推送代码
```bash
git add .
git commit -m "Update code"
git push origin main
# 如果之前已保存 token，无需再次输入
```

### 拉取更新
```bash
git pull origin main
```

---

## 🔐 安全提醒

- ⚠️ **Token 等同于密码，请妥善保管**
- ⚠️ **不要将 Token 提交到代码仓库**
- ⚠️ **不要在公开场合分享 Token**
- ⚠️ **如果 Token 泄露，请立即前往 https://github.com/settings/tokens 撤销**

---

## ❓ 常见问题

### Q: Token 忘记了怎么办？
A: Token 只显示一次，忘记了只能重新生成。前往 https://github.com/settings/tokens 删除旧的，创建新的。

### Q: 提示认证失败？
A: 检查：
1. Token 是否正确复制（没有多余空格）
2. Token 是否已过期
3. Token 是否有足够的权限

### Q: 每次都要输入 Token？
A: 配置 credential helper：
```bash
git config --global credential.helper store
```
下次输入后会自动保存。

---

## 🎉 完成！

现在你可以使用这个 token 来：
- ✅ 克隆私有仓库
- ✅ 推送代码
- ✅ 使用 GitHub API
- ✅ 集成第三方工具

**需要更详细的说明？查看 [完整版指南](https://github.com/Y1fe1-Yang)**
