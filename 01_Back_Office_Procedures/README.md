# 01 后台操作流程 (Back-Office Procedures)

> 账户创建、模拟账户自助创建、邮箱变更、密码重置、杠杆修改及故障排查的统一作业标准。

---

## 核心要点（基础客服必读）

| 主题 | 核心要点 | 严禁 |
|------|----------|------|
| **1. 账户创建** | KYC/AML 前置校验；KYC 未通过时填写具体原因，引导客户重新上传 | 不核对即开通；口头告知密码 |
| **2. MT5 Live 账户** | 在 Portal 自助创建；MT5 + Classic；凭证发至邮箱；服务器 `AsiaFutureTrading-Server`；Platinum 需 $3,000 | 与 MT5 模拟账户流程混淆 |
| **3. 邮箱变更** | 双邮箱确认链接、24–72 小时冷却期；敏感操作需二次验证 | 未经核验即改绑 |
| **4. 重置密码** | 仅通过系统「忘记密码」链接；邮箱变更 + 密码重置时，需先完成邮箱变更再引导客户在 Portal 修改 | 口头/截图/邮件发送新密码 |
| **5. 杠杆修改** | **必须先确认无持仓**；修改完成后告知账号 ID 与新杠杆倍数 | 未清仓即修改（易导致爆仓） |
| **6. 故障排查** | 三步法：确认现象 → 复现与隔离 → 升级转 IT；记录工单号与预计回复时间 | 无记录即升级；承诺「马上修好」 |
| **7. MT5 模拟账户** | 与真实账户为不同场景；引导客户在 MT5 内自助创建，服务器：`AsiaFutureTrading-Server` | 替客户代为创建 |

---

## 目录

| 序号 | 主题 | 链接 |
|------|------|------|
| 1 | KYC 账户创建 (Account Creation / 口座開設) | [1. 账户创建](plan.html#01-1) |
| 2 | 如何创建 MT5 Live 账户 (MT5 Live Account) | [2. MT5 Live 账户](plan.html#01-2) |
| 3 | 邮箱变更 (Email Change / メール変更) | [3. 邮箱变更](plan.html#01-3) |
| 4 | 重置密码 (Password Reset / パスワード再設定) | [4. 重置密码](plan.html#01-4) |
| 5 | 杠杆修改 (Leverage Change / レバレッジ変更) | [5. 杠杆修改](plan.html#01-5) |
| 6 | 故障排查三步法 (Troubleshooting) | [6. 故障排查](plan.html#01-6) |
| 7 | MT5 模拟账户自助创建 (Demo Account / デモ口座) | [7. MT5 模拟账户](plan.html#01-7) |
| 8 | Zendesk 文档中心快速索引 | [8. Zendesk 文档](plan.html#01-8) |

---

## Zendesk 文档中心（客服快速定位）

官网帮助中心：https://support.afttmarkets.com/

| 分类 | 入口链接 |
|------|----------|
| **Beginner's Guide** 初学者指南 | [Beginner's Guide](https://support.afttmarkets.com/hc/en-au/sections/12436122038671-Beginner-s-Guide) |
| **My Account** 我的账户 | [My Account](https://support.afttmarkets.com/hc/en-au/categories/11339680801167-My-Account) |

→ 完整文章列表见 [8. Zendesk 文档](plan.html#01-8)

---

## 使用说明

- 点击上方链接可在当前页面跳转至对应主题
- 标准回复模版均放在 **📋 复制即用** 代码块中，选中后可直接复制
- **每个项目/场景均预留 中文、日文、英文 (Chinese / Japanese / English)** 三种语言的标准回复
- 需填写处用 `[xxx]` 或 `〇〇` 标注
- **切记：** 回复不同语言客户时，帮助中心（Zendesk）文章链接须使用**客户对应语言版本**（中文 zh-cn / 日文 ja-jp / 英文 en-au）
