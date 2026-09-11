# Blue Diary 玄関ページ

「Blue Diary」（本体はGoogle Apps Script）をiPhoneのホーム画面にアイコンとして置くための玄関ページ。
GASの画面をiframeで表示するだけの小さなPWA。GitHub Pagesで公開（.nojekyll あり）。

## ファイル

- index.html：玄関ページ本体（iframe・読み込み中画面・ログイン状態の保持）
- manifest.webmanifest／icon-*.png：ホーム画面アイコン用

## 決まり

- 本体の機能はGAS側にある。ここではアイコン配信とiframe表示に関することだけを扱う
- テーマ色はBFPブルー #0050BD
- コミットは日本語メッセージ。mainに直接push

## 本部（gf-headquarters）への報告【セッション終了前に必ず】

このプロジェクトの記録は本部vaultにもある：
/Users/ogino/dev/gf-headquarters/40_自社ツール/Blue Diary/

セッションを終える前に、必ず次を行う。

1. 上のフォルダの経緯.md に、今日やったこと・決めたことを日付つきで1〜3行足す
2. 次に活かせる学び（失敗・勝ちパターン）があれば 学び.md に足す
3. 誰かに頼んだこと・期限のあることがあれば 宿題と約束.md に足す（期限の正はGrass ToDo）
4. 本部フォルダのほかのファイルは書き換えない。書きたいことがあれば経緯.mdに「本部への相談」として書く

書き方は小学5年生でもわかる言葉で。会社名は「株式会社Grass Family.」（最後のピリオド必須）。
