# 4. 重置密码 (Password Reset / パスワード再設定)

---

## 4.1 安全原则

| 要点 | 说明 |
|------|------|
| 唯一入口 | 仅通过「忘记密码」链接或客服内网发起重置，禁止将新密码以明文形式通过邮件/聊天发送 |
| 一次性链接 | 重置链接有效期不超过 1 小时，单次使用后失效 |
| 通知 | 重置成功后向注册邮箱/手机发送通知，便于客户发现异常 |

> [!CAUTION]
> 任何情况下不得向客户口头告知、粘贴或截图发送新密码。若客户坚持「需要密码」，引导其使用「忘记密码」自助流程或核实身份后由系统发送重置链接。

---

## 4.2 话术建议

| 类型 | 推荐用语 | 禁忌用语 |
|------|----------|----------|
| 引导 | 「您可通过登录页的『忘记密码』获取重置链接，链接将发至您注册邮箱，有效期为 1 小时。」 | 「新密码是 xxx」「我帮您设成 123456」 |
| 异常 | 「检测到您账户有安全风险，我们已暂时锁定登录。请按邮件指引完成身份验证后重置密码。」 | 直接代为重置并告知密码 |

### 标准回复（中文 / 日文 / 英文）

| 场景 | 中文 | 日文 | 英文 (English) |
|------|------|------|----------------|
| 引导 | 您可通过登录页的「忘记密码」获取重置链接，链接将发至您注册邮箱，有效期为 1 小时。 | ログイン画面の「パスワードをお忘れですか」よりリセットリンクを取得できます。リンクは登録メールに送信され、1時間有效です。 | You may obtain a reset link via "Forgot Password" on the login page. The link will be sent to your registered email and is valid for 1 hour. |
| 异常 | 检测到您账户有安全风险，我们已暂时锁定登录。请按邮件指引完成身份验证后重置密码。 | お客様のアカウントにセキュリティリスクを検出しました。ログインを一時的にロックしております。メールの案内に従い本人確認を完了のうえ、パスワードを再設定してください。 | We have detected a security risk on your account and temporarily locked your login. Please complete identity verification as instructed in the email and reset your password. |

---

## 4.3 场景：邮箱变更与 MT5 密码重置（需先完成邮箱变更）

客户同时申请邮箱变更与 MT5 主密码重置时，因安全考虑**无法直接查询或重发原始密码**。需引导客户在**邮箱变更完成后**，登录会员后台自助修改 MT5 密码。

### 操作步骤

| 步骤 | 动作 |
|------|------|
| 1 | 登录会员后台：https://portal.asiafuturetrading.com/ |
| 2 | 点击菜单「账户」(Accounts) |
| 3 | 选择需重置密码的 MT5 交易账户 |
| 4 | 点击「操作」(Action) 或设置图标，选择「修改密码」(Change Password) |
| 5 | 输入新密码并保存 |

> ※ 邮箱变更完成后，新邮箱会收到通知邮件，请客户收到后再操作。

### 📋 复制即用 · 中文

```
〇〇 先生/女士

您好。这里是 AFTT 客户中心。
关于您申请变更邮箱以及重置主密码的事宜，回复如下：

出于安全考虑，我司无法直接查询并重发您的原始密码。
麻烦请在邮箱变更完成后，登录会员后台按照以下步骤重新设置密码：

【交易账户密码重置步骤】

1. 登录会员后台（https://portal.asiafuturetrading.com/）。
2. 点击菜单中的「账户」(Accounts)。
3. 点击您需要重置密码的对应交易账户 (MT5 账户)。
4. 点击「操作」(Action) 或设置图标，选择「修改密码」(Change Password)。
5. 输入新密码并保存。

※ 当邮箱变更完成后，您的新 Gmail 邮箱会收到通知邮件，请在那之后进行操作。

如果操作过程中有任何不明之处，请随时联系我们。
请多多关照。
```

### 📋 复制即用 · 日文

```
〇〇 様

お世話になっております。AFTT カスタマーサポートでございます。
メールアドレスの変更申請およびメインパスワードの再設定について、以下の通りご案内申し上げます。

セキュリティ保護の観点から、弊社よりパスワードを直接お調べして再送することができかねます。
恐れ入りますが、メールアドレスの変更完了後に、クライアントポータルより以下の手順でパスワードの再設定をお願いいたします。

【取引口座パスワードの再設定手順】

1. クライアントポータル（https://portal.asiafuturetrading.com/）にログインします。
2. メニューの「アカウント」をクリックします。
3. パスワードを再設定したい該当の取引口座（MT5口座）を選択します。
4. 「アクション」（または設定アイコン）をクリックし、「パスワードの変更」（Change Password）を選択します。
5. 新しいパスワードを入力し、保存してください。

※ メールアドレスの変更が完了したタイミングで、新しい Gmail アドレス宛に通知が届きますので、それまで今しばらくお待ちください。

操作方法にご不明な点がございましたら、お気軽にお問い合わせください。
何卒よろしくお願い申し上げます。
```

### 📋 复制即用 · 英文 (English)

```
Dear Mr./Ms. 〇〇,

Hello. This is AFTT Customer Support.
Regarding your request to change your email address and reset your main password, please find our response below:

For security reasons, we are unable to look up or resend your original password.
Please log in to the Client Portal after your email change is complete and follow the steps below to reset your password:

【Trading Account Password Reset Steps】

1. Log in to the Client Portal (https://portal.asiafuturetrading.com/).
2. Click "Accounts" in the menu.
3. Select the trading account (MT5 account) for which you wish to reset the password.
4. Click "Action" (or the settings icon) and select "Change Password."
5. Enter your new password and save.

※ Once your email change is complete, a notification will be sent to your new Gmail address. Please proceed with the above steps after receiving this notification.

If you have any questions during the process, please do not hesitate to contact us.
Thank you for your understanding.
```
