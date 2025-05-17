## 基本

英文法に倣って語順や語系を決めること

### 具体例: イベントリスナーの命名

✅ 良い例: `MessageTextViewClickEventListener`

- 語順が自然: [対象物][動作][イベント][リスナー]
- 各要素が明確:
  - 対象: MessageTextView (メッセージテキストビュー)
  - 動作: Click (クリック)
  - 種類: Event (イベント)
  - 役割: Listener (リスナー)

❌ 悪い例: `ClickListenerMessageText`

- 語順が不自然
- 対象と役割が混在
- 何のイベントなのか不明確

❌ 悪い例: `MsgTxtClickHandler`

- 略語を使用して意味が不明確
- Handler という一般的すぎる単語を使用

### 命名のポイント

1. 語順を英文法に従って自然に並べる

   - 主語(対象) → 動詞(動作) → 目的語/補語(種類・役割)

2. 略語を避け、完全な単語を使用する

   - Msg → Message
   - Txt → Text
   - Btn → Button

3. 役割を明確に示す具体的な単語を選ぶ

   - Handler → EventListener
   - Callback → ClickEventListener

4. コンポーネントの種類を明示する
   - Text → TextView
   - Button → ButtonView
