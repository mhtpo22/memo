#Version（2019/7現在）

| プログラミング言語      | 概要（フレームワーク / パッケージ管理ツール / バージョン管理ツール） |
| ----------------------- | ------------------------------------------------------------ |
| Ruby（2.6.3）           | ・Rails（5.2.3）<br />・gem（2.7.6）<br />・rbenv            |
| Python（2.7.2 / 3.7.4） | ・Django（3.7.4）<br />・pip（19.2.1）<br />・pyenv          |
| PHP（7.3.7）            | ・Laravel（5.7）<br />・composer（1.8.6）<br />・phpbrew /phpenv |
| Node（12.6.0）          | ・Express（4.17.1）<br />・npm（6.10.2）/ yarn（1.17.3）<br />・nodebrew /nvm /nodenv |

※バージョン管理ツール：[anyenv](https://anyenv.github.io/)がオススメ。



| プログラミング言語 | コマンド                                                     |
| ------------------ | ------------------------------------------------------------ |
| Ruby               | rbeny install -l（バージョン一覧）<br />rbeny global install x.x.x（インストール）<br />rbeny versions（インストール済みのバージョン）<br />rbeny local x.x.x（バージョンを適応させる） |
| Python             | pyenv install -l（バージョン一覧）<br />pyenv global install x.x.x（インストール）<br />pyenv versions（インストール済みのバージョン）<br />pyenv local x.x.x（バージョンを適応させる） |
| PHP                | nodebrew ls-remote（バージョン一覧）<br />nodebrew install-binary vx.x.x（インストール）<br />nodebrew list（インストール済みのバージョン）<br />nodebrew use vx.x.x（バージョンを適応させる） |
| Node               | phpbrew  known（バージョン一覧）<br />nodebrew install-binary vx.x.x（インストール）<br />nodebrew list（インストール済みのバージョン）<br />phpbrew use x.x.x（バージョンを一時的に適応させる）<br />phpbrew switch x.x.x（バージョンを適応させる） |



| macOS用パッケージマネージャー | コマンド                                                     |
| ----------------------------- | ------------------------------------------------------------ |
| brew                          | brew install xxx<br />brew list<br />brew outdated<br />brew doctor |



| Mac OSのバージョン出力コマンド | 一覧                                                         |
| ------------------------------ | ------------------------------------------------------------ |
| sw_vers                        | Sierra(10.12)[2016/9]<br />High Sierra(10.13)[2017/6]<br />Mojave(10.14)[2018/6]<br />Catalina(10.15)[2019/6] |






