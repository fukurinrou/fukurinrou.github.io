福林楼 QR注文システム v5.6.2（4桁コード版）
2026-09-06 15:49 変更済み

上書きするファイル
- index.html
- staff.html

Firebase Rules
- firebase_rules_v562.json
  ※内容は v5.6.1 の読み取り権限修正版と同じです。
  ※すでに v5.6.1 のRulesをFirebaseで公開済みなら、Rulesの再設定は不要です。

変更内容
1. 店内確認コードを6桁 → 4桁へ変更
2. お客様側の入力欄を4桁に変更
3. 管理画面のコード生成を4桁に変更
4. 画面説明を「4桁」に統一
5. 既存のメニュー、読み上げ、写真、注文確認±ボタン、セキュリティ方式は変更なし

反映手順
1. VS Codeで index.html と staff.html を上書き
2. Source Control → Commit → Push
3. GitHub Pages反映後、管理画面を Ctrl+F5
4. 会計 → テーブル注文受付 → 受付開始
5. 4桁コードが表示されることを確認
