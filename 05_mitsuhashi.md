        --
目次

#contents
        --
#  BodyParts3D/Anatomographyとは [#nfe4fc8e]
BodyParts3D(ボディパーツ3D)は人体各部位の位置や形状を3次元モデルで記述したデータベースです。Anatomography(アナトモグラフィー)を使って、BodyParts3Dから解剖学用語を選択して自由に人体のモデル図を作成できます。

#  BodyParts3D/Anatomographyの場所 [#a2dda02c]
- [[統合データベースプロジェクト:http://lifesciencedb.jp]]の「ツール＆解析サービス」から。
- [[トップページURL (http://lifesciencedb.jp/bp3d):http://lifesciencedb.jp/bp3d]]
- [[「BodyParts3D or Anatomography or アナトモグラフィー」でgoogle検索:http://www.google.co.jp/search?q=BodyParts3D&ie=utf-8&oe=utf-8&aq=t&hl=ja&client=firefox-a&rlz=1R1GGGL_ja___JP322]]

# 【実習1】基本的な操作手順を覚える [#y3064a5a]

- 「Information」タブ→「ユーザガイド」→「[[Getting Started:http://lifesciencedb.jp/bp3d/info/userGuide/gettingStarted/index.html]]」をひと通り実施します。

# 【実習2】AQP3遺伝子の臓器別発現量を人体ヒートマップで表示し発現状況を可視化する [#ca13912f]

+アクアポリン３(AQP3)という遺伝子の発現量ヒートマップを作成します。
++データソース：[[BioGPS:http://biogps.gnf.org/#goto=genereport&id=360]]
#ref(aqp3.png,left)
+作成済みマップのリンクをクリックしてください。→
[[作製済みマップのリンク:http://bp3d-dev.lifesciencedb.jp/bp3d/?tp_ap=av%3D09051901%26iw%3D640%26ih%3D590%26bcl%3DFFFFFF%26cf%3D0%26bv%3D2.0%26dt%3D20100603215605%26cx%3D-0.622%26cy%3D-984.5671%26cz%3D828.6308%26tx%3D-0.622%26ty%3D-96.5107%26tz%3D828.6308%26ux%3D0%26uy%3D0%26uz%3D1%26zm%3D0%26cm%3DN%26oid001%3DFMA7203%26osc001%3D300%26osz001%3DS%26oop001%3D1.0%26orp001%3DS%26oid002%3DFMA7394%26osc002%3D1500%26osz002%3DZ%26oop002%3D1.0%26orp002%3DS%26oid003%3DFMA7198%26osc003%3D1200%26osz003%3DS%26oop003%3D1.0%26orp003%3DS%26oid004%3DFMA9600%26osc004%3D1250%26osz004%3DS%26oop004%3D1.0%26orp004%3DS%26oid005%3DFMA7195%26osc005%3D1500%26osz005%3DS%26oop005%3D1.0%26orp005%3DS%26oid006%3DFMA7197%26osc006%3D250%26osz006%3DS%26oop006%3D1.0%26orp006%3DS%26oid007%3DFMA7163%26osz007%3DS%26oop007%3D0.1%26orp007%3DS%26lt%3D%26le%3D%26la%3D]]
+[[「臓器別に取得された数値を色情報に変換してヒートマップを作成するには」:http://lifesciencedb.jp/bp3d/info/userGuide/faq/value.html]]を参考に、発現量を入力できることを確認します。
+[[「Palletの中で選択した臓器にフォーカスするには」:http://lifesciencedb.jp/bp3d/info/userGuide/faq/focus.html]]を参考に、画像を見やすい大きさにします。

# 【実習3】BodyParts3Dの人体の特徴を調べる[#ca13912f]

+身長は何センチでしょうか。
++ヒント：BodyParts3Dには座標系が定義されています。
+左肺と右肺はどちらが大きいでしょうか。その理由は。
++[[ヒント:http://lifesciencedb.jp/bp3d/?tp_ap=av%3D09051901%26iw%3D590%26ih%3D650%26bcl%3DFFFFFF%26cf%3D0%26bv%3D2.0%26dt%3D20100603233154%26cx%3D-1.3695%26cy%3D-994.9948%26cz%3D1244.0601%26tx%3D-1.3695%26ty%3D-106.9384%26tz%3D1244.0601%26ux%3D0%26uy%3D0%26uz%3D1%26zm%3D2.6%26cm%3DN%26oid001%3DFMA7195%26ocl001%3DFF0000%26osz001%3DS%26oop001%3D0.2%26orp001%3DS%26oid002%3DFMA7088%26ocl002%3D0000FF%26osz002%3DZ%26oop002%3D1.0%26orp002%3DS%26lt%3D%26le%3D%26la%3D]]
+左右の腎臓の高さが異なる理由は。
++[[ヒント:http://lifesciencedb.jp/bp3d/?tp_ap=av%3D09051901%26iw%3D590%26ih%3D650%26bcl%3DFFFFFF%26cf%3D0%26bv%3D2.0%26dt%3D20100603232808%26cx%3D-16.4353%26cy%3D770.6758%26cz%3D1101.9546%26tx%3D-16.4353%26ty%3D-117.3805%26tz%3D1101.9546%26ux%3D0%26uy%3D0%26uz%3D1%26zm%3D3%26cm%3DN%26oid001%3DFMA7203%26ocl001%3DFF0000%26osz001%3DS%26oop001%3D1.0%26orp001%3DS%26oid002%3DFMA7197%26ocl002%3D0000FF%26osz002%3DZ%26oop002%3D1.0%26orp002%3DS%26lt%3D%26le%3D%26la%3D]]
//+正面から見た場合、心臓は体の中心線から左にどのくらいずれているでしょうか。

※現段階ではBodyParts3Dで観測できる全ての特徴が解剖学的に正しいとは限りませんので、正確には書籍等で確認してください。

#  講習会資料(pdf)ダウンロード [#y8e495b5]

#ref(ajacs18Bp3d.pdf,left)

//* 統合TVアナトモグラフィー [#r7f40866]
//
//-http://togotv.dbcls.jp/movie/080926ag3_f.html
//-http://togotv.dbcls.jp/movie/080606AgService2_f.html
