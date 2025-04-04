# 📝 作業ログ

## 📌 記録の凡例
- 👨‍🏫 メンターのご指導日
- ✅ 完了したタスク
- 📝 次回のタスク
- 📌 メモ・気づき

> 💡 メンターのご指導内容は[mentor_notes.md](./mentor_notes.md)で管理しています。

## 【**2025/04/05**】学習記録管理の改善

### 完了したこと ✅
- memo_followup.mdファイルの作成
- 師匠への確認事項と自分で調べることを記録する仕組みの整備
- ワークログにその日学んだ単語を記録する仕組みを追加
- コマンドフレーズ「確認メモに追加して」と「調査メモに追加して」を追加


### 次回やること 📝
- JavaScript学習の継続
- フォローアップメモへの項目の追加

### メモ 📌
- memo_followup.mdを表形式で管理することで視認性が向上
- 状態を「未」「済」で管理することでタスク完了状況が一目でわかるようになった

## 【**2025/04/05**】アコーディオン部分のCSS解読

### 完了したこと ✅
- アコーディオン部分のCSS解読
- Chromeの検証機能とcursorの解説を活用したコード理解
- コードにコメントを残すことで理解が深まる学習手法

### 学んだこと 📚
- 特定のCSSセレクタを検証したい場合、Chrome検証の左上矢印でエレメント選択にして要素を選択すると下のパネルに関連したCSSやJavaScriptの項目が出てくる
- コードにコメントを残すことで自分の理解を整理し、後から見返した時にも分かりやすくなる

### 今日学んだ用語 📖
- **セレクタ**: CSSでスタイルを適用する対象を指定する部分（例: `h1 { color: red; }` の `h1`）
- **クラス**: 複数の要素に同じ名前をつけて共通のスタイルを適用する仕組み
- **アコーディオンヘッダー**: クリック可能なUI要素で、コンテンツの表示/非表示を切り替える部分

### 次回やること 📝
- JavaScriptの学習継続
- アコーディオンメニューのJavaScript部分の理解

### メモ 📌
- 検証時に探したいセレクタが見つからない場合は重複項目で上書きされている場合もある

## 【**2025/04/05**】アコーディオンメニューのファイル作成

### 完了したこと ✅
- WEB SKILLセクションのデザインをアコーディオンメニュー仕様に変更
- アコーディオンメニューのヘッダーテキスト色の調整
- 左側カラー部分の幅調整とデザイン修正
- Chromeの検証機能とcursorの解説を活用したコード理解

### 学んだこと 📚
- CSSパディング指定の5通り：
  - 個別: `padding-top/right/bottom/left`
  - 4値: `padding: 上 右 下 左`（時計回り）
  - 3値: `padding: 上 右左 下`
  - 2値: `padding: 上下 右左`
  - 1値: `padding: 全方向`
- CSSの重複スタイル定義の優先順位：
  - 詳細度高い方が優先（インラインスタイル > ID > クラス > 要素）
  - 同じ詳細度なら後に書かれた方が優先
  - 学習目的では未使用のコードも参考として残しておくと有益

### 次回やること 📝
- ファイル内容理解をすることでアコーディオンメニューを習得

### メモ 📌
- 青い帯の幅は65pxから70pxに調整し、ラベルテキストの視認性を向上させた

## 【**2025/04/04**】HTML/CSSファイルの理解を深める

### 完了したこと ✅
- 課題の完成HTMLファイルとCSSファイルの理解を深める
- CSSの構造とプロパティの関連性を確認

### 学んだこと 📚
- HTMLとCSSファイルの構造

### 次回やること 📝
- JavaScriptの基礎学習を開始
- HTMLとCSSの連携部分の理解を深める
- 学習した内容を活用した小さなプロジェクトの計画

### メモ 📌
- デバッグにはブラウザの開発者ツールが非常に役立つ
- CSSファイルの詳細理解はJavaScriptの学習と同時に進める

## 【**2025/04/03**】プロフィールカードのデザイン最終調整

