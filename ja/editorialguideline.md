# 表記ルール

mozilla.jp の表記ルールとして採用しているものを公開しています。mozilla.jp に限らず各サイトでの表記の参考にしてください。

## 英数字の表記

* 特に理由がなければ半角を用いる
* 見やすさのため、日本語と英数字の間には半角スペースを挿入する。(Microsoft
  * のドキュメントも同じルールを採用している)
* サイト上では、アンカーの前後にも同じく半角スペースを挿入する。
* ただし、句読点、括弧などの日本語
* [約物](http://ja.wikipedia.org/wiki/%E7%B4%84%E7%89%A9)
    と英数字が隣接する場合は挿入しない。
* 全角英数字を用いる例外: 社名など (例: 「Ｊストリーム」)

例: ブラウザーのパフォーマンスを劇的に向上させる新しい JavaScript エンジン「TraceMonkey」が Firefox 3.5 に搭載されました。

## 単位など

* 日付
  * 西暦表記。文書内では YYYY 年 MM 月 DD 日
* 数字
  * 半角英数字。3 ケタごとに区切り文字を入れる。例: 1,024
* 記憶容量
  * 「バイト」はカタカナ。それ以外の接頭辞付き単位は大文字英語表記。数字と単位の間に半角スペースを入れる。例: 5 MB、100 KB
* 人名・団体名
  * 原則として英語表記のままにする。

## カタカナ語の表記

* 半角カタカナは使わない。
* **長音表記**
  * **-er、-or、-ar、-cy、-ry、-gy で終わる単語はすべて長音とする。Microsoft のような例外はなし。**
      * 例: コンピューター、ブラウザー、ユーザー、サーバー、カレンダー、プライバシー、ディレクトリー
  * -ear、-eer、-re、-ty、-dy、-xy で終わる単語は長音としない。
      * 例: ボランティア、エンジニア、ソフトウェア、アクセシビリティ、セキュリティ、ボディ、プロキシ
  * [詳細ルール](https://docs.google.com/spreadsheets/d/1yIKTUY07tjAALpBecYW0ZQ0r4pbAppEO82OwivfY7iQ)
* その他カタカナ語の表記について
  * **「Web」は 2016 年 8 月以降は「ウェブ」と記載する。**
  * 「Cookie」はそのまま。カタカナや複数形にはしない。
  * 「ウィルス」ではなく「ウイルス」
  * 「サインイン」「サインアウト」ではなく「ログイン」「ログアウト」
  * カタカナで構成された語句について、Microsoft
        は半角スペースを挿入しているが、MJ では挿入しない (例:
        「オペレーティング システム」「ハード ディスク
        ドライブ」)。ただし、操作方法の説明などで Windows
        のメニューについて言及する場合はその限りではない (例:
        「コントロール パネル」)。

## 約物の表記

* カギ括弧以外は半角を用いて前後に半角スペースを挿入する。
* 句読点は全角の「。」「、」を採用。
* 三点リーダーは半角ドット 3 つ「...」を採用。
* コロン「:」やセミコロン「;」は半角 (必要なら直後にスペース)
* 感嘆符と疑問は全角「！」「？」。ただし連続する場合は半角「!?」。
* スラッシュは半角「/」。
* 中黒は全角「・」。
* 波ダッシュ「〜」の入力には注意が必要。Mac のキーボードから入力すると
    Unicode 301C (波ダッシュ) で確定されるが、これは Windows XP
    でジャギーが見られる文字なので、避けなければならない。回避策としては、文字パレットから
    Unicode FF5E (全角チルダ)
    を入力する。([参考](http://ja.wikipedia.org/wiki/%E6%B3%A2%E3%83%80%E3%83%83%E3%82%B7%E3%83%A5))
* [ダッシュ記号](http://ja.wikipedia.org/wiki/%E3%83%80%E3%83%83%E3%82%B7%E3%83%A5_%28%E8%A8%98%E5%8F%B7%29)
    の使い分けにも注意が必要。現状統一ルールがないので今後改善が必要。

## メニュー等の表記

* Microsoft
    の表記に準拠。半角大括弧を用いて前後に半角スペースを挿入する。
* メニューの三点リーダーは省略する。

例: さらに、[検索バーの管理] をクリックすれば、順番を並べ変えたり、他の選択肢を追加したり、お気に入りの検索エンジンにキーワード (ショートカット) を割り当てることができます。

## 日本語の文体

* 行頭に全角スペースは付けない。
* 語尾は原則として「ですます調」を採用し、文書内で統一する。
* 動詞の送りがなは本則に従う。○ 読み込み、貼り付け × 読込み、貼付け
* 読みづらい漢字は適宜ひらがなにする。ただし、現状統一ルールがないので今後改善が必要
    ([「記者ハンドブック」準拠](https://docs.google.com/spreadsheets/d/1y-hC-xMXawCgcYZwJDnvuSlAOTgMRLLyqXurpYkJbYE/)で良いか？)。
* 「下さい」ではなく「ください」
* 有り/無し OR あり/なし -* _TBD_
* 例え (ば) OR たとえ (ば) -* _TBD_
* 共に OR ともに -* _TBD_
* 「〜に」は基本的に漢字。例外として「すでに」「さらに」「まれに」「たまに」はひらがなにする。-* _TBD_
* 「全て」「殆ど」「幾つか」ではなく「すべて」「ほとんど」「いくつか」
* 「於いて」「於ける」ではなく「おいて」「おける」
* 「居る」ではなく「いる」
* 「通り」ではなく「どおり」
* 「出来る」ではなく「できる」
* 「〜の為」ではなく「〜のため」
* 「〜毎」ではなく「〜ごと」
* 「とき」「ところ」「もの」「こと」
  * 特定の時刻や場所を表す場合は「時」「所」
* 「但し」ではなく「ただし」
* 「或いは」「又は」「及び」ではなく「あるいは」「または」「および」
* 「2 か月」「5 か所」「10 か国語」
* あまり丁寧すぎると浮いてしまうので、内容が改まったものでなければ、一般的な丁寧語で記述する。特にブログは多少カジュアルでも良い。
  * OK: 「皆さん」「公開します」「よろしくお願いします」
  * NG: 「皆様」「公開いたしました」「よろしくお願いいたします」

## 専門用語の表記

* Firefox の表記に準拠。[L10N ガイドライン](https://github.com/mozilla-japan/translation/wiki/L10N-Guideline) も参照。

## ブランディング

Mozilla 全体の [ブランディング翻訳のスタイルガイド](http://www.mozilla.org/en-US/styleguide/communications/translation/) に留意すること。組織や製品の名称については Mozilla から発信する場合は基本的に英語表記とする (カタカナでの表記は一部メディアのルールで必要となる場合のみ)。

## 会社名

* (正式) 一般社団法人 Mozilla Japan
* (略) Mozilla Japan
* (訳語) モジラジャパン

* (正式) Mozilla Corporation
* (訳語) モジラコーポレーション

* (正式) Mozilla Foundation
* (訳語) モジラファウンデーション

## 役員

* (正式) Mitchell Baker
* (訳語) ミッチェル・ベーカー
* 肩書き
  * (正式) Chairman, Mozilla Corporation
  * (訳語) Mozilla Corporation 会長
  * (正式) Chief Lizard Wrangler
  * (訳語) トカゲ世話役主任 (Mozilla Japan
        の訳ではないが、伝統的にこの訳が使われている)

* (正式) 瀧田佐登子
* 肩書き
  * (正式日本語) Mozilla Japan 代表理事
  * (正式英語） Chair of the Board of Directors

## 製品名

* (正式) Mozilla Firefox
* (略) Firefox
* デザイン仕様の場合は登録商標マーク ® を右肩につける
* (訳語) ファイアーフォックス
* ただし、製品・公式ページ内での製品の訳語の使用は認められていない。

* (正式) Mozilla Thunderbird
* (略) Thunderbird
* デザイン仕様の場合は ™ マークを右肩につける
* (訳語) サンダーバード

## 参考

* [Microsoft 日本語スタイルガイド](https://www.microsoft.com/Language/ja-jp/StyleGuides.aspx)
* [JTF 日本語標準スタイルガイド（翻訳用） 第 2.2 版](http://www.jtf.jp/jp/style_guide/styleguide_top.html)