# Microsoft 365 Copilot を使用して、サンプル データを確認する

これらのラボでは、次のファイルを参照する Microsoft 365 Copilot のプロンプトを作成します。

- [ラテン アメリカにおけるチャイ ティーのプロモーション計画](https://go.microsoft.com/fwlink/?linkid=2269126)
- [Market Analysis Report for Mystic Spice Premium Chai Tea.docx](https://go.microsoft.com/fwlink/?linkid=2268826)
- [Contoso Chai Tea market trends 2023.xlsx](https://go.microsoft.com/fwlink/?linkid=2268822)

これらのファイルに Microsoft 365 Copilot が後でアクセスできるように、それらをまず OneDrive にアップロードします。

## OneDrive にファイルをアップロードする

**OneDrive**に必要なすべてのファイルをアップロードするには、次の手順を実行します。

1. テナント プロバイダーによって提供される仮想マシンに、パスワード `Pa55w.rd` を使用してローカルの**管理者**アカウントとしてログインします。

2. Windows タスクバーで、**Microsoft Edge** を選択します。

3. アドレス バーに「`https://onedrive.live.com/login`」と入力します。

4. **Microsoft 365 へようこそ**の下で、**[サインイン]** を選択します。

5. **サインイン プロンプト**で、(テナント プロバイダーから提供された) userx@yourtenant.onmicrosoft.comを入力し、**[次へ]** を選択します。

6. **[パスワードの入力]** 画面で、(テナント プロバイダーから提供された) パスワード 1 を入力してから、**[サインイン]** を選択します。

7. **サインインの状態を維持しますか?** というプロンプトが表示されたら、**[今後、このメッセージを表示しない]** を選択して、**[はい]** を選択します。

8. **[OneDrive]** の左上隅で、**+** (新規追加)、**[ファイルのアップロード]** の順に選択します。

    ![[新しいファイルの追加] のスクリーンショット](../Labs/Media/add_new.png)

9. **ファイル エクスプローラー**で、**この PC** > **ローカル ディスク (C:)** の順に選択し、**ResourceFiles** フォルダーを開きます。

10. **ResourceFiles** フォルダー内のすべてのファイルを選択し、**[開く]** を選択して、**OneDrive** にアップロードします。

11. アップロードが完了すると、画面の下部中央に **マイ ファイルに 29 個のアイテムがアップロードされました** と表示されます。

12. **Edge** を開いたままにして、次のタスクに進みます。

### 参照するフィールド

Copilot からファイルを参照すると、提供された提案からファイルが見つからない場合があります。 これは、Copilot を使用する一部のエクスペリエンスでは、最近使用した (MRU) リストのファイルしか参照しませんが、他のエクスペリエンスでは、OneDrive を参照してファイルを見つけることができるために発生することがあります。 そのリストに追加するのは、適切な Microsoft 365 アプリで開くのと同じくらい簡単です。  ファイルが開かれると、MRU リストに表示されます。

> [!IMPORTANT]
> Microsoft 365 Copilot は、OneDrive に保存されたファイルでのみ機能します。 ファイルが PC のローカル フォルダーに保存されている場合は、ファイルを OneDrive に移動して Copilot をアクティブにする必要があります。

先に進むと、これらのファイルに対して他のプロンプトを試す機会が得られます。自分のプロンプトのスキルを確認して強化するために実際に試してみることをお勧めします。
