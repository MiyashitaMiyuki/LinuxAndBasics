LinuxAndBasics
==============

Những vấn đề về tệp  
---------------------

### Subject 03 

今回作ってもらうShellScriptは、ディレクトリ data の下にあるすべてのファイルの中身を書き換えるscriptです。  
ShellScript lần này các em sẽ làm script thay đổi nội dung trong tất cả các tệp nằm dưới thư mục data.  
書き換えのルールは、"Windows" という文字列を "Linux" に 書きかえる、という単純なものです。  
Nguyên tắc thay đổi rất đơn giản, chữ "Windows" đổi thành chữ "Linux".     

Ví dụ:  
Có tệp abc.txt trong đó có nội dung là  

        I like Windows.

thì các em đổi thành  

        I like Linux.

に書き換えます。  
dataの下に何というファイルがあるのかは、スクリプトを実行するまでわからないものとします。  
また、data ディレクトリの下にデータファイルを作るのも自分の作業としてやってください。

今回のポイントとしては、  

* sed コマンドの使い方を調べましょう。

-----
