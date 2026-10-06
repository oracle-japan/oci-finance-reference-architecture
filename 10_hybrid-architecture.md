# ハイブリッドアーキテクチャ

データを顧客データセンター内に配置する要件や、既存システムとの低遅延な通信を考慮し、オンプレミスとOCIを組み合わせる構成例です。  
Compute Cloud@Customerを顧客データセンターに設置し、FastConnectでOCIリージョンと接続する設計を紹介します。
メインフレーム周辺システム、データ配置、移行が難しい既存データベースへのアクセスを題材に、フロントエンドとバックエンドの配置を検討できます。

この構成で確認できること
- FastConnectを用いたプライベート接続と、接続経路の冗長化
- メインフレーム周辺システムを顧客データセンターに置き、OCIのフロントエンドと連携する構成
- データレジデンシーを考慮した配置と、オンプレミスDBに近接させるバックエンド設計

<iframe class="speakerdeck-iframe" frameborder="0" src="https://speakerdeck.com/player/129b7f03d977416da5dc2ed7281d771b" title="10_OCI金融リファレンスアーキテクチャ_ハイブリッドアーキテクチャ" allowfullscreen="true" allow="web-share" style="border: 0px; background: padding-box padding-box rgba(0, 0, 0, 0.1); margin: 0px; padding: 0px; border-radius: 6px; box-shadow: rgba(0, 0, 0, 0.2) 0px 5px 40px; width: 100%; height: auto; aspect-ratio: 560 / 315;" data-ratio="1.7777777777777777"></iframe>

## Terraformスクリプト
Coming Soon

<script data-goatcounter="https://ojfsi.goatcounter.com/count"
        async src="//gc.zgo.at/count.js"></script>