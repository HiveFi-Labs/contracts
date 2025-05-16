# HiveFi Contracts

このリポジトリには、HiveFiプロジェクトの各種スマートコントラクトが含まれています。

## プロジェクト構成

- `ingredients/` - Solanaのコンフィデンシャル転送機能の実装コンポーネント
- `recipes/` - コンフィデンシャル転送のテスト実行シーケンス
- `utils/` - ユーティリティ関数

## Confidential Tokens

<img src="https://github.com/user-attachments/assets/02292d9c-1da1-492a-9bad-286698b59783" width="500" />

Solanaのコンフィデンシャル転送機能を利用したトークン実装です。
このリポジトリには、[Token Program CLI](https://github.com/solana-program/token-2022/tree/969cff212c0e0add812932e50f6771933f14ff5c/clients/cli)に類似したコンフィデンシャル転送フローを実装しています。

## セットアップ

以下の手順でセットアップを行ってください：

1. `.env.example`ファイルを`.env`にコピーします
2. 必要に応じて`.env`ファイルを編集します
3. `cargo build`を実行します 