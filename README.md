# orthodox-christian-lectionary
This repository provides metadata for the Eastern Orthodox Lectionary.  It provides the data as a comma delimited file (csv) and as json.  It maps the readings to the IDs used by AGES Initiatives.

## Understanding the AGES IDs

An ID in AGES and OLW is a domain plus a topic plus a key.  In OLW the three parts are delimited using a ~ (tilde).  In AGES there are key-value files (with an .ares extension) such that the filename contains the domain and topic and the keys are within the file.
In this repository the domains have been removed from the ID, leaving just the topic and key.

Examples: 
- le.ep.ge.hierarch~legeLI.Epistle.chapverse = an epistle reading for a hierarch
- le.ep.mc.d001~lemcLI.Epistle.chapverse = the epistle reading for the first day of the movable cycle
- le.ep.me.m01.d01~lemeLI.Epistle.chapverse = the epistle reading for the first day of the first month, from the Menaion
- le.ep.va.baptism~levaBAP.Epistle.chapverse = the epistle reading for a Baptism service
- le.go.lu.d001~leluLI.Gospel.chapverse = the Gospel reading for the liturgy on the first day of the Lukan cycle
- le.go.mc.d001~lemcLI.Gospel.chapverse = the Gospel reading for the liturgy on the first day of the movable cycle
- le.go.mc.d068~lemcMA.Gospel.chapverse = the Gospel reading for Matins on the 68th day of the movable cycle

The abbreviations are:

- BAP = baptism
- chapverse = the chapter and verse
- d01 = day 1 of the month
- d001 = day 1 of a cycle, either the movable cycle or the cycle of readings from Luke, Matthew, etc.
- dSatAC = Saturday after Christmas.  
- dSatBC = Saturday before Christmas.  
- dSunAC = Sunday after Christmas.  
- dSunBC = Sunday before Christmas.  
- ep = epistle
- ge = general epistle (for someone, e.g. a hierarch, a martyr, etc.).
- go = gospel
- H1 = Hour 1
- HW = Holy Week
- le = lectionary
- LI = Liturgy
- lu = Luke
- MA = Matins (Orthros)
- mc = movable cycle.  The movable cycle starts with the Sunday of the Publican and the Pharisee.  It runs from day d001 to d364 or the Saturday before the Sunday of the Publican and the Pharisee, whichever comes first.
- me = menaion
- m1 = month 1 (in AGES, month 1 is January)
- va = various occaisions
- VE = Vespers

## The files:

- lectionary.csv provides the reading data associated with each AGES ID.
