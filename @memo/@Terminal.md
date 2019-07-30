# Terminal入門(iTerm2+zsh)

## 基礎編1

### [ 開く ]

1. option + space：ターミナルを開く

2. command + N：新規画面を開く

3. command + T：新規タブ開く
4. control + L：再起動

### [ 閉じる ]

1. command + Q：画面を閉じる(非推奨)

2. command + W：タブを閉じる
3. control + d：終了(非推奨)

### [ 画面操作 ]

1. command + shift + [←/→]：タブの移動
2. command + []：画面の移動
3. command + D：横に分割する
4. command + shift + D：縦に分割する
5. command + Enter：全画面
6. control + L：再描画

### [ カーソル ]

1. control + A：行頭

2. control + E：行末

3. control + W：１単語消去

4. control + U：行頭まで消去

5. control + K：行末まで消去

6. control + Y：貼り付け



 ## 基礎編2

### [ ファイルの操作 ]

1. mkdir(md) xxx
2. touch xxx
3. rm xxx
4. cp xxx yyy
5. mv xxx yyy

### [ CPUの温度を確かめる(要インストール) ]

1. istats：実行
2. stats scan：全てのセンサーをスキャン

### [ パソコンが重くなった時 ]

1. sudo rm -rf ~/Library/Caches：キャッシュの削除
2. sudo purge：メモリ解放

### [ Webサーバを停止させる ]

1. PIDを探す
   1. ps ax|grep [プロセス名]
   2. lsof -c [コマンド名]
   3. lsof -i:[ポート番号]
   4. cat tmp/pids/server.pid
2. PIDを削除する
   1. <方法>kill -9 [PID]

### [ 自動スリープ抑制 ]

1. caffeinated -i

2. caffeinate -u -t time

### [ Grepを使う]

1. cat hoge.txt | grep xxx

2. cat ./* | grep xxx
3. ls folder|grep xxx
4. tail -f log.txt
5. find *.txt | xargs grep -n xxx

| grep(オプション) | 概要             |
| ---------------- | ---------------- |
| i                | 文字の区別なし   |
| n                | 行番号           |
| v                | 除外             |
| c                | ヒット数         |
| w                | 独立した文字のみ |
| r                | 再帰的           |
| l                | ファイル名       |





## 応用編

### [ homebrew ]

1. brew install xxx

2. brew list

3. brew doctor

### [ rails ]

1. rails new xxx

2. rails server(rs)

3. rails generate(rg)

4. rails destroy

5. rails db:migrate

6. rails routes

7. rails console(rc)→pry

8. rails dbconsole(rdb)

9. rails db:seed

10. bundle install(bi)

11. bundle update(bu)
12. rails g xxx:install(devise/rspec)

### [ git ]

1. git init：初期化
2. git add *：追加
3. git commit -m "hoge"：コミット
4. git push origin master：プッシュ
5. git push heroku master：プッシュ
6. git status：状態表示
7. git log -n 10：ログ
8. git diff --stat：変更具合
9. git diff -w：改行や空白を無視する

### [ heroku ]

1. heroku open

2. heroku start

3. heroku logs -t

4. heroku run bundle exec rake db:migrate





