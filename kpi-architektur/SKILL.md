---
name: kpi-architektur
description: Leitet aus einer Nordstern-Metrik einen MECE-Treiberbaum bis zu konkreten KPIs mit Handlungsschwellen ab und prüft jede Kennzahl auf Manipulierbarkeit, bevor sie zur Steuerungsgröße wird.
---

# KPI-Architektur

## Wann einsetzen
Nutzen Sie dieses Vorgehen, wenn eine Organisation ein Kennzahlen-Dashboard hat, das aus zwanzig oder mehr Metriken besteht, ohne klare Hierarchie oder Verbindung zueinander, sodass niemand sagen kann, welche Kennzahl bei einem Zielkonflikt tatsächlich den Ausschlag geben soll. Es ist auch das richtige Werkzeug beim Aufbau eines neuen Geschäftsbereichs oder Produkts, bevor überhaupt Steuerungsmetriken existieren. Das Signal, jetzt zu handeln: Zwei Teams berichten in derselben Sitzung auf Basis unterschiedlicher Metriken jeweils Erfolg, während das Geschäftsergebnis insgesamt stagniert. Ohne eine saubere KPI-Architektur optimieren Teams lokale Metriken, die sich gegenseitig widersprechen oder sich leicht manipulieren lassen, ohne dass sich das eigentliche Geschäftsergebnis verbessert.

## Was es leistet
Dieser Skill definiert eine einzige Nordstern-Metrik, zerlegt sie in einen überschneidungsfreien Treiberbaum bis auf die Ebene handlungsfähiger KPIs, ordnet jede Metrik einer von drei Schichten zu (Ergebnis, Treiber, Gesundheitsindikator) und prüft jede Kennzahl darauf, ob sie sich durch Verhalten manipulieren lässt, das dem eigentlichen Ziel schadet. Das Ergebnis ist ein Kennzahlensystem, in dem jede Metrik einen benannten Verantwortlichen und eine klare Handlungsschwelle hat.

## Vorgehen
1. Definieren Sie die Nordstern-Metrik: die eine Kennzahl, die am direktesten den langfristigen Erfolg des Geschäfts oder Bereichs repräsentiert, formuliert so präzise, dass keine zwei Personen sie unterschiedlich berechnen würden.
2. Zerlegen Sie die Nordstern-Metrik in einen Treiberbaum: die zwei bis vier Haupttreiber, die sie arithmetisch oder kausal bestimmen, und darunter jeweils deren eigene Untertreiber, bis Sie bei tatsächlich beeinflussbaren Größen ankommen.
3. Prüfen Sie den Treiberbaum auf MECE-Struktur: Überschneiden sich zwei Treiber, wird ihr kombinierter Effekt doppelt gezählt; fehlt ein relevanter Treiber, bleibt ein blinder Fleck in der Steuerung.
4. Ordnen Sie jede Kennzahl im Baum einer von drei Schichten zu: Ergebnismetriken (das Was, meist verzögert und schwer direkt zu beeinflussen), Treibermetriken (das Wie, führend und direkt beeinflussbar) und Gesundheitsindikatoren (Leitplanken, die verhindern, dass eine Treibermetrik auf Kosten der Qualität optimiert wird).
5. Legen Sie für jede Treiber- und Gesundheitsmetrik eine konkrete Handlungsschwelle fest — den Wert, bei dessen Über- oder Unterschreiten eine definierte Reaktion ausgelöst wird — statt Kennzahlen nur zu berichten, ohne dass ein Schwellenwert eine Handlung erzwingt.
6. Prüfen Sie jede vorgeschlagene Kennzahl auf das Risiko der Proxy-Manipulation: Wie könnte ein Team diese Zahl verbessern, ohne dem eigentlichen Geschäftsziel zu nutzen oder sogar zu seinem Schaden? Ergänzen Sie für jede anfällige Treibermetrik eine Gegenmetrik, die diese Manipulation sichtbar machen würde.
7. Benennen Sie für jede Kennzahl im Baum eine einzelne verantwortliche Person oder Funktion, die für Bewegungen dieser Zahl rechenschaftspflichtig ist — eine Kennzahl ohne benannten Verantwortlichen wird in der Praxis von niemandem aktiv gesteuert.
8. Legen Sie für jede Schicht eine passende Überprüfungskadenz fest: Ergebnismetriken monatlich oder quartalsweise, Treibermetriken wöchentlich, Gesundheitsindikatoren kontinuierlich oder bei Schwellenüberschreitung.

## Inputs
- Die aktuelle Unternehmens- oder Bereichsstrategie und ihre übergeordneten Ziele
- Bestehende Kennzahlen-Dashboards und Berichtsstrukturen
- Historische Daten zu Kennzahlen, die in der Vergangenheit missbraucht oder manipuliert wurden, sofern bekannt
- Die Organisationsstruktur, um Kennzahlen realistisch Verantwortlichen zuordnen zu können

## Output-Format
Eine benannte Nordstern-Metrik, ein visualisierter MECE-Treiberbaum bis zur KPI-Ebene, eine Schichtzuordnung (Ergebnis/Treiber/Gesundheit) je Kennzahl, eine Handlungsschwellen-Tabelle, eine Proxy-Manipulations-Prüfung mit Gegenmetriken wo nötig, und eine Verantwortlichkeits- und Kadenztabelle je Kennzahl.

## Beispiel
Ein Abo-Software-Unternehmen definiert Nettoumsatzretention als Nordstern-Metrik und zerlegt sie in Expansions-, Abwanderungs- und Kontraktionstreiber. Als Treibermetrik für den Vertrieb wird "Anzahl geführter Upsell-Gespräche pro Woche" vorgeschlagen — die Proxy-Prüfung zeigt jedoch, dass Vertriebsmitarbeiter die Zahl der Gespräche künstlich hochtreiben könnten, ohne echte Abschlüsse zu erzielen. Als Gegenmetrik wird "Abschlussquote der geführten Upsell-Gespräche" als Gesundheitsindikator ergänzt, sodass ein Anstieg der Gesprächszahl bei gleichzeitig fallender Abschlussquote sofort sichtbar wird. Jede Kennzahl erhält einen benannten Verantwortlichen im Customer-Success-Team und eine Handlungsschwelle, ab der ein eskaliertes Coaching-Gespräch ausgelöst wird.

## Häufige Fallstricke
- Einen Treiberbaum bauen, der sich überschneidende Treiber enthält, was zu doppelt gezählter Wirkung und falschen Priorisierungsentscheidungen führt.
- Kennzahlen ohne Handlungsschwelle einführen, sodass sie berichtet, aber nie tatsächlich zur Steuerung genutzt werden.
- Treibermetriken einführen, ohne sie auf Manipulierbarkeit zu prüfen, sodass Teams die Zahl optimieren, ohne dem eigentlichen Geschäftsziel zu dienen.
