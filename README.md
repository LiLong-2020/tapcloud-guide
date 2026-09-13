# Tapcloud 使用指南与邀请码网站

这是一个适合部署到 GitHub Pages 的纯静态网站，用于展示 Tapcloud 使用教程、设备导入说明、FAQ、推广披露与免责声明。

## 文件说明

- `index.html`：网站主页面
- `styles.css`：页面样式

## 上线前必须修改

当前已经使用你的真实 Tapcloud 邀请链接：`https://tapcloud.me/web/#/login?code=qbuZflSl`。如以后更换邀请码，再替换 `index.html` 中的该链接。

如果你有固定邀请码，也可以把首页按钮旁边的提示文案改成：

```text
邀请码：你的邀请码
```

## GitHub Pages 发布步骤

1. 创建 GitHub 仓库，例如：`tapcloud-guide`
2. 上传本目录中的 `index.html` 和 `styles.css`
3. 进入仓库 `Settings` → `Pages`
4. Source 选择 `Deploy from a branch`
5. Branch 选择 `main`，目录选择 `/root`
6. 保存后等待几分钟
7. 访问：`https://你的用户名.github.io/tapcloud-guide/`

## 合规提醒

- 不要托管 VPN 客户端安装包、破解工具、账号密码、订阅链接或节点配置。
- 不要冒充 Tapcloud 官方。
- 保留页面中的推广披露和免责声明。
- 用户需自行遵守所在地法律法规。
