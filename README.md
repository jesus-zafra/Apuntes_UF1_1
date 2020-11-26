# Introducció: Elements del desenvolupament d'aplicacions    
## Tipus de Software  
1. Software de sistemes:  
    Són aquells que treballen amb el maquinari del sistema. p.ex. sistemes operatius, els drivers...
2. Software d'aplicacions:  
    Aquells programes que són d'utilitat per als usuaris, p.ex. suite ofimàtica, navegadors web...
3. Software de desenvolupament:  
    Tot programa que serveixi per desenvolupar quelcom que s'ha de produïr. p.ex. editors, compiladors, programes de CAD...
  
## Relació Hardware-Software  
* Disc dur:  
    Emmagatzema permanentment fitxers de dades o executables.
* Memòria RAM: 
    Emmagatzema temporalment dades binàries que poden ser codi executable o informació. Es moltíssim molt més ràpida d'accedir que un disc dur.
* CPU:  
    llegeix i executa instruccions o dades emmagatzemades en la memòria RAM.
* E/S:  
    recull noves dades desde perifèrics d'entrada (p.ex. un teclat) o mostra resultats mitjançant perifèrics de sortida (p.ex. un monitor).
  
## Codi font, objecte i executable  
* Codi font:   
    El codi font és el programa escrit fent ús de la sintaxi del llenguatge de programació que utilitzem, i està guardat amb codis alfanumèrics
* Codi objecte:  
    El codi objecte és la traducció del programa en codi font a un codi binari determinat que servirà per muntar després el codi directament executable.
* Codi executable:  
    Es compon de codis en llenguatge màquina, expressat en codi binari (amb uns i zeros), que son directament executats per la màquina.
  
## Fases del desenvolupament de software    
* Anàlisi
* Disseny
* Codificació
* Proves
* Manteniment
  
Primer l'*arquitecte de software* farà un **anàlisi** de la viabilitat per resoldre el problema especificant els *requisits del client*. L'arquitecte estudiarà el temps que es pot trigar en fer-lo i les inversions que seràn necessàries. La especificació dels requisits és molt important que siguin clars i concissos, ha d'evitar detalls de disseny o implementació, ha de ser comprensible pel client.  
  
Els *analistes* s'ocuparan de **dissenyar** els diagrames que usaran els *programadors* en la **fase de codificació** del programa.
  
Les activitats més habituals a la fase de disseny són:
* Disseny arquitectònic
* Disseny detallat
* Disseny de dades
* Disseny d'interfícies

A partir del disseny comença la fase de codificació pròpiament dita on es fa el programa utilitzant diferents llenguatges informàtics.
  
Un cop codificat el programa, es fan proves i quan tot funcioni correctament s'entrega el programa al client. Durant la explotació del sofware, amb el el programa ja a les mans dels clients comença la **fase de manteniment**. En aquesta darrera fase es poden afegir noves funcionalitats i/o corregir possibles errors que apareguin.
## Tipus de Manteniment
* **Correctiu**: es corregeixen errors
* **Perfectiu**: millores del funcionament
* **Evolutiu**: s'afegeixen noves funcionalitats
* **Adaptatiu**: s'adapta a nous entorns.

<img src="http://jamj2000.github.io/entornosdesarrollo/1/assets/cascada.png" alt ="model en cascada" />
[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)]()
