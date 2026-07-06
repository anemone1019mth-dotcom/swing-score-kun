# スイング採点くん

正面＋後方の2分割ゴルフスイング動画を読み込み、AI骨格検出で簡易採点するWebアプリです。

## 使い方

1. 左が正面、右が後方の2分割動画を選ぶ
2. 「AIチェック開始」
3. 「動画を自動サンプル採点」
4. 結果を保存、またはコピー

## GitHub Pagesで公開

1. GitHubで新しいリポジトリを作る
2. このフォルダの中身を全部アップロード
3. Settings → Pages
4. Sourceを「Deploy from a branch」
5. Branchを `main`、Folderを `/root` にしてSave

## 注意

- 採点は練習用の目安です。
- AI骨格検出はMediaPipe Poseを利用しています。
- 初回読み込みにはネット接続が必要です。
