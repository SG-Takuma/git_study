# git_study
I will document what I have learned about Git and my achievements.

# Git 学習メモ

## 目的
- Gitの基本操作を理解する
- 個人開発・業務で困らず使えるようになる
- GitHubでの管理に慣れる

## 学習環境
- OS：Windows11
- ターミナル：Cursor/powershell
- リポジトリ管理：GitHub
- 使用ツール：Gig,Github,SorceTree

---

## Gitとは
- ソースコードの**変更履歴を管理**するツール
- 複数人開発やバックアップに必須

### GitとGitHubの違い
- Git：ローカルで動く履歴管理ツール
- GitHub：Gitリポジトリを**クラウドで管理**するサービス

---

## 基本用語
| 用語 | 意味 |
|----|----|
| リポジトリ | ファイルと履歴を管理する場所 |
| ワーキングツリー | 作業中のディレクトリ |
| ステージ | コミット前の待機エリア |
| コミット | 変更履歴の確定 |
| ブランチ | 作業の分岐 |

---

## 基本コマンド一覧

### git init
リポジトリを初期化する
```bash
git init
```

### git status
現在の状態を確認する
```bash
git status
```

### git add
変更をステージに追加
```bash
git add .
```

###git commit
変更を履歴として保存
```bash
git commit -m "コミットメッセージ"
```

##git log
コミット履歴を確認
```bash
git log
```