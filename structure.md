# Structure

Wir verwenden zwei verschiedene Ordnerstrukturen für unser Story Rework. Transcription oder alle anderen :\) Alle anderen Ordner sind Walkthrough Abschnitte wie Beispielsweise die Stadt Tenebrea oder den Friedhof. Diese Abschnitte beschreiben dei Umgebung, welche NPC wo zu finden ist und den dementsprechenden Link zum Transcription. Im späteren Verlauf wird es einen Story Ordner geben, welche den roten Faden der Hauptstory beschreibt \(als eine Datei\) und für jede Nebenquest je Gebiet in eine seperate Datei.

### Transcription

Der Transcription Ordner listet jeden NPC auf mit jeder Zeile Dialog den diese\(r\) von sich gibt. Jede Dialogoption ist mit einer ID festgehalten \(1...99\). Wenn eine Dialogoption von einer anderen abhängt verwenden wir das Keyword **from** **X**, wobei X eine Zahl zwischen 1...99 ist. Muss eine bestimmte Quest, Gegenstand oder ein Event zuvor stattfinden, so wird dies mit **depends** **&lt;link&gt;** markiert. &lt;link&gt; stellt dabei die Seite in gitbooks dar.

Die Struktur der NPC sieht wie folgt aus:

Einleitung: Hier wird das Einführungsgespräch aufgezeichnet

Dialogoptionen: Auflistung der Dialogoptionen mit Ankerlink und Nummerierung zur dementsprechenden Position

Dialog X: Die Dialogoption X \(X ist eine Zahl zwischen 1....99\) mit Voraussetzung.

Eine Sektion wird "Issues - Plot holes - dialog cut" genannt und hier werden wir Fragen stellen für späteres Bearbeiten.

