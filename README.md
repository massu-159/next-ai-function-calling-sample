

# next-ai-function-calling-sample
OpenAIのAPIを利用したお天気アプリ。Function Calling学習のために作成。
Next.js
UIには、TailwindCSSのライブラリである[shadcn/ui](https://ui.shadcn.com/)を使用。

urlはこちら
https://github.com/massu-159/next-ai-function-calling-sample


## 目次
1. 環境構築
2. アプリケーションの仕様
3. 環境変数

## 1. 環境構築

### 1-1. ライブラリ インストール

```Bash
npm install

または

yarn
```

### 1-2. アプリケーション実行

```Bash
npm run dev

または

yarn dev
```

## 2. アプリケーションの仕様

### 2-1. 仕様
- chat
  - チャット投稿
  - AIによる返答自動生成
  - 関数呼び出し

### 2-2. 構成技術
- axios: ^1.4.0,
- eslint: 8.46.0,
- moment-timezone: ^0.5.43,
- next: 13.4.12,
- openai: ^3.3.0,
- react: 18.2.0,
- react-hook-form: ^7.45.4,
- tailwindcss: 3.3.3,
- typescript: 5.1.6,
- zod: ^3.21.4

## 環境変数
.envを作成し、環境変数を設定。
```.env
OPENAI_API_KEY=xxxxxxxxxxxxxxxxxx
OPEN_WEATHER_API_KEY=xxxxxxxxxxxxxxxxxx
```
