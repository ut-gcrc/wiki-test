# Data Format

・FXYEフォーマット

例

121011_001.osc　　　

BANK 1 2700 2700 CONST 300.00 1.00 0 0 FXYE

         300 24.42645055 0.256162785

         301 24.38663241 0.434407862

         302 24.36118259 0.433460603



一行目　タイトル

二行目　BANK BANK#(たいてい１）　データ数　データ行（１行に１データの場合はデータ数と同じ）　CONST(constant) 最初の2th(centi degree) 2th step (centi deg.) 0(dummy) 0(dummy) FXYE

３行目以降

　　　2th   Intensity  error



・FXYフォーマット

ほぼFXYEと同じ、３行目以降が

　2th Intensity