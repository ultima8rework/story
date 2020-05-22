# Structure

### Transcription

Der Transcription Ordner listet jeden NPC auf mit jeder Zeile Dialog den diese\(r\) von sich gibt. Jede Dialogoption ist mit einer ID festgehalten \(1...99\). Wenn eine Dialogoption von einer anderen abhängt verwenden wir das Keyword **from** **X**, wobei X eine Zahl zwischen 1...99 ist. Muss eine bestimmte Quest, Gegenstand oder ein Event zuvor stattfinden, so wird dies mit **depends** **&lt;link&gt;** markiert. &lt;link&gt; stellt dabei die Seite in gitbooks dar.

Die Struktur der NPC sieht wie folgt aus:

Einleitung: Hier wird das Einführungsgespräch aufgezeichnet

Dialogoptionen: Auflistung der Dialogoptionen mit Ankerlink und Nummerierung zur dementsprechenden Position

Dialog X: Die Dialogoption X \(X ist eine Zahl zwischen 1....99\) mit Voraussetzung.

