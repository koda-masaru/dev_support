# Electron アプリのビルド

## Electron をインストール

- Node.jsは既にインストール済み
- Node.jsは最近のv5.9.1で試した

```
npm -g install electron-prebuilt
```

## Projectを作成

```
cd {project directory}
npm init -y
```

## package.json 編集
Electronでは, package.jsonのmainに記載されたJavaScriptファイルがアプリケーションのエントリポイントとなります.
ここではmain.js とします.

``` package.json
{
  ...
  "main": "main.js",
  ...
}
```

## main.js を作成


## index.html を作成


## Electron アプリを実行

```
electron .
```

index.htmlを表示するデスクトップアプリが表示されればOK


# Electron アプリのパッケージング


## electron-packager をインストール

- electron-packagerを使ってパッケージするのでインストールする

```
npm install electron-packager -g
```

## electron-packager を使いパッケージング

```
electron-packager <sourcedir> <appname> --platform=<platform> --arch=<arch> [optional flags...]

electron-packager . parser --platform=darwin,win32 --arch=x64 --version=0.37.2 --overwrite
```

- プラットフォーム毎にパッケージングされていれば成功










