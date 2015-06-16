# EffekseerForDXLib

DXライブラリ向けEffekseerのラッパーです。

## 開発版コンパイル方法

### 環境構築

VisaulStudio2012,2013をインストールします。

pythonの3系列をインストールします。

### ファイルの準備

EffekseerとEffekseerForDXLibをgithubからcloneし同じディレクトリに配置します。

```
(Root)/Effekseer/
(Root)/EffekseerForDXLib/
```

となります。

DXライブラリの最新版をダウンロードして解凍し、EffekseerForDXLibの直下に配置します。

```
(Root)/Effekseer/
(Root)/EffekseerForDXLib/DxLib_VC/
```

となります。

### コンパイル

Effekseerをコンパイルします。

```
(Root)/Effekseer/VisualStudio_Library.bat
```

を実行します。

```
(Root)/EffekseerForDXLib/generate_release_package.py
```

を実行します。


```
(Root)/EffekseerForDXLib/Dev/EffekseerForDXLib_vs2013.sln
```

で、ラッパーの開発ができるようになります。

## ユーザー向けパッケージの作成

上記の開発環境を整えて、Dev内のプロジェクトを全設定でコンパイルした後、

```
(Root)/EffekseerForDXLib/copy_package.py
```

を実行します。