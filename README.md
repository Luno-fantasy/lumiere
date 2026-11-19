# LUMIÈRE（リュミエール）

物語の一瞬に、光を灯す。ÉTERNOAの姉妹サイトです。

- `index.html` は共通の入口です。
- `library/` に5コレクションのHTML、検索・コピー機能、サンプル画像を収録しています。
- `atelier.html` ではプロンプトの自動分解、キャラクターの管理、イベントCG用プロンプトの生成を行えます。

公開先は [GitHub Pages](https://luno-fantasy.github.io/lumiere/) です。ビルドは不要です。
ローカルではリポジトリ直下で `python -m http.server 8000` を実行して確認できます。

キャラクターは同じブラウザの `lunostill.characters` に保存されます。別の端末やブラウザへ移すときは、ATELIERの「JSON書出」「JSON読込」を使ってください。

## 旧URLからの移行

同じブラウザとプロファイルであれば、GitHub Pagesのホスト名が共通なのでキャラクターを引き続き読み込めます。保存キーとJSON形式は共通です。

移行前に旧URLのATELIERで「JSON書出」、新URLのATELIERで「JSON読込」を選ぶと、別のブラウザや端末にも移せます。旧版が書き出した `lunostill-characters.json` も読み込めます。
