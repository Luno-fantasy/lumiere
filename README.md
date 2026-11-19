# LUNOSTILL

画像生成プロンプトのライブラリと、キャラクター・イベントCG用のプロンプト工房。

- `index.html` は共通の入口です。
- `library/` に7コレクションのHTML、検索・コピー機能、サンプル画像を収録しています。
- `atelier.html` ではプロンプトの自動分解、キャラクターの管理、イベントCG用プロンプトの生成を行えます。

公開先は [GitHub Pages](https://luno-fantasy.github.io/lunostill/) です。ビルドは不要です。
ローカルではリポジトリ直下で `python -m http.server 8000` を実行して確認できます。

キャラクターは同じブラウザの `lunostill.characters` に保存されます。別の端末やブラウザへ移すときは、ATELIERの「JSON書出」「JSON読込」を使ってください。
