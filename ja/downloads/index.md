---
layout: page
title: "ダウンロード"
lang: ja
---

ここでは、Rubyインタプリタの代表的な入手方法を説明します。

現在の安定版は {{ site.downloads.stable[0].version }}です。
[Ruby’sライセンス][license]を必ずお読み下さい。

### Rubyのインストール方法

メジャーなプラットフォームでは Ruby をインストールする方法はいくつかあります。

* Linux/UNIX マシンでは、そのシステムのパッケージ管理ツールや、rbenv、RVMなどのサードパーティツールが使えます。
* OS Xマシンでは、rbenv、RVMなどのサードパーティのパッケージ管理ツールが使えます。
* Windowsマシンでは、RubyInstallerといったツールが使えます。

各パッケージマネージャ及びサードパーティーツールの詳細は、[インストールガイド][installation] ページを参照して下さい。

もちろん、メジャーなプラットフォームでソースからRubyをインストールすることも可能です。

### ソースコードからRubyをコンパイルする

ソースコードからのインストールは、利用したいプラットフォームや環境に合った設定を使うことができる、いい方法です。
また、利用したいプラットフォーム向けのパッケージが存在しない場合にも使えるいい方法でもあります。

もしコンパイルで問題がある場合、[インストールガイド][installation] ページで解説しているサードパーティーツールの利用が助けになるかもしれません。

* **最新の安定版:**
  [Ruby {{ site.downloads.stable[0].version }}]({{ site.downloads.stable[0].url.gz }})<br>
  sha256: {{ site.downloads.stable[0].sha256.gz }}

* **前世代の安定版:**
  [Ruby {{ site.downloads.stable[1].version }}]({{ site.downloads.stable[1].url.gz }})<br>
  sha256: {{ site.downloads.stable[1].sha256.gz }}

* **古い安定版:**
  [Ruby {{ site.downloads.stable[2].version }}]({{ site.downloads.stable[2].url.gz }})<br>
  sha256: {{ site.downloads.stable[2].sha256.gz }}

{% if site.downloads.security_maintenance %}
* **さらに古い安定版 (まもなく EOL):**
  [Ruby {{ site.downloads.security_maintenance[0].version }}]({{ site.downloads.security_maintenance[0].url.gz }})<br>
  sha256: {{ site.downloads.security_maintenance[0].sha256.gz }}
{% endif %}

* **スナップショット:**
  * [安定版のスナップショット]({{ site.downloads.stable_snapshot.url.gz }}):
    最も新しい現在の安定版ブランチのスナップショットのtarballです。
  * [ナイトリースナップショット]({{ site.downloads.nightly_snapshot.url.gz }}):
    毎晩SVNに入っているものから作成しているtarballです。
    バグやその他の問題があるかもしれません。利用する場合は自己責任でお願いします！

RubyのSubversionやGitリポジトリについての情報は、[リポジトリガイド](/ja/documentation/repository-guide)を参照してください。

Rubyのソースコードは、世界各国の[ミラーサイト][mirrors]からダウンロードできます。
お近くのミラーサイトをお使いください。

### Windows版Rubyバイナリ

Windows向けのバイナリが有志により配布されています。

* [ActiveScriptRuby][active-script-ruby]
  安定版に幾つかの便利なライブラリを加え、さらにRubyをCOMサーバとしても利用可能にしたもの。ベースはmswin32版
* [RubyInstaller][rubyinstaller] (英語)
  安定版に多数の便利なライブラリを加えたもの。ベースはmingw32版
* [RailsInstaller][railsinstaller] (英語)
  RubyInstaller に Rails の開発に必要なものを加えたもの。



[license]: {{ site.license.url }}
[installation]: /ja/documentation/installation/
[mirrors]: /en/downloads/mirrors/
[active-script-ruby]: http://www.artonx.org/data/asr/
[rubyinstaller]: http://rubyinstaller.org/
[railsinstaller]: http://railsinstaller.org/
