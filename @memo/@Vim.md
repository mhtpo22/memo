# Vim 入門

##基礎編

###[ **カーソル移動に関する問題** **]**

1.  基本の移動(上下左右)をする。<u>(h/j/k/l)</u>

2. 行頭・行末に移動する。<u>(gg/G)</u>

3. 最初の行・最後の行に移動する。<u>(^/$)</u>

4. 現在の画面の上・中・下に移動する。<u>(H/M/L)</u>

5. 半ページ・１ページ分に上・下画面を移動する。<u>(cotrol+u/d/b/f)</u>

6. 段落ごとに上・下する。段落<u>({/})</u>

7. 単語ごとに移動する。<u>(w/e/b)</u>

8. 括弧の対応する場所に移動する。<u>(%)</u>

9. 1文字検索する。<u>(f/t)</u>

10. 単語を検索する。<u>(//n)</u>



### **[** **文字削除に関する問題** **]**

1. 行を削除する。<u>(dd)</u>
2. カーソルの右・左を削除する。<u>(d^/d$)</u>
3. １部の単語を削除する。<u>(dw)</u>
4. 単語を削除する。<u>(diw)</u>
5. 特定の文字が出るまで削除する。<u>(dt)</u>
6. １文字消去(<u>x</u>)



###**[** **コピーに関する問題** **]**

1. 行をコピーする。<u>(yy)</u>

2. 単語をコピーする。<u>(yw)</u>

3. ビジュアルモードでコピーする。<u>(v → y)</u>



###**[** **ペイストに関する問題** **]**

1. 次の行にペーストする。<u>(p)</u>

2. 前の行にペーストする。<u>(P)</u>



###**[** **置換に関する問題** **]**

1. 全置換せよ。<u>(:%s/hoge/HOGE/g)</u>

2. 部分置換せよ。<u>(:s/hoge/HOGE/g)</u>



###**[** **ウインドウに関する問題** ]

1. 縦分割・横分割する。<u>(:split/:vsplit)</u>
2. 画面を閉じる。<u>(:close)</u>
3. 縦・横画面に新規ファイルを作成する。<u>(:new hoge/:vnew hoge)</u>
4. 画面を移動する。<u>(control+w 方向)</u>
5. リロードする。(<u>:e!</u>)



### [ 戻るに関する問題 ]

1. 前の状態に戻す。(u)
2. 元の状態に戻す。(control+r)



### [ 動作の繰り返し ]

1. 繰り返す。(<u>.</u>)



## 実践編

###[webfやiaoを用いた問題 ]

1. 行頭/行末から挿入せよ。(wi/bi)

2. 適当なカーソル位置から挿入せよ。(A/I)

3. 行頭から挿入せよ。(ei)

4. 次・前の行に文字を挿入せよ。(o/O)

   (例題)

   a. There are [] lot of trees

   b. There are a lot of tree[]/[] are a lot of tree

   c. There ar[] a lot of tree

   d. [前の行]There are a lot of trees[次の行]

## その他

● 便利な機能

1. 整形：(1)<u>ggVG</u> → (2)<u>=</u>

2. 補完：<u>control+n</u>

3. 検索：<u>vimgrep xxx **/*.html | cw</u>



● 忘れた時に

1. ヘルプを見る。(<u>:h</u>)

2. チュートリアルを見る。(<u>vimtutor</u>)



● Neobundle

1. プラグインをインストールする。(:NeoBundleInstall)

2. プラグインを更新する。(:NeoBundleUpdate)

3. プラグインを削除する。(:NeoBundleClean)



## オプション（Vimium）

####[ 移動 ]

1. 上・下に移動する。[k/j]

2. 一番上・一番下に移動する。[gg/G]

3. 半分上・下に移動する。[u/d]

#### [ ウィンドウ ]

1. t：タブを開く
2. H/L：タブを移動する。

2. x：閉じる

3. r：リロードする

4. h/l：戻る・進む

####[ URL ]

1. yy：URLをコピーする

2. p /P：現在（新規）のタブから

####[ モード切り替え ]

1. i：リンクモード

2. gi：インプットへ



## 参考URL

・[知識0から始めるVim講座](https://www.google.com/url?q=https%3A%2F%2Fqiita.com%2FJpnLavender%2Fitems%2Ffabcc79b4ab0d52e1f6d&sa=D&sntz=1&usg=AFQjCNHA912OvGf8Ofp9p5PevkIWhddGkA)

・[よく使う Vim のコマンドまとめ](https://www.google.com/url?q=https%3A%2F%2Fqiita.com%2Fhide%2Fitems%2F5bfe5b322872c61a6896&sa=D&sntz=1&usg=AFQjCNHPdy2sQcawQvW8iG8tBoIBdCYLAA)

・[アニメーションで学ぶVim入門 ～精選10機能～](https://www.google.com/url?q=https%3A%2F%2Fqiita.com%2FKoyanagiHitoshi%2Fitems%2F82ef910432552d0a4553&sa=D&sntz=1&usg=AFQjCNHWIvZgoO3ddZDAbS_CbbkCku2Exg)

・[新人達を1ヶ月でガチvimmerにした方法](https://www.google.com/url?q=https%3A%2F%2Fqiita.com%2Fnyantera%2Fitems%2F4bf29ca6f11bc797a9cb&sa=D&sntz=1&usg=AFQjCNEIVtKnAcHulBYyo2Xl09I_kyITjQ)

・[脱初心者を目指すなら知っておきたい便利なVimコマンド25選 (Vimmerレベル診断付き)](https://www.google.com/url?q=https%3A%2F%2Fqiita.com%2Fjnchito%2Fitems%2F57ffda5712636a9a1e62&sa=D&sntz=1&usg=AFQjCNG9f3a_d05VT98U7asoePHxdpiydw)

・[Vimの便利な画面分割＆タブページと、それを更に便利にする方法](https://www.google.com/url?q=https%3A%2F%2Fqiita.com%2Ftekkoc%2Fitems%2F98adcadfa4bdc8b5a6ca&sa=D&sntz=1&usg=AFQjCNG8Juoohx4TZ8Brwqi182Nx5NDV6Q)

・[vimgrepとQuickfix知らないVimmerはちょっとこっち来い](https://www.google.com/url?q=https%3A%2F%2Fqiita.com%2Fyuku_t%2Fitems%2F0c1aff03949cb1b8fe6b&sa=D&sntz=1&usg=AFQjCNFTWwpf1FeeokyKtIcPqGqOjMX5yw)

・[vimgrepでファイル横断検索をする方法](https://www.google.com/url?q=https%3A%2F%2Fblog.onk164.net%2Farchives%2F517.html&sa=D&sntz=1&usg=AFQjCNEXCasK__gjciBBTDanlc_NXy04Ww)

・[Vim Cheat Sheet](https://www.google.com/url?q=https%3A%2F%2Fvim.rtorr.com%2Flang%2Fja&sa=D&sntz=1&usg=AFQjCNEG6iTMzStKz4M1yzjXawfgGJw8aA)