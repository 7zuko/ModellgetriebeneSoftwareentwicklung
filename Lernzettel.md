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






