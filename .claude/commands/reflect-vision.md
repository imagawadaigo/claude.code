# ビジョン・哲学に反映

会話の内容をもとに `businesses/philosophy.md` を更新し、NotionのページにもSync（同期）する。

## 手順

1. **`businesses/philosophy.md` を読む**

2. **会話から反映すべき内容を判断する**
   - 原体験・ミッションに関する新たな言語化
   - 判断基準（温度テスト・きっかけテスト・双方向テスト）の更新
   - ターゲット解像度の変化
   - 「やらないこと」リストの更新
   - ミッションとの一貫性に関する気づき

3. **`businesses/philosophy.md` を編集する**
   - 既存セクションへの追記 or 修正
   - 変更後に「こう変えました」と報告

4. **GitHubにコミット・プッシュ**
   ```
   git add businesses/philosophy.md
   git commit -m "Update philosophy: [変更内容の要約]"
   git push
   ```

5. **Notionの「ビジョン・哲学」ページを更新する**
   - ページID: `33b1ff54-005f-8154-85dd-d5c69bda6965`
   - `notion-fetch` で現状確認 → `notion-update-page` で更新
   - GitHubのファイルと内容を一致させる

6. **完了報告**：何をどこに追記・変更したかを一言で伝える
