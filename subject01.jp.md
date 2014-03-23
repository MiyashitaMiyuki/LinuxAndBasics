LinuxAndBasics
==============

Vấn đề về tệp.
---------------------

### Subject 01 

Subject lần này là các em sẽ làm một shell script hơi khó một chút.
Nhân tiện thì cũng viết một lập trình C đơn giản.
Các em cũng cho câu trả lời giống như cách làm của subject lần trước.


Về trọng điểm của lần này là

* Phương thức đánh giá xem chương trình chạy thành công hay thất bại.
* Phương thức tiếp nhận argument bằng shell script.

Vậy, các em hãy làm shell script với những điều kiện dưới đây.

1. Tên là runcprog.sh
2. Compile source code viết bằng C rồi cho chạy.
3. Cách gọi được viết ở dòng dưới、

        ./runcprog.sh Tên tệp của chương trình của C
4. Về lập trình C, các em hãy viết một chương trình mẫu nhé.   
Nội dung là:

Viết một chương trình hiển thị "Hello World!" đơn giản.

5. Tên của chương trình C đã làm ở 4., giả định là mytest.c thì gọi 

         ./runcprog.sh mytest.c

thì đầu ra sẽ là

        Starting your C program:
        Hello World!

6. Trong trường hợp có lỗi ở mytest.c thì runcprog.sh sẽ xuất hiện thông báo dưới và kết thúc.

        Your C program is something wrong, please fix it.

7. Dù tên tệp của chương trình C là gì đi nữa thì các em hãy làm thế nào để nó chạy cho thành công.

Hết
