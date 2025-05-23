## 基本

英文法に倣って語順や語系を決めること。特に、以下のような語順を意識すると、より自然な命名になります。

- 名詞 (対象物) + 動詞 (動作) + 形容詞 (種類) + 名詞 (役割)

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

## その他の命名規則

### 変数

- 変数名は、その変数の内容を明確に示す名詞を使用する。
- 真偽値の場合は、`is`や`has`などの接頭辞をつけることを検討する。（例: `isEnabled`, `hasError`)

### 関数

- 関数名は、その関数の動作を明確に示す動詞を使用する。（例: `calculateTotal`, `updateDisplay`)
