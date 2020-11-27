# Introducció: Elements del desenvolupament d'aplicacions    
## Tipus de Software  
1. **Software de sistemes**:  
   ![logos de varis S.O.](https://raw.githubusercontent.com/jesus-zafra/Apuntes_UF1_1/main/so-icons.jpg)  
   Són aquells que treballen amb el maquinari del sistema. p.ex. sistemes operatius, els drivers...  
2. **Software d'aplicacions**:  
   ![icona del wordpad](https://raw.githubusercontent.com/jesus-zafra/Apuntes_UF1_1/main/wordpad-paint.jpg)  
    Aquells programes que són d'utilitat per als usuaris, p.ex. suite ofimàtica, navegadors web...
3. **Software de desenvolupament**: 
   ![programa de diseny amb un braç robòtic](https://raw.githubusercontent.com/jesus-zafra/Apuntes_UF1_1/main/autocad-brazo-robot.jpg)  
    Tot programa que serveixi per desenvolupar quelcom que s'ha de produïr. p.ex. editors, compiladors, programes de CAD...
  
#### Relació Hardware-Software  
* **Disc dur**:  
   ![foto de un disc dur](https://raw.githubusercontent.com/jesus-zafra/Apuntes_UF1_1/main/disco-duro.jpg) 
  
    Emmagatzema permanentment fitxers de dades o executables.
* **Memòria RAM**: 
  
   ![foto de un disc dur](https://raw.githubusercontent.com/jesus-zafra/Apuntes_UF1_1/main/memoria-ram.jpg)  
  
    Emmagatzema temporalment dades binàries que poden ser codi executable o informació. Es moltíssim molt més ràpida d'accedir que un disc dur.
* **CPU**: 
   ![foto d'una CPU](https://raw.githubusercontent.com/jesus-zafra/Apuntes_UF1_1/main/cpu.jpg)  
      
    llegeix i executa instruccions o dades emmagatzemades en la memòria RAM.
* **E/S**:  
   ![foto de un disc dur](https://raw.githubusercontent.com/jesus-zafra/Apuntes_UF1_1/main/perifericos.gif)  
  
    Els **perifèrics d'entrada** ens faciliten l'entrada de les dades. Un típic exemple d'aquest és el teclat. Per altra banda, els **perifèrics de sortida** permeten que visualitzem (o millor dit, percibim), els resultats de la gestió de les entrades que vam entrar. El perifèric de sortida típic per excel·lència són els monitors, però també ho són els altaveus, les impressores, etc.
  
#### Codi font, objecte i executable  
* Codi font:   
    El codi font és el programa escrit fent ús de la sintaxi del llenguatge de programació que utilitzem guardat amb codis alfanumèrics.
* Codi objecte:  
    El codi objecte és la traducció del programa en codi font a un codi binari determinat que servirà per muntar el codi executable.
* Codi executable:  
    Es compon de codis en llenguatge màquina, expressat en codi binari (amb uns i zeros), que són directament executats per la màquina.
# Cicle de vida del software  
#### Fases del desenvolupament de software    
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
#### Tipus de Manteniment
* **Correctiu**: es corregeixen errors.
* **Perfectiu**: millores del funcionament.
* **Evolutiu**: s'afegeixen noves funcionalitats.
* **Adaptatiu**: s'adapta a nous entorns.
# Models de Software
* **Models clàsics**:  
   **Model en cascada**
   **Model en V**
* **Model de construcció de prototips**
* **Models evolutius o incrementals**
   **Model en espiral (iteratiu)**
   **Metodologies àgils**
#### Model en Cascada
   En el model en cascada pasem de fase a fase una darrera de l'altre desde la primera fins a la darrera fase, d'amunt cap avall, en aquest precís ordre, i cada fase s'ha de conformar amb el resultat que li dona la fase anterior. Aquesta rigidessa fa que els projectes fets seguint aquest model s'adaptin mal a un continuat canvi en les especificacions d'un producte.
   ![diagrama de model en cascada](https://raw.githubusercontent.com/jesus-zafra/Apuntes_UF1_1/main/metodologia-cascada.png)  

#### Model en V
   En el model en V, es parteix de les fases d'anàlisi cap avall igual que en el model en cascada però durant tot el procès es comuniquen varis departaments per verificar i validar parts del programa i tornar-los a una fase prèvia si fos necessari, tal i com s'observa al diagrama. És un model que s'adapta millor davant molts canvis en les especificacions dels programes al contrari que succeïa amb el *model en cascada*.
   
   ![diagrama de model en V](https://raw.githubusercontent.com/jesus-zafra/Apuntes_UF1_1/main/modelo-v.jpg)   
### Model en Espiral
   En el model en espiral sempre s'està treballant i portant la part adient al departament que calgui portar-lo per fer-li millores o adaptacions necessàries. És el model ideal per desenvolupar programes en els que, en un futur es prevegin nombrosos canvis en les seves especificacions.
   
   ![diagrama de model en espiral](https://raw.githubusercontent.com/jesus-zafra/Apuntes_UF1_1/main/model-espiral.png)  


   
[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)]()
