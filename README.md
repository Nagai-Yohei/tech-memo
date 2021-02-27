# tech-memo
自分用の技術メモです。

# Node.js, React

## 実行開始

```
npm start
```

## Reactのインストール

以下のサイトでNode.jsをインストール。  
https://nodejs.org/ja/

インストールが終わったら、バージョン情報を確認。  
```バージョン情報確認
node -v
```
きちんと返ってきたらインストールされている。  
実行するだけなら、これで準備が整った状態となる。

## 開発環境のセットアップ(React, Redux)

### create-react-appのインストール

```
npm install -g create-react-app
```

### Reactプロジェクトの作成

```
create-react-app <プロジェクト名>
```

### Reduxのインストール

上記で作ったプロジェクトフォルダにおいて、以下を実行。
```
npm install --save redux react-redux redux-logger
```



