# OverTheWire Bandit

[OverTheWire](http://overthewire.org/wargames/bandit)

Level 0:
<br>
The goal of this level is for you to log into the game using SSH. The host to which you need to connect is bandit.labs.overthewire.org, on port 2220. The username is bandit0 and the password is bandit0. Once logged in, go to the Level 1 page to find out how to beat Level 1.
```
ssh bandit0@bandit.labs.overthewire.org -p 2220
Password: bandit0
```
![image](https://user-images.githubusercontent.com/47408756/129326145-3e736463-2e7f-45e8-8bc6-e532c2a5e2d0.png)


Level 0 - Level 1:
<br>
The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.
```
ssh bandit0@bandit.labs.overthewire.org -p 2220
Password: boJ9jbbUNNfktd78OOpsqOltutMc3MY1
```
![image](https://user-images.githubusercontent.com/47408756/129327009-be170199-084b-426d-b77c-b9caf032f2aa.png)

Level 1 - Level 2:
<br>
The password for the next level is stored in a file called - located in the home directory
```
ssh bandit0@bandit.labs.overthewire.org -p 2220
Password: CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
```
![image](https://user-images.githubusercontent.com/47408756/129328159-8f3b498d-a2d0-4860-af10-ef801cc0d306.png)

Level 2 - Level 3:
<br>
The password for the next level is stored in a file called spaces in this filename located in the home directory
```
ssh bandit1@bandit.labs.overthewire.org -p 2220
Password: CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
```
![image](https://user-images.githubusercontent.com/47408756/129329018-7a4cb1c2-005a-4b89-86d8-7eee931b1d4d.png)

Level 3 - Level 4:
<br>
The password for the next level is stored in a hidden file in the inhere directory.
```
ssh bandit3@bandit.labs.overthewire.org -p 2220
Password: UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK
```
![image](https://user-images.githubusercontent.com/47408756/129329450-94e02aab-db93-4e4d-ad9f-2ef0a6eabb34.png)

Level 4 - Level 5:
<br>
The password for the next level is stored in the only human-readable file in the inhere directory. Tip: if your terminal is messed up, try the “reset” command.
```
ssh bandit4@bandit.labs.overthewire.org -p 2220
Password: pIwrPrtPN36QITSp3EQaw936yaFoFgAB
```
![image](https://user-images.githubusercontent.com/47408756/129329758-195cb9a4-12a7-4b79-9b80-ad1ec9f3e8b7.png)

Level 5 - Level 6:
<br>
The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:

human-readable
1033 bytes in size
not executable
```
ssh bandit5@bandit.labs.overthewire.org -p 2220
Password: koReBOKuIDDepwhWk7jZC0RTdopnAYKh
```
![image](https://user-images.githubusercontent.com/47408756/129330082-b16bf928-ed1e-4e6b-992e-3f222cd539dc.png)

Level 6 - Level 7:
<br>
The password for the next level is stored somewhere on the server and has all of the following properties:

owned by user bandit7
owned by group bandit6
33 bytes in size
```
ssh bandit6@bandit.labs.overthewire.org -p 2220
Password: DXjZPULLxYr17uwoI01bNLQbtFemEgo7
```
