cass: left, top
background-image: url(img/RUBtitleimage-4x3.jpg)
.attribution[
    Image credit: <a href="http://www.ruhr-uni-bochum.de/bilder">Ruhr-Universität Bochum</a>
]

<div class="container">
.logo[
    ![RUB](img/Label_RUB_WEISS-BLAU_4c.png)
]


## Datenstrukturierung und -beschreibung im Forschungsprozess: Usecase SFB 

### Johannes Frenzel

[AG Forschungsdatenmanagement](https://www.ruhr-uni-bochum.de/researchdata) 

[Ruhr-Universität Bochum](https://www.ruhr-uni-bochum.de)

</div>

??? 

---
[Forschungsdatenmanagement an der RUB](https://www.rub.de/researchdata)
--------------------

#### [Arbeitsgemeinschaft "AG FDM"](https://www.rub.de/researchdata)
* [IT.SERVICES](http://www.it-services.ruhr-uni-bochum.de/)   
* [Universitätsbibliothek](http://www.ub.ruhr-uni-bochum.de/)  


--
#### Rektoratsprojekt  
 **Ziel**:  
 Etablierung eines zentral koordiniertem und nachhaltigem FDM 


--
* Sechs UseCases 
* Kooperation und Austausch: 
   UA Ruhr, NRW, ...  
 
???

---
UseCase SFB  
--------------------------------

**Anfrage zur Unterstützung**  
* Erstellung Richtlinien für die Datenablage (zentraler Fileservice)

--

**Rahmen und Anforderungen**
* Datenerzeugung in Teilprojekten (Experimente, Simulation) 
* (Format)Standardisierung in zwei Fokusgruppen 
* Rollen- und Rechtemanagement
* Teilen der Daten innerhalb SFB
* Einfache Benutzung durch Forschende 
* Datenablage durchsuchbar (projektrelevanten Metadaten)    
* kontrolliertes Vokabular
???
---
Metadaten- und Datenablageschema 
--------------------------------
* Schnell im Einsatz und integriert in vorhande Workflows und Tools. 
* Daten und Metadaten in hirachischer Ordnerstruktur
  * logische Abbildung des exp. Setup, z.B. Datensatz Messtation   
  * gewohnte Arbeitsumgebung
  * lesbar durch Forschende (ohne Werkzeug)   
???
---
Metadaten- und Datenablageschema 
--------------------------------

* Verzeichnisstruktur (unendlich) verschachtelt
* Metadatendefinition für Verzeichnisse und Dateien möglich


```bash
Example of directory structure


experimentXYZ
├── experimentXYZ.meta.json
├── group1
│   ├── group1.meta.json
│   ├── subject01
│   │   ├── subject01.meta.json
│   │   ├── dataA.abc
│   │   ├── dataA.meta.json
│   │   ├── dataB.bcd
│   │   ├── dataB.meta.json
│   ├── subject02
│   │   ├── subject02.meta.json
│   │   ├── dataA.abc
│   │   ├── dataA.meta.json
│   │   ├── dataB.bcd
│   │   ├── dataB.meta.json
│   ├── subject03
│   │   ├── subject03.meta.json
│   │   ├── dataA.abc
│   │   ├── dataA.meta.json
│   │   ├── dataB.bcd
│   │   ├── dataB.meta.json
├── group2
│   ├── subject04
│   │   ├── subject04.meta.json
│   │   ├── dataA.abc
│   │   ├── dataA.meta.json
│   ├── subject05
│   │   ├── subject05.meta.json
│   │   ├── dataA.abc
│   │   ├── dataA.meta.json
```

???
* Daten in `$name` und Metadaten in Dateien mit dem Namen
   * `name` der Datei oder des Verzeichnisses
   * zugeordnete Metadaten in Datei  `$name.meta.$extension`  
     $extension Typ der Metadatendatei (json, ymal, txt ...)
   * hierarchisches Auslesen der Metadaten (Ordner top-down)
---
Herausforderungen 
--------------------------------

* Nutzung der zentralen Datenablage im Forschungsalltag
  * Offensichtlicher Mehrwert für den Forschenden    
  * Forcierung: koppeln an Einreichung von Manuskripten  
* Datenmanagement Mitarbeitern ohne Publikationsdruck zugeordnen   
* Nachhaltige Entwicklung von Software 
* Planung und Umsetzung von Unterstützungsinfrastruktur vor Projektstart  
* Erarbeitung Metadatenschema
  * Fach- und forschungsspezifische Metadatenformate
  * Administrative und technische Metadaten automatisiert erfassen 
  
