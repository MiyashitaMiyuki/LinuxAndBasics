LinuxAndBasics
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



