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

## 4.3 MT5 交易账户密码重置详细步骤

适用于客户在**会员后台（Client Portal）**自助重置 MT5 主密码或只读密码。分两种入口：**「忘记密码」**（系统发邮件通知新密码）与**「修改密码」**（已知当前密码时直接修改）。

### 操作步骤（详细）

| 步骤 | 动作 | 备注 |
|------|------|------|
| 1 | 登录**会员页面（Client Portal）** | https://portal.asiafuturetrading.com/ |
| 2 | 在菜单中点击 **「口座」(Accounts)** | 进入账户列表 |
| 3 | 选择需要重置密码的 **MT5 交易账户** | 点击该账户行 |
| 4 | 点击 **「操作」(Action)** 或设置图标，选择 **「パスワードを忘れた場合」/「忘记密码」** 或 **「修改密码」(Change Password)** | 忘记密码：提交后系统发邮件通知新密码；修改密码：需输入新密码并保存 |
| 5 | （若为忘记密码）选择要重置的密码类型 | **主密码 (Master/マスターパスワード)** 或 **只读密码 (Investor/閲覧専用パスワード)** |
| 6 | 提交重置请求 | 若为「忘记密码」，提交后等待邮件；若为「修改密码」，直接保存即可 |

**※ 注意：** 重置完成后，系统会向**注册邮箱**发送通知。若未收到，请客户检查垃圾邮件文件夹。收到邮件后，请使用新密码登录 MT5。

---

### 📋 复制即用 · 中文（MT5 密码重置引导）

```
〇〇 先生/女士：

感谢您提供账户编号（520101）的信息。

以下为交易账户（MT5）密码重置步骤，请按下列流程操作。

【交易账户密码重置步骤】

1. 登录会员页面（客户门户）：https://portal.asiafuturetrading.com/
2. 在菜单中点击「账户」(Accounts)。
3. 选择需要重置密码的 MT5 交易账户。
4. 点击「操作」(Action) 或设置图标，选择「忘记密码」。
5. 选择要重置的密码类型（主密码 / 只读密码）。
6. 提交重置请求。

※ 注意：重置完成后，系统会向您注册的邮箱发送通知。若未收到邮件，请检查垃圾邮件文件夹。收到邮件后，请使用新密码登录。

如有任何疑问，请随时与我们联系。
谢谢。
```

### 📋 复制即用 · 日文（MT5 密码重置引导）

```
XX 様

口座番号（520101）のご連絡ありがとうございます。
取引口座（MT5）のパスワード再設定手順をご案内いたします。

お手数ですが、以下の手順に沿ってお手続きをお願い申し上げます。

【取引口座パスワードの再設定手順】

**会員ページ（クライアントポータル）**にログインします。
（https://portal.asiafuturetrading.com/）

メニューから**「口座（Accounts）」**をクリックします。

パスワードを再設定したい対象のMT5口座を選択します。

**「操作（Action）」または設定アイコンをクリックし、「パスワードを忘れた場合」**を選択します。

再設定するパスワードの種類（マスターパスワード / 閲覧専用パスワード）を選択します。

リセットのリクエストを送信します。

※ご注意：
変更が完了すると、ご登録のメールアドレスに通知が届きます。メールが届かない場合は、迷惑メールフォルダもご確認ください。メールを確認後、新しいパスワードでログインをお試しください。

ご不明な点がございましたら、お気軽にお問い合わせください。
よろしくお願い申し上げます。
```

*口座番号（520101）与 XX 様 请按实际客户信息替换。*

### 📋 复制即用 · 英文 (English)（MT5 密码重置引导）

```
Dear Mr./Ms. 〇〇,

Thank you for providing your account number (520101).

Please find below the steps to reset your trading account (MT5) password. We ask that you follow the procedure below.

【Trading Account Password Reset Steps】

1. Log in to the **Client Portal**: https://portal.asiafuturetrading.com/
2. Click **"Accounts"** in the menu.
3. Select the MT5 trading account for which you wish to reset the password.
4. Click **"Action"** or the settings icon, then select **"Forgot Password."**
5. Select the type of password to reset (Master Password / Investor [Read-Only] Password).
6. Submit the reset request.

※ Please note: Once the change is complete, a notification will be sent to your registered email address. If you do not receive the email, please check your spam or junk folder. After confirming the email, please try logging in with your new password.

If you have any questions, please do not hesitate to contact us.
Thank you for your cooperation.
```

*Replace account number (520101) and salutation with the actual client details.*

---

## 4.4 场景：邮箱变更与 MT5 密码重置（需先完成邮箱变更）

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
