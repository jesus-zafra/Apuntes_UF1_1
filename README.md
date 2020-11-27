# Introducció: Elements del desenvolupament d'aplicacions    
## Tipus de Software  
Es poden clasificar en tres grups:
1. **Software de sistemes**  
2. **Software d'aplicacions**  
3. **Software de desenvolupament**  
---  
* **Software de sistemes**:  
   ![logos de varis S.O.](https://raw.githubusercontent.com/jesus-zafra/Apuntes_UF1_1/main/so-icons.jpg)  
   
   Són aquells que treballen amb el maquinari del sistema. p.ex. sistemes operatius, els drivers... 
   
* **Software d'aplicacions**:  
   ![icona del wordpad](https://raw.githubusercontent.com/jesus-zafra/Apuntes_UF1_1/main/wordpad-paint.jpg) 
   
    Aquells programes que són d'utilitat per als usuaris, p.ex. suite ofimàtica, wordpad, paint, navegadors web, etc.
    
* **Software de desenvolupament**: 
  
   ![programa de diseny amb un braç robòtic](https://raw.githubusercontent.com/jesus-zafra/Apuntes_UF1_1/main/autocad-brazo-robot.jpg)  
   
    Tot programa que serveixi per desenvolupar quelcom que s'ha de produïr. p.ex. editors, compiladors, programes de CAD, etc.
---  
#### Relació entre Hardware / Software  
* **Disc dur**:  

   ![foto de un disc dur](https://raw.githubusercontent.com/jesus-zafra/Apuntes_UF1_1/main/disco-duro.jpg) 
  
    Emmagatzema permanentment fitxers de dades o executables.
    
* **Memòria RAM**: 
  
   ![foto de un disc dur](https://raw.githubusercontent.com/jesus-zafra/Apuntes_UF1_1/main/memoria-ram.jpg)  
  
    Emmagatzema temporalment dades binàries que poden ser codi executable o informació. Es moltíssim molt més ràpida d'accedir que un disc dur.
    
* **CPU**: 

   ![foto d'una CPU](https://raw.githubusercontent.com/jesus-zafra/Apuntes_UF1_1/main/cpu.jpg)  
      
    La CPU, o unitat central de procés, llegeix i executa instruccions o dades emmagatzemades en la memòria RAM. 
    
* **E/S**:  

   ![foto amb exemples de perifèrics E/S](https://raw.githubusercontent.com/jesus-zafra/Apuntes_UF1_1/main/perifericos.gif)  
  
    Els **perifèrics d'entrada** ens faciliten l'entrada de les dades. Un típic exemple d'aquest és el teclat. Per altra banda, els **perifèrics de sortida** permeten que visualitzem (o millor dit, percibim), els resultats de la gestió de les entrades que vam entrar. El perifèric de sortida típic per excel·lència són els monitors, però també ho són els altaveus, les impressores, etc.
---  
# Programes: Tipus de codi
#### Codi font, objecte i executable  
* Codi font:   
    El codi font és el programa escrit fent ús de la sintaxi del llenguatge de programació que utilitzem guardat amb codis alfanumèrics.
* Codi objecte:  
    El codi objecte és la traducció del programa en codi font a un codi binari determinat que servirà per muntar el codi executable.
* Codi executable:  
    Es compon de codis en llenguatge màquina, expressat en codi binari (amb uns i zeros), que són directament executats per la màquina.
---  
# Cicle de vida del software  
#### Fases del desenvolupament de software    
* **Anàlisi**  
* **Disseny**  
* **Codificació**  
* **Proves**  
* **Manteniment**  
  
Primer l'*arquitecte de software* fa un **anàlisi** de la viabilitat per resoldre el problema especificant els *requisits del client*. L'arquitecte estudiarà el temps que es pot trigar en fer-lo i les inversions que seràn necessàries. La especificació dels requisits és molt important que siguin clars i concissos, ha d'evitar detalls de disseny o implementació, ha de ser comprensible pel client.  
  
Els *analistes* s'ocuparan de **dissenyar** els diagrames que usaran els *programadors* en la **fase de codificació** del programa.
  
Les activitats més habituals a la fase de disseny són:  
  
* **Disseny arquitectònic** 
* **Disseny detallat**   
* **Disseny de dades**  
* **Disseny d'interfícies**  
  
A partir del disseny comença la fase de codificació pròpiament dita on es fa el programa utilitzant diferents llenguatges informàtics.  
    
Un cop codificat el programa, es fan proves i quan tot funcioni correctament s'entrega el programa al client. Durant la explotació del sofware, amb el el programa ja a les mans dels clients comença la **fase de manteniment**. En aquesta darrera fase es poden afegir noves funcionalitats i/o corregir possibles errors que apareguin.  
#### Tipus de Manteniment  
* **Correctiu**: es corregeixen errors.  
* **Perfectiu**: millores del funcionament.  
* **Evolutiu**: s'afegeixen noves funcionalitats.  
* **Adaptatiu**: s'adapta a nous entorns.  
  
---  
  
# Models de Software
* **Models clàsics**:  
   **Model en cascada**  
   **Model en V**  
* **Model de construcció de prototips**  
   **Model en espiral (iteratiu)**  
   **Metodologies àgils**  
  
#### Model en Cascada  
   En el model en cascada pasem de fase a fase una darrera de l'altre desde la primera fins a la darrera fase, d'amunt cap avall, en aquest precís ordre, i cada fase s'ha de conformar amb el resultat que li dona la fase anterior. Aquesta rigidessa fa que els projectes fets seguint aquest model s'adaptin mal a un continuat canvi en les especificacions d'un producte.
   ![diagrama de model en cascada](https://raw.githubusercontent.com/jesus-zafra/Apuntes_UF1_1/main/metodologia-cascada.png)  

#### Model en V  
   En el model en V, els nivells superiors indiquen una major abstracció mentre que els nivells inferiors indiquen més detall i s'apropen al resultat final tangible. Es parteix de les fases d'anàlisi d'amunt cap avall de forma semblant a com es fa en el model en cascada, però aquí durant tot el procès es comuniquen els diferents departaments que participen en el desenvolupament del projecte per verificar i validar els apartats convenients retornant el resultat a una fase prèvia en cas de no ser satisfactori tal i com s'observa al diagrama.  
   
   És un model que s'adapta bé davant nombrosos canvis en les especificacions, al contrari del que succeïa amb el *model en cascada*.
   
   ![diagrama de model en V](https://raw.githubusercontent.com/jesus-zafra/Apuntes_UF1_1/main/modelo-v.jpg)   

### Model de construcció de prototips
   Quan el client no detalla bé el que necessita fer o per no tenir experiència es fa un prototip per anar perfilant el disseny a partir d'aquest. El principal motiu és el fet de no construir un producte final que es molt més costós per després tenir que llençar-ho amb les pèrdues econòmiques i de temps que això comporta.
   El procès consisteix en crear un prototip a la fase d'anàlisi i se li dóna a provar al client per anar detallant els requisits i poder començar el projecte a partir d'ells. Aquest pas es repeteix les vegades que faci falta.  
     
#### Tipus de prototips  

* **Ràpids**    
   El prototip es fa amb qualsevol eina sabent que no tindrà més canvis o adaptacions en el futur, de tal manera que una vegada acabat i obtinguts els requisits per començar el projecte, el prototip ja no serveix per res i es rebutja.  

* **Evolutius**    
   El prototip és disenyat amb les mateixes eines amb que es desenvoluparà i es conserva com a base per a possibles adaptacions o extensions que es puguin necessitar en un futur.  
  
### Model en Espiral  
   En el model en espiral sempre s'està treballant i portant la part adient al departament que calgui portar-lo per fer-li millores o adaptacions necessàries. És el model ideal per desenvolupar programes en els que, en un futur es prevegin nombrosos canvis en les seves especificacions.  
   
   ![diagrama de model en espiral](https://raw.githubusercontent.com/jesus-zafra/Apuntes_UF1_1/main/model-espiral.png)  
  
### Metodologies Àgils
* Es basen en el desevolupament iteratiu e incremental
* Els requisits i solucions evolucionen amb el temps d'equips organitzats
* El treball es realitza amb la cooperació multidisciplinar 
* les més conegudes son:
  * Kanban  
  * Scrum
  * XP (eXtrem Programming)  
---

   ![llenguatges de programació](https://raw.githubusercontent.com/jesus-zafra/Apuntes_UF1_1/main/lenguajes.jpg)  
   
# Llenguatges de programació  
  
#### Obtenció de codi executable  
per obtenir el codi executable podem fer-ho de dos formes:  

   1. **Compilar**  
   2. **Interpretar**  

Per poder executar el programa a partir del codi font es fa un **anàlisi lèxic**, on es verifica que les instruccions estàn escrites de forma que el compilador/interpret les entén i partir de cada instrucció obté un token (un codi intern que identifica cada instrucció). Quan ja té tot "tokenitzat" fa un **anàlisi sintàctic** on les diferents instruccions s'uneixen a través dels tokens per formar estructures de programació, en un símil no informàtic es pot veure com si el lèxic son les paraules i la sintaxis les frases que es formen amb les paraules.
Quan no hi han errors es genera el **codi objecte**, el que no vol dir que el programa funcioni tal com volem que funcioni (podría ser que els nostres algorismes siguien erronis, per exemple).  
  
#### Llenguatges compilats
* **Exemples**: *C*, *C++*, *Ensamblador*
* **Avantatges**: execució molt eficient i ràpida. 
* **Inconvenients**: Cada vegada que necessitem modificar el codi font, s'ha de compilar tot de nou i pot ser un procés lent.  El programa només funcionará a la màquina o dispositiu per a la que s'ha compilat.
  
#### Llenguates interpretats
* **Exemples**: *PHP*, Javascript
* **Avantatges**: El codi font s'interpreta directament i no es depenent de la màquina, o sigui que es multiplataforma i ho podem executar a qualsevol màquina o dispositiu amb el programa interpret (la màquina virtual en Java, per exemple).
* **Inconvenients**: l'execució és més ineficient que si l'haguessim compilat.

### JAVA
* LLenguatge compilat e interpretat
* El codi font es compila donant lloc a un codi binari intermedi denominat **bytecode**. Es un codi objecte destinat a la màquina virtual de Java en lloc de codi objecte especific per a una màquina o dispositiu en particular.
* Aquest **bytecode** és interpretat per executar-lo.  
  
* **Avantatges**:
  * Estructurat i orientat a objectes.
  * Fàcil d'aprendre.
  * Bona documentació i base d'usuaris.    
  
* **Inconvenients**:  
   * Execució menys eficient que els llenguatges compilats.  

# Tipus de llenguatges segons el seu paradigma
Hi han dos paradigmes:  
* **Declaratiu** 
  Als llenguatges de tipus **declaratius** indiquem el resultat **que** volem aconseguir, i aquest s'encarrega d'usar els mètodes necessaris per aconseguir-lo.
   * **Tipus de llenguatges declaratius**: (normalment son interpretats)
    * **Lògics**: Utilitzen regles. p.ex.: *Prolog*
    * **Funcionals**: Usen funcions. p.ex.: *Lisp*
    * **Algebraics**: Usen sentencies. p.ex.: *SQL*
     
* **Imperatiu**  
  En aquests els programadors indiquen al llenguatge **com** volen aconseguir el resultat, pas per pas.  
  * **Tipus de llenguatges imperatius**: (la majoria son compilats)
   * **Estructurats**: *C*
   * **Orientats a objectes**: *Java*
   * **Multiparadigma**: *C++*, *Javascript*  
    
   *(Els llenguatges orientats a objectes també són llenguatges estructurats)*
# Tipus de Llenguatges segons el seu nivell d'abstracció:
* **Baix nivell**: *Ensamblador*
* **Mig nivell**: *C*, *C++*
* **Alt nivell**: *Java*  
  
---  
  
   ![llenguatges de programació](https://raw.githubusercontent.com/jesus-zafra/Apuntes_UF1_1/main/lenguajes2.jpg)     
   
# Criteris per sel·leccionar un llenguatge
* **Facilitat d’aprenentatge**  
   És molt important que el llenguatge sigui fàcil d’entendre. Per això cal que hi hagi abundant documentació, i que aquesta sigui de bona qualitat. També és recomanable que hi hagi una certa base d’usuaris per tal de solucionar possibles dubtes o problemes de forma ràpida, posant-los en comú amb altres programadors.  

* **Camp d’aplicació**  
   El llenguatge escollit ha de ser el més adequat per a la tasca que volem desenvolupar.  

* **Eines de desenvolupament**  
   És important que el llenguatge disposi d’una bona quantitat d’eines que ens ajudin a desenvolupar de forma més ràpida i eficient.  
  
* **Portabilitat**  
   També és molt important poder trobar el nostre entorn de desenvolupament disponible en el màxim de sistemes operatius/màquines o dispositius facilitant-nos el poder treballar allà on estem sense problemes.  
  
* **Reusabilitat**  
   Es tracta de trobar un llenguatge o entorn de programació que ens permeti resoldre les diferents tasques que volem desenvolupar utilitzant un mínim d’accessoris externs.  
  
* **Imposició del client**  
   De vegades ens resultarà interessant utilitzar el mateix llenguatge que tothom utilitza de tal forma que tots parlem el mateix idioma. També pot ser que el client o una empresa ens imposi el que hem d’utilitzar.  
   
[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)]()
