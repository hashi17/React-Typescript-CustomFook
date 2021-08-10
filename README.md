# React-Typescript-CustomFook

Created with CodeSandbox

# カスタムフック

## カスタムフックを使わない

- ロジックが増えるとかなりゴチャゴチャする
  https://jsonplaceholder.typicode.com/users
  から

1. axios でデータを取得
2. その返却値から必要なデータを抜き出して加工
   3． 取得中はローディング表示
3. エラーならその旨を表示
4. axios.finaly() が使えるように tsconfig に"es2018"を設定
