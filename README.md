[bash2.txt](https://github.com/user-attachments/files/21079072/bash2.txt)[bash1.txt](https://github.com/user-attachments/files/21079068/bash1.txt)Работа с git и bash.

Задача 1: 
[Uploading ba1)touch bash1.txt
2)cd /C/Games/bash
3)basename "$PWD"
4)mkdir test1
5)cd /C/Games/bash/test1
6)touch 1.txt 2.txt 3.txt
7)ls
8)cd ..
9)mkdir test2
10)rmdir test2
11)rm /C/Games/bash/test1/2.txt
12)mkdir test3 
   touch 1.txt 2.txt
13)rm -r test3
14)mkdir test4
15)mv /C/Games/bash/test1/1.txt /C/Games/bash/test1/3.txt /C/Games/bash/test4/
16)for i in {1..3}; do echo "line" >> 1.txt; done
17)cat 1.txt
18)for i in {1..3}; do echo "line" >> 3.txt; done
19)cat 1.txt 3.txt
20)nano 1.txtsh1.txt…]()

Задача 2:
[Uplo1)touch bash2.txt
2)cd /C/Games/bash
3)mkdir test3
4)touch 4.txt 5.txt 6.txt
  echo -e "row1\nrow2\nrow3\nrow4" >> "4.txt"
  echo -e "row1\nrow2\nrow3\nrow4" >> "5.txt"
  echo -e "row1\nrow2\nrow3\nrow4" >> "6.txt"
5)grep "row2" 5.txt
6)grep -r "row" test3/
7)grep -c "row" 6.txt
8)-name "5.txt"
9)find . -type f -name "5.txt" -exec rm {} \;
10)echo test > 4.txt
11)sed -i 's/test/fail/' 4.txt
12)echo test >> 4.txt
13)ps -ef
14)kill 666
15)ping rusau.net
16)ping -c 5 rusau.net
17)curl -X GET "https://petstore.swagger.io/v2/pet/findByStatus?status=available,pending,sold"
18)curl -X POST "https://petstore.swagger.io/v2/user" \
-H "Content-Type: application/json" \
-d '{
  "id": 1,
  "username": "new",
  "firstName": "Иван",
  "lastName": "Иванов",
  "email": "ivanov@example.com",
  "password": "123",
  "phone": "1234567890",
  "userStatus": 1
}'ading bash2.txt…]()
