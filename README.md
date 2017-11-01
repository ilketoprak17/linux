# linux
Aldığım Hatalar:

DISCONNECT HATASI:1

Traceback (most recent call last):
  File "bfsoft.py", line 27, in <module>
    smtpserver.login(user, password)
  File "/usr/lib/python2.7/smtplib.py", line 610, in login
    AUTH_PLAIN + " " + encode_plain(user, password))
  File "/usr/lib/python2.7/smtplib.py", line 394, in docmd
    return self.getreply()
  File "/usr/lib/python2.7/smtplib.py", line 368, in getreply
    raise SMTPServerDisconnected("Connection unexpectedly closed")
smtplib.SMTPServerDisconnected: Connection unexpectedly closed  
  
  NOT:Hatanın sebebi çok büyük bi' ihtimalle gmail'in beni çok fazla deneme yüzünden bloklaması peki o halde bunu nasıl çözeceğim?
  
  PASSWORD FOUND HATASI:2
  
  Enter the target's username: ilketoprak17@gmail.com
Enter the password File: pass.txt
[-] Password is incorrect ===> 123456
 
[-] Password is incorrect ===> 2345
 
[-] Password is incorrect ===> 9054
 
[-] Password is incorrect ===> hjfk
 
[-] Password is incorrect ===> *******************
 
[-] Password is incorrect ===> 4tfgj
 
[-] Password is incorrect ===> 345

NOT:Yıldızlı kısımda şifrem doğru bir şekilde var fakat Password Found sonucunu alamıyorum.
