# Test-Azure-Container-Apps-Functionalities
こちらはAzure Container Apps のスケーリング機能と認証機能に関しての Hands on になります。
+ 記載の内容については、2023年12月時点の環境をベースとしています。
+ 参考1: Azure Container Apps [スケーリング機能](https://learn.microsoft.com/ja-jp/azure/container-apps/scale-app?pivots=azure-cli#http)
+ 参考2: Azure Container Apps [認証と認可の機能](https://learn.microsoft.com/ja-jp/azure/container-apps/authentication)
+ **なお、こちらに記載の内容はあくまでサンプルとなりますので、ご注意ください。**

## 前提条件
|  要件  |  手順  |  用途  |
| ---- | ---- | ---- |
|  Hands on 用 Azure Subscription 準備  |  [Azure の無料アカウント](https://azure.microsoft.com/ja-jp/free/)より新規作成 | |
|  デプロイ済みの Azure Container Apps | サンプルアプリの作り方は[こちら](https://learn.microsoft.com/ja-jp/azure/container-apps/tutorial-deploy-first-app-cli?tabs=bash)を参考にしてください | 任意の事前に準備した Container Apps に機能を追加してい |
<!-- + Hands on 用 Azure Subscription 準備
  + 参考： [Azure の無料アカウント](https://azure.microsoft.com/ja-jp/free/)より新規作成
+ Github アカウントの準備
  + アカウントが存在しない場合： [Github Top ページの Sign up for GitHub](https://github.com/) より新規作成
  + 用途：認証機能を Github を用いて追加します
+ デプロイ済みの Azure Container Apps
  + サンプルアプリの作り方は[こちら](https://learn.microsoft.com/ja-jp/azure/container-apps/tutorial-deploy-first-app-cli?tabs=bash)を参考にしてください
  + 用途：任意の事前に準備した Container Apps に機能を追加していくためです
     -->
## アジェンダ
+ [事前準備](README.md)
+ [スケーリングの検証](scaling-valification.md)
+ [認証と認可の機能の検証](authentication-valification.md)
