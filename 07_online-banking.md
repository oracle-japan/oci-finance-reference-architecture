# オンラインバンキング

口座開設・残高照会・振込を題材に、オンラインバンキングをマイクロサービスで構成する設計例です。  
API Gateway、OCI Functions、Autonomous AI Database、OCI Streamingを組み合わせ、業務単位の機能追加とイベント駆動による非同期処理を検討できます。
取引の整合性を考えるために、Sagaやアウトボックスを用いる処理フローに加え、OKEとデータベースのTxEventQを利用する構成も紹介します。

この構成で確認できること
- 口座開設・振込の処理フローと、勘定系APIを介した業務連携
- StreamingとService Connector Hubによるイベント配信、および取引・イベント履歴の管理
- Functionsによるサーバレス構成と、OKE・TxEventQを利用した構成の違い

<iframe class="speakerdeck-iframe" frameborder="0" src="https://speakerdeck.com/player/85a767d02b2d4a479100d12eb8ab9196" title="07_OCI金融リファレンスアーキテクチャ_オンラインバンキング" allowfullscreen="true" allow="web-share" style="border: 0px; background: padding-box padding-box rgba(0, 0, 0, 0.1); margin: 0px; padding: 0px; border-radius: 6px; box-shadow: rgba(0, 0, 0, 0.2) 0px 5px 40px; width: 100%; height: auto; aspect-ratio: 560 / 315;" data-ratio="1.7777777777777777"></iframe>

## Terraformスクリプト
こちらのTerraformは本リファレンスアーキテクチャで示す構成や考え方を理解するための **参考実装（サンプルコード）** です。  
使用方法、免責事項についてはフォルダ内のReadmeをご確認ください。

[Terraform online-bankingサンプル一式をダウンロード](./terraform/online-banking-package.zip)

<script data-goatcounter="https://ojfsi.goatcounter.com/count"
        async src="//gc.zgo.at/count.js"></script>