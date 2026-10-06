# メインフレーム・ホスト連携

金融機関のメインフレームとOCIを連携し、既存の勘定系・決済系システムのデータを分析や新サービスに活用する構成例です。  
既存資産への影響を抑えながら連携基盤を設計するために、データレプリケーション、非同期メッセージング、ファイル転送の3方式を紹介します。
FastConnectによる閉域接続を軸に、データの鮮度、メッセージの順序性、障害時の継続性に応じた構成の違いを確認できます。

この構成で確認できること
- データレプリケーションとOCI Streamingを用いた、基幹データのニアリアルタイム連携
- 非同期メッセージングの冗長化方式と、順序性・永続化・切替時の考慮点
- ファイル転送による外部システム連携、分析用データの受け渡し、バックアップへの活用

<iframe class="speakerdeck-iframe" frameborder="0" src="https://speakerdeck.com/player/b0451a45ad8a4868a7a732d49c85f007" title="01_OCI金融リファレンスアーキテクチャ_メインフレーム・ホスト連携" allowfullscreen="true" allow="web-share" style="border: 0px; background: padding-box padding-box rgba(0, 0, 0, 0.1); margin: 0px; padding: 0px; border-radius: 6px; box-shadow: rgba(0, 0, 0, 0.2) 0px 5px 40px; width: 100%; height: auto; aspect-ratio: 560 / 315;" data-ratio="1.7777777777777777"></iframe>

## Terraformスクリプト
Coming Soon

<script data-goatcounter="https://ojfsi.goatcounter.com/count"
        async src="//gc.zgo.at/count.js"></script>