# myFirstRepo
[![ScreenShot](téléchargement.jpg)](https://www.youtube.com/watch?v=dQw4w9WgXcQ&ab_channel=RickAstley)

code
*** Export ASSEMBLEUR x86, compilateur TASM ***
*******************
```.model small
.stack 100h

.data
hello  db  "Hello the World !$"

.code
main  proc

MOV  AX,@data
MOV  DS,AX

MOV  DX,offset hello
MOV  AX,0900h
INT  21h

MOV  AX,4C00h		  
INT  21h

main endp
end main
```
