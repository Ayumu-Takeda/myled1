#myled

リポジトリの概要：ラズパイ４を使ったled点灯

動作環境：ubuntu18.04,ラズパイ4

使用した物：led(赤）、抵抗1個（200Ω）、ケーブル2本、ブレッドボード

動画のリンク：「http://www.youtube.com/watch?v=nCTzosFBwT8」

インストール方法：makeをし、エラーがないかを確認し、sudo insmod myled.koでカーネルモジュールをインストール

led点灯方法：echo 1 > /dev/myled0 で点灯　echo 0 > /dev/myled0で消灯
                
ライセンス：GNU