### 完了したこと ✅
- プロフィールカードのデザイン最終調整
- ラベルの配置と表示の最適化
- スキルボタンのデザイン改善と複雑なアニメーションの削除
- レイアウトの微調整と洗練化
- 文章の改行を自然な形に修正

### 学んだこと 📚
- デザインにおける統一感の重要性
- 無駄なアニメーションを削除してシンプルに保つことの価値
- 左ボーダーを活用したラベル表示テクニック
- レイアウトの一貫性がもたらす視覚的な美しさ

### 次回やること 📝
- LEVELタグの調整
- ABOUT MEの文章推敲
- AIに文章スペルチェックをしてもらう
- 下部の枠２つの色の修正
- リンクの追加

### メモ 📌
- デザインは「引き算」の芸術である
- 複雑なエフェクトよりもシンプルで洗練されたデザインの方が使いやすい
- 文章の区切りと改行は読みやすさに大きく影響する

## 【**2025/04/03**】CSS基礎課題デザインの完成

### 完了したこと ✅
- CSS基礎課題デザインの完成
- 昨日のデザインから軽微な修正
- 修正に苦戦していた縦列の配置に成功

### 学んだこと 📚
- 「guideline-text」という共通クラスを作って、すべての段落に同じスタイルを適用
- ABOUT MEとVISIONセクションの縦列が合わなかったので両方の文章にその共通クラスを直接指定
- タグの種類が違っても同じクラスを使うことで、ブラウザの解釈の違いを克服し、強制的に見た目を揃えることができる

### 次回やること 📝
- HTML、CSSファイルの理解
- 各ファイル内にコメントにて解説を記載することにより理解を深める
- ファイル内容を自分の口で解説できるようにする

## 【**2025/04/02**】課題仕様書作成と改善点洗い出し

### 完了したこと ✅
- CSS基礎教材課題①の仕様書を作成
- 作成途中の課題の改善点の洗い出し
- 仕様書作成を通じて目的やイメージの明確化

### 学んだこと 📚
- 仕様書の重要性とその作成方法
- デザイン目標を明確にすることでブレない実装が可能になる
- 改善点を先に洗い出すことで効率的な作業が可能になる

### 次回やること 📝
- 作成中課題の改善と完成
- デザインの統一感を高める修正

### メモ 📌
- 仕様書は自分のためだけでなく、他の人と共有する際にも重要
- 目的を明確にすることで、無駄な作業を減らせる

## 【**2025/04/01**】CSS基礎教材課題①のデザイン案ほぼ完成、チャットウィンドウの移動方法の振返り

### 完了したこと
- CSS基礎教材課題①のデザイン案ほぼ完成
- チャットウィンドウの移動方法の振返り

### 次回やること
- HTMLとCSSファイルの内容理解を深める

## 【**2025/03/31**】CSS基礎教材課題①とファイル命名規則の改善

### 完了したこと ✅
- CSS基礎教材課題①の環境構築
  - プロフィールカード用のHTMLファイルとCSSファイルの作成
  - 画像ファイルの準備
- ファイル作成時の命名規則の改善
  - 日本語のローマ字表記を避ける
  - HTMLファイルとCSSファイルは一般的な名前（index.html, style.css）を使用し、区別はフォルダ名で行う
- .cursorrulesにファイル命名に関するルールを追加

### 学んだこと 📚
- ファイル命名規則の重要性と業界標準
  - 日本語のローマ字表記を避けることでグローバルな理解がしやすくなる
  - index.html, style.cssなどの一般的な名前を使うことでの利点
- フォルダ構造による課題の整理方法
  - 日付フォルダを使って課題を整理する手法

### 次回やること 📝
- CSS基礎教材課題①のスタイリング実装
- CSS基本プロパティ（カラー、フォント、ボックスモデル）の学習と適用

### メモ 📌
- Web開発におけるファイル命名の慣習は重要
- 師匠からのファイル命名に関するアドバイスは実務でも役立つ知識

## 【**2025/03/30**】友達へのGitHub学習状況報告とフィードバック

### 完了したこと ✅
- 友達にGitHub上で学習状況を報告
  - これまでの学習経過と学習方法について詳細に説明
  - プログラミング初心者向けに専門用語を噛み砕いて説明
  - 学習記録の継続性とその効果について共有
- 学習内容の再整理と目標の明確化

### 学んだこと 📚
- 他者へのアウトプットが自己理解を深める効果
  - 専門知識を初心者向けに説明することで自分の理解が深まる
  - 説明する過程で知識の欠落部分が明確になる
- 第三者視点からのフィードバックの重要性
  - 客観的な意見が新たな気づきをもたらす
  - モチベーション維持における共有と称賛の効果

### 次回やること 📝
- HTML/CSS学習の継続
- 定期的な学習状況の共有と振り返りの習慣化

### メモ 📌
- 言語化していくことの大切さ
- AIとの関係性の築き方


## 【**2025/03/30**】師匠への進捗確認と振り返り、HTMLリストのカスタマイズ

### 完了したこと ✅
- HTML基礎教材課題①完成
- HTMLファイル内にコメントアウトで解説を記載することで理解を深めた
- OPEN IN defaultbrowserのインストール
- github上で学習状況をスクショを用いて振り返る方法を習得
　- readmeにスクショを用いた学習記録を追加


- 師匠に学習進捗を確認してもらう
- 昨日の学習内容の振り返り
- 作業ログと時間ログの更新
- HTMLでの順序付きリスト（OLタグ）のカスタマイズ方法の学習
  - リスト番号を「1位、2位、3位」のように表示する3つの方法を習得
 


### 学んだこと 📚
- GitHubでの学習経過の見せ方の重要性
  - 課題のスクリーンショットを貼ると経過がわかりやすい
  - プログラミングに詳しくない人にも理解できる説明の重要性
- 学習記録の継続的な更新の価値
- style="list-style-type: none;"の活用方法
- コピーライト表示の意味と使い方
- メタデータの役割と重要性

### 次回やること 📝
- HTML教材の練習課題の続き
- CSS基礎の学習開始

### メモ 📌
- 師匠からのアドバイス詳細は[mentor_notes.md](./mentor_notes.md)を参照
- 学習記録の継続が自分の成長を可視化する重要なツールになっている
- HTMLリストのカスタマイズはCSSの理解を深める良い練習になった

## 【**2025/03/29**】.cursorrulesとrules for AIの違いについて学習、ルール追加、HTML教材の練習課題

### 完了したこと ✅
- @WEBを使ったウェブ検索機能の使用方法を学習
- rules for AIと.cursorrulesの違いと使い分けについて理解
- .cursorrulesファイルへのルール追加
  - 学習提案はワークログの次回やることを中心にすること
  - 学習提案はロードマップとweb-basicsに基づくこと
  - 教材はweb-basicsファイル内を指すことを明示
- HTML教材の練習課題に取り組み
  - 作成したHTMLファイル内でタグやコードの意味をコメントアウトして記録

### 学んだこと 📚
- Cursor IDEのウェブ検索機能：@WEBをつけるとウェブ検索が実行できる
- rules for AIとcursorrulesの違い：
  - rules for AI：広範なAIツール全般に適用される倫理的・法的なガイドライン
  - .cursorrules：Cursor IDE専用の設定ファイルで、AIアシスタントの動作をプロジェクト固有にカスタマイズするためのもの
- 文字コードとUTF-8について：
  - 文字コードはコンピュータが文字を扱うための数値表現システム
  - **Web開発では特に重要で、HTMLファイルの文字コード指定がないとブラウザが文字化けを起こす可能性がある**
  - 現代のWeb開発ではUTF-8が国際標準として使用される
  - HTMLでは `<meta charset="UTF-8">` で指定する
- HTMLのタイトルタグの役割：「Webページの名前を定義し、ブラウザ、検索エンジン、ユーザーがページを識別するための最重要メタデータ」
- HTMLのヘッダータグとは：Webページの上部に表示される導入エリアで、サイトのタイトル・ロゴ・メニューなどを配置する場所
- HTMLのリストタグの使い分け：
  - `<ul>`: 順序なしリスト（箇条書き）。項目の順番に意味がない場合
  - `<ol>`: 順序ありリスト（番号付き）。項目の順番に意味がある場合
  - `<li>`: リスト項目。`<ul>`または`<ol>`の中で使用
- HTMLタグの具体的な使い方と実践：
  - 学習したタグの実際の使い方を練習課題で実践
  - コメントアウト機能を活用してコードの理解を深める

### 次回やること 📝
- CSS練習課題に取り組む
  - プロフィールカードのスタイリング（課題1）
  - レスポンシブ対応の実装（課題2）
  - カラーパレットの作成と適用（課題3）
- JavaScript基礎の学習開始

### メモ 📌
- .cursorrulesはプロジェクト固有の設定を行うための重要なファイル
- ウェブ検索機能は最新の情報を得る際に非常に便利な機能
- 定期的にルールを更新することでAIとの効率的なコミュニケーションが実現できる
- HTMLコメントアウトのショートカット：Mac（Command + /）、Windows（Ctrl + /）
- サジェストは[Tab]キーで決定する


## 【**2025/03/28**】Gitのステージングとコミットについての理解、教材の作成と理解、readme更新

### 完了したこと ✅
- Gitのファイル状態記号（U、M、A、D、R、C、?）について学習
- ステージングとコミットの概念を深く理解
- 各種ログファイル（技術用語辞典、メモ、ワークログ）にGit関連情報を追記
- .cursorrulesファイルの更新（コミットメッセージに関するルール追加）
- .cursorrulesへの理解を深める
- 教材の追加・修正
- README.mdの更新
- 教材内容の理解と復習

### 学んだこと 📚
- Gitファイル状態記号の意味と使い方：
  - U (Untracked): 追跡されていない新しいファイル
  - M (Modified): 変更されたファイル
  - A (Added): ステージング領域に追加されたファイル
  - D (Deleted): 削除されたファイル
  - R (Renamed): 名前変更されたファイル
  - C (Copied): コピーされたファイル
  - ? (Untracked): 未追跡ファイル
- ステージングとコミットの違いと役割：
  - ステージング: 変更をコミット前に準備する段階
  - コミット: 変更を記録としてリポジトリに保存する段階

### 次回やること 📝
- CSS練習課題の継続
- JavaScript基礎の学習開始

### メモ 📌
- ファイル状態記号を理解することで、Gitの状態をより正確に把握できるようになった
- CursorやVSCodeでのGit操作がより直感的になった
- コミットメッセージの統一ルールを設定したことで記録の一貫性が保てる

## 【**2024/03/27**】.cursorrulesファイルの作成と更新

### 完了したこと ✅
- メンターノートの更新
- .cursorrulesファイルの作成・更新
- GitHubへの手動プッシュ実践

### 次回やること 📝
- ルールは随時更新する
- .cursorrulesの継続的な改善
- GitHubへの変更項目ごとのプッシュの実践

### メモ 📌
- .cursorrulesはAIとのコミュニケーションを効率化するための重要なファイル
- 記録の更新ルールを明確にすることで作業効率が上がる

## 【**2024/03/27**】師匠とGitHubへのファイルプッシュ方法の復習

### 完了したこと ✅
- GitHubへのファイルプッシュ方法の復習
- 進捗状況の確認

### 学んだこと 📚
- GitHubへのプッシュは変更項目ごとに行うと良い
- ファイル名の作り方や学習の進め方の提案は.cursorrulesに記載
- READMEと.cursorrulesの役割の違いを理解

### 次回やること 📝
- .cursorrulesの作成
- ファイル名の改善（ローマ字を避ける）
- 変更項目ごとのプッシュ方法の実践

### メモ 📌
- README：仕様書、人に向けて
- .cursorrules：AIに向けて

## 【**2024/03/26**】Privateページの実装と学習計画ツールの作成

### 完了したこと ✅
- Privateページの作成と実装
- ハンバーガーメニューのJavaScript機能実装
- 学習ロードマップとスキルチェックリストの作成
- SKILL & VISIONページの内容更新
- デザインの改善（パステルカラー化とシンプル化）

### 学んだこと 
- CSSのカラー変数を使用した効率的なスタイリング
- 学習計画管理の方法論
- レスポンシブデザインのベストプラクティス

### 次回やること 📝
- JavaScriptの基礎学習
- サイト内ページ遷移のスムーズスクロール実装
- モバイル表示の最適化
- 過去NOTIONメモの見直し
- モデルとなるWEBページを探す
- 快適なWi-Fi環境の整備

### メモ 📌
- Cursor上でのGit操作方法：
  1. 左サイドバーの「ソース管理」アイコン（分岐マーク）をクリック
  2. 変更ファイル横の「+」でステージング追加
  3. コミットメッセージを入力して「✓」をクリック
  4. 「...」メニューから「プッシュ」を選択

## 【**2024/03/25**】自己紹介ページの作成と更新

### 完了したこと ✅
- 自己紹介ページの作成と更新
  - プロフィール画像の設定
  - Skill & Visionページの構造改善
  - 学習目標の更新（短期・中期・長期）

### 学んだこと 📚
- セマンティックHTMLの実践
- CSSのFlexboxを使用したレイアウト
- レスポンシブデザインの実装

### 次回やること 📝
- Privateページの作成
- ハンバーガーメニューのJavaScript実装

### メモ 📌
- AIのモードがなぜかAUTOに切り替わっていた
- サイト構造を理解しきれていない、完成したら一つ一つコメントつけながら見直していきたい

## 【**2024/03/24**】.mdファイルと.cursorrulesの違いを学ぶ

### 学んだこと 📚
- .mdファイルと.cursorrulesの違いを理解
  | 項目 | .mdファイル | .cursorrules |
  |------|-------------|--------------|
  | 拡張子 | .md | .cursorrules |
  | 用途 | ドキュメント作成 | AIとのコミュニケーションルール設定 |
  | プレビュー | 可能 | 不可 |
  | 記法 | Markdown記法 | シンプルテキスト |
  | 主な機能 | ・見出し<br>・リスト<br>・テーブル<br>・画像挿入<br>・リンク | ・ルール設定<br>・作業フロー定義<br>・プロジェクト規約 |
  | 使用目的 | ドキュメント作成・説明文 | AIとの効率的なコミュニケーション |

### 次回やること 📝
- .cursorrulesの継続的な改善
- GitHubへの変更項目ごとのプッシュの実践

### メモ 📌
- .mdファイルはドキュメント作成用、.cursorrulesはAIとのコミュニケーション設定用
- それぞれのファイル形式に適した使い方を心がける

## 【**2025/04/04**】
### 学習開始： 8:00

#### 学習内容
- 師匠と学習状況と今後の見通しを確認
- CSS課題を見てもらう
- JavaScriptのアコーディオンメニューを実装
- 学んだことの記録
- 今後の制作物を検討

#### 気づき/学び
- アコーディオンメニューはJavaScriptの基本的な機能だが、実装方法には様々なバリエーションがある
- CSSとJavaScriptの連携が重要で、クラスの付け外しによる表示制御がポイント
- 今後の制作物としてポートフォリオサイトの構想を固めていく

#### 次回やること
- アコーディオンメニューの機能を完成させる
- スムーズなアニメーション効果を追加する
- ポートフォリオサイトのワイヤーフレーム作成

## 【**2025/04/04**】
### 学習時間：14:30-15:30, 16:00-18:00, 23:30-0:00（合計3.5時間）

#### 学習内容
- 師匠と学習状況と今後の見通しを確認
- CSS課題を見てもらう
- JavaScriptのアコーディオンメニューを実装
- 学んだことの記録
- 今後の制作物を検討

#### 気づき/学び
- アコーディオンメニューはJavaScriptの基本的な機能だが、実装方法には様々なバリエーションがある
- CSSとJavaScriptの連携が重要で、クラスの付け外しによる表示制御がポイント
- 今後の制作物としてポートフォリオサイトの構想を固めていく

#### 次回やること
- アコーディオンメニューの機能を完成させる
- スムーズなアニメーション効果を追加する
- ポートフォリオサイトのワイヤーフレーム作成

## 【**2025/03/24**】技術用語・ショートカット辞典の作成

### 完了したこと ✅
- 昨日の振り返り、ワークログ作成
- 技術用語・ショートカット辞典を作成
  - Gitおよびショートカット関連の用語を整理
  - Mac、Cursorのショートカットをカテゴリ別に記録
  - WEB関連用語（GUIとCUI）の追加
- 今日のファイル更新内容をgitへプッシュ

### 次回やること 📝
- 技術用語・ショートカット辞典の更新
- .cursorrulesの作成
- userrulesの更新


## 【**2025/03/23**】GitHubへのファイルプッシュ方法を学ぶ

### 完了したこと ✅
- GitHubへのファイルプッシュ手順を学習
  - git add、git commit、git pushの基本的な流れを理解
  - READMEにGitHubの使い方を追記
  - メンターノートの記録方法を統一（新しい記録を上部に配置）
  - READMEにもメンターノートの記録方法について追記

### 次回やること 📝
- 教材を進めながら日々のファイル更新をGitHubにプッシュする習慣をつける
- 覚えた用語やショートカットを表形式にまとめる

### メモ 📌
- 作業ツリー上で直接編集しないように注意
- Claude-3.7-Sonnetを活用してAIの解説を理解する
- わからない用語は随時調べて理解を深める

## 【**2025/03/22**】mac初期化、データ復旧作業

### 完了したこと ✅
- mac初期化作業
- データ復旧作業

## 【**2025/03/21**】振り返り

### 完了したこと ✅
- cursorにおやすみ言った
- ワークログとメモの振り返り

## 【**2025/03/20**】GitHubリポジトリ作成

### 完了したこと ✅
- GitHubアカウントの作成
  - アカウント設定
  - 2段階認証の設定
- リポジトリの作成
  - リポジトリ名：web_study
  - パブリック設定

### 次回やること 📝
- プロジェクトのバージョン管理の実践
  - ローカルのstudyフォルダをGitHubにプッシュ（アップロード）

### メモ 📌
・リポジトリはプロジェクトの保存場所。変更履歴も保存される賢いフォルダ
・パブリック（公開）とプライベート（非公開）の2種類がある
・命名規則：小文字、アンダーバー、英数字のみ使用
・プッシュ：ローカルのファイルをGitHubのリポジトリにアップロードすること

## 【**2025/03/20**】夜間学習開始

### 開始したこと ✅
- 20:30から学習開始

### 次回やること 📝
- GitHubアカウントの作成
- プロジェクトのバージョン管理の実践

### メモ 📌
・夜間の学習は集中力が高まる時間帯
・適度な休憩を取ることを心がける

## 【**2025/03/20**】Gmailアカウント作成とワークログ整備

### 完了したこと ✅
- Gmailアカウントの作成
- 午前中の振り返り
  - 作業内容の整理
  - 時間管理の更新

### 次回やること 📝
- GitHubアカウントの作成

## 【**2025/03/19**】WEBページ仕様書と構成設計

### 完了したこと ✅
- WEBページ仕様書作成
- HTML構成設計

### メモ 📌
・深夜の時間帯を活用して設計作業を進めた
・構造を明確にすることで次の実装がスムーズになる

## 【**2025/03/18**】WEBページ設計と復旧作業

### 完了したこと ✅
- HTMLファイル消失の復旧作業
- WEBページ仕様書作成
- WEBページ構成をノートに書いた

### 学んだこと 📚
- データ管理の必要性
  - バックアップの重要性
  - 定期的な保存の習慣づけ

### 課題 📋
- 的確な指示の出し方
  - 要求を明確に伝える方法
  - 効率的なコミュニケーション

### メモ 📌
・他のファイルの情報も参照して開発を進める

## 【**2025/03/17**】CSS基礎の学習

### 完了したこと ✅
- CSS基礎：自己紹介ページの基本スタイリング

## 【**2025/03/16**】セマンティックHTML演習の完了

### 完了したこと ✅
- 自己紹介ページの構造化
  - セマンティックHTMLの実践
  - 適切なタグの使い分け
  - 学習目標と動機の整理
- 各セクションの内容充実
  - SKILL（WORK/WEB/PRIVATE）
  - VISION（GOAL/MOTIVATION）
  - PRIVATE（BASIC INFO/FAVORITES）

### 次回やること 📝
- CSSによるスタイリング
- レスポンシブデザインの適用
- アクセシビリティの向上

### メモ 📌
【今日使用したタグの説明】
・`<header>`: ページのヘッダー部分を定義
・`<main>`: メインコンテンツを囲む
・`<section>`: 関連する内容をグループ化
・`<article>`: 独立したコンテンツを定義
・`<div>`: 汎用的なグループ化
・`<h1>-<h4>`: 見出しの階層構造
・`<ul>`: 順序なしリスト
・`<ol>`: 順序付きリスト
・`<li>`: リストの項目
・`<p>`: 段落
・`<strong>`: 重要な文字列の強調
・`<br>`: 改行
・`<a>`: ハイパーリンク
・`<footer>`: ページのフッター部分を定義

## 【**2025/03/16**】HTML基礎演習と環境整備

### 完了したこと ✅
- HTML基礎演習：自己紹介ページの作成
- studyファイルの構造整理
  - memoディレクトリの作成と整理
  - 学習記録用ファイルの体系化
- 学習動機の整理と文書化
- ショートカット機能の学習と記録

### 反省点 📝
- 自己紹介の内容検討に予定以上の時間（30分）を要した
- 改行時のショートカット（Shift + Enter）に慣れておらず、操作にロスが発生
- 作業中のメモ取りとワークログ記録は順調に実施できた
- メモ環境の整備に時間を使ったが、今後の学習をスムーズにする基盤ができた
- 自己紹介ページ作成を通じて学習動機を明確化できた

### 今後の展望 🎯
- 自己紹介ページの完成
  - セマンティックHTML化の実施
  - CSSを活用したデザイン適用
- 整理した学習動機と目標を基に学習計画を具体化
- 効率的な作業のためのショートカット習得

### メモ 📌
【今日の気づき】
・自己紹介ページを作ることで、自分の学習動機や目標が明確になった
・ファイル構造を整理することで、学習記録の取り方が改善された
・ショートカットの重要性を実感、効率化のために優先的に習得する必要性

## 【**2025/03/16**】振り返りと記録改善

### 完了したこと ✅
- 昨日の学習内容の振り返り
- READMEの改訂とワークログの整理
- Composerを活用した質問対応と記録
  - セマンティックHTMLについての理解深化
  - 記録方法の改善

### 次回やること 📝
- HTML基礎の実践演習
- Composerでの質問スキル向上
- 学んだ内容の復習と整理

### メモ 📌
【今日の成果】
・Composerを積極的に活用し、AIとの対話を通じて記録作成
・質問の仕方を工夫し、より効果的な回答を得られるように
・手打ちではなくAIを活用することで、より効率的な学習記録の実現

【工夫したポイント】
・ワークログをComposer上で作成し、AIへの質問力を向上
・昨日の疑問点を整理して質問することで理解を深化
・記録の仕方を改善し、より分かりやすい形式に

【今日学んだこと】
・Composerを積極的に活用し、AIとの対話を通じて記録作成
・質問の仕方を工夫し、より効果的な回答を得られるように
・手打ちではなくAIを活用することで、より効率的な学習記録の実現
・サジェスト機能は`Tab`キーで決定すると素早く入力できる

## 【**2025/03/15**】うーろん先生のCursorスタートアップ講座

### 完了したこと ✅
- プロジェクトの初期設定
- README.mdの作成
- HTML基礎の解説ファイル作成
  - 基本構造の説明
  - タグの使い方
  - 実践例の追加
- CSSの基本概念の理解
- 基本的なスタイリング方法の学習
- テキストスタイリングの実践

### 次回やること 📝
- CSS基礎の解説ファイル作成
- 自己紹介ページのスタイリング
- レスポンシブデザインの説明
- ボックスモデルの詳細学習
- レイアウトの基礎
- 自己紹介ページのスタイリング続き

### メモ 📌 
【セマンティックHTML】
セマンティックHTMLとは、HTMLの要素に適切な意味付けを行い、文書の構造を明確に表現する記述方法です。従来の`<div>`や`