# ICBM研究ツリー日本語化ファイル

![](https://github.com/ferho256/ICBM_Japanese/blob/main/img/example.png)

Steamで販売されている核戦争シミュレーションゲーム[ICBM](https://store.steampowered.com/app/1178220/ICBM/)の研究ツリーを日本語化する

## 方法

各自ファイルパスは読み替えてください

1. `"E:\Steam\steamapps\common\ICBM\LANG\Eng"`のバックアップを取る  

2. フォントを入手する  
   [配布ページ](https://fonts.google.com/noto/fonts?noto.lang=ja_Jpan&noto.script=Jpan)からNoto Sans Japaneseをダウンロードする
   
3. ダウンロードしたファイルを解凍してotfファイルを`ICBM.exe`と同じファイルに置く  
  `NotoSansCJKjp-Medium.otf`と`NotoSansCJKjp-Regular.otf`のみでよい
  ![](https://github.com/ferho256/ICBM_Japanese/blob/main/img/fonts.png)
  [注意]  
    exeファイルと同階層に置かないと起動できなくなる  
    `codepage.table`を書き換えるので、起動時にフォントが見つからないと落ちる？

4. `E:\Steam\steamapps\common\ICBM\LANG\Eng`の`tech_t.lng`と`codepage.table`を同梱のファイルと差し替える  
  `codepage.table`はフォント部分を書き換えただけ  
  ここを自分の使いたいフォントに書き換えると良い
  ![](https://github.com/ferho256/ICBM_Japanese/blob/main/img/font_setting.png)
  
