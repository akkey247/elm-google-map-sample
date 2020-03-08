# electron-packaging-sample

Electronのパッケージングを行うサンプル。

# 使い方

1. インストール

```
$ npm i
```

2. Elmのビルド

```bash
$ npx elm make src/Main.elm
```

3. 起動

```bash
$ npx electron .
```

4. パッケージ化(Mac)

```bash
$ node build-mac
```

`dist/mac/xxx.app` が本体になる。