# Flat Rate Navigator 2025

## 概要

**Flat Rate Navigator 2025** は、2025年3月時点のフラットローン金利予測（フラット20・フラット35）を基に、住宅ローンの返済計画をシンプルにシミュレーションするツールです。  
ユーザーは、物件購入価格、頭金、10年目以降の追加返済額（すべて「万円」単位）を入力するだけで、各プランの毎月返済額、10年後の残高、完済までの期間、返済総額・利息総額（概算）などを確認できます。

## 背景と目的

### 背景
- **金利上昇の予測**  
  近年、日銀の金融政策や市場金利の上昇に伴い、住宅ローン金利は上昇傾向にあります。  
  2025年3月時点では、フラット20は約1.720％、フラット35は約2.110％と予測され、今後も金利動向に注意が必要です。

- **住宅ローン選択の重要性**  
  住宅ローンは数百万円から数千万円規模の大きな資金計画です。正確な返済シミュレーションは、将来の家計計画や借入条件の判断に大きく役立ちます。

### 目的
- ユーザーが簡単な入力操作で、フラット20およびフラット35の返済シミュレーション結果を取得できるようにする。  
- 将来のローン選択や返済戦略を検討するための情報提供を支援する。  
- シンプルかつ視覚的にわかりやすいUI/UXで、誰でも直感的に利用できるツールを目指す。

## 特徴

- **シンプルな入力**  
  - 必要な入力項目は「物件購入価格」「頭金」「追加返済額」だけ。
  - 単位はすべて「万円」なので、余分な変換の手間がありません。

- **金利カスタム機能**  
  - デフォルトではフラット20は1.720％、フラット35は2.110％を適用。
  - 任意で金利を上書き可能（カスタム入力欄あり）。

- **詳細なシミュレーション結果**  
  - 毎月返済額、10年後の残高、完済までの総月数、返済総額（概算）、利息総額（概算）をテーブル形式で表示。
  - 各月の返済内訳（利息、元金返済、残高）の詳細スケジュールも折りたたみ式で確認可能。

- **美しいUI/UX**  
  - 絵文字、グラデーション背景、アニメーションを採用したフレンドリーなデザイン。
  - 入力欄のエラーチェックとリアルタイムのフィードバックにより、入力ミスを防止。

## 使い方

1. **ファイルを開く**  
   本プロジェクトは単一のHTMLファイルです。  
   ブラウザで `index.html` を開いてください。

2. **入力値を設定する**  
   - **物件購入価格**（例：4000 → 4000万円）
   - **頭金**（例：300 → 300万円）
   - **追加返済額**（例：10 → 毎月10万円の追加返済）
   ※ 入力欄にはプレースホルダーと単位の表示があり、すぐにどの値を入力すればよいか分かります。

3. **金利のカスタム設定（任意）**  
   - 「金利を上書きする（任意）」セクションで、フラット20およびフラット35の金利をカスタム入力できます。  
   - 未入力の場合は、2025年3月時点の予測金利（フラット20: 1.720％、フラット35: 2.110％）が適用されます。

4. **シミュレーション実行**  
   - 「🔍 シミュレーション実行」ボタンをクリックすると、両プランのシミュレーション結果が表示されます。
   - ローディングメッセージが表示され、計算完了後に結果と詳細スケジュール（任意）が展開されます。

5. **詳細スケジュールの確認**  
   - 結果の下部にある「詳細スケジュールを表示/非表示」ボタンで、各月の返済内訳をテーブルで確認できます。

## 注意事項

- このシミュレーション結果は概算です。  
  金利や返済条件は金融機関によって異なるため、最終的な借入れの決定にあたっては、必ず金融機関または専門家にご相談ください。

- 表示される金利は2025年3月時点の予測値です。市場動向により将来的な金利は変動する可能性があります。

## ライセンス

このプロジェクトはMITライセンスの下で公開されています。詳細はLICENSEファイルを参照してください。

---

## お問い合わせ

ご質問やフィードバックがありましたら、お気軽にIssueやPull Requestをお寄せください。

---

このツールが皆様の住宅ローン戦略の検討にお役立ちできれば幸いです！

## 更新履歴

- **2025-02-24**: ヘルプモーダル機能を追加。README.md、HowToUse.md、index.htmlをそれぞれ更新し、最新の機能とUIに合わせました。
