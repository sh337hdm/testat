# Codebuch
Codebuch Stand 2022-12, erstellt von Sara Hedrich (sh337@hdm-stuttgart.de)

## Inhalt
edges.csv (Edgelist)

nodes.csv (Nodelist)

codebuch.md (Codierung der Datensätze)

## Ursprung und Datenerhebung
Ich habe den Datensatz unter eigener Recherche im Internet im Rahmen des Testats des dritten Semesters im Kurs Netzwerkanalyse erhoben.

Das Netzwerk ist ein gerichtetes two-mode Netzwerk. 

Es wurden folgende Aspekte untersucht: 

Wer ist mit wem vernetzt? Und wie sind sie vernetzt? 
Welche gesellschaftlichen Sektoren sind daran beteiligt gewesen? 

Umgang mit fehlenden Werten: Fehlende Werte werden nicht erfasst.

# EDGE-Attribute
**from**
initiierender Knoten mit eindeutiger Kennung, lässt sich in *id* der Nodelist exakt wiederfinden

**to**
erhaltender Knoten mit eindeutiger Kennung, lässt sich in *id* der Nodelist exakt wiederfinden

**relation**
Beziehungsart zwischen den Knoten
1=*friends*
2=*love*
3=*colleagues*
4=*member*
5=*founder*

# NODE-Attribute
**id**
Identische ID wie aus der edgelist zur Identifikation der Knoten.

**name**
Numerische ID. 

**type**
1=*Person*
2=*gesellschaftlicher Sektor*

**sector**
1=*Wirtschaft*
2=*Militär*
3=*Politik*
4=*Adel*
5=*Religion*
6=*Justiz*
7=*Gesundheitswesen*
8=*Kultur*




