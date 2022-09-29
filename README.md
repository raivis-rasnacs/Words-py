# Words-py
Uzdevums par vārdu veidošanu
---
## **Problēmas apraksts:**<br>
Doti 2 vārdi, kuru garums nepārsniedz 20 burtus. Nepieciešams pārbaudīt, vai no pirmā vārda burtiem var izveidot otro vārdu. Zināms, ka otrais vārds ir īsāks par pirmo un tajā neviens burts neatkārtojas.<br>

## **Specifikācija**:<br>
Programma pieprasa ievadīt 2 atbilstošus vārdus. Algoritms caurskata abus vārdus un pārbauda, vai visi otrā vārda burti ir sastopami arī pirmajā vārdā. Ja pirmajā vārdā burts ir vienu reizi, arī otrajā vārdā tas var parādīties tikai vienu reizi. Ja vārdu iespējams izveidot, programma izvada "var", citādi izvada "nevar". Programma izvada paziņojumu "nederīgi dati" un neveic pārbaudi, ja izpildās kāds no kritērijiem:
* kāds no vārdiem ir garāks par 20 simboliem
* otrais vārds ir garāks par pirmo

### Testpiemēri:
|Ievaddati|Izvaddati|
|---|---|
|saule aula|var|
|skola ola|var|
|blūze lūza|nevar|
|ploteris motelis|nevar|

## Izpildes nosacījumi:
Sastādi algoritmu dotajā failā **words.py**!
Atceries komentēt kodu!
Beigās pievieno komentāru ar uzvārdu un klasi!
