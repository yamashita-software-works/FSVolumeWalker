### 0.1.4.0

- File System Statisticsウィンドウを追加。   
  VolumesまたはMS-DOS Drivesウィンドウでボリュームやドライブを選択し、メニューまたはコンテキストメニューから\[File System Statistics\]を選択します。

### 0.1.3.0

- DLLの名称変更。 fsvolumeinfo.dll -> fsvolumehelp.dll

- CSimpleValArrayはATLとクラス名が重複するため、CValArrayに変更。

- Disk Drive Information ウィンドウでパーティション情報にDOSドライブレターが表示されていなかった不具合を修正。

- コード整理、細かい不具合修正など。

### 0.1.2.1

- Aboutダイアログに表示されるSystem Boot Timeを、日時をローカル時間で取得した後、再度ローカル時間に変換して表示していた不具合を修正。

### 0.1.2.0

- VolumeList,DriveListに\[Usage\] (使用量)列を追加。

- Volume InformationでReFSのボリュームを表示した場合、REFS_VOLUME_DATA_BUFFER情報の表示を追加。

- DriveLayoutでのメモリリークを修正。

- 共通ライブラリを更新。

- その他コード整理。

### 0.1.1.0

- ボリュームや物理ドライブから開く情報ウィンドウを、ボリューム/ドライブ毎の単一ウィンドウ（シングルトン）に変更（以前は同じボリューム/ドライブのウィンドウを複数開くことができた）。

- MDI子ウィンドウを最大化している時に新しいウィンドウを開いた時、メインメニューがちらつく現象を回避。

- その他コード整理、スペルミス修正など。 

### 0.1.0.0

- GitHubに公開。

