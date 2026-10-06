# コアバンキング（勘定系）

預金・為替・融資などを扱う銀行の勘定系システムを対象に、高可用性とデータ保護を考慮したOCI構成例を紹介します。  
WebLogicとOracle Exadata Database Serviceによる冗長化に加え、東京・大阪リージョンを利用した災害対策とバックアップの設計を整理しています。
勘定処理と総勘定元帳の役割分担を検討できるよう、Oracle Fusion Cloud ERPとのデータ連携も取り上げます。

この構成で確認できること
- アプリケーションのクラスタ構成、Oracle RAC、Active Data Guardを用いた可用性設計
- リージョン障害時の切替方式と、データベースのバックアップによる復旧への備え
- Oracle Integrationを介した勘定系とOracle Fusion Cloud ERPの連携

<iframe class="speakerdeck-iframe" frameborder="0" src="https://speakerdeck.com/player/0cd691b13c9a4dc5b7acc2b8596dbee4" title="02_OCI金融リファレンスアーキテクチャ_コアバンキング" allowfullscreen="true" allow="web-share" style="border: 0px; background: padding-box padding-box rgba(0, 0, 0, 0.1); margin: 0px; padding: 0px; border-radius: 6px; box-shadow: rgba(0, 0, 0, 0.2) 0px 5px 40px; width: 100%; height: auto; aspect-ratio: 560 / 315;" data-ratio="1.7777777777777777"></iframe>

## Terraformスクリプト
Coming Soon

<script data-goatcounter="https://ojfsi.goatcounter.com/count"
        async src="//gc.zgo.at/count.js"></script>