# oyainput-fcitx5-backspace-colon-swap

## 本フォークについて（日本語訳）
これは [yq0810/oyainput](https://github.com/yq0810/oyainput) のフォークです。yq0810/oyainput は、オリジナルの [inwskatsube/oyainput](https://github.com/inwskatsube/oyainput) を Fcitx5 に対応させたフォークです。
本フォークには次の特徴があります。
(1) fcitx5, fcitx, ibusのIMに対応しています。
(2) IME がオフのときでも、バックスペースキーとコロンキーを入れ替えます。
(3) .oyainputconf に KUTOUTENKAKUTEIの項目を追加しました。KUTOUTENKAKUTEI=TRUE のとき、oyainput は句点・読点の後に Ctrl+M を出力します。
(4) ROYAKEY+6で［、ROYAKEY+7で］が出力されます。

本フォークはオリジナル版を置き換えることを意図したものではありません。
MX Linux 25 で動作を確認しています。

## oyainput（日本語訳）
日本語親指シフトキーボードをエミュレートするソフトウェア

### これは何？
日本語親指シフトキーボード（親指シフトキーボード）をエミュレートするソフトウェアです。
Linux専用です。Ubuntu 16.04LTS 以降を推奨します。

### インストール方法
ターミナルで次のコマンドを入力するだけで、ビルドとインストールができます。

$ make clean; make; sudo make install

うまくいかない場合は、コンパイルのために GNU make と gcc をインストールする必要があります。

$ sudo apt-get install -y make gcc

注意：sudo を実行できるか、su コマンドで root になれる必要があります。

### 使い方

$ oyainput [ユーザー名]

### 設定
設定ファイルは初回実行時に作成されます。
場所は `(ホームディレクトリ)/.oyainputconf` です。

# oyainput
software to emulate Japanese thum shift keyboard (oyayubi-shift keyboard)


# What is this?
It is software to emulate Japanese thum shift keyboard(oyayubi shift keyboard).
This is only for Linux, recommend Ubuntu 16.04LTS or Higher.


# How to install
Simply enter commands as follows on terminal to make and install.

$ make clean; make; sudo make install

If not, You need install gnu make and gcc, to compile.

$ sudo apt-get install -y make gcc

Note. You must be able to run sudo, or need to be root with su command.


# Usage

$ oyainput [username]


# Configure
Conig file is made on first run. 
location is`(Home Dir)/.oyainputconf`


