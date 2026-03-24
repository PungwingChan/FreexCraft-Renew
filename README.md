# FreeXCraft 自动续期

自动登录 freexcraft.com，每2小时续期服务器。

流程：登录 → 续期 → 获取服务器信息 → TG 通知

---

## Secrets 配置

| Secret | 格式 | 说明 | 必填 |
|--------|------|------|------|
| `FXC_ACCOUNT` | `email,password` | 登录账号 | ✅ |
| `TG_BOT` | `chat_id,bot_token` | Telegram 通知 | ⬜ |
| `GOST_PROXY` | `socks5://user:pass@host:port` | 代理 | ⬜ |
