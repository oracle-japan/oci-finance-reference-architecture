# 市場データ配信

株価や為替レートなどの市場データを社内外から収集し、加工して利用者へ配信する金融機関向けの構成例です。  
データを受信するHandler、計算・加工するComposer、配信するDistributorの3層に分け、Oracle Container Engine for Kubernetes（OKE）とOCI Streamingで連携します。
リアルタイム配信を対象に、データの取り込みから利用者ごとの配信形式・頻度の調整まで、一連の処理と各層の役割を確認できます。

この構成で確認できること
- 外部データプロバイダーからの受信と、Streamingを介したデータの受け渡し
- 市場データと社内の参照データを使った計算・加工処理
- クライアントに応じた形式・頻度・粒度の調整と、OKEを用いた各処理層の構成

<iframe class="speakerdeck-iframe" frameborder="0" src="https://speakerdeck.com/player/b303b286dc9f4389849f7cbcb1d2a8c9" title="08_OCI金融リファレンスアーキテクチャ_市場データ配信" allowfullscreen="true" allow="web-share" style="border: 0px; background: padding-box padding-box rgba(0, 0, 0, 0.1); margin: 0px; padding: 0px; border-radius: 6px; box-shadow: rgba(0, 0, 0, 0.2) 0px 5px 40px; width: 100%; height: auto; aspect-ratio: 560 / 315;" data-ratio="1.7777777777777777"></iframe>

## Terraformスクリプト
Coming Soon

<script data-goatcounter="https://ojfsi.goatcounter.com/count"
        async src="//gc.zgo.at/count.js"></script>