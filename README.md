# MSX BASIC FILE LAUNCHER

## 概要
MSX BASICで作成したファイルランチャーです。  
本プログラムを実行すると、Aドライブにセットされているフロッピーディスクのファイル一覧を表示します。  
赤色のカーソルでファイルを選択すると、選択したファイルを実行します。  
> `AUTOEXEC.BAS`で本プログラムが自動実行されるようにすると便利です。  

#### 操作方法
- カーソルキーまたはJoypadの十字ボタンでカーソル移動します。  
- スペースキーまたはJoypadのAボタンで決定し実行します。  
- ESCキーでプログラムを終了します。  
  >本プログラム自体はNEWされます。  
msx0の`Gamepad Face`のSELECTボタンにESCキーが割り当てられているため、この仕様としました。  

## 制限事項等
- MSX-DOS(1)想定で作成しています。  
MSX-DOS2の機能(ディレクトリ等)には対応していません。
- Aドライブ以外のドライブには対応していません。
- 実行対象は、拡張子が`.BAS` `.EXE`です。  
  >他の拡張子のファイルは、選択しても無視されます。  
他の拡張子も実行したい場合は、プログラムを改修してください。
- 一覧表示するファイル数が40を超えた場合を想定していません。
- 本プログラムは`SCREEN` `KEY OFF` `WIDTH` `SPRITE` 命令文を使用しています。  
- 一切の動作保証をしておりません。  
利用者の責任において利用してください。  
- バグの修正依頼は受け付けておりません。  
利用者の責任において修正してください。  

## ライセンスについて
- ライセンスはCC0 1.0としましたので、改変および再配布に制限はありません。  
https://creativecommons.org/publicdomain/zero/1.0/deed.ja
