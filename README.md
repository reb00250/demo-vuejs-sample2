# vuejs-sample

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).


# Codyにおけるvueプロジェクトでのコード生成＆テストコード生成について

## コード生成時のプロンプト

@design\coding_rules.md @design\components\Modal.md コーディングルールとModalの詳細設計書をもとに以下の条件を満たしたvueコンポーネントのコードを生成してください
1. コードは省略せずに生成してください
2. 分割して最大レスポンス上限ごとに生成してください
3. 分割して続きのコードがある場合、続きがある旨のコメントを記載してコード生成を止めてください
4. 分割して続きがない場合、生成完了のメッセージを出力してください
5. 一番最初に生成したコードに続くようにコードを生成してください
6. 全ての分岐処理を網羅したコードを生成してください

### 引き続きのコード生成がある場合は以下を追加実行

続きのコードを生成してください

## テストコード生成時のプロンプト

@src\components\Modal2.vue 以下の条件を満たした単体テストコードを生成してください。
1. テストコードは省略せずケース名は日本語で生成してください
2. 分割して最大レスポンス上限ごとに生成してください
3. 分割して続きのコードがある場合、続きがある旨のコメントを記載してコード生成を止めてください
4. 分割して続きがない場合、生成完了のメッセージを出力してください
5. 一番最初に生成したコードに続くテストコードを生成してください
6. 全ての分岐処理を網羅したテストコードを生成してください

### 引き続きのコード生成がある場合は以下を追加実行

続きのコードを生成してください

