# Lernzettel MDSD

## 1. Einführung in MDSD

### 1️⃣ Motivation

Warum modellieren wir überhaupt?

- menschliche Fähigkeit zur Abstraktion.

#### 1. Generalisierung
Aus mehreren Objekten entsteht ein gemeinsamer Begriff.
```
BMW
Audi
VW
↓
Auto
```

#### 2. Klassifizierung
Objekte werden Gruppen zugeordnet.
```
Hund
Katze
Pferd
↓
Tier
```

#### 3. Aggregation
Mehrere kleine Objekte bilden ein großes.
```
Motor
Reifen
Lenkrad
↓
Auto
```
---
#### Klausurklassiker 💡
**Warum modellieren wir?**  
Antwort:
- Komplexität reduzieren
- Realität abstrahieren
- Kommunikation verbessern
- AUtomatisierung ermöglichen
- Grundlage für Codegenerierung schaffen

### 2. Was ist überhaupt ein Modell?

#### 🚀 Sehr Klausurrelevante Definition:  
**Ein Modell ist eine vereinfachte und abstrahierte Darstellung eines Ausschnitts   der Realität, die für einen bestimmten Zweck erstellt wird.**  
Wörter zum Merken:
- Abstraktion ✅
- Vereinfachung ✅
- Teil der Realität ✅
- bestimmter Zweck ✅
---
Beispiel:

**Realität**
```
🚗 Mein Auto

Marke
Motor
Reifen
Gewicht
Farbe
Radio
Kilometerstand
Motorsteuerung
Bremslage
...
```

**Modell
```
Auto

- Marke
- Farbe
```

Alles andere interessiert uns vielleicht gerade gar nicht.  
Das Modell ist also nicht falsch.  
Es ist lediglich **vereinfacht**.
---
#### ⭐️ Die drei Merkmale eines Modells
##### 1. Verkürzungsmerkmal  
Ein Modell zeigt nicht alles.  
Nur die relevanten Eigenschaften.  
##### 2. Abbildungsmerkmal
Ein Modell ist immer ein Modell von etwas.  
Es bildet ein Original ab.
##### 3. Pragmatisches Merkmal 🚀
Ein Modell existiert immer
- für jemanden
- zu einem bestimmten Zeitpunkt
- für einen bestimmten Zweck

#### 🧠 Merkhilfe
**V-A-P**  
V → Verkürzt  
A → Abbildung  
P → Praktischer Zweck

### Was ist Modellgetriebene Softwareentwicklung?

Klaissche Softwareentwicklung:
```
Anforderung
↓
Java-Code
↓
Programm
```

Modellgetriebene Softwareentwicklung:
```
Anforderung
↓
Modell
↓
Transformation
↓
Code
↓
Programm
```
#### 👉 Das Modell wird zum zentralen Artefakt der Entwicklung.

Der Code wird ganz oder teilweise automatisch aus dem Modell erzeugt.

### Klausurklassiker 🚀
1. Was ist ein Modell?
2. Warum modelliert man?
3. Was bedeutet Abstraktion
4. Nenne die drei Modellmerkmale
5. Was ist der Unterschied zwischen klassischer und modellgetriebener Softwareentwicklung?

---

### 📌 Wichtigste Definitionen

| Begriff | Definition |
| :--- | :--- |
| Modell | Vereinfachte, abstrahierte Darstellung der Realität |
| Abstraktion | Weglassen unwichtiger Details |
| Modellierung | Erstellen eines Modells |
| MDSD | Entwicklung, bei der Modelle die zentrale Grundlage bilden und zur automatischen Codegenerierung genutzt werden |

### 🧠 Merksätze
- Ein Modell beschreibt **nie die komplette Realität**.
- Ein Modell besitzt **immer einen Zweck**.
- **Abstraktion** bedeutet: Wichtiges behalten, Unwichtiges weglassen
- Bei MDSD ist **das Modell wichtiger als der Code**.

---

## 1. Einführung in MDSD

### Das große Ganze
Die wichtigste Grafik des Kapitels verbindet alle Begriffe.   Wir lernen sie nicht auswendig, sondern verstehen sie logisch.
Der Ablauf sieht vereinfacht so aus:
```
Domäne
   │
   ▼
Metamodell
   │
   ▼
Modellierungssprache
   │
   ▼
Modell
```
**Jeder Begriff baut auf dem vorherigen auf.**
---
### 1. Begriff - **Domäne**
#### Definition
Eine **Domäne** ist ein **klar abgegrenztes Wissens- oder Interessensgebiet**.  Es gibt fachliche und technische Domänen; große Domänen können zudem in Subdomänen aufgeteilt werden.
#### Beispiele
**Fachliche Domäne**  
🏦 Bank  

