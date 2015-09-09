# HikiDoc

## はじめに

'HikiDoc' は「テキスト→ HTML」変換ツールです。書きやすく読みやすい文法の
テキストをまともな HTML (や XHTML) に変換します。

## 必要なもの

HikiDoc の実行には Ruby 1.8.2 以降が必要です。

## ダウンロード

GitHub レポジトリ [https://github.com/hiki/hikidoc](https://github.com/hiki/hikidoc) から取得して
ください。

```
(例)
git clone https://github.com/hiki/hikidoc.git
```

## インストール

### 半手動でのインストール

以下のように 'setup.rb' スクリプトを用いてインストールします。

```
$ ruby setup.rb config
$ ruby setup.rb setup
# ruby setup.rb install
```

### RubyGems経由でのインストール

以下のようにインストールします。

```
$ gem install hikidoc
```

## 文法

[TextFormattingRules.ja](TextFormattingRules.ja) をご覧ください。

## メーリングリスト

参加を希望される方は、以下のようなメールを送信してください。

```
To: hikidoc@ml.fdiary.net
Cc: kazuhiko@fdiary.net

本文に自己紹介など
```

過去のメールは [http://www.fdiary.net/ml/hikidoc/](http://www.fdiary.net/ml/hikidoc/) で公開しています。

## 関連するソフトウェア

以下のソフトウェアで HikiDoc ライブラリ、または HikiDoc フォーマットが用いられています。

<dl>
<dt><a href="http://www.tdiary.org/">tDiary</a></dt>
<dd>ウェブ日記ソフトウェア</dd>
<dt><a href="http://hikiwiki.org/">Hiki</a></dt>
<dd>多機能かつ高速な Wiki クローン</dd>
<dt><a href="http://lily.sourceforge.jp/">lily</a></dt>
<dd>シンプルな CMS (Web サイト構築システム)</dd>
<dt><a href="http://search.cpan.org/perldoc?Text::HikiDoc">Text::HikiDoc</a></dt>
<dd>Perl による HikiDoc の実装</dd>
<dt><a href="http://github.com/moro/piki_doc/">PikiDoc</a></dt>
<dd>HikiDocの「プラグイン」機能を追加できるライブラリです</dd>
<dt><a href="http://sourceforge.jp/projects/mail2weblog/wiki/FrontPage">mail2weblog</a></dt>
<dd>高機能メール投稿型モブログ</dd>
</dl>

## ライセンス

Modified BSD ライセンスです。

```
Copyright (c) 2005, Kazuhiko <kazuhiko@fdiary.net>
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are
met:

    * Redistributions of source code must retain the above copyright
      notice, this list of conditions and the following disclaimer.
    * Redistributions in binary form must reproduce the above
      copyright notice, this list of conditions and the following
      disclaimer in the documentation and/or other materials provided
      with the distribution.
    * Neither the name of the HikiDoc nor the names of its
      contributors may be used to endorse or promote products derived
      from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
"AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT
OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT
LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```

