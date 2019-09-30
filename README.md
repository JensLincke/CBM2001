<!-- lang:de_DE -->

# CBM2001
## 1. 

```
print "hello"
hello
```
* führt eine Anweisung einfach aus
```
10 print "hello"
run
hello
run
hello
```
* Anweisung ist an Zeile gebunden (10)
* `run` lässt Programm abspielen 
* die Zeilen werden von 1 aufsteigend abgespielt
* Die Zeilen müssen nicht Direkt aufeinander folgend sein 
```
10 print "hello"
20 go to 10 
```
* Programmabschnitt wiederholt sich immer wieder von Zeile 10 bis 20
* schreibt immer wieder "hello" bis man das Programm unterbricht 
```
list
```
* zeigt alle Programme (an Zeilen gebundene Anweisungen) an
``` 
save 
```
* speichert das gesamte Programm auf einer Kassette, falls eine solche angeschlossen ist
* Speichert man ein Programm auf einer Kassette kann man es durch `load`
wieder laden, falls es durch ausstellen des Computers,oder ähnliches, gelöscht wurde
* kann eine Weile dauern
```
10 i=0
20 print i
30 i=i+1
40 go to 20
```

