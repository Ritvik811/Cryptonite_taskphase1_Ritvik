# File Globbing Module
This is an interesting module as i didn't know what globbing was before so it was a new concept. 
The challenges were easy except **pondering paths** as I passed the argument as /home/hacker/challenge/files but quickly realised my mistake and changed it to /challenge/files.
Mixing globs was a bit tough but manageble once it prompted me to use [].

## Matching with *
Here we learn how to use *. we use that to change directory and get the flag

![image](https://github.com/user-attachments/assets/d1caeb85-6e25-4347-a531-cd47349e3390)

## Matching with ?
Here we learn how to use ?. same as aboove but we use ?.

![image](https://github.com/user-attachments/assets/47a19de4-edc5-44e0-af29-cc89ce918aff)

## Matching with []
Here we use [] to glob. the challenge was simple

![image](https://github.com/user-attachments/assets/0dc5a677-fcdb-4d70-bd4f-7e51265d51fa)

## Matching paths with []
It is the same as last quesion but without changing the cwd. we use /challenge/run /challenge/files/file_[bash].
**flag : pwn.college{8lx1pRDWfr_0xu5v5A4WkAiCVl8.dRjM4QDLwUTO0czW}**

## mixing globs
Here i noticed the first character of every file in the directory was unique so i used the following command to get the flag

![image](https://github.com/user-attachments/assets/8991f5db-c265-4639-b10a-9a13554a1a54)

## exclusionary globbing
Here we learn how to exclude using ! or ^. the challenege was easy and i used /challenge/run [!pwn]*. this is just like the previous challenge with a slight change
**flag: pwn.college{IvuBaJS-OVf_cXzSQZnq0hxL-dy.dZjM4QDLwUTO0czW}**
