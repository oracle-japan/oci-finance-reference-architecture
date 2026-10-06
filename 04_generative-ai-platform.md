# 生成AI活用基盤

社内規程、マニュアル、稟議書、商品資料などを活用し、検索・回答や文書作成を支援する金融機関向け生成AI基盤の構成例です。  
OCI Generative AI Agents、Autonomous AI Database、Object Storageを組み合わせ、社内文書を検索して回答生成に利用するRAG（検索拡張生成）の構成を紹介します。
閉域接続やアクセス制御を考慮しながら、ナレッジの更新、音声データの活用、API連携を含めたアプリケーション基盤を検討できます。

この構成で確認できること
- Object Storageの文書とAutonomous AI Databaseのベクトルデータを活用するRAG基盤
- OCI Speechによる会議音声・通話の文字起こしと、要約などへの二次利用
- OCI Functions、API Gateway、IAMを組み合わせた処理連携とアクセス制御

<iframe class="speakerdeck-iframe" frameborder="0" src="https://speakerdeck.com/player/30dced47674b4f77b867fab763de0a55" title="04_OCI金融リファレンスアーキテクチャ_生成AI活用基盤" allowfullscreen="true" allow="web-share" style="border: 0px; background: padding-box padding-box rgba(0, 0, 0, 0.1); margin: 0px; padding: 0px; border-radius: 6px; box-shadow: rgba(0, 0, 0, 0.2) 0px 5px 40px; width: 100%; height: auto; aspect-ratio: 560 / 315;" data-ratio="1.7777777777777777"></iframe>

## Terraformスクリプト
こちらのTerraformは本リファレンスアーキテクチャで示す構成や考え方を理解するための **参考実装（サンプルコード）** です。  
使用方法、免責事項についてはフォルダ内のReadmeをご確認ください。

[Terraform generative-ai-platformサンプル一式をダウンロード](./terraform/generative-ai-platform-package.zip)

<script data-goatcounter="https://ojfsi.goatcounter.com/count"
        async src="//gc.zgo.at/count.js"></script>