# 技術用語・ショートカット辞典

## JavaScript
- **配列インデックス**: 配列の要素の位置を示す番号。JavaScriptでは0から始まる。例：`const colors = ["赤", "青", "緑"]`で`colors[0]`は「赤」になる。
- **フォールスルー**: switch文でbreakがない場合に起こる現象。条件に一致したcase以降の全ての処理が実行されてしまう。意図的に使う場合もあるが、多くの場合はバグの原因になる。
- **二重ループ**: ループの中に別のループがある構造（入れ子になったループ）。外側のループは「行」、内側のループは「列」を制御することが多い。例：掛け算表では外側のループが「何の段か」、内側のループが「1から9までの掛け算」を担当する。
- **Node**: JavaScriptをブラウザ外で実行するための環境。サーバーサイドJavaScriptの実行やコマンドラインツールの開発に使われる。
- **スクレイピング**: Webサイトからデータを自動的に収集する技術。プログラムがWebページの内容を解析し、必要な情報を抽出する。
- **ループ処理**: 同じ処理を繰り返し実行するためのプログラミング構文。for文やwhile文などがあり、配列の処理や繰り返し計算に使われる。

## 命名規則
- **スネークケース**: 単語をアンダースコア(_)で区切る命名規則。例：user_name, first_login_date
- **キャメルケース**: 最初の単語は小文字で始まり、それ以降の単語は大文字で始まる命名規則。例：userName, firstLoginDate

## HTML/CSS
- **内部CSS配置**: HTMLの`<head>`タグ内に`<style>`タグを配置する場合、`<head>`の終了直前に配置するのが一般的。配置順序は通常「メタ情報→タイトル→外部CSS→内部CSS」の順になる。 