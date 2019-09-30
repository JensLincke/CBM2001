<!-- lang:de_DE -->

# Praktikumsbericht Pauline Lincke HPI September/Oktober 2019 



# CBM2001

## 1. Einfache Programme

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
* Anweisung ist an Zeile gebunden 
* Es kann eine beliebige Zeilennummerierung gewählt werden
* die Zeilen werden von 1 aufsteigend abgespielt
* Die Zeilen müssen nicht Direkt aufeinander folgend sein
* Eine Nummerierung mit nicht direkt aufeinander folgenden Zahlen ist vorteilhaft, da man so noch Platz für Einschübe in das Programm hat
* `run` lässt Programm abspielen
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
10 i=0
20 print i
30 i=i+1
40 go to 20
```
* Mit diesen Befehlen zählt der Computer von 0 in einer-Schritten aufwärts, bis man ihn stoppt
* 0 ist der Startpunkt
* `i=i+1` gibt an, dass das Programm in Einer-Schritten zählen
* ` go to 20` lässt das Programm sich immer wieder wiederholen
## 2. Speichern
``` 
save 
```
* speichert das gesamte Programm auf einer Kassette, falls eine solche angeschlossen ist
* Speichert man ein Programm auf einer Kassette kann man es durch `load`
wieder laden, falls es durch ausstellen des Computers,oder ähnliches, gelöscht wurde
* dies kann eine Weile dauern
## 3. Drucken
```
10 Open 5,4,0
20 For k = 1 to 50
30 Print#5,k
40 next k
50 close 5
```
* öffnet den Drucker im normalen Druckmodus 
* druckt die Zahlen 1 bis 50 
* Damit dass funktioniert muss man einen Drucker anschließen, welcher funktionstüchtig ist und ein Blatt Papier einlegen
* schreibt man die "k's" in Großbuchstaben funktioniert es nicht #interessant 





