# Datensatz Beziehung zwischen Akteuren auf Staatsebene
Codebuch stand 2025-06
erstellt von Emely Sträter (es162@hdm-stuttgart.de)

## Inhalt

- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

## Ursprung und Datenerhebung  
Das Netzwerk ist ein *gerichtetes one-mode Akteursnetzwerk*. Es wurden zwei getrennte Fragen erhoben:
**Zusammenarbeitsnetzwerk**
1) In welchem Verhältnis stehen Regierungschefs und deren Stellvertreter zueinander?
2) Welche Akteure haben ihr Amt an welchen Nachfolger übergeben?

# Edge-Attribute
**id**
(eindeutige Codierung des Knoten)
codiert von 1 bis 16, jede ID entspricht einem Akteur

**from**
initiierender Knoten, in diesem Fall hat eine Beziehung zu dem jweiligen Akteur

**relation**
Verhältnis 
1 = Arbeit,
2 = Amtsübergabe

**time**: Zeitpunkt der Beziehung/Interaktion
 

# Node-Attribute

**id**  
Identische ID wie aus der edgelist zur Identifikation der Knoten.

**name**
numerische ID

**partei**: Parteizugehörigkeit 1= csu 2= cdu 3= spd 4= fdp 5= parteilos (numeric)\
**education**: Fachrichtung des Studiums 1= jura 2= geschichte 3= powi 4= mewi (numeric)\
**journalist**: TRUE/ FALSE
**type**: Form des Seiens 1 Person, 2 Organisation, 3 Partei (numeric)\


 
