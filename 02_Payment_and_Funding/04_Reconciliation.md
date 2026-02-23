# 4. 未到账对账标准 (Reconciliation for Unreceived Funds / 未着金照合基準)

> 入金问题常用标准场景：正在核实、法币未到账说明、索要支付凭证。适用于加密货币与法币入金。

---

## 4.1 安全原则

| 要点 | 说明 |
|------|------|
| **核实前不承诺到账** | 未在后台确认到账前，不可承诺「已到账」或具体到账时间 |
| **凭证真实性** | TXID、截图须可溯源；切勿接受模糊、裁剪过度或无法核验的凭证 |
| **时效说明** | 法币 1–3 工作日、加密货币视网络而定；超时再索要凭证，避免过早打扰客户 |
| **升级路径** | 客户提供凭证后仍无法核对的，记录工单号并转财务/支付渠道专项调查 |

> [!CAUTION]
> 不得在未核实的情况下告知客户「资金已丢失」或「无法找回」。链选错等极端情况需转技术/风控确认后再答复。

---

## 4.2 话术建议

| 场景 | 推荐用语 | 禁忌用语 |
|------|----------|----------|
| 正在核实 | 「我们正在与财务部门核实，着金确认后将立即为您入账并通知。」 | 「再等等」「我们也不知道」 |
| 法币未到账 | 「法币通常需 1–3 个工作日。超时后请提供带姓名、金额、日期、流水号的凭证。」 | 「肯定丢了」「银行的问题」 |
| 索要凭证 | 「为加快核实，请提供 TXID（虚拟货币）或支付成功截图（法币）。收到后立即提交调查。」 | 「你发个图过来」不说明用途 |

---

## 4.3 场景一：入金正在核实中（需客户等待）

**适用情况**：客户催促资金为何没到账，客服已上报给后台或支付渠道，正在排查中。

### 📋 复制即用 · 中文

```
您好。

关于您的入金申请，我们目前正在与相关财务部门（及支付服务商）进行核实。

由于区块链网络的确认拥堵或系统数据的同步可能需要一些时间，麻烦您耐心等待。一旦核实到账，我们将立即为您处理入账并通知您。

感谢您的理解与配合。
```

### 📋 复制即用 · 日文

```
お世話になっております。

お客様の入金申請につきまして、現在担当部署（および決済プロバイダー）にて確認作業を行っております。

ブロックチェーンネットワークの混雑やシステムの同期にお時間をいただく場合がございますので、恐れ入りますが今しばらくお待ちください。着金が確認でき次第、速やかに口座へ反映し、ご連絡させていただきます。

ご理解とご協力のほど、よろしくお願い申し上げます。
```

### 📋 复制即用 · 英文 (English)

```
Hello.

Regarding your deposit, we are currently verifying it with the relevant finance team (and the payment provider).

Blockchain confirmation or system synchronization may take some time. We ask for your patience. Once the deposit is confirmed, we will credit your account and notify you without delay.

Thank you for your understanding and cooperation.
```

---

## 4.4 场景二：法币入金尚未到账（说明时效性）

**适用情况**：客户使用银行电汇、信用卡或当地支付（如 Peska）入金，这类支付有固定的清算时间。

### 📋 复制即用 · 中文

```
您好。

关于您反馈的法币入金，我们目前尚未在系统中查询到该笔款项。

通常情况下，法币转账可能需要 **1–3 个工作日** 才能到达我们的清算账户（周末及法定节假日除外）。

如果超过该时间仍未到账，麻烦您提供【带有付款人姓名、金额、日期和流水号的转账凭证/截图】，以便我们向支付渠道作进一步专项调查。
```

### 📋 复制即用 · 日文

```
お世話になっております。

法定通貨でのご入金につきまして、現在弊社システムにて着金が確認できておりません。

通常、法定通貨の送金手続きには、弊社の口座に反映されるまで **1〜3 営業日程度**（土日祝日を除く）かかる場合がございます。

もし上記の期間を過ぎても反映されない場合は、お手数ですが調査のために【お振込名義人、金額、日付、取引番号が確認できる送金明細（またはスクリーンショット）】をご提出いただけますでしょうか。
```

### 📋 复制即用 · 英文 (English)

```
Hello.

Regarding your fiat deposit, we have not yet been able to confirm receipt of the funds in our system.

Fiat transfers typically take **1–3 business days** (excluding weekends and public holidays) to reach our settlement account.

If the funds have not been reflected after this period, please provide 【a transfer receipt or screenshot showing the payer name, amount, date, and transaction/reference number】 so we can conduct a follow-up investigation with the payment channel.
```

---

## 4.5 场景三：要求客户提供支付凭证 (TXID / 截图)

**适用情况**：资金去向不明，需要客户提供转账证据以便追踪。

### 📋 复制即用 · 中文

```
您好。

为了加快为您核实入金进度，麻烦您提供该笔交易的详细凭证：

· 虚拟货币入金：请提供 **【交易哈希值 (TXID / Hash)】**
· 法币或其他方式入金：请提供 **【完整的支付成功截图】**

收到您的凭证后，我们将立即提交给相关部门进行追踪排查。
```

### 📋 复制即用 · 日文

```
お世話になっております。

お客様のご入金状況を早急に調査するため、該当取引の詳細がわかる証明書類のご提出をお願いいたします。

· 暗号資産（仮想通貨）のご入金：**【トランザクションID（TXID / ハッシュ値）】** をお送りください
· その他の決済方法：**【支払完了が確認できるスクリーンショット】** をお送りください

ご提出いただき次第、担当部署にて至急追跡調査を進めさせていただきます。
```

### 📋 复制即用 · 英文 (English)

```
Hello.

To speed up verification of your deposit, please provide proof of the transaction:

· Cryptocurrency deposits: **【Transaction ID (TXID / Hash)】**
· Fiat or other payment methods: **【Screenshot showing successful payment】**

Once we receive your proof, we will submit it to the relevant team for tracking and investigation.
```