Begriffe:
- Konto
- Kunde
- Kredit
- Überweisung
---
**Fachliche Domäne**  
🏥 Krankenhaus  

Begriffe:
- Arzt
- Patient
- Station
- Diagnose
---
**Technische Domäne**  
💻 Datenbank  

Begriffe:
- Tabelle
- Primärschlüssel
- Fremdschlüssel

---
#### Klausurfrage - Was ist eine Domäne? 🚀

##### Musterantwort:
**Eine Domäne ist ein klar abgegrenzter Wissens- oder Interessensgebiet, das durch Modelle beschrieben werden kann.**

### 2. Begriff - **Subdomäne**
Eine Domäne kann sehr groß sein.  
Beispiel:
```
Krankenhaus
```
Unterteilt in:
```
Patientenverwaltung
Abrechnung
Personal
Labor
```
Diese kleineren Bereiche nennt man **Subdomänen**.  
Warum macht man das?  
**Komplexität reduzieren**

### 3. Begriff - **Modellierungssprache**
Eine Modellierungssprache legt fest,
- welche Elemente verwendet werden dürfen
- wie sie geschrieben werden
- was sie bedeuten

Beispiele:
- UML
- XML
- Ecore
- BPMN

### 4. Begriff - **Syntax**
Syntax bedeutet, **wie etwas geschrieben wird.**  
Es geht nur um die Form, nicht um die Bedeutung.  
Beispiel:
```
int alter = 20;
```
Syntax korrekt
---
```
int = alter 20
```
Syntax falsch

### Begriff 5 - **Semantik**
Semantik beantwortet, was etwas bedeutet?  
Beispiel:
```
Auto
```
Syntax:   
Der Text lautet "Auto".  
  
Semantik:  
Der Text beschreibt ein Fahrzeug.

---
### Begriff 6 - **Metamodell** 🚀
#### **Definition**
**Ein Metamodell beschreibt die Struktur, Regeln und zulässigen Elemente  eines Modells.**  
  
Einfacher:  
Ein Metamodell beschreibt, wie Modelle aufgebaut sein dürfen.
---
##### Beispiel
**Modell**
```
Person

Name
Alter
```
Das ist ein Modell.
---
**Metamodel**
Das Metamodell sagt:  

Eine Klasse darf
- Attribute besitzen
- Referenzen besitzen
- von anderen Klassen erben
Es beschreibt also nicht die Person, sondern die Regeln zum Erstellen des Modells.

---
#### Vergleich
Stell dir LEGO vor.  

**Realität**  
Ein echtes Haus.  
🏠
---
**Modell**  
Ein LEGO-Haus.  
🧱
---
**Metamodell**  
Die LEGO-Bausteine und die Regeln, wie sie zusammengesteckt werden dürfen.  
🧩  
Das Metamodell beschreibt nicht das Haus, sondern wie Häuser aus Bausteinen aufgebaut werden können.
---
#### Der wichtigste Satz für Ecore
Ecore ist ein metamodell, weil es nicht die Realität beschreibt, sondern festlegt, aus welchem Elementen Modelle bestehen dürfen (z.B. EClass, EAttribute und EReference)
---
### M0 - M3 🚀
Die 4 Ebenen:
```
M3
Meta-Metamodell
        │
        ▼
M2
Metamodell
(Ecore)
        │
        ▼
M1
Modell
(Hochschulmodell)
        │
        ▼
M0
Reale Welt
(Student Max, Professor Müller ...)
```
---
#### M0
Die echte Welt.  
Beispiel:  
👨 Max Mustermann  
👩 Professor Müller  
📖 Software Engineering
---
#### M1
Jetzt modellierst du die Realität
```
Student

name

matrikelnummer
```
Das ist ein Modell
---
#### M2
Woher kommt eigentlich die Klasse Student? -> aus EClass  
Woher kommen die Attribute? -> aus EAttribute  
Das kommt alles aus Ecore.  
**M2 ist das Metamodell**
---
#### M3
MOF (Meta Object Facility)  
MOF beschreibt Ecore.  
Deshalb ist MOF das Meta-Metamodell.
---
#### Der wichtigste Merksatz:
```
M0 → Realität

M1 → Modell

M2 → Ecore

M3 → MOF
```
---
### Ecore 🚀
#### Klausurdefinition
**Ecore ist das Metamodell des Eclipse Modeling Frameworks (EMF). Es beschreibt, aus welchen Elementen Modelle bestehen dürfen und wie diese miteinander in Beziehung stehen.**
##### Merksatz
Ecore beschreibt, wie Modelle aufgebaut werden.
#### Die vier wichtigsten Elemente
**EClass**  
Klasse  

**EAttribute**  
Attribut  
  
**EReference**  
Beziehung zwischen Klassen  

**EDataType**  
Datentyp
