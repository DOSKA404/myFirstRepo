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
---
title: "Habits"
author: John Doe
date: March 22, 2005

 powerpoint_presentation:
    reference_doc: my-styles.pptx
---

# In the morning

## Getting up

- Turn off alarm
- Get out of bed

## Breakfast

- Eat eggs
- Drink coffee

# In the evening

## Dinner

- Eat spaghetti
- Drink wine

---

```{r, cars, fig.cap="A scatterplot.", echo=FALSE}
plot(cars)
```

## Going to sleep

- Get in bed
- Count sheep
