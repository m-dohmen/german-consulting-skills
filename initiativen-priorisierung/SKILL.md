---
name: initiativen-priorisierung
description: Verdichtet eine lange Initiativenliste auf die tatsächlich umsetzbare Anzahl anhand von Wirkung, Machbarkeit und realer Kapazität, mit einer expliziten Kill-Liste für alles Übrige.
---

# Initiativen-Priorisierung

## Wann einsetzen
Nutzen Sie dieses Vorgehen, wenn eine Planungsrunde eine lange Liste von Initiativen hervorgebracht hat — häufig 20 bis 40 — und die aktuelle Priorisierung im Wesentlichen "alles ist wichtig" lautet, was in der Praxis bedeutet, dass Teams überlastet werden und nichts richtig fertiggestellt wird. Es ist auch das richtige Werkzeug an jedem Quartals- oder Jahresplanungs-Checkpoint, an dem eine bestehende Roadmap gegen tatsächliche Fortschritte und verfügbare Kapazität neu bewertet werden muss. Das Signal, jetzt zu handeln: Die Roadmap-Präsentation zeigt mehr "hohe Priorität"-Initiativen, als das Team im Planungszeitraum überhaupt abarbeiten kann. Ohne eine disziplinierte Verdichtung verteilt sich Kapazität dünn über zu viele Initiativen, sodass am Ende des Zeitraums vieles angefangen und wenig abgeschlossen ist.

## Was es leistet
Dieser Skill bewertet jede Initiative konsistent nach Wirkung und Machbarkeit, modelliert die tatsächlich verfügbare Kapazität (nicht die nominelle), sequenziert nach Abhängigkeiten und Cashflow-Bedarf, und produziert eine explizite Kill-Liste für alles, was nicht in den realen Kapazitätsrahmen passt. Das Ergebnis ist eine kurze, ausführbare Liste statt einer langen Wunschliste.

## Vorgehen
1. Normalisieren Sie die Rohliste auf ein einheitliches Format: jede Initiative mit demselben Detailgrad zu erwarteter Wirkung, benötigten Ressourcen und Zeitrahmen, damit Äpfel nicht mit Birnen verglichen werden.
2. Plotten Sie alle Initiativen in einer Wirkung-versus-Machbarkeit-2x2-Matrix als ersten groben Filter, um offensichtlich niedrigwertige oder unrealistische Initiativen früh auszusortieren.
3. Bauen Sie für die verbleibenden Kandidaten ein gewichtetes Scoring-Modell mit expliziten, im Voraus vereinbarten Kriterien und Gewichtungen (zum Beispiel: strategische Passung, erwarteter finanzieller Effekt, Umsetzungsrisiko, Zeit bis zur Wirkung) statt reiner Bauchgefühl-Reihung.
4. Modellieren Sie die tatsächlich verfügbare Kapazität realistisch: Ziehen Sie laufende Betriebslast, geplante Abwesenheiten und historische Schätzungenauigkeit ab, statt mit theoretischer Vollauslastung zu planen — die meisten Priorisierungen scheitern, weil sie mit optimistischer statt tatsächlicher Kapazität rechnen.
5. Sequenzieren Sie die verbleibenden Initiativen unter Berücksichtigung von Abhängigkeiten (was muss vor was fertig sein) und Cashflow-Bedarf (was braucht wann welches Budget), nicht nur nach reinem Score-Ranking.
6. Testen Sie die sequenzierte Liste gegen die Kapazitätsobergrenze: Addieren Sie den tatsächlichen Ressourcenbedarf der Initiativen von oben nach unten, bis die verfügbare Kapazität erschöpft ist — das markiert die harte Schnittlinie.
7. Formulieren Sie für alles unterhalb der Schnittlinie eine explizite Kill-Liste mit Begründung je Initiative, statt sie stillschweigend im Backlog verschwinden zu lassen — das schafft Klarheit gegenüber den Initiativen-Sponsoren und verhindert, dass dieselben Initiativen in der nächsten Runde ungeprüft wieder auftauchen.
8. Legen Sie einen festen Wiedervorlage-Zeitpunkt fest, an dem die Kill-Liste erneut mit aktueller Evidenz bewertet wird, statt sie endgültig zu verwerfen — Prioritäten und verfügbare Kapazität ändern sich, und eine gute Idee zum falschen Zeitpunkt bleibt eine gute Idee.

## Inputs
- Die vollständige Rohliste der vorgeschlagenen Initiativen mit grober Wirkungs- und Aufwandsschätzung
- Die tatsächlich verfügbare Team- und Budgetkapazität für den Planungszeitraum
- Bekannte Abhängigkeiten zwischen Initiativen
- Historische Daten zu Schätzgenauigkeit vergangener Planungsrunden, sofern verfügbar

## Output-Format
Eine Wirkung-versus-Machbarkeit-2x2-Matrix als erster Filter, eine gewichtete Scoring-Tabelle mit Kriterien und Gewichtungen, eine kapazitätsgeprüfte, sequenzierte Ausführungsliste mit Abhängigkeitshinweisen, und eine explizite Kill-Liste mit Begründung je gestrichener Initiative sowie dem vereinbarten Wiedervorlage-Termin.

## Beispiel
Ein Planungsteam mit 34 vorgeschlagenen Initiativen für das kommende Quartal reduziert die Liste über das gewichtete Scoring-Modell auf 14 ernsthafte Kandidaten. Die realistische Kapazitätsmodellierung — nach Abzug von 20 % Betriebslast und einer geplanten Systemmigration — zeigt, dass tatsächlich nur Kapazität für 6 Initiativen im Quartal besteht. Nach Sequenzierung nach Abhängigkeiten (zwei Initiativen setzen den Abschluss der Systemmigration voraus) landen 6 Initiativen über der Schnittlinie und 8 werden explizit auf die Kill-Liste gesetzt, mit Begründung wie "Initiative X: hoher Score, aber abhängig von einer Dateninfrastruktur, die erst in zwei Quartalen bereitsteht — Wiedervorlage Q3."

## Häufige Fallstricke
- Initiativen nach optimistischer Nominalkapazität statt tatsächlich verfügbarer Kapazität priorisieren, was systematisch zu viele Initiativen freigibt.
- Gewichtungen im Scoring-Modell im Nachhinein anpassen, bis die bevorzugte Initiative oben landet, statt die Gewichte vor der Bewertung festzulegen.
- Initiativen unterhalb der Schnittlinie stillschweigend im Backlog verschwinden lassen, statt eine explizite, begründete Kill-Liste zu kommunizieren.
