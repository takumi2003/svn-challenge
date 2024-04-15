# svn-challenge
svnの基本的使い方を試せるコマンド

# 使い方

`git clone https://github.com/takumi2003/svn-challenge.git`

をターミナルの***ルートディレクトリ直下にcommandディレクトリを作成しその内部で実行してファイルを取得してください。***  
その後

`echo $SHELL`

で使用しているターミナルを確認し、bashなら .bash_profile、zshなら .zshrcに  

`export PATH=$HOME/command:$PATH`

の一文を追加してください。

# コマンド
`test-command -checkout`
svnのcheckoutを体験できます。  
`test-command -commit`
svnのcommitを体験できます。  
`test-command -help`
helpの参照
