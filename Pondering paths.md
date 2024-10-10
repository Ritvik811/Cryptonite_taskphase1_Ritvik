# Pondering Paths module
since i have used ubuntu before i do have a little idea about the file system in linux and the CLI commands such as cd, ls, rm, mkdir etc

coming to the module it was pretty basic module. i knew the concepts before but i didn't know terms like **Relative Path** and **Absolute Path**
which was new to me. I unnecessarly spend 5 mins on "Home Sweet Home" module because of the 3 characters or less rule. 

## The root
'/' is the root directory and in this challenege we just had to invoke a file pwn
**flag: pwn.college{8HAOguu2maQ0gu3rJ1OxiW78bL8.dhzN5QDLwUTO0czW}**

## Program and Abosulte Path
We just added another path here to get the flag 
**flag: pwn.college{4SgtoJyfzUminRcBzexcRE39BF1.dVDN1QDLwUTO0czW}**

## Position thy self
Here I initially was comfused on how to get the desired directory but after running /challenge/run, It shows which directory is needed so it was pretty staright forward from there

![pondering paths ](https://github.com/user-attachments/assets/af9e8dcc-f212-4087-973f-5c973efeb89a)

## Position elsewhere 
This was the same problem as before but in a different directory
**flag: pwn.college{MiU9LPxc410CdNrwDi3VXIAttZq.ddDN1QDLwUTO0czW}"

## Position Yet elsewhere
Yet another same one but this time we needed to change into the root directory
**flag: pwn.college{s9-sUeH-9cS1hnMGcOjTVwjxpeP.dhDN1QDLwUTO0czW}**

## implicit relative paths, from /
This introduced the concepts of relative paths and was an easy solve to get the flag

![pp2](https://github.com/user-attachments/assets/14824dfa-1859-42db-9bea-009dddff0b65)

## explicit relative paths, from /
This was pretty similar too but here i have used '.'
**flag: pwn.college{4FYcvts6cJdrNvMraUmT0iFobIl.dBTN1QDLwUTO0czW}**

## implicit relative path 
This challenge displayed that linux explicitly doesn't run files unless specified. Here i used ./run to get the flag after changing the directoey
**flag: pwn.college{op85RGeLnF-cuUxisBjNJ-FOhUf.dFTN1QDLwUTO0czW}**

## Home Sweet Home
![image](https://github.com/user-attachments/assets/dff7bdcb-e732-4c5d-bda1-b31527fd4f0a)
