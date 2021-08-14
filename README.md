## Contents
* [Level 0](#level-0)
* [Level 0 - Level 1](#level-0---level-1)
* [Level 1 - Level 2](#level-1---level-2)
* [Level 2 - Level 3](#level-2---level-3)
* [Level 3 - Level 4](#level-3---level-4)
* [Level 4 - Level 5](#level-4---level-5)
* [Level 5 - Level 6](#level-5---level-6)
* [Level 6 - Level 7](#level-6---level-7)
* [Level 7 - Level 8](#level-7---level-8)
* [Level 8 - Level 9](#level-8---level-9)
* [Level 9 - Level 10](#level-9---level-10)
* [Level 10 - Level 11](#level-10---level-11)
* [Level 11 - Level 12](#level-11---level-12)

## Level 0

The goal of this level is for you to log into the game using SSH. The host to which you need to connect is bandit.labs.overthewire.org, on port 2220. The username is bandit0 and the password is bandit0. Once logged in, go to the Level 1 page to find out how to beat Level 1.
```
ssh bandit0@bandit.labs.overthewire.org -p 2220
Password: bandit0
```
![image](https://user-images.githubusercontent.com/47408756/129326145-3e736463-2e7f-45e8-8bc6-e532c2a5e2d0.png)


## Level 0 - Level 1
The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.
```
ssh bandit0@bandit.labs.overthewire.org -p 2220
Password: boJ9jbbUNNfktd78OOpsqOltutMc3MY1
```
![image](https://user-images.githubusercontent.com/47408756/129327009-be170199-084b-426d-b77c-b9caf032f2aa.png)

## Level 1 - Level 2
The password for the next level is stored in a file called - located in the home directory
```
ssh bandit0@bandit.labs.overthewire.org -p 2220
Password: CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
```
![image](https://user-images.githubusercontent.com/47408756/129328159-8f3b498d-a2d0-4860-af10-ef801cc0d306.png)

## Level 2 - Level 3
The password for the next level is stored in a file called spaces in this filename located in the home directory
```
ssh bandit1@bandit.labs.overthewire.org -p 2220
Password: CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
```
![image](https://user-images.githubusercontent.com/47408756/129329018-7a4cb1c2-005a-4b89-86d8-7eee931b1d4d.png)

## Level 3 - Level 4
The password for the next level is stored in a hidden file in the inhere directory.
```
ssh bandit3@bandit.labs.overthewire.org -p 2220
Password: UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK
```
![image](https://user-images.githubusercontent.com/47408756/129329450-94e02aab-db93-4e4d-ad9f-2ef0a6eabb34.png)

## Level 4 - Level 5
The password for the next level is stored in the only human-readable file in the inhere directory. Tip: if your terminal is messed up, try the “reset” command.
```
ssh bandit4@bandit.labs.overthewire.org -p 2220
Password: pIwrPrtPN36QITSp3EQaw936yaFoFgAB
```
![image](https://user-images.githubusercontent.com/47408756/129329758-195cb9a4-12a7-4b79-9b80-ad1ec9f3e8b7.png)

## Level 5 - Level 6
The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:
<br>
human-readable
<br>
1033 bytes in size
<br>
not executable
```
ssh bandit5@bandit.labs.overthewire.org -p 2220
Password: koReBOKuIDDepwhWk7jZC0RTdopnAYKh
```
![image](https://user-images.githubusercontent.com/47408756/129330082-b16bf928-ed1e-4e6b-992e-3f222cd539dc.png)

## Level 6 - Level 7
The password for the next level is stored somewhere on the server and has all of the following properties:
<br>
owned by user bandit7
<br>
owned by group bandit6
<br>
33 bytes in size
```
ssh bandit6@bandit.labs.overthewire.org -p 2220
Password: DXjZPULLxYr17uwoI01bNLQbtFemEgo7
```
![image](https://user-images.githubusercontent.com/47408756/129330543-aab3fe37-64f3-41e1-b294-86268aa256ff.png)
<br>
![image](https://user-images.githubusercontent.com/47408756/129330569-90f0e53a-5cd3-4178-bf37-a57f9a9a146e.png)
<br>
![image](https://user-images.githubusercontent.com/47408756/129330662-b316cbec-b13d-44b3-9a46-e2d905ec6680.png)

## Level 7 - Level 8
The password for the next level is stored in the file data.txt next to the word millionth
```
ssh bandit7@bandit.labs.overthewire.org -p 2220
Password: HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs
```
![image](https://user-images.githubusercontent.com/47408756/129331646-cc5f7467-79f6-473a-952e-cf4720e5eacc.png)
<br>
![image](https://user-images.githubusercontent.com/47408756/129332049-1508ed8f-7e31-433a-bd8f-f5359ea89b49.png)

## Level 8 - Level 9
The password for the next level is stored in the file data.txt and is the only line of text that occurs only once
```
ssh bandit8@bandit.labs.overthewire.org -p 2220
Password: cvX2JJa4CFALtqS87jk27qwqGhBM9plV
```
![image](https://user-images.githubusercontent.com/47408756/129332460-a154381c-82d6-4ed8-8bb2-e172d1ca132e.png)

## Level 9 - Level 10
The password for the next level is stored in the file data.txt in one of the few human-readable strings, preceded by several ‘=’ characters.
```
ssh bandit9@bandit.labs.overthewire.org -p 2220
Password: UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR
```
![image](https://user-images.githubusercontent.com/47408756/129332898-6a8f1dc0-6ec7-47a0-85a4-ebd115304a44.png)

## Level 10 - Level 11
The password for the next level is stored in the file data.txt, which contains base64 encoded data
```
ssh bandit10@bandit.labs.overthewire.org -p 2220
Password: truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk
```
![image](https://user-images.githubusercontent.com/47408756/129333206-c1b4ec0e-2e53-4918-9005-c8e039272e14.png)

## Level 11 - Level 12
The password for the next level is stored in the file data.txt, where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions
```
ssh bandit11@bandit.labs.overthewire.org -p 2220
Password: IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR
```
![image](https://user-images.githubusercontent.com/47408756/129333361-2828230c-8c96-4747-89b6-cc60080d138a.png)

## Level 12 - Level 13
The password for the next level is stored in the file data.txt, which is a hexdump of a file that has been repeatedly compressed. For this level it may be useful to create a directory under /tmp in which you can work using mkdir. For example: mkdir /tmp/myname123. Then copy the datafile using cp, and rename it using mv (read the manpages!)

```
ssh bandit12@bandit.labs.overthewire.org -p 2220
Password: 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu
```
![image](https://user-images.githubusercontent.com/47408756/129439976-5a28d58e-e8b7-4d2c-8417-f56931f2857d.png)
![image](https://user-images.githubusercontent.com/47408756/129439979-3b66c234-455f-4049-8840-7adde05a92de.png)
![image](https://user-images.githubusercontent.com/47408756/129439971-8e8a3692-7ec7-4c91-a8e8-4dcf465de647.png)


## Level 13 - Level 14
The password for the next level is stored in /etc/bandit_pass/bandit14 and can only be read by user bandit14. For this level, you don’t get the next password, but you get a private SSH key that can be used to log into the next level. Note: localhost is a hostname that refers to the machine you are working on
```
ssh bandit13@bandit.labs.overthewire.org -p 2220
Password: 8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL
```
![image](https://user-images.githubusercontent.com/47408756/129440086-c9ddc1ad-0f16-4ba5-a3bc-82d239f8bdfc.png)
![image](https://user-images.githubusercontent.com/47408756/129440090-1fbeac7a-feb5-4abc-9569-8b69119512fb.png)

## Level 14 - Level 15
The password for the next level can be retrieved by submitting the password of the current level to port 30000 on localhost.
```
ssh bandit14@bandit.labs.overthewire.org -p 2220
Password: 4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e
```
![image](https://user-images.githubusercontent.com/47408756/129440154-04d6204b-0cb3-4d22-ab71-324f735a07d0.png)


## Level 15 - Level 16
The password for the next level can be retrieved by submitting the password of the current level to port 30001 on localhost using SSL encryption.

Helpful note: Getting “HEARTBEATING” and “Read R BLOCK”? Use -ign_eof and read the “CONNECTED COMMANDS” section in the manpage. Next to ‘R’ and ‘Q’, the ‘B’ command also works in this version of that command
```
ssh bandit15@bandit.labs.overthewire.org -p 2220
Password: BfMYroe26WYalil77FoDi9qh59eK5xNr
```
![image](https://user-images.githubusercontent.com/47408756/129440260-942ff8d8-656b-40e6-81a2-9c28b05095cc.png)
![image](https://user-images.githubusercontent.com/47408756/129440264-4b93d0b8-526c-4c5e-9b96-ba1b15441b9e.png)

## Level 16 - Level 17
The credentials for the next level can be retrieved by submitting the password of the current level to a port on localhost in the range 31000 to 32000. First find out which of these ports have a server listening on them. Then find out which of those speak SSL and which don’t. There is only 1 server that will give the next credentials, the others will simply send back to you whatever you send to it.
```
ssh bandit16@bandit.labs.overthewire.org -p 2220
Password: cluFn7wTiGryunymYOu4RcffSxQluehd
```
