# Bunker App — お問い合わせ・不具合報告 / Issue Tracker

このリポジトリは、船舶補油支援アプリ **Bunker App** の**お問い合わせ窓口**です。
不具合の報告と機能のご要望を [Issues](../../issues) で受け付けています。

**アプリ本体のソースコードはここには含まれません。**

> This repository is the issue tracker for **Bunker App**, an iOS app that supports
> marine bunkering operations. Bug reports and feature requests are accepted in
> [Issues](../../issues). The app's source code is not hosted here.

---

## 報告のしかた / How to report

1. まず [Issues](../../issues) を開き、**同じ内容が既に報告されていないか**を確認してください
2. 無ければ **New issue** を押し、「不具合の報告」か「機能のご要望」を選んでください
3. 表示される項目を埋めて送信してください

> 1. Check [Issues](../../issues) first — the same thing may already be reported.
> 2. If not, press **New issue** and choose "Bug report" or "Feature request".
> 3. Fill in the form and submit.

---

## ⚠️ 書かないでほしいこと / Please do not include

Issue は**誰でも読める公開の場**です。次のものは書かないでください。

- **実際の船名・会社名・BDNの数量**（取引に関わる情報です）
- 乗組員の氏名、連絡先などの個人情報
- 実データの写ったスクリーンショット

数値を示す必要があるときは、**実際と桁が同じダミーの値**に置き換えてください
（例: 実際が `1,847.263 MT` なら `1,000.000 MT` と書く）。
桁が同じであれば、桁数に起因する不具合はそのまま再現できます。

> Issues are **public**. Do not post real vessel or company names, BDN quantities,
> personal information, or screenshots containing real data. If you need to show a
> number, replace it with a dummy value **of the same magnitude** — that is enough to
> reproduce digit-related problems.

---

## 添えていただけると助かること / What helps

- **アプリのバージョン**（アプリ内 サポート → アプリについて → バージョン）
- **どの画面で、どの操作をしたか**（例: ダッシュボード → 記録の入力 → 「この記録を保存」）
- **どうなると思ったか / 実際にどうなったか**
- 端末（例: iPhone 15 Pro）と iOS のバージョン

> The app version (Support → About → Version), which screen and which action, what you
> expected versus what happened, and your device and iOS version.

---

## 返信について / Response

個人開発のため、返信までに日数をいただくことがあります。
また、洋上で使うアプリという性質上、報告者の方もすぐには返信を確認できない前提で運用しています。

> This is a personally developed app. Replies may take a while.

---

## プライバシー / Privacy

Bunker App は**完全にオフラインで動作**します。入力された記録は端末内にのみ保存され、
外部のサーバーへ送信されることはありません。
このリポジトリに情報が載るのは、**利用者ご自身が Issue に書いたときだけ**です。

> Bunker App works entirely offline. Records are stored only on the device and are never
> sent to any server. Information appears in this repository only when a user writes it
> in an issue themselves.
