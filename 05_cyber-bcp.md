# サイバーBCP

ランサムウェアなどのサイバー攻撃を想定し、バックアップの保護からシステムの隔離・復旧までを検討する構成例です。  
本番環境とは別のコンパートメントにバックアップを論理的に隔離し、保持ロックや最小権限のアクセス制御によって削除・改ざんへの耐性を高める設計を紹介します。
バックアップから独立した環境を再構築する流れと、不審な活動の検知を契機にワークロードの通信を制限する流れを取り上げます。

この構成で確認できること
- データベースのRecovery ServiceとObject Storageを用いたバックアップの保管・保護
- OCI Resource ManagerとFunctionsによる、復旧環境の構築・リストアを自動化する構成
- Cloud Guard、Functions、Notificationsを連携したネットワーク隔離と管理者への通知

<iframe class="speakerdeck-iframe" frameborder="0" src="https://speakerdeck.com/player/e67ba236d747470b9f544f1391604647" title="05_OCI金融リファレンスアーキテクチャ_サイバーBCP" allowfullscreen="true" allow="web-share" style="border: 0px; background: padding-box padding-box rgba(0, 0, 0, 0.1); margin: 0px; padding: 0px; border-radius: 6px; box-shadow: rgba(0, 0, 0, 0.2) 0px 5px 40px; width: 100%; height: auto; aspect-ratio: 560 / 315;" data-ratio="1.7777777777777777"></iframe>

## Terraformスクリプト
サイバーBCPは運用を主としたリファレンスアーキテクチャであるためTerraformスクリプトはございません。

<script data-goatcounter="https://ojfsi.goatcounter.com/count"
        async src="//gc.zgo.at/count.js"></script>