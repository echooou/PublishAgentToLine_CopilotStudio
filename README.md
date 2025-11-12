# PublishAgentToLine_CopilotStudio
Copilot Studio で作成したエージェントを LINE に公開してみます

## Prerequisites

## Steps
1. Azure CLI をインストールする https://learn.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest
2. コマンドを開き、azure にログイン、サブスクリプションを選択する
> az login
3. リソースグループを作成する
> az group create --name "<ResourceGroupName>" --location "<region>"
4. アイデンティティを作成する
> az identity create --resource-group "<ResourceGroupName>" --name "<identity>"
5. ARM テンプレートでリソースを作成する


## Steps
1. Azure portal にログインする
2. Bot service と検索し、新規作成を行う
3. Azure Bot を選択して必要な項目を埋める
4. 
