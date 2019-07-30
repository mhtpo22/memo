# Framework入門

## Python（django）

| 種類     | 動作                   | 概要                                      |
| -------- | ---------------------- | ----------------------------------------- |
| Init     | プロジェクトの作成     | $ django-admin startproject [xxx_project] |
|          | アプリケーションの作成 | $ python manage.py startapp [xxx]         |
|          | ルーティングの設定     | [xxx]/urls.py                             |
| View     | ビューの作成           | manager/views.py                          |
| Template | テンプレートの作成     | manager/template/[zzz].html               |
| Model    | モデルの作成           | manager/model.py                          |
|          | モデルを有効にする     | [xxx]/setting.py                          |
|          | マイグレーションの作成 | $ python manage.py makemigrations         |
|          | データベースの適応     | $ python manage.py migrate                |
| Do       | 動作確認               | $ python manage.py runserver              |
|          | コンソール             | $ python manage.py shell                  |



pip install xxx（インストール）[Django/anaconda]

pip  -U xxx（アップグレード）

pip list（リスト表示）



<参考>

[Djangoを最速でマスターする[Qiita]](https://qiita.com/gragragrao/items/373057783ba8856124f3)

[Django Girlsのチュートリアル](https://tutorial.djangogirls.org/ja/)

[Django Projectのチュートリアル](https://docs.djangoproject.com/ja/2.2/intro/tutorial01/#)



## Ruby（Rails）

| 種類       | 動作                   | 概要               |
| ---------- | ---------------------- | ------------------ |
| Init       | アプリケーションの作成 | $ rails new [xxx]  |
|            | MVCの生成              | $ rails generate   |
|            | ルーティングの設定     | config/routes.rb   |
| Controller | コントローラーの作成   | app/controller     |
| View       | ビューの作成           | app/view           |
| Model      | モデルの作成           | app/model          |
|            | データベースの適応     | $ rails db:migrate |
| Do         | 動作確認               | $ rails server     |
|            | コンソール             | $ rails console    |
|            |                        | $ rails dbconsole  |



[データベースの変更]

実行：rails new xxx --d mysql(--database==mysql)

Gimfileの編集「gem 'mysql2'」

database.ymlの編集「development部分」

実行：rails db:create



[testファイルなし]

rails new xxx -T(--skip-test-unit)



[ログを見る]

tails -f log/development.log



[必要なGemファイルのみインストール]

bundle install -without development



[Gemfile記載法]

gem 'hoge', '~>1.2'	#1.2以上かつ2.0未満



[gem]

・gem list(ローカル)

・gem search(リモート)

・gem search ^hoge$ -ra

・gem outdated



<参考>

・ [Ruby on Rails チュートリアル](https://railstutorial.jp) 

・ [Ruby on Rails ガイド](https://railsguides.jp/)

・[るびま](https://magazine.rubyist.net/)



## PHP（Laravel）

| ---        | ---                    |                                                 |
| ---------- | ---------------------- | ----------------------------------------------- |
| Init       | アプリケーションの作成 | $ composer create-project laravel/laravel [xxx] |
|            | MVCの生成              | $php artisan make:model [yyy] -m -c -r          |
|            | ルーティングの設定     | routes/web.php                                  |
| Controller | コントローラーの作成   | app/Http/Controllers                            |
| View       | ビューの作成           | resources/views                                 |
| Model      | モデルの作成           | app                                             |
|            | データベースの適応     | $php artisan migrate                            |
| Do         | 動作確認               | $php artisan serve                              |



## Node.js

・グローバルインストール（/usr/local/bin）

npm install xxx -g（便利ツールのインストール：gulp）

npm list -g



・ローカルインストール

npm init -y（package.jsonの作成）

npm install xxx（ライブラリをダウンロード）



npm run dev（開発時）

npm run build（リリース時）



npm run watch（ファイル更新後に自動ビルド）

npm run serve（）



webpack（複数のJavaScriptを1つにまとめる）

「webpack / webpack-cli / typescript / ts-loader」

「vue / vue-class-component」

package.json

TypeScriptの設定ファイル：tsconfig.json

webpackの設定ファイル：webpack.comfig.js

https://ics.media/entry/16329/



「@babel/core @babel/preset-env babel-loader」

「 css-loader file-loader」

「 vue-loader vue-template-compiler」

「 webpack webpack-cli」

「vue」



npm-scripts（タスク管理）

Gulp

bower

browserify（ライブラリをJSから参照できるツール）

babel



<参考>

[node.js](https://nodejs.org/ja/)
