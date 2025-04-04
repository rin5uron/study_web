# 📝 学習メモ

## 📌 メモの書き方
- 日付と内容を明確に記載
- 必要に応じてカテゴリ分けを行う
- 重要なポイントは強調して記載

## 【環境設定】
- 使用PC：MacBook Air
- OS：macOS
- 主要アプリケーション：VSCode, Chrome

## WEB用語

### マークダウン記法（Markdown）
テキストを構造化するための軽量マークアップ言語。主な記法：
- `#`：見出し（# 大見出し、## 中見出し）
- `-` or `*`：箇条書きリスト
- `1.`, `2.`：番号付きリスト
- `**太字**`：**太字**表示
- `*斜体*`：*斜体*表示
- `` `コード` ``：`コード`表示
- `[リンク](URL)`：ハイパーリンク
- `![代替テキスト](画像URL)`：画像挿入

GitHubやNotion等で広く使用される。HTMLより簡潔に記述可能。

## 【CSS関連】

### リセットスタイル
ブラウザの標準スタイル設定をリセットして、全ブラウザで一貫したデザインの土台を作るためのCSSコード。

```css
{
    margin: 0;      /* すべての余白をゼロに */
    padding: 0;     /* すべての内部余白をゼロに */
    box-sizing: border-box; /* ボーダーとパディングを幅と高さに含める */
}
```

**目的**：
- ブラウザごとの見た目の違いをなくす
- 予期せぬスタイルの干渉を防ぐ
- 一からデザインを構築しやすくする

**主な種類**：
- シンプルリセット：上記のような最小限のコード
- Normalize.css：過度にリセットせず、有用なデフォルト設定は残す
- Reset CSS (Eric Meyer)：すべてのスタイルを徹底的にリセット

### フォントフォールバックシステム
CSSでフォントを複数指定する仕組みで、環境によって最適なフォントを表示するための技術。

```css
body {
    font-family: 'Helvetica Neue', Arial, sans-serif;
}
```

**詳細な説明**：
1. **優先順位方式**：左から順に適用を試みる
   - 最初の'Helvetica Neue'が存在すればそれを使用
   - なければ2番目のArialを使用
   - それもなければ最後のgeneric family（sans-serif）を使用

2. **主な目的**：
   - クロスプラットフォーム互換性の確保（Windows、Mac、Linuxなど）
   - デザインの一貫性を保つ
   - すべての環境で確実に表示を保証する

3. **フォント指定の種類**：
   - 具体的なフォント名：'Helvetica Neue', Arial, Roboto など
   - ジェネリックファミリー：sans-serif, serif, monospace, cursive, fantasy
     - 必ず最後にジェネリックファミリーを指定するのが良い習慣

4. **Webフォントとの併用**：
   - Google FontsやAdobeフォントなどのWebフォントを使用する場合も、
     フォールバックとしてローカルフォントを指定することが推奨される

### Flexboxレイアウト
CSSの強力なレイアウト機能で、要素を柔軟に配置・整列させるための仕組み。

```css
body {
    display: flex;         /* フレックスボックスレイアウト */
    justify-content: center; /* 水平方向の中央揃え */
    align-items: center;   /* 垂直方向の中央揃え */
    min-height: 100vh;     /* ビューポートの高さいっぱいに */
}
```

**詳細な説明**：

1. **`display: flex;`**
   - コンテナ要素に指定することで、その子要素がフレックスアイテムになる
   - デフォルトでは子要素が横並びになる（`flex-direction: row`）
   - 通常のブロックレイアウトとは異なる独自の配置ルールが適用される

2. **`justify-content: center;`**
   - メインアクシス（デフォルトでは横方向）に沿った配置を制御
   - 主な値：
     - `flex-start`：先頭（左）揃え（デフォルト）
     - `flex-end`：末尾（右）揃え
     - `center`：中央揃え
     - `space-between`：両端揃えで、アイテム間の間隔を均等に
     - `space-around`：アイテムの周囲の間隔を均等に
     - `space-evenly`：すべての間隔を完全に均等に

3. **`align-items: center;`**
   - クロスアクシス（デフォルトでは縦方向）に沿った配置を制御
   - 主な値：
     - `stretch`：コンテナの高さいっぱいに伸ばす（デフォルト）
     - `flex-start`：上揃え
     - `flex-end`：下揃え
     - `center`：中央揃え
     - `baseline`：テキストのベースラインで揃える

4. **`min-height: 100vh;`**
   - `vh`は「viewport height」の略で、表示領域の高さに対する相対値
   - `100vh`は表示領域（ブラウザの表示部分）の高さの100%を意味する
   - 画面サイズに関わらず、コンテンツを画面いっぱいに表示できる
   - `min-height`を使うと、コンテンツが増えた場合に自動的に拡張される

**このコードの効果**：
上記のコード組み合わせにより、ページの内容を画面の中央（水平・垂直方向とも）に配置し、どんな画面サイズでも最低でも画面いっぱいの高さを確保します。プロフィールカードなど、単一の要素を画面中央に美しく配置するのに最適な方法です。

### CSSの重複スタイル定義の優先順位
CSSで同じ要素に対して複数のスタイル定義がある場合の適用ルール：

```css
/* 優先順位の基本原則 */
1. 詳細度が高いセレクタが優先される
2. 同じ詳細度なら後に書かれたスタイルが優先される
3. !important指定は最優先される（通常は使用を避ける）
```

詳細度の強さ順：
- インラインスタイル（style属性）> ID > クラス > 要素
- 例: #header > .header > div
- 複合セレクタは合算される（例: div.header > .header）

これは「カスケーディング」（継承と上書き）のルールと呼ばれるCSSの基本原則の一つ。

### パディング（padding）の表記方法
CSSのパディング指定は以下の5通りあります：

```css
/* 1. 四辺個別指定 */
padding-top: 10px;    /* 上 */
padding-right: 20px;  /* 右 */
padding-bottom: 15px; /* 下 */
padding-left: 25px;   /* 左 */

/* 2. 一括指定（4値）- 時計回り：上→右→下→左 */
padding: 10px 20px 15px 25px;

/* 3. 一括指定（3値）- 上、右左、下 */
padding: 10px 20px 15px; /* 左=右の値(20px) */

/* 4. 一括指定（2値）- 上下、右左 */
padding: 10px 20px; /* 上=下(10px), 右=左(20px) */

/* 5. 一括指定（1値）- 全方向同じ値 */
padding: 10px; /* 上下左右すべて10px */
```

🔑 **覚え方**: 時計回りに「上→右→下→左」、省略時は対応する値が使われる

## 【サジェスト機能の使い方】
### 基本的な使い方
- 文字を入力すると自動的に候補が表示される
- 候補の選択方法：
  - `Tab`キーで確定（最優先）
  - 矢印キー（↑↓）で選択し、`Enter`キーで確定
  - マウスでクリックして選択

### 手動で候補を表示する方法
- Mac: `Command + Space`
- Windows/Linux: `Ctrl + Space`

## 【HTMLのショートカット入力】
### リストタグの入力方法
- 順序なしリスト（ul）: `ul>li*3` + `Tab`
  - 結果：3つの`<li>`タグを持つ`<ul>`が生成される
- 順序付きリスト（ol）: `ol>li*3` + `Tab`
  - 結果：3つの`<li>`タグを持つ`<ol>`が生成される
- リスト項目の追加: `li` + `Tab`

### 順序付きリスト（OL）で「1位、2位、3位」のように表示する方法
1. **CSSで「位」を追加する方法**
   ```css
   ol li::after {
     content: "位";
   }
   ```

2. **リスト項目に直接記述し、デフォルトの番号を非表示にする方法**
   ```html
   <ol style="list-style-type: none;">
     <li>1位: 山田太郎</li>
     <li>2位: 鈴木一郎</li>
     <li>3位: 佐藤花子</li>
   </ol>
   ```

3. **カスタムカウンターを使用する方法（最も柔軟）**
   ```css
   ol {
     counter-reset: ranking;
     list-style-type: none;
   }

   ol li::before {
     counter-increment: ranking;
     content: counter(ranking) "位";
     margin-right: 8px;
   }
   ```

   ```html
   <ol>
     <li>山田太郎</li>
     <li>鈴木一郎</li>
     <li>佐藤花子</li>
   </ol>
   ```

**注意点**: 方法2を使用する場合、OLタグのデフォルト番号と記述した「1位」が重複表示されるため、必ず `list-style-type: none;` で番号を非表示にすること。

## Git・GitHub関連

### 基本用語
- リポジトリ：プロジェクトの保存場所。変更履歴も保存される賢いフォルダ
- プッシュ：ローカルのファイルをGitHubのリポジトリにアップロードすること
- ステージング：変更したファイルをコミット前に準備するプロセス。次のコミットに含めるファイルを指定する作業

### ステージングについて
- 目的：どのファイルの変更をコミットに含めるかを選択すること
- 実行方法：`git add <ファイル名>`