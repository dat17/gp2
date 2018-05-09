# Unity HubとUnity2018.1.0f2のインストール
## Unity Hubをインストール
Unityのバージョンやパッケージ管理用のUnity謹製のツールです。これをインストールしておくと、複数のバージョンを簡単に共有ができる上に、バージョンアップも簡単になるので入れておきます。

- https://public-cdn.cloud.unity3d.com/hub/prod/UnityHubSetup.exe からインストーラーをダウンロード
- ダウンロードした`UnityHubSetup.exe`を起動
- ライセンスを同意する

![ライセンスの同意](images/unityhub/img00.png)

- アクセスを許可してパスワード入力

以上でインストール完了して、Unity Hubが起動する。

## Unity2018.1.0f2のインストール
Unity Hubからインストールできます。

- Installsをクリック
- Official Releasesをクリック
- Unity 2018.1.0f2 の右のDownloadをクリック

![インストール](images/unityhub/img01.png)

- インストールする項目を以下のように設定
  - Standard AssetsとWebGL Build Supportにチェックを入れる

![Standard Assets](images/unityhub/img02.png)


![WebGL Build](images/unityhub/img03.png)

- 他に必要なものがあったらチェックを入れて、Doneをクリック

ダウンロードとインストールが自動的に始まるので、完了まで待つ。

以上で完了です。

# ライセンスの通し方
Unityは、ファイルベースでのライセンス確認ができます。これを設定しておくと、違うアカウントでもライセンスを通しなおす必要がなくなる可能性があります。

## 手順
- Unityを起動
- HelpメニューからManageLicese...を選択

![Manage License](images/unityhub/img10.png)

- Manual Activationをクリック

![Manual Activation](images/unityhub/img11.png)

- Save License Requestをクリック

![Save License Request](images/unityhub/img12.png)

すべてのユーザーからアクセスできるパブリックのドキュメントフォルダーに保存します。

- Windows7_OS (C:)を選択してから、ユーザーをダブルクリックで開く

![ユーザーフォルダー](images/unityhub/img13.png)

- パブリックをダブルクリック

![パブリックフォルダー](images/unityhub/img14.png)

- パブリックのドキュメントをダブルクリック

![パブリックのドキュメントフォルダー](images/unityhub/img15.png)

- 保存ボタンをクリックして、ライセンスファイルを保存

![保存](images/unityhub/img16.png)

保存したファイルを指定して、アクティベーションします。

- Activation URLの後ろのリンクをクリックしてアクティベーションページを開く

![license page](images/unityhub/img20.png)

- 学校のUnityライセンスでサインイン

![サインイン](images/unityhub/img21.png)

- Browseをクリックして、先ほどパブリックのドキュメントフォルダー内に保存した`Unity_lic.alf`を開く

![activation](images/unityhub/img22.png)

- Nextボタンをクリック
- Activate your licenseで、Unity Personal Editionを選択して、Nextをクリック

![Activate your license](images/unityhub/img23.png)

- Download license fileをクリックして、パブリックのドキュメントフォルダー内に、保存する
  - <b>保存時に、`.xml`という拡張子が付く場合、拡張子を消すこと</b>

![Download license file](images/unityhub/img24.png)

保存が完了したら、保存したライセンスファイルをUnityで読み込む。

- Unityに切り替える
- Load Licenseボタンをクリック

![Load](images/unityhub/img25.png)

- パブリックのドキュメントフォルダーにダウンロードしたライセンスファイルを選択して、OKをクリック

以上で、Start Using Unityをクリックして開始する。

# 注意！
