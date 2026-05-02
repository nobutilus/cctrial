# Claude Code お試し環境 (GitHub Codespaces)

GitHub Codespaces も Claude Code も触ったことがない人向けの **遊び場テンプレート** です。  
「Use this template」→「Codespace を作成」の 2 ステップで、数分で Claude Code を試せる環境が手に入ります。

---

## 🚀 はじめかた

### 1. テンプレートからリポジトリを作成する

画面上部の **「Use this template」** → **「Create a new repository」** をクリックし、自分のアカウントにリポジトリを作成します。

> [GitHub テンプレートリポジトリの使い方 (公式ドキュメント)](https://docs.github.com/ja/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template)

### 2. Codespace を起動する

作成したリポジトリで **「Code」** → **「Codespaces」** タブ → **「Create codespace on main」** をクリックします。

数分待つと VS Code がブラウザで開き、Claude Code がすぐ使える状態になります。

> [GitHub Codespaces クイックスタート (公式ドキュメント)](https://docs.github.com/ja/codespaces/quickstart)

### 3. Claude Code を使う

Codespace のターミナルで以下のコマンドを実行します：

```bash
claude
```

初回起動時に認証が求められるので、画面の指示に従って認証を完了してください。  
認証後、ターミナル上で Claude と対話しながらコーディングができます。

---

## 📦 この環境に含まれるもの

| ツール | 説明 |
|--------|------|
| Claude Code | ターミナルから使える AI コーディングアシスタント |
| Git | バージョン管理 |
| GitHub CLI (`gh`) | GitHub 操作用 CLI |
| Bun | JavaScript/TypeScript ランタイム |
| Docker (DooD) | コンテナ実行環境 |

---

## 💡 Claude Code でできること（例）

- 「FizzBuzz を書いて」→ コードを生成してファイルに保存
- 「このコードにテストを追加して」→ テストファイルを自動作成
- 「READMEを日本語に翻訳して」→ ファイルを直接編集
- 「git commit して」→ コミットメッセージ付きでコミット

自由に試してみてください！

---

## ⚠️ 注意事項

- GitHub Codespaces には **月あたりの無料枠** があります。使い終わったら Codespace を停止・削除してください。
- Claude Code の利用には Anthropic アカウントでの認証が必要です（初回のみ）。

---

## 📖 参考リンク

- [GitHub Codespaces ドキュメント](https://docs.github.com/ja/codespaces)
- [Claude Code 公式ドキュメント](https://docs.anthropic.com/en/docs/claude-code)
