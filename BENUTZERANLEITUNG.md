# SortLab Benutzeranleitung für Anfänger

Diese Anleitung ist für Personen gedacht, die Sortieralgorithmen noch nicht kennen oder keine Informatik-Erfahrung haben.

## Was ist SortLab?

SortLab ist eine Website, die zeigt, wie ein Computer Zahlen sortiert.

Statt nur Code zu lesen, sieht man farbige Balken. Jeder Balken steht für eine Zahl. Wenn ein Algorithmus läuft, sieht man, wie die Balken verglichen und vertauscht werden.

## Was kann man damit lernen?

Mit SortLab kann man verstehen:

- wie Sortieralgorithmen grundsätzlich funktionieren
- warum manche Algorithmen schneller sind als andere
- was Vergleiche und Swaps bedeuten
- wie sich ein unsortiertes Array Schritt für Schritt verändert

## Starten

Wenn du das Projekt lokal starten willst:

```bash
git clone https://github.com/Aleksandros2/sortlab.git
cd sortlab
npm install
npm run dev
```

Danach zeigt das Terminal eine Adresse an, meistens:

```text
http://localhost:5173
```

Diese Adresse im Browser öffnen.

## Bedienung

### 1. Array erzeugen

Am Anfang wird ein zufälliges Array angezeigt. Dieses Array besteht aus Balken mit unterschiedlicher Höhe.

Wenn du ein neues Array möchtest, klicke auf den Button zum Mischen oder Neu-Erzeugen des Arrays.

### 2. Algorithmus auswählen

Wähle einen Sortieralgorithmus aus, zum Beispiel:

```text
Bubble Sort
Selection Sort
Insertion Sort
Quick Sort
Heap Sort
```

### 3. Sortierung starten

Klicke auf **Start** oder den entsprechenden Start-Button.

Jetzt beginnt SortLab, das Array Schritt für Schritt zu sortieren.

### 4. Geschwindigkeit ändern

Mit dem Geschwindigkeitsregler kannst du einstellen, ob die Animation langsam oder schnell laufen soll.

Langsam ist besser zum Lernen. Schnell ist besser, wenn du nur das Ergebnis sehen möchtest.

### 5. Werte beobachten

Während der Sortierung zeigt SortLab Statistiken an, zum Beispiel:

- Vergleiche
- Swaps
- Schritte
- Laufzeit

Diese Werte helfen dir zu verstehen, wie aufwendig ein Algorithmus ist.

## Was bedeuten die wichtigsten Begriffe?

### Array

Ein Array ist eine Liste von Werten. In SortLab wird diese Liste als Balken dargestellt.

### Sortieren

Sortieren bedeutet, die Werte in die richtige Reihenfolge zu bringen, zum Beispiel von klein nach groß.

### Vergleich

Ein Vergleich bedeutet: Der Algorithmus prüft zwei Werte und entscheidet, welcher größer oder kleiner ist.

### Swap

Ein Swap bedeutet: Zwei Werte tauschen ihren Platz.

### Laufzeit

Die Laufzeit zeigt, wie lange der Algorithmus gebraucht hat.

## Empfehlung zum Lernen

1. Starte mit **Bubble Sort**, weil dieser Algorithmus leicht zu verstehen ist.
2. Stelle die Geschwindigkeit langsam ein.
3. Beobachte, welche Balken verglichen und vertauscht werden.
4. Vergleiche danach Bubble Sort mit Quick Sort oder Heap Sort.

## Häufige Fragen

### Warum bewegen sich die Balken?

Die Balken bewegen sich, weil der Algorithmus Werte vergleicht und vertauscht.

### Warum sind manche Algorithmen schneller?

Manche Algorithmen brauchen weniger Vergleiche und Swaps. Deshalb sind sie bei größeren Arrays schneller.

### Muss ich programmieren können?

Nein. SortLab ist dafür gedacht, dass man Sortieralgorithmen visuell verstehen kann.

### Was ist das Ziel?

Am Ende sollen alle Balken sortiert sein, also von klein nach groß angeordnet.
