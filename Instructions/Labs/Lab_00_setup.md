# Microsoft 365 Copilot を使用して、サンプル データを確認する

これらのラボでは、次のファイルを参照する Microsoft 365 Copilot のプロンプトを作成します。

- [ラテン アメリカにおけるチャイ ティーのプロモーション計画](https://go.microsoft.com/fwlink/?linkid=2269126)
- [Market Analysis Report for Mystic Spice Premium Chai Tea.docx](https://go.microsoft.com/fwlink/?linkid=2268826)
- [Contoso Chai Tea market trends 2023.xlsx](https://go.microsoft.com/fwlink/?linkid=2268822)

これらのファイルに Microsoft 365 Copilot が後でアクセスできるように、それらをまず OneDrive にアップロードします。

## OneDrive にファイルをアップロードする

**OneDrive**に必要なすべてのファイルをアップロードするには、次の手順を実行します。

1. テナント プロバイダーによって提供される仮想マシンにログインします。

1. **Microsoft Edge** ブラウザーを開き、+++https://onedrive.live.com/login/+++ に移動します。 指定された資格情報を入力してログインします。

1. **[OneDrive の準備ができました]** を選択し、**[作成またはアップロード] > [ファイルのアップロード]** の順に選択します。

1. **エクスプローラー**で、**[この PC]**  >  **[ローカル ディスク (C:)]** の順に選択し、**MS-4018 ResourceFiles** フォルダーを開きます。

1. **MS-4018 ResourceFiles** フォルダー内のすべてのファイルを選択し、**[開く]** を選択します。

1. アップロードが完了すると、画面の下部中央に **[ドキュメントに 3 個のアイテムがアップロードされました]** と表示されます。

### 参照するフィールド

Copilot からファイルを参照すると、提供された提案からファイルが見つからない場合があります。 これは、Copilot を使用する一部のエクスペリエンスでは、最近使用した (MRU) リストのファイルしか参照しませんが、他のエクスペリエンスでは、OneDrive を参照してファイルを見つけることができるために発生することがあります。 そのリストに追加するのは、適切な Microsoft 365 アプリで開くのと同じくらい簡単です。  ファイルが開かれると、MRU リストに表示されます。

> [!IMPORTANT]
> Microsoft 365 Copilot は、OneDrive に保存されたファイルでのみ機能します。 ファイルが PC のローカル フォルダーに保存されている場合は、ファイルを OneDrive に移動して Copilot をアクティブにする必要があります。

先に進むと、これらのファイルに対して他のプロンプトを試す機会が得られます。自分のプロンプトのスキルを確認して強化するために実際に試してみることをお勧めします。
