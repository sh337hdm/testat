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

Wer ist mit wem vernetzt? Wie sind sie vernetzt? 

Welche gesellschaftlichen Sektoren sind daran beteiligt gewesen? 

Umgang mit fehlenden Werten: Fehlende Werte werden nicht erfasst.

# EDGE-Attribute
**from**

initiierender Knoten mit eindeutiger Kennung, lässt sich in *id* der Nodelist exakt wiederfinden

**to**

erhaltender Knoten mit eindeutiger Kennung, lässt sich in *id* der Nodelist exakt wiederfinden

**relation**

Beziehungsart zwischen den Knoten

1=*Privater Kontakt*

2=*(Ex-)Liebesbeziehung*

3=*Kollegen*

4=*Mitglieder/Teilnehmer*

5=*Gründer*

6=*Angestellter*

# NODE-Attribute
**id**

Identische ID wie aus der edgelist zur Identifikation der Knoten.

**name**

Numerische ID. 

**type**

1=*Person*

2=*Organisation*

**sector**

1=*Wirtschaft*

2=*Politik*

3=*Adel*

4=*Religion*

5=*Judikative*

6=*Exekutive*

7=*Gesundheitswesen*

8=*Kultur*




