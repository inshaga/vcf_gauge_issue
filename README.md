# VCF Gauge — 課題管理 / Issue Tracker

船舶補油支援アプリ **VCF Gauge** の課題管理用リポジトリです。
**アプリ本体のソースコードは含まれません。**

> Issue tracker for **VCF Gauge**, an iOS app that supports marine bunkering operations.
> The app's source code is not hosted here.

---

## 📮 不具合の報告・ご要望はこちらから / Report a problem

### → **[報告フォームを開く / Open the form](https://tally.so/r/BzRqyK)**

**GitHubアカウントは不要です。** アプリの「サポート」画面からも同じフォームを開けます。
そちらから開くと、アプリのバージョンと端末の情報が自動で入るので、**どの画面で何をしたかを書くだけ**で送れます。

> **No GitHub account is needed.** The same form opens from the app's Support screen, where
> the app version and device details are filled in automatically.

いただいた内容は開発者のみが確認します（このリポジトリには自動では載りません）。

> Submissions are seen only by the developer and are not posted here automatically.

---

## このリポジトリの使い方 / How this repository is used

フォームで受け取った報告のうち、対応するものを開発者が Issue として起票し、
状況（未着手・対応中・完了）をここで管理しています。
**外部の方が直接 Issue を立てる必要はありません**（そのためのフォームです）。

> The developer files issues here from the reports received through the form, and tracks
> their status. External contributors do not need to open issues directly.

進捗を見たい方は [Issues](../../issues) をご覧ください。

---

## ⚠️ 実データの扱い / About real data

フォーム・Issue のいずれでも、次のものは書かないでください。

- **実際の船名・会社名・BDNの数量**（取引に関わる情報です）
- 乗組員の氏名、連絡先などの個人情報
- 実データの写ったスクリーンショット

数値を示す必要があるときは、**実際と桁が同じダミーの値**に置き換えてください
（例: 実際が `1,847.263 MT` なら `1,000.000 MT` と書く）。
桁が同じであれば、桁数に起因する不具合はそのまま再現できます。

> Whether in the form or in an issue, please do not include real vessel or company names,
> BDN quantities, personal information, or screenshots containing real data. If you need to
> show a number, replace it with a dummy value **of the same magnitude** — that is enough to
> reproduce digit-related problems.

---

## 返信について / Response

個人開発のため、返信までに日数をいただくことがあります。
また、洋上で使うアプリという性質上、報告者の方もすぐには返信を確認できない前提で運用しています。

> This is a personally developed app. Replies may take a while.

---

## プライバシー / Privacy

VCF Gauge は**完全にオフラインで動作**します。入力された記録は端末内にのみ保存され、
外部のサーバーへ送信されることはありません。
情報が外へ出るのは、**利用者ご自身が報告フォームに書いたときだけ**です。

> VCF Gauge works entirely offline. Records are stored only on the device and are never sent
> to any server. Information leaves the app only when a user writes it in the report form.
