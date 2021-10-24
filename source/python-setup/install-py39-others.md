(install-py39-others)=

# Pythonのインストール(その他)
ここでは、{ref}`install-py39-win`、{ref}`install-py39-mac`の方法以外のインストール方法を紹介します。

以下の方法を使ってPythonのインストールはできますが、特別な理由がない限り、{ref}`install-py39-win`または{ref}`install-py39-mac`に従って公式インストーラを使ったほうがトラブルが少ないためお勧めです。

## Homebrew(macOSのみ)
Homebrewはコマンドラインで開発用の便利なツールやアプリケーションをインストールできるmacOS用パッケージ管理ツールです。
Homebrewのインストール方法は以下公式サイトを参照してください。

[https://brew.sh/index_ja](https://brew.sh/index_ja)

Python 3.9をインストールする場合は`brew install python@3.9`を実行します。

## Anaconda
Anacondaはデータサイエンス用のツールがまとまったPython環境です。Pythonの実行環境に加えて、便利なサードパーティーのライブラリがあらかじめインストールされています。

Pythonの初心者向けのツールではありません。機械学習やデータ解析を中心にPythonを使いたくなった際には`pip`を利用して必要なライブラリをインストールすることをお勧めします。

Anacondaをインストールするには、以下公式サイトからインストーラをダウンロードして実行します。

[https://www.anaconda.com/products/individual](https://www.anaconda.com/products/individual)

## Microsoft Store(Windowsのみ)
Microsoft StoreはWindows向けのアプリケーションを配布しているプラットフォームです。

Python 3.9は以下URLからインストールできます。

[https://www.microsoft.com/ja-jp/p/python-39/9p7qfqmjrfp7?activetab=pivot:overviewtab](https://www.microsoft.com/ja-jp/p/python-39/9p7qfqmjrfp7?activetab=pivot:overviewtab)

## Chocolatey(Windowsのみ)
ChocolateyはWindows用のパッケージ管理ツールです。コマンドラインでツールやアプリケーションをインストールできます。

Chocolateyのインストール方法は以下公式サイトを参照してください。

[https://chocolatey.org/install](https://chocolatey.org/install)

Python 3.9をインストールする場合は`choco install python --version=3.9.x`[^1]を実行します。

[^1]: `x`には数字が入ります。その時点での最新のバージョン番号によって値は異なります
