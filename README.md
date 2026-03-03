# Git 07: Fork / Clone (SSH) Practice Repo

このリポジトリは、授業「07：GitHub導入（登録＋clone/push/pull）」用です。  
やることは **fork → SSHでclone → origin確認 → VSCodeで開く** です。

---

## 0. 今日のゴール
- GitHubにログインできる
- SSH鍵を登録して、`ssh -T git@github.com` が成功する
- 自分のアカウントに **fork** できる
- 自分のforkしたrepoを **SSHでclone** できる
- `git remote -v` で **origin** を確認できる
- `code .` でVSCodeを開ける

---

## 1. Fork（GitHub上の操作）
1. このリポジトリ（om036702/gitrefrepo）を開く
2. 右上の **Fork** を押す
3. 自分のアカウント配下に repo ができたらOK

---

## 2. SSH接続チェック（ターミナル）
SSH鍵の登録ができたら、次で確認します。

```bash
ssh -T git@github.com
