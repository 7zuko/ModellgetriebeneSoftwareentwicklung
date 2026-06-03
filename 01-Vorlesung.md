---
title: Vorlesungs Notizen 1
module: Modellgetriebene Softwareentwicklung
date: 2026-06-03
vorlesung: Nr. 1 – Einführung
dozent: T. Eckwert
raum: E-019 D - PC-Raum
tags: [Vorlesung, MDSD, MDSE, MBD, MBE, MDE, MDA, MDD, Modelmerkmale]
version: 1.0
---

# 📚 Vorlesung: Einführung

> 🏫 **Modul:** Modellgetriebene Softwareentwicklung  
> 📅 **Datum:** 03.06.2026  
> 👨‍🏫 **Dozent:** T. Eckwert  
> 🚪 **Raum:**  E-019 D - PC-Raum
> ⏰ **Dauer:** 08:00 – 13:00 Uhr  
> 🎯 **Schwerpunkt:** Softwareentwicklung 

---

## 🎯 Lernziele

Nach dieser Vorlesung sollte ich...

- [ ] Modellierungs Merkmale kennen
- [ ] Akronyme kennen
- [ ] Deskriptive und Preskriptive Modelle erkennen/verstehen

---

## 🗂️ Agenda

1. 🖋️ Übungen besprechen
2. 🚀 Einführung
3. 📖 Modellierungsmerkmale
4. 💬 Akronyme

---

## 📝 Notizen (chronologisch)

| Uhrzeit | Notiz |
|----------|--------|
| 09:50 | Notiz |
| 10:15 | Wichtiger Begriff: ... |
| 10:45 | Entscheidung / Ergebnis |
| 11:30 | Beispiel / Diskussion |

---

## 📖 Wichtige Begriffe & Definitionen

### 🔹 Modell
> Objekt oder Gebilde, das die inneren Beziehungen und Funktionen eines Systems vereinfacht darstellt oder veranschaulicht.

### 🔹 Merkmale von Modellen
> Verkürzungsmerkmal: Modelle verfassen im allgemeinen nicht alle Attribute durch sie repräsentierten Originals, sondern nur solche, die den jeweiligen Modellerschaffern und/pder Modellbenutzern relevant erscheinen

> Abbildungsmerkmal: Modelle sind stets Modelle von etwas, nämlich Abbildungen, Repräsentationen natürlicher oder künstlicher Originale, die selbst wieder Modelle sein können

> Pragmatisches Merkmal: Modelle sind ihren Originalen nicht per se eindeutig zugeordnet. Sie erfüllen ihre Ersetzungsfunktion a) für bestimmte - erkennende und/pder handelnde, modellbenutzende Subjekte, b) innerhalb bestimmter Zeitintervalle und c) unter Einschränkung auf bestimmte gedankliche oder tatsächliche Operationen

> Drei entscheidenende Fragen für Pragmatische Merkmale:
    für wen?
    wann?
    wozu?

### 🔹 Modelling Levels
#### Modelle als Skizzen
> Verwendung zum Zwecke der Kommunikation
> Lediglich Teile des Systems sind modelliert
#### Modelle als Blaupausen
> Modelle bieten eine vollständige und detaillierte Sicht auf das System
#### Modelle als Programme
> Modelle treten an die Stelle von Programmcode zur Erstellung des Systems

### 🔹 Dekriptives vs. Preskriptives Modellieren
#### Deskriptive Modelle
> veranschaulichen bereits existierende Systeme
> abstrahieren Eigenschaften, die nicht von Interesse sind
> betonen Eigenschaften, die im Fokus des jeweiligen Kontexts stehen
> werden zur Diskussion, Kommunikation und Analyse eines Systems eingesetzt
#### Preskriptive Modelle
> können für die automatisierte Generierung eines Systems verwendet werden
> weisen einen hohen Grad an Präzision, Formalität, Vollständigkeit und Konsistenz auf
> bilden die Basis für modellgetriebene Softwareentwicklung

### 🔹 MDSE - Basiscs
> Unter Model Driven Software Engineering (MDSE) wird eine Menge von Instrumenten und Richtlinien subsumiert.
> MDSE zielt darauf, Softwareentwicklung von den möglichen Vorteilen des Modellierens profitieren zu lassen
#### Bestandteile:
> Konzepte: Modelle und Transformationen
> Notationen: Modellierungssprachen
> Prozesse und Regeln: Anleitungen, welche Modelle zu welchem Zeitpunkt zu erstellen sind.
> Tools: Werkzeuge, die - das Erstellen der Konzepte unter Verwendung geeigneter Notationen unterstützen / das Verhalten der Atefakte unterstützen / die Einhaltung der Prozessabläufe sowie der definierten Regeln unterstützen

### 🔹 MDSD - Definition
Modellgetriebene Softwareentwicklung ist ein Oberbegriff für Techniken, die aus formalen Modellen automatisiert lauffähige Software erzeugen.
> formale Modelle
> lauffähige Software
> automatisiert

