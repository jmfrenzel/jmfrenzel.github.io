class: center, bottom

<style>
.logo img {
    width: 360px;
    margin-bottom: 400px;
}
</style>

.logo[
    ![RDMO](img/RDMO-logo.png)
]

# AG DMP in NRW 
## Anforderungen an RDMO aus Nutzersicht

##### Johannes Frenzel  ([AG FDM](http://www.rub.de/researchdata) - [Ruhr-Universität Bochum](http://www.rub.de))



---

Zusammenarbeit Datenmanagementpläne 
--------------------

#### Workshop mit 16 Einrichtungen und [fdm.nrw](https://www.fdm.nrw) der [DH.NRW](https://www.dh.nrw) im Mai '19 (Bochum)
  * fast ausschließlich RDMO als DMP Tool genutzt oder geplant
  * verschiedene Erfahrungsstände mit RDMO -- niederschwelliger Einstieg gewünscht, insbesondere Erstellung von Fragenkatalogen und RDMO Deployment
  * Austausch über RDMO-Infrastruktur?: [Slack](https://rdmo.slack.com), [Email-Liste](mailto:rdmo-team@listserv.dfn.de)  

--

#### AG DMP 
  * Momentane Mitarbeit von sechs Universitäten und Begleitung von [fdm.nrw](https://www.fdm.nrw)
  * Inhaltlich (DMP's) und technisch (RDMO)

???
AG DMP: Einrichtungen mit langjähriger Erfahrung bei Erstellung von DMP's sowie erfahrene RDMO Anwender/Nutzer

 RWTH Aachen, BTU Wuppertal, UA Ruhr: Ruhr-Uni Bochum / TU Dortmund / Uni Duisburg-Essen, Uni Bielefeld
---

Erfahrungen aus dem Einsatz von RDMO 
-------------------
#### Praxisbeispiele Anwender (Forschende und Manager) 
* Beantwortung der Fragen zusammen mit Forschenden, z.B. im Beratungsgespräch
   * Übertragung in RDMO aus persönl. Interviews (Embeded Datamanager)
   * kurze, ggf. mehrfache  Mailabfragen (2-5 Fragen)   
* Wichtig: kurze, fachlich, methoden-  oder [prozessbezogene](https://github.com/FDM-UARuhr/rdmo-catalog-uaruhr) Fragenkataloge/Hilfetexte

???
1-2 Jahre Erfahrung aus der Arbeit mit Forschenden und Infrastrukturpersonal (UBs, Rechenzentren)

DMPs sollten integriert in eine Beratung erstellt werden, Forschende brauchen i.R. initiale
Schulung zur Nutzung unterstützender Werkzeuge, wie RDMO.    

Wichtig sind kurze (max 20 Fragen), fachlich oder prozessbezogene Fragenkataloge/Hilfetexte
. Erste Umsetzungen gibt es bereits (Aachen, FoDaKo, UA Ruhr, Bielefeld).

individuelle Art (Fliesstext vs. Abstrakt vs. detailiertes Interview)

--
* Hochschulübergreifende RDMO-Instanzen: 
   * RWTH Aachen nutzt [Instanz der TU Darmstadt](https://rdmo.ulb.tu-darmstadt.de/)
   * [UA Ruhr Instanz](https://rdmo.uaruhr.de) für die drei Universitäten
* Die BTU Wuppertal betreibt alle drei RDMO-Instanzen für FoDaKo-Partner
???
Hochschulübergreifende RDMO-Instanzen: Die RWTH Aachen nutzt in Kollaboration die
Instanz der TU Darmstadt und die UA Ruhr stellt eine hochschulübergreifende Instanz für die
drei beteiligten Universitäten bereit.

Rechtliche-Administrative  Hürden, z.B. Kooperationsvertrag   

---
Wichtige Erweiterungen aus Anwendersicht
------
#### Nutzer/Manager 
* [#152 Templates for projects and data sets ](https://github.com/rdmorganiser/rdmo/issues/152)
* [#153 Extend interview and views by alternative display options for data sets ](https://github.com/rdmorganiser/rdmo/issues/153)
* [#154 Dynamic Interview](https://github.com/rdmorganiser/rdmo/issues/154)
* [#155 Filtering and faceting a project per user and role](https://github.com/rdmorganiser/rdmo/issues/155)
* [#156 Data upload to a project (supplementary data)](https://github.com/rdmorganiser/rdmo/issues/156)

#### Katalogverwaltung/Betrieb
* [#157 Add draft mode to catalog creation / editing workflow](https://github.com/rdmorganiser/rdmo/issues/157)
* [#158 Version catalogs and questions](https://github.com/rdmorganiser/rdmo/issues/158)
* [#159 rdmo-app test environment ](https://github.com/rdmorganiser/rdmo/issues/159)

???
Erfahrung aus der Arbeit mit Forschenden und Infrastrukturpersonal (UBs, Rechenzentren)

\#152 nachnutzung; Klonen und Templates (SFB's) 

\#153 zusätzlich 'per Datensatz' und Entkopplung von Fragen an Datensatz (Industriekooperation, Patente) 

\#154 Dynamic Interview: spez. Verbergen, Anzeigen von Fragen, Markiren von Fragen, Volltextsuche, Generierung der entsprechende Anzeige/Ausgabe (view)      


\#155 Tagging ([#84](https://github.com/rdmorganiser/rdmo/issues/84) ) Zuordung von Fragen an Nutzer, Nutzerspezifisches Subinterview im Projekt, Querauswertung von Antworten 

\#156 Projektmanagement: Abbildungen (Ablauf- und Zeitpläne, (Überblicks)tabellen)  

