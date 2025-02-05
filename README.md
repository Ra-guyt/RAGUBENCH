RAGUBENCHについて

このソフトには2025年2月5日現在「VRAM Load Mode」という機能が実装されています

この機能はGPU専用メモリ(VRAM)の空き容量を減らして、リソースが不足しているときのPC全体の動作を模擬してテストする目的で制作しました


TurboWarpで制作し、HTML形式でパッケージしているため、Webブラウザ上ですべて完結します


最初から用意されている12個のプリセットを使用するか、128MBから65536MBの範囲でスライダーを動かして書き込み量を指定することができます (厳密に書き込み量のテストをしたわけではないので、大体の目安としてご利用ください)


GPU専用メモリ(VRAM)がない場合や、空き容量が不足した場合はPC全体のメモリ領域に書き込まれます

仕組みとしては、メモリ領域に同一のSVGデータを大量に複製して書き込んでいるだけなので故障することはないと思いますが、万が一このソフトを使用して損害が生じても責任は負いかねますので、ご利用は自己責任でお願いします
