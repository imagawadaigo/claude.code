# 認知プロファイルに反映

会話の内容をもとに `businesses/cognitive-profile.md` を更新し、NotionのページにもSync（同期）する。

## 手順

1. **`businesses/cognitive-profile.md` を読む**

2. **会話から反映すべき内容を判断する**
   - 新しい思考パターン・行動のクセ
   - 新たな盲点・気づき
   - 「嫌いなこと」リストへの追加
   - 他者からのフィードバックで確認されたこと
   - 失敗パターンの更新
   - ビジョン二層構造の変化

3. **`businesses/cognitive-profile.md` を編集する**
   - 既存セクションへの追記 or 新セクションの追加
   - 「このプロファイルの更新ルール」に従い、追記後に「こう追記しました」と報告

4. **GitHubにコミット・プッシュ**
   ```
   git add businesses/cognitive-profile.md
   git commit -m "Update cognitive profile: [変更内容の要約]"
   git push
   ```

5. **Notionの「認知プロファイル」ページを更新する**
   - ページID: `33b1ff54-005f-8145-9f2f-cb34e2b7a818`
   - `notion-update-page` または `notion-fetch` → 内容確認 → 更新
   - GitHubのファイルと内容を一致させる

6. **完了報告**：何をどこに追記・変更したかを一言で伝える
