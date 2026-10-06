# データレイク/DWH

入出金明細、口座情報、顧客情報などを収集・蓄積し、分析や意思決定に活用するデータレイク・DWH（データウェアハウス）の構成例です。  
Object Storageを中心に、未加工のRaw、標準化したNormalized、目的別のAnalyticsという3層でデータを管理します。
OCI Data Integrationによるデータ変換から、Autonomous AI LakehouseとOracle Analytics Cloudによる分析・可視化まで、データの流れと役割分担を確認できます。

この構成で確認できること
- 原本データの保持、名寄せ・形式統一・マスキング、分析用データの作成
- IAMによる職務別のアクセス制御と、Data Catalogによるメタデータ管理
- データ蓄積と処理の分離、およびDWH・BIへつなぐ分析基盤の構成

<iframe class="speakerdeck-iframe" frameborder="0" src="https://speakerdeck.com/player/e447866f769b4e7daf70e2490904d720" title="09_OCI金融リファレンスアーキテクチャ_データレーク・DWH" allowfullscreen="true" allow="web-share" style="border: 0px; background: padding-box padding-box rgba(0, 0, 0, 0.1); margin: 0px; padding: 0px; border-radius: 6px; box-shadow: rgba(0, 0, 0, 0.2) 0px 5px 40px; width: 100%; height: auto; aspect-ratio: 560 / 315;" data-ratio="1.7777777777777777"></iframe>

## Terraformスクリプト
こちらのTerraformは本リファレンスアーキテクチャで示す構成や考え方を理解するための **参考実装（サンプルコード）** です。  
使用方法、免責事項についてはフォルダ内のReadmeをご確認ください。

[Terraform data-lake-dwhサンプル一式をダウンロード](./terraform/data-lake-dwh-package.zip)

<script data-goatcounter="https://ojfsi.goatcounter.com/count"
        async src="//gc.zgo.at/count.js"></script>