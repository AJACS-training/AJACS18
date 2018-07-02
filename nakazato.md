「文献検索にまつわる各種ツールの使いこなし術」

        --
[[AJACS湘南3>AJACS18]] > 「文献検索にまつわる各種ツールの使いこなし術」
        --

# 概要 [#vf8a5200]
- 時間も時間ですし、話すのは省略します。
## なぜ文献の検索をするのか [#nfcee7b5]
- 今までに何がわかっているのか知る
    -すでに知られていることをやっても意味がないのだ（新規性）
    -今までにやられていることを前提に自分の研究を進める

## 文献検索の実際 [#pfe8ca7d]
### 文献を読むってどういうこと? [#ocb3b351]
- 目的の文献（などのリソース）を探し出す
- 目的の文献（などのリソース）に何が書いてあるか理解する（あるいは、そのための整理をする）
### 文献を読むまでの流れ [#t287af51]
    -あとでやる
    -みんな知っていたら飛ばす
- [前提] 研究の世界で文献、というと学術雑誌に載っている学術論文のことです
- パターン１：各雑誌社のサイトに行く → 論文を見つける → PDF落としてくる → 画面で読むとか印刷して読むとか
    -雑誌の例
        -nature http://www.nature.com/nature/
        -science http://www.sciencemag.org/
        -パスワードがかかっているものもある（学術機関内は不要の場合も多い）
- パターン２：学術雑誌リストからたどる → 各雑誌社のサイトに行く → （パターン１と同じ）
- パターン３：学術論文データベースからたどる → 各雑誌社のサイトに行く → （パターン１と同じ）

        --
ここから本題
        --


# PubMed http://pubmed.gov/ [#g9279691]
    -泣く子も黙るライフサイエンス系学術論文検索の総本山
    -[ナニコレ] NIHの下の図書館部門NLM (National Library of Medicine:[[場所:http://maps.google.co.jp/maps?f=q&source=s_q&hl=ja&geocode=&q=U.S.+National+Library+of+Medicine,+8600+Rockville+Pike,+Bethesda,+MD+20894&sll=36.5626,136.362305&sspn=43.597785,76.640625&ie=UTF8&ll=38.995215,-77.096577&spn=5.335735,9.580078&z=7]])の提供するライフサイエンス系学術論文データベース検索サイト
    -http://www.ncbi.nlm.nih.gov/sites/entrez?db=PubMed からもアクセスできる（というか、こちらが本来のもの）

- 【演習】口蹄疫ウイルスのゲノム決定論文を探してみよう
    -2000年に宮崎で流行したもの。
++http://pubmed.gov/ にアクセス
++検索窓に「foot-and-mouth disease virus」と入れてGoをクリック<br>
        -「Results: 1 to 20 of 3937」の部分に表示されている 数字が検索の結果ヒットした数 … この場合、3937
++「genome」を追加して検索<br>
次第に絞り込まれ数が減少していく
++さらに「Japan」をキーワードに加えて絞り込む
これくらいの件数になれば、タイトル・アブストラクトを見ればよい。
#fold(（←ここをクリック）これですかね。。。,[[The complete nucleotide sequence of the PanAsia strain of foot-and-mouth disease virus isolated in Japan.:http://www.ncbi.nlm.nih.gov/pubmed/12416675]])
++ → この先、実際に雑誌社のサイトに行って、PDFを落として読んだりする

- 【トリビア】PubMedには全部で何件の論文が登録されているでしょう。
    -→「All[Filter]」で検索してみる。
#fold(←こたえはここをクリック,およそ2000万件。正確には、19,859,155件[5/28現在]。去年は18,856,879件['09/5/14現在]でした)
- 【トリビア】一番、古いものは?
    -→「All[Filter]」で検索した後、「Sort by」を「Pub Date」にして、最後のページにアクセス
#fold{{{
←こたえはここをクリック
1865年[5/28現在]<br>
元々は、1950年代からの論文をカバーしていたのですが、最近は、さらにさかのぼって古いのも入れるようになっています。
```

- 人名からの検索
    -基本：苗字＋イニシャル … Nakazato T
    -応用：フルネームで（ただし、2003年くらい以降。とりこぼしあり）… Nakazato, Takeru（苗字+コンマ+スペース+名前）
- 【演習】（人名からの検索）山中伸弥 京大教授のiPS細胞の論文を検索してみよう
    -ヒント：2006年 Cell（雑誌）に掲載
++http://pubmed.gov/ にアクセス
++Yamanaka, Shinya と入力
++探してみる
    -【さらに】自分の先生の名前などで検索してみよう
    -【参考】「09.04/13 秋篠宮文仁殿下が本学部博物館をご見学になりました」（[[情報元:http://www.brs.nihon-u.ac.jp/news_contents/news/20090413/aki_news.html]] → リンク切れ）とのことなので、秋篠宮文仁殿下の論文を検索してみよう
        -皇室の方の名前は特殊なので、「Akishinonomiya, Fumihito」でなくて「Fumihito, Akishinonomiya」です（姓と名が逆）のものがあります。その理由は、、、[[ここ:http://blog.dbcls.jp/portal/20081227.html]]
        -これで出てきたものだけが結果ではないです（Akishinonomiya, Fumihito ときちんと (?) 登録されているものもある。また、フルネームでひけない古いものがあるが、Fumihito Aでひくとノイズが混じる）

- 【小技】より一層の絞り込みは「Preview/Index」タブをクリックして指定するとよい。
    -たとえば「Title/Abstract」や「Author」「Publication Date」を指定するなどで絞りこめる
    -First Author や Last Author でも絞り込みが可能

- MeSH  (Medial Subject Headings)
    -遺伝子や病気、生物種などは、名前がたくさんあるので、キーワードに対応づけて、そのキーワードのついている文献も検索されるようになっている。
    -そのキーワードが「MeSH」。メタデータ、タグと理解してもよい
    -実際にどのようなキーワードに展開されて検索されているかは「Datails」欄を見るとわかる
    -そのキーワードを使って検索するには、「AND キーワード[MeSH Terms]」と付け加える

//++「History」タブをクリックすると、今までの検索ワードとヒット件数が一覧表示される。

- 【小技】FireFoxの場合、検索バー（ブラウザの右上にある「G」マークのところ）をクリックすると、「Pubmed search」を検索バーに登録できます

- 【応用】: RSS feedを使って、定点観測するには
    -統合TV: http://togotv.dbcls.jp/20070920.html ([[YouTube>http://www.youtube.com]]版: http://www.youtube.com/watch?v=5K8-xnkcClo ) を参照
    -「Send to」のタブから「RSS feed」を選択すると、データが更新されたときに自動的に通知してくれます。

# 文献（フルテキスト） [#me744421]
## PubMed Central http://pubmedcentral.gov/ [#u02c9d23]
- PubMedはアブストラクト（要約）のみ。フルテキストを収載。
- オープンアクセスの流れを受けて、今は、フルテキストも見られるものが出てきました。
#fold(←何件あるか? Search all articles で All[Filter],およそ200万件。正確には1,989,845件 ('10-05-31現在))
- とりあえずPubMedで検索してみる。PMC収載のものは、リンクがある

## Google scholar http://scholar.google.com/ [#zd6f228b]
- 世の中のGoogleが取得できる（パスワードなど要求されない）論文を集めて検索できるようにしたサイト
- メリット
    -その論文を引用している論文も見ることができる（図書館では有料でそういったサービスを買っていたりもする）

# その他... [#e1dc47ea]
## 大学の図書館サイト [#e487a1cb]
- 雑誌や号がわかっている場合は、そこからアクセス
    -参考：[[日本大学生物資源科学部図書館 契約電子ジャーナル:http://hp.brs.nihon-u.ac.jp/~tosyo/e-journal.html]]

## NACSIS WebCat http://webcat.nii.ac.jp/ [#ga671fa9]
- DBCLSの兄貴分にあたるNII（国立情報学研究所）がやっている大学などの図書館の収載書籍／雑誌の横断検索
- 自分の図書館が契約していないものや、PDF化されていない昔のものは、とりよせるとか、自分が図書館に出向くとか
- で、どの図書館に冊子体があるか、を検索できる

## 口コミ [#h190ec21]
- 論文を紹介しているブログをウォッチする
- オンラインブックマーク、twitterなど

# 日本語リソース [#w145737b]
## 蛋白質核酸酵素検索 http://lifesciencedb.jp/pne/ [#e291341e]
- ライフサイエンス系総説雑誌。日本語リソースが検索できる。すごい!
- （多分、横断検索のところでも触れられていますが、再掲）
- 「口蹄疫」 → 「foot-and-mouth disease」に変換もして検索

## 学会要旨検索 http://lifesciencedb.jp/lsdb.cgi?gg=tool_tproc [#r69b40d5]

# 文献を読みこなすために [#n6a538b8]
## ライフサイエンス辞書（WebLSD: Life Science Dictionary)  http://lsd.pharm.kyoto-u.ac.jp/ja/ [#de7452ee]
- 生命科学向け英日対訳辞書（京大薬・金子周司先生 他）
- 統合TV：http://togotv.dbcls.jp/20090227.html (オンライン辞書の利用)
- この共起検索も秀逸（ある語の前後にどういう語が出てくるか）
    -ネイティブの方の書かれた論文を情報源にしているので、日本人がおかしやすい間違いなどは出てこない
    -統合データベースプロジェクトで、InMeXes http://docman.dbcls.jp/im/ という逐次検索のサービスもしています

## Allie http://allie.dbcls.jp/ [#v869387e]
- 略語と略さない語のペアを検索
- 【実習】「口蹄疫」(Foot-And-Mouth disease)の略であるFMDで検索してみよう。他にどんな語が「FMD」の略語を用いているだろうか
- 詳しい使い方：統合TV：Allieを使って略語の正式名称を検索する2009 http://togotv.dbcls.jp/20091015.html

## TogoDoc http://docman.dbcls.jp/pubmed_recom /TogoDoc Client http://tdc.cb.k.u-tokyo.ac.jp/ [#r236f485]
- 文献推薦システム／文献管理ツール
- 要登録（OpenID）：統合TV  http://togotv.dbcls.jp/20100225.html
- 統合TV http://togotv.dbcls.jp/20100402.html#p01 （日本農芸化学会2010年度大会ランチョンセミナー 「文献執筆支援ツールの紹介」）


        --
[[AJACS湘南3>AJACS18]] > 「文献検索にまつわる各種ツールの使いこなし術」
        --
