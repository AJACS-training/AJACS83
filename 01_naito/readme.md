塩基配列解析のためのデータベース・ウェブツール
---------------

ライフサイエンス統合データベースセンター（DBCLS）  
内藤 雄樹（[自己紹介](http://researchmap.jp/meso_cacase/)）  
2020年10月14日 統合データベース講習会 AJACSオンライン2

  - [スライドPDF](AJACS83_01_naito.pdf)

講習で紹介するデータベースやウェブツールへのリンクです。

#### NCBI ####

![スクリーンショット](https://raw.githubusercontent.com/AJACS-training/AJACS83/master/01_naito/images/ncbi_600.png
"スクリーンショット")

  - NCBI - http://www.ncbi.nlm.nih.gov/

#### NCBI BLAST ####

![スクリーンショット](https://raw.githubusercontent.com/AJACS-training/AJACS83/master/01_naito/images/ncbiblast_600.png
"スクリーンショット")

  - NCBI BLAST - http://www.ncbi.nlm.nih.gov/BLAST

#### UCSC BLAT ####

![スクリーンショット](https://raw.githubusercontent.com/AJACS-training/AJACS83/master/01_naito/images/BLAT.png
"スクリーンショット")

  - UCSC BLAT - https://genome.ucsc.edu/cgi-bin/hgBlat
  - 配列を探してみよう - tgaatgaagacgatcgactcaaattcacagctccacaggatggaattcttcttaacaaagctcgacaattcgga （線虫）
  - 統合TVによる解説動画
    - [高速アラインメントツールBLATをプライマー設計支援ツールとして使い倒す2009](http://togotv.dbcls.jp/ja/20090619.html)

#### UCSCゲノムブラウザ ####

![スクリーンショット](https://raw.githubusercontent.com/AJACS-training/AJACS83/master/01_naito/images/867440539.png
"スクリーンショット")

  - UCSCゲノムブラウザ – https://genome.ucsc.edu/cgi-bin/hgTracks
  - 統合TVによる解説動画
    - [UCSC Genome Browserの使い方〜基本編](http://togotv.dbcls.jp/ja/20091113.html)
    - [UCSC Genome Browserの使い方〜表示編](http://togotv.dbcls.jp/ja/20091126.html)
    - [UCSC Genome Browser の使い方〜アノテーショントラック編〜](http://togotv.dbcls.jp/ja/20100722.html)
    - [UCSC Genome Browserの使い方〜wig形式のファイルをトラックとして追加する〜](http://togotv.dbcls.jp/ja/20120116.html)
    - [UCSC Genome Browserの使い方〜表示+ENCODE編〜 2012](http://togotv.dbcls.jp/ja/20120528.html)
    - [UCSC genome browserの使い方～配列取得編～2013](http://togotv.dbcls.jp/ja/20131113.html)


#### 統合遺伝子検索GGRNA ####

![スクリーンショット](https://raw.githubusercontent.com/AJACS-training/AJACS83/master/01_naito/images/GGRNA.v2.jpg
"スクリーンショット")

  - 統合遺伝子検索GGRNA – https://GGRNA.dbcls.jp/
  - 統合TVによる解説動画
    - [GGRNAで遺伝子をGoogleのように検索する](http://togotv.dbcls.jp/ja/20120124.html)
  - ヒトのnanogを検索 – https://GGRNA.dbcls.jp/hs/nanog
  - Accession番号から検索 –  https://GGRNA.dbcls.jp/NM_003380
  - 塩基配列から検索
    - 14bp – https://GGRNA.dbcls.jp/hs/caagaagagattgc
    - 11bp – https://GGRNA.dbcls.jp/hs/caagaagagat
    - 8bp – https://GGRNA.dbcls.jp/hs/caagaaga
  - アミノ酸配列から検索 – https://GGRNA.dbcls.jp/SEHPL+MTCQSC
  - PCRプライマー検索 – https://GGRNA.dbcls.jp/hs/seq%3aagctcattactttatcagtgca+comp%3atgacgtattcactcttctggtt
  - マイクロアレイのプローブ検索 – https://GGRNA.dbcls.jp/1552311_a_at

#### 高速配列検索GGGenome ####

![スクリーンショット](https://raw.githubusercontent.com/AJACS-training/AJACS83/master/01_naito/images/GGGenome_screen2.png
"スクリーンショット")

- 高速配列検索GGGenome – https://GGGenome.dbcls.jp/
  - 統合TVによる解説動画
    - [高速配列検索 GGGenome《ゲゲゲノム》の使い方](http://togotv.dbcls.jp/ja/20131025.html)
    - [GGGenome《ゲゲゲノム》で転写因子結合サイトを検索してゲノムブラウザに表示する](http://togotv.dbcls.jp/ja/20150721.html)
  - ミスマッチやギャップを含む検索 – https://GGGenome.dbcls.jp/hg19/2/TTCACTGACAACATTGAGTA
  - 表計算ソフトで塩基配列検索
    - [Googleスプレッドシート](https://docs.google.com/spreadsheet/ccc?key=0AqoKv30zqpDbdHJpSFI1SzJOZmxjVkYzUXByMFhrWWc&usp=sharing#gid=0) を参照
  - 検索結果をゲノムブラウザ上に表示
    1. UCSCゲノムブラウザ (http://genome.ucsc.edu/cgi-bin/hgTracks)
    2. 「add custom tracks」ボタン
    3. 「https://GGGenome.dbcls.jp/hg19/(検索したい配列).bed」と入力

#### CRISPR設計ウェブサーバCRISPRdirect ####

![スクリーンショット](https://raw.githubusercontent.com/AJACS-training/AJACS83/master/01_naito/images/CRISPRscreen.png
"スクリーンショット")

  - CRISPRdirect - https://crispr.dbcls.jp/
  - 統合TVによる解説動画
    - [CRISPRdirectを使ってCRISPR/Cas法のガイドRNA配列を設計する](http://togotv.dbcls.jp/ja/20140412.html)

#### 参考：各生物種のゲノム ####

  - NCBI Genome - https://www.ncbi.nlm.nih.gov/genome/browse/
  - Ensembl Genomes - http://ensemblgenomes.org/
    - 昆虫はEnsembl Metazoa - http://metazoa.ensembl.org/
    - 植物はEnsembl Plants - http://plants.ensembl.org/

License
--------

Copyright &copy; 2020 Yuki Naito
 ([@meso_cacase](http://twitter.com/meso_cacase)) at  
Database Center for Life Science (DBCLS), Japan.  
Licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.ja).  
(クレジットを表示することにより自由に改変および再利用が可能です)
