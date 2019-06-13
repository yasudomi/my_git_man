# my\_git\_man

--
gitとgithubの使い方を書く。あとはMarkdownの練習。

1. ローカルリポジトリの作り方  
`cd (リポジトリを作成したいディレクトリ)`  
`git init` 

2. gitのインデックスにファイルを追加する。(add)
`git add (インデックスに追加するファイル名)` 
> ディレクトリのファイルを全て入れたいときは、 
> 
> `git add *`
　 
3. 変更結果をローカルリポジトリにコミットする。(commit)
`git commit -m "コミットするときのコメント(何を変更したかわかるように)"`

4. リモートリポジトリに反映させるためにリモートリポジトリのアドレス情報を入力 
`git remote add origin https://github.com/yasudomi/my_git_man.git`
5. ローカルリポジトリをプッシュしてリモートリポジトリに反映させる。(push)
`git push origin master`


