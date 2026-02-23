# 5. 出金标准场景 (Withdrawal Scenarios / 出金標準シナリオ)

> 出金业务涉及合规（AML 反洗钱）与风控（保证金）。回复要点：**明确告知规则、原因及下一步操作**。

---

## 5.1 安全原则

| 要点 | 说明 |
|------|------|
| **原路返回** | 出金方式须与入金方式一致（AML 硬性规定）；拒绝前必须写明客户入金方式，并指引其重选 |
| **保证金核实** | 有持仓时出金可导致强平；拒绝前须确认可用保证金/持仓状态，说明原因并给出平仓或减额路径 |
| **时效说明** | 审核 1–3 工作日、汇出后法币 3–5 工作日；不承诺具体到账时间 |
| **已打款口径** | 后台已 Approved 时，不得否认打款；可说明通道延迟并承诺超时可提供凭单 |

> [!CAUTION]
> 不得在未核实入金方式的情况下拒绝原路返回类出金。不得在未确认持仓/保证金的情况下拒绝出金而不说明具体原因。

---

## 5.2 话术建议

| 场景 | 推荐用语 | 禁忌用语 |
|------|----------|----------|
| 已受理 | 「1–3 工作日完成审核，处理完成后资金将汇出。如有异常会邮件通知。」 | 承诺具体到账时间 |
| 持仓/保证金不足 | 「您账户有未平仓订单，出金将导致可用保证金不足、触发强平风险。请平仓或减额后重新申请。」 | 「不能出金」不说明原因 |
| 原路返回 | 「AML 规定出金须与入金方式一致。您入金为 [USDT/信用卡等]，请选择相同方式重新申请。」 | 不写明入金方式即拒绝 |
| 已汇出未到账 | 「已于 [日期] 汇出。法币 3–5 工作日 / 加密货币可能延迟。超时可提供凭单。」 | 否认已打款、推责给客户 |

---

## 5.3 场景一：出金申请已受理，审核处理中

**适用情况**：客户提交了出金申请并催促进度。告知标准处理时效以安抚客户。

### 📋 复制即用 · 中文

```
〇〇 先生/女士：

您好。我们已收到您的出金申请，目前相关财务部门正在进行审核处理。

通常情况下，出金审核及处理需要 **1–3 个工作日**。一旦处理完成，资金将被汇出，请您耐心等待。

如有任何异常情况，我们会第一时间通过邮件通知您。感谢您的理解与支持。
```

### 📋 复制即用 · 日文

```
〇〇 様

お世話になっております。お客様からの出金申請を無事に受領し、現在、担当部署にて審査および処理を行っております。

通常、出金処理には **1〜3 営業日** ほどお時間をいただいております。処理が完了し次第、速やかに資金が送金されますので、今しばらくお待ちくださいませ。

万が一確認事項等が発生した場合は、速やかにメールにてご連絡いたします。ご理解のほどよろしくお願い申し上げます。
```

### 📋 复制即用 · 英文 (English)

```
Dear Mr./Ms. 〇〇,

Thank you for your withdrawal request. We have received it and our finance team is currently reviewing and processing it.

Withdrawal review and processing typically takes **1–3 business days**. Once completed, the funds will be sent. We ask for your patience.

If any issue arises, we will notify you by email as soon as possible. Thank you for your understanding and support.
```

---

## 5.4 场景二：出金被拒 —— 账户内有持仓 / 可用保证金不足

**适用情况**：客户在有未平仓订单（Open Positions）的情况下申请出金，导致可用保证金不足，申请被拒以防止爆仓。

### 📋 复制即用 · 中文

```
〇〇 先生/女士：

您好。关于您的出金申请，很抱歉未能通过审核。

经查，由于您的交易账户内目前**仍有未平仓的订单**，提取该笔资金将导致您的可用保证金比例过低，存在触发强制平仓的风险。

为了保障您的账户安全，麻烦您**在平仓所有订单后，或调整出金金额（确保留有足够的可用保证金）**，再次提交出金申请。
```

### 📋 复制即用 · 日文

```
〇〇 様

お世話になっております。ご申請いただいた出金の件ですが、誠に恐れ入りますが今回は審査を見送らせていただきました。

お調べしたところ、現在お客様の口座に**保有中のポジション（未決済建玉）**があり、このまま出金されますと有効証拠金が不足し、ロスカット（強制決済）のリスクが生じるためです。

お客様の口座の安全を確保するため、**全てのポジションを決済されるか、出金希望額を減額（十分な余剰証拠金を残す）**した上で、改めてご申請いただけますでしょうか。
```

### 📋 复制即用 · 英文 (English)

```
Dear Mr./Ms. 〇〇,

We are sorry to inform you that your withdrawal request could not be approved.

Our review shows that your trading account currently **has open positions**. Withdrawing the requested amount would leave your available margin too low and could trigger forced liquidation (stop-out).

To protect your account, please **either close all open positions or reduce the withdrawal amount** so that sufficient available margin remains, then submit a new withdrawal request.
```

---

## 5.5 场景三：出金被拒 —— 违反「原路返回」规则（反洗钱规定）

**适用情况**：客户用 USDT 入金却申请法币出金，或用 A 银行卡入金却申请提现到 B 银行卡。

### 📋 复制即用 · 中文

```
〇〇 先生/女士：

您好。您的出金申请已被退回。

根据国际反洗钱（AML）及金融安全规定，**出金方式必须与您的入金方式保持一致（即原路返回）**。

经核实，您之前的入金是通过 **[填写此前的入金方式，如：USDT / 信用卡]** 完成的。

请您在出金页面选择相同的支付方式并重新提交申请。给您带来不便敬请谅解。
```

### 📋 复制即用 · 日文

```
〇〇 様

お世話になっております。ご申請いただいた出金の件ですが、お手続きを差し戻しとさせていただきました。

国際的なマネーロンダリング防止（AML）およびセキュリティの規定により、**出金方法は入金時と同じ方法（同一ルートでの返金）である必要がございます**。

確認いたしましたところ、お客様の入金は **[入金方法を記入：例：USDT / クレジットカード]** で行われております。

お手数ですが、出金ページより入金時と同じ決済方法をご選択の上、再度ご申請をお願いいたします。ご不便をおかけしますが、何卒ご了承ください。
```

### 📋 复制即用 · 英文 (English)

```
Dear Mr./Ms. 〇〇,

Your withdrawal request has been returned.

Under international anti-money laundering (AML) and financial security rules, **the withdrawal method must match the method used for your deposit (same route / like-for-like)**.

We have verified that your previous deposit was made via **[fill in: e.g. USDT / credit card]**.

Please select the same payment method on the withdrawal page and submit your request again. We apologize for any inconvenience.
```

---

## 5.6 场景四：出金已汇出，但客户反馈未到账

**适用情况**：后台显示已打款（Approved），但客户表示银行卡或加密钱包尚未收到。需说明通道延迟。

### 📋 复制即用 · 中文

```
〇〇 先生/女士：

您好。经核实，您的出金申请已于 **[填写日期，如：2月20日]** 在我司后台处理完毕，资金已成功汇出。

· **法币出金**：受跨国银行清算及中转行处理时间影响，资金通常需要 **3–5 个工作日** 才能到达您的收款账户。
· **虚拟货币出金**：受区块链网络拥堵程度影响，到账可能存在一定延迟。

麻烦您再耐心等待一下。若超过上述时间仍未到账，请随时联系我们，我们将为您提供汇款凭单以便您向收款方查询。
```

### 📋 复制即用 · 日文

```
〇〇 様

お世話になっております。確認いたしましたところ、お客様の出金申請は **[日付を記入：例：2月20日]** に弊社側での処理が完了し、既に資金の送金手続きが行われております。

· **法定通貨の場合**：経由銀行や受取銀行の処理状況により、お客様の口座へ反映されるまで **3〜5 営業日** ほどかかる場合がございます。
· **暗号資産の場合**：ブロックチェーンの混雑状況により、着金に遅延が生じる場合がございます。

恐れ入りますが、もうしばらくお待ちいただけますでしょうか。万が一、上記の日数を過ぎても着金が確認できない場合は、送金証明書を発行いたしますので、いつでもお申し付けください。
```

### 📋 复制即用 · 英文 (English)

```
Dear Mr./Ms. 〇〇,

We have verified that your withdrawal was processed on our side on **[fill in date, e.g. 20 February]** and the funds have been sent successfully.

· **Fiat withdrawals**：Due to cross-border bank clearing and correspondent processing, it typically takes **3–5 business days** for the funds to reach your receiving account.
· **Cryptocurrency withdrawals**：Depending on blockchain congestion, there may be a delay before the funds are credited.

We ask for your patience. If the funds have not arrived after the above period, please contact us and we can provide a remittance certificate for you to follow up with your bank or wallet provider.
```

---

## 5.7 话术要点

| 场景 | 关键信息 | 禁忌 |
|------|----------|------|
| 已受理 | 1–3 工作日、完成后汇出、异常会邮件通知 | 承诺具体到账时间 |
| 持仓/保证金不足 | 未平仓导致可用保证金不足、强平风险；平仓或减额后重申请 | 「不能出金」不说明原因 |
| 原路返回 | AML 规定、出金须与入金方式一致；写明其入金方式并请重选 | 不填写入金方式即拒绝 |
| 已汇出未到账 | 已打款日期；法币 3–5 工作日 / 加密货币可能延迟；超时可提供凭单 | 否认已打款、推责给客户 |
