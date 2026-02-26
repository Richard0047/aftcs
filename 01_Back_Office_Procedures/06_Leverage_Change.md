# 6. 杠杆修改 (Leverage Change / レバレッジ変更)

---

## 6.1 风险控制要点

| 要点 | 说明 |
|------|------|
| 持仓检查 | 修改前必须确认该账户下**无未平仓订单 (Open Position / 建玉)** |
| 风险告知 | 向客户说明杠杆倍数与强平 (Margin Call / ロスカット) 的关系，并记录客户确认 |
| 冷静期 | 部分司法辖区要求修改后 X 小时内不可再次调高杠杆 |

> [!CAUTION]
> 未清仓即修改杠杆可能导致强平线重算、客户瞬间爆仓。操作前必须在后台确认「当前持仓」与「可用杠杆变更」的兼容性，否则禁止提交。

---

## 6.2 话术建议

| 类型 | 推荐用语 | 禁忌用语 |
|------|----------|----------|
| 修改前 | 「调高杠杆会提高强平风险。请您确认当前无持仓或已知晓风险后，我们再为您提交申请。」 | 「改杠杆没风险」「随便改」 |
| 修改后 | 「杠杆已按您的要求调整，请留意保证金与强平距离，谨慎交易。」 | 不提示风险 |

---

## 6.3 场景：申请修改交易杠杆

回复核心在于强调**「无持仓」(No Open Position / 保有中ポジションなし)** 这一硬性条件，以防修改过程中因保证金比例突变导致客户爆仓。

### 6.3.1 确认前提（要求客户检查持仓）

### 📋 复制即用 · 中文

```
〇〇 先生/女士

收到您的杠杆修改申请。为了确保账户安全，修改杠杆的前提是您的账户内不能有任何正在持有的仓位（持仓）。
麻烦请先确认并平仓，随后告知我您的**「交易账号（登录ID）」以及您希望调整到的「杠杆倍数（如 1:500）」**，我将立即为您处理。
```

### 📋 复制即用 · 日文

```
〇〇 様

レバレッジ変更のご依頼、承知いたしました。
変更のお手続きにあたり、「口座内に保有中のポジション（注文）」がないことが必須条件となります。

お手数ですが、全てのポジションを決済（平倉）された後、対象の**「取引口座番号（ログインID）」とご希望の「レバレッジ倍率（例：1:500）」**をこちらに返信いただけますでしょうか。
確認が取れ次第、速やかに対応させていただきます。
```

### 📋 复制即用 · 英文 (English)

```
Dear Mr./Ms. 〇〇,

We have received your leverage change request. For account security, a prerequisite for changing leverage is that your account must have no open positions.

Please confirm and close all positions, then reply with your **"Trading Account Number (Login ID)"** and your **"desired leverage ratio (e.g., 1:500)"**. We will process your request as soon as we receive this information.
```

---

### 6.3.2 修改完成告知

### 📋 复制即用 · 中文

```
〇〇 先生/女士

您好。您的交易账号 [账号ID] 的杠杆已成功调整为 [杠杆倍数]。
您现在可以登录 MT5 确认或继续交易。如有其他需要，请随时联系我们。
```

### 📋 复制即用 · 日文

```
〇〇 様

お世話になっております。
対象の口座 [口座番号] のレバレッジ変更が完了し、現在は [倍率] に設定されております。

MT5 にてご確認のうえ、お取引を再開していただけます。
また何かございましたら、お気軽にお問い合わせください。
```

### 📋 复制即用 · 英文 (English)

```
Dear Mr./Ms. 〇〇,

Hello. The leverage for your trading account [Account ID] has been successfully adjusted to [Leverage Ratio].
You may now log in to MT5 to confirm and continue trading. If you need any further assistance, please do not hesitate to contact us.
```