### 🔹 Akronyme
#### MDD - Model-Driven Deployment
> Modelle sind die bestimmenden Artefakte
> Die Implementierung des Systems geschieht (semi-)automatisiert auf Basis der Modelle
#### MDA - Model-Driven Architecture
> MDSD-Variante definiert von der OMG
> Verwendet OMG-Standards (u.a. für Notation der Modelle und Transformationen)
#### MDE - Model-Driven Engineering
> Umfasst zusätzlicvhe modellgetriebene Aufgaben, die über die Implementierung des Systems hinausgehen
> Model-driven system evolution
> Model-driven reverse engineering

#### MBD - Model-Based Development
> Aufgeweichte Version vopn MDD
> Modelle sind wichtige Artefakte, werden aner eher als Skizzen oder Blaupausen denn als ausführbare Artefakte genutzt
#### MBE - Model-Based Engineering
> Aufgeweichte Version von MDE
> Modelle sind wichtige Artefakte, werden aber eher als Skizzen oder Blaupausen denn als ausführbare Artefakte genutzt
#### MDSE - Model-Driven Software Engineering
> Modelle werden zur (semi-)automatisierten Generierung von Software genutzt
> Subsummiert unter MDE

### 🔹 Formale Modelle
#### In Projekten werden zahlreiche Arten von Modellen eingesetzt
> Architekturskizzen an Tafeln, Whiteboards, Hand-outs
> UML-Diagramme zur Herausarbeitung eines bestimmten Design-Aspekts
> ER-Diagramme als konzeptioneller Entwurf der Datenbank
> Relationen-Modell zur logischen beschreibung der Datenbank
> Flussdiagramme zur groben Beschreibung von Prozessen
#### Nur eine Teilmenge der o.g. Modelle ist tatsächlich formal genug, um einsetzbar für MDSD zu sein
#### Formal:
> vollständige Beschreibung der wesentlichen Elemente eines Teilaspektes der Software (vollständig != alles)
> klare Regeln, über was ein Modell Aussagen treffen kann und muss
> klare Regeln, wie die Beschreibung erfolgt
> formale Modelle müssen nicht zwingend UML-Modelle sein!
---
## 📷 Bilder / Diagramme

#### Original-Modell-Abbildung nach Stachwoiak
<img width="1836" height="692" alt="image" src="https://github.com/user-attachments/assets/df70ebb0-c309-44a6-b2a2-cda8033b9b15" />

#### Akronyme Diagramm
<img width="1498" height="894" alt="image" src="https://github.com/user-attachments/assets/05e783d2-a48e-4988-9ff4-c073905688c3" />

#### MDSE - Übersicht
<img width="1516" height="824" alt="image" src="https://github.com/user-attachments/assets/20be55ea-d121-437c-a57f-b7f15e6b520f" />

#### MDSD - Übersicht
<img width="1500" height="830" alt="image" src="https://github.com/user-attachments/assets/82f4257a-39e0-44a9-b905-1f7ea9384bc2" />

---

## 💡 Kernaussagen / Takeaways

> Die wichtigsten Erkenntnisse der Vorlesung:

- ⭐ Aussage 1
- ⭐ Aussage 2
- ⭐ Aussage 3

---
## 📋 Aufgaben
**Erde → Globus**:

## Drei wesentliche Modellmerkmale

**1. Abbildungsmerkmal**
Ein Modell bildet ein Original ab.
Hier: Der **Globus** bildet die **Erde** ab. Er zeigt Kontinente, Länder, Ozeane, ungefähre Form und Lagebeziehungen.

**2. Verkürzungsmerkmal**
Ein Modell zeigt nie alles, sondern vereinfacht.
Der Globus zeigt nicht jede Stadt, jedes Haus, jeden Berg, jede Wolke oder die echte Größe. Er ist stark verkleinert und reduziert.

**3. Pragmatisches Merkmal**
Ein Modell hat immer einen Zweck.
Der Globus ist z. B. nützlich, um Geografie, Kontinente, Länder oder Entfernungen grob zu verstehen. Für Wetter, Erdbeben oder echte Navigation reicht er nicht aus.

---

## Begriffe am Beispiel

**Abbildungsvorbereich**
Das sind die Eigenschaften des Originals, die für die Modellbildung betrachtet werden.
Bei der Erde z. B.: Kugelform, Kontinente, Meere, Ländergrenzen, geografische Lage.

**Präterierte Attribute**
Das sind Eigenschaften des Originals, die im Modell weggelassen werden.
Beim Globus z. B.: echte Größe, Wetter, Menschen, Gebäude, reale Höhenunterschiede, Bewegung der Erde, Atmosphäre.

**Abundante Attribute**
Das sind Eigenschaften, die das Modell zusätzlich hat, obwohl sie das Original nicht hat.
Beim Globus z. B.: Ständer, Achse, Beschriftungen, Farben für Länder, eingezeichnete Grenzen, Maßstab.

**Abbildungsnachbereich**
Das sind die Eigenschaften, die im Modell tatsächlich dargestellt werden.
Beim Globus z. B.: Kontinente, Ozeane, Länder, grobe Form der Erde, geografische Beschriftungen.

Kurz gesagt:
Die **Erde** ist das Original, der **Globus** ist das Modell. Der Globus bildet nur bestimmte Eigenschaften ab, lässt vieles weg und fügt manche künstlichen Dinge hinzu, damit er für einen bestimmten Zweck brauchbar ist.

---

## 📐 Formeln & Regeln

### Formel 1
```text
Formel / Regel 1
