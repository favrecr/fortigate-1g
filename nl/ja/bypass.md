---

copyright:
  years: 2017
lastupdated: "2017-10-30"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}
{:download: .download}

# ファイアウォール・ルールのバイパス

ファイアウォール・ルールをバイパスするには、以下の手順を実行します。

1. ブラウザーから、[カスタマー・ポータル![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")](https://control.softlayer.com/){: new_window}を開き、アカウントにログインします。
2. カスタマー・ポータル・ナビゲーションで、**「ネットワーク」>「IP 管理」>「VLAN」**に移動し、バイパスするファイアウォール・デバイスをクリックします。
3. **「デバイスの詳細」**ページの**「構成」**タブで、**「アクション」**ドロップダウン・メニューを使用して**「経路バイパスの設定」**を選択することや、**「状況」**セクションで**「ルールのバイパス」**ボタンをクリックすることができます。 

	もう 1 つのオプションは、ファイアウォールを迂回するように経路指定することです。これは、**「回る経路」**ボタンをクリックすることで実行できます。どの方法でも、確認ダイアログが表示されます。**「はい」**をクリックすると、アクションが確定されます。 ルールのバイパスは、約 2 分で有効になります。バイパス・モードの間、「状況」は「ファイアウォールを回る経路」となります。

## ルールの再有効化

ルールを再有効化するには、上記の手順に従いデバイスの**「構成」**タブにアクセスし、**「アクション」**ドロップダウン・メニューをクリックし、**「経路バイパスの設定」**を選択します。確認ダイアログが表示されます。**「はい」**をクリックすると、アクションが確定されます。 「状況」が 2 分以内に「ファイアウォールを通る経路」に戻ります。