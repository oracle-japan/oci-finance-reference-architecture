# API連携基盤

残高・相場情報の照会から資金移動などの外部企業連携まで、金融機関のオープンAPI基盤を設計するための構成例です。  
OCI API GatewayとOracle Container Engine for Kubernetes（OKE）を中心に、ベーシックAPIと金融グレードAPI（FAPI）を想定した構成を紹介します。

この構成で確認できること
- API Gatewayでのトークン検証と、OKE上のバックエンドへのリクエスト連携
- mTLS、Functions Authorizer、外部認可サーバーまたはKeycloakを組み合わせた認証・認可
- FastConnectによるオンプレミス接続と、東京・大阪リージョンを利用した冗長構成


<iframe class="speakerdeck-iframe" frameborder="0" src="https://speakerdeck.com/player/804f6ccba48a491e90e05b5dbf6a560e" title="06_OCI金融リファレンスアーキテクチャ_API連携基盤" allowfullscreen="true" allow="web-share" style="border: 0px; background: padding-box padding-box rgba(0, 0, 0, 0.1); margin: 0px; padding: 0px; border-radius: 6px; box-shadow: rgba(0, 0, 0, 0.2) 0px 5px 40px; width: 100%; height: auto; aspect-ratio: 560 / 315;" data-ratio="1.7777777777777777"></iframe>

## Terraformスクリプト
Coming Soon

<script data-goatcounter="https://ojfsi.goatcounter.com/count"
        async src="//gc.zgo.at/count.js"></script>