LinuxAndBasics
==============

問題ファイル（日本語）
---------------------

### Subject 02 

今回もShellScriptを作ってもらいます。  
作ってもらうのは、  
ディレクトリ data の下にあるすべてのファイルのファイル名の後ろに old をつける。  
というスクリプトです。  

例えば、   
abc.txt   
というファイルが有った場合、  
abc.txt.old  
というふうに名前を変更します。  
dataの下に何というファイルがあるのかは、スクリプトを実行するまでわからないものとします。  

今回のポイントとしては、  

* for 文を使って繰り返し処理をします。
Shell script における、for 文の使い方を調べましょう。
* ディレクトリの下にあるファイルの名前は、スクリプトを実行するまでわからないので、実行時に取得しなければなりません。
* ` ` または、$() の使い方を調べましょう。

例:  

        mycomputer: ~/tmp$ ls data
        aaa.txt
        bbb.txt
        ccc.txt
        mycomputer: ~/tmp$ ./changefilenames.sh
        mycomputer: ~/tmp$ ls data
        aaa.txt.old
        bbb.txt.old
        ccc.txt.old
        mycomputer: ~/tmp$


==============  

Vấn đề về tệp  
---------------------  

### Subject 02   

Lần này các em cũng sẽ làm ShellScript.  
Việc của các em là cho  old  vào đằng sau tên của tất cả các tệp nằm dưới thư mục data.  

Ví dụ:  
Nếu có tệp tên là abc.txt thì các em sẽ đổi tên nó thành abc.txt.old  

Các em sẽ không biết dưới thư mục data có những tệp gì cho đến khi chạy Script.  

Trọng điểm của lần này là  

*Thực hiện câu lệnh vòng lặp for  
Đối với Shellscript, các em hãy tìm hiểu về cách sử dụng câu lệnh for  
* Vì các em không biết tên tệp có ở dưới thư mục cho đến khi chạy Script, do vậy khi cho Script chạy các em phải lấy được tên tệp.  
* Các em hãy tìm hiểu về ` `  hoặc là $().  

Ví dụ:    

        mycomputer: ~/tmp$ ls data  
        aaa.txt  
        bbb.txt  
        ccc.txt  
        mycomputer: ~/tmp$ ./changefilenames.sh  
        mycomputer: ~/tmp$ ls data  
        aaa.txt.old  
        bbb.txt.old  
        ccc.txt.old  
        mycomputer: ~/tmp$  



