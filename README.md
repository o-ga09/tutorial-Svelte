# tutorial Svelte + Sveltekit

Svelte + Sveltekitで何か作ってみるリポジトリ

## 作るもの

ウイスキー初心者のための第一歩のアプリ
【WiLove】

Wiskey + Love = ウイ　＋　好き(＝Love)　＝　WiLove

## 要件

- MVP1 : ***飲んだウイスキーの種類を記録できる***
- MVP2 : ***どこで飲んだか記録できる***
- MVP3 : ***どんなウイスキーがあるのか探すことがができる***

## デザイン

- UI/UXを考えて、ユーザーが気持ちよくなるデザインにする
- Figmaを使用してワイヤーフレームから考える

WIP

## 構成要素

- エンティティ
  - ユーザ
    - uid
    - user_name
    - password
  - ウイスキー
    - w_id
    - w_name
    - w_place
    - w_year
    - w_fav_rate

## プロジェクトの始め方

```bash
git clone https://github.com/o-ga09/tutorial-Svelte.git
cd tutorial-Svelte
npm i
```

## 開発サーバの起動

```bash
npm run dev

npm run dev -- --open
```

## テスト

```bash
npm run test
```

## ビルド

```bash
npm run build
```
