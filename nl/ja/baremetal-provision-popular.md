---



copyright:
  years: 2017, 2018
lastupdated: "2018-06-21"


---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:table: .aria-labeledby="caption"}


# 最もポピュラーなサーバーからの選択
「最もポピュラーなサーバー (Most Popular Servers)」リストに載っているサーバーは、ほとんどのクライアント・ユースケースのニーズを満たすよう事前構成されており、注文後 30 分ないし 40 分で稼動準備が整います。
1. [{{site.data.keyword.cloud_notm}} カタログ](https://console.bluemix.net/catalog/){:target="_blank"}を開きます。   
2. 「ベアメタル・サーバー」を選択します。
3. 「作成」をクリックします。
2. 次の情報を選択します。
    <table>
    <CAPTION>表 1. ベアメタルの選択肢</CAPTION>
    <THEAD>
    <TR>
    <th>フィールド</th>
    <th>値</th>
    </TR>
    </THEAD>
    <TBODY>
    <tr>
    <td>数量</td>
    <td>+ アイコンと - アイコンを使用して、プロビジョンする同一サーバーの台数を指定します。<br>仕様が異なる複数のサーバーをプロビジョンしたい場合は、それらを個別にプロビジョンする必要があります。<tr>
    <td>場所</td>
    <td>サーバーの配置先となる地域およびデータ・センターを選択します。</td>
    </tr>
    <tr>
    <tr>
    <td>ホスト名およびドメイン</td>
    <td>これらのフィールドは、デフォルトで指定済みです。指定内容は変更できます。</td>
    </tr>
    <tr>
    <td>サーバーの選択</td>
    <td>**「ポピュラーなサーバー (Popular Servers)」**で、ニーズに合ったサーバーを選択します。ここに載っているサーバーは事前構成されており、30 分ないし 40 分で使用する準備が整います。
    </tr>
    <tr>
    <td>RAM</td>
    <td>選択したサーバーに基づくデフォルトです。</td>
    </tr>
    <tr>
    <td>SSH 鍵</td>
    <td>SSH 鍵の公開鍵を指定します。これは、サーバーがプロビジョンされた後、そのサーバーにログインするために使用します。</td>
    </tr>
    <tr>
    <td>イメージ<br>(オペレーティング・システム)</td>
    <td>インスタンスのオペレーティング・システムを選択します。 **注**: サーバーとオペレーティング・システムの間に矛盾が存在する場合は、エラーメッセージが表示されます。例えば、Microsoft SQL Server で Linux を選択する場合です。</td>
    </tr>
    <td>アップリンク・ポート速度</td>
    <td>内部インターフェースおよび外部インターフェースの速度を決定します。</td>
    </tr>
    <tr>
    <td>アドオン</td>
    <td> 該当のオプションを選択するか、デフォルト値を使用します。</td>
    </tr>
    </TBODY>
    </table>

3.  「発注要約」セクションで、**「時間単位」**課金、または**「月単位」**課金を選択します。
4.  オーダーを確認します。
5.  リストされたサード・パーティー・サービス契約をすべて確認し、**「サード・パーティー・サービスのご使用条件」**チェック・ボックスをクリックします。
6.  **「プロビジョン」**をクリックします。 プロビジョニングの注文番号を含む画面にリダイレクトされます。 この画面は、プロビジョニングの注文の受信を示すものでもあるため、印刷できます。

 一連の E メール (プロビジョニングの注文の確認応答、プロビジョニングの注文の承認と処理、およびプロビジョニングの完了) が管理者に送信されます。 プロビジョニング完了の E メールには、ユーザーが {{site.data.keyword.cloud_notm}} にログインできるよう、そのユーザーの *「デバイスの詳細」*ページへのリンクが含まれています。また、直接 {{site.data.keyword.slportal}}にログインすることもできます。


## 次のステップ
{{site.data.keyword.baremetal_short}} のプロビジョン後に、その管理を開始できます。 詳しくは、『[{{site.data.keyword.baremetal_short}} の管理](../bare-metal/managing.html)』を参照してください。
