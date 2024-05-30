# FTP
FTP (File Transfer Protocol) คือ server สำหรับการฝาก file และสำหรับการเป็นที่พัก file ให้ผู้อื่นมา download โดยใน lab นี้เราจะทำการเข้าถึง FTP Server ด้วย anonymous user ซึ่งเป็น user ที่เป็น user สำหรับบุคคลภายนอก ซึ่งมีหลายๆครั้งที่การอนุญาตให้บุคคลภายนอกดังกล่าวเข้าถึงได้กลายเป็นข้อมูลรั่วไหลจากจุดดังกล่าว

1.เปิด FTP client:

ftp [IP address]

2.ล็อกอิน:

หากได้รับการร้องขอใส่ username:

Name (hostname:yourusername): [username]

หากได้รับการร้องขอใส่ password:

Password: [password]

Lab : หาไฟล์ flag โดยการเข้าถึง FTP Server

IP: 149.28.159.195

ด้วย user anonymous user

1. ftp (target ip)
   
2. user : anonymous
   
3. password :

4.ls

5.get flag.txt 

6.lpwd (/home/kali)

7.bye

8.cat /home/kali/flag.txt 

Ans : The flag is recon{e97VgZXRclQeUIA0KG95336gZp4@o}

![image](https://github.com/thanawut2903/FTP/assets/159118913/d4773f59-8f72-48af-9e81-86b2dbfd0aef)




