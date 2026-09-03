---
name: annahmen-audit
description: Legt die unausgesprochenen Annahmen offen, auf denen eine Strategie beruht, bewertet die Evidenzlage dahinter und prüft gezielt jene Annahmen, die den Plan zum Scheitern bringen würden, sollten sie falsch sein.
---

# Annahmen-Audit

## Wann einsetzen
Setzen Sie dieses Vorgehen ein, bevor eine Strategie, ein Business Case oder eine Investitionsentscheidung final verabschiedet wird — insbesondere dann, wenn ein Plan die Freigabe passiert hat, weil alle der Schlussfolgerung zustimmen, ohne dass jemand ausgesprochen hat, was dafür wahr sein muss. Es ist ebenso der richtige Zeitpunkt, wenn ein Vorhaben bereits läuft, die Ergebnisse aber hinter den Erwartungen zurückbleiben und niemand zurückgegangen ist, um zu prüfen, welche der ursprünglichen Annahmen sich stillschweigend als falsch erwiesen haben. Das Signal, jetzt zu handeln: Jemand sagt "das wird doch offensichtlich passieren" und niemand kann die Evidenz dafür benennen. Ohne diese Disziplin scheitern Strategien lautlos — nicht weil die Logik falsch war, sondern weil eine tragende, nie geprüfte Annahme sich als falsch herausstellt, meist erst nachdem das Budget bereits ausgegeben ist.

## Was es leistet
Dieser Skill extrahiert jede Annahme, von der ein Plan implizit abhängt, trennt die bequemen von den tatsächlich tragenden Annahmen und richtet die Prüfung ausschließlich auf Letztere. Das Ergebnis ist ein belastbares Bild davon, wo eine Strategie tatsächlich fragil ist, welche Evidenz diese Fragilität auflösen würde und wie die Geschichte endet, wenn die fragilen Annahmen brechen.

## Vorgehen
1. Rekonstruieren Sie die Logik des Plans als explizite Kette: "Wir erreichen [Ergebnis], weil [Annahme 1] und [Annahme 2] und [Annahme 3] zutreffen." Tun Sie dies, bevor Sie einzelne Annahmen prüfen — die Annahmen eines Plans sind meist implizit, und erst das laute Aussprechen der Kette macht sie sichtbar.
2. Erstellen Sie aus dieser Kette ein vollständiges Annahmenregister: jede Überzeugung zu Marktverhalten, Kundenreaktion, interner Fähigkeit, Wettbewerberverhalten, Kosten, Timing und regulatorischem Umfeld, die der Plan voraussetzt.
3. Klassifizieren Sie jede Annahme als Fakt (heute unabhängig verifizierbar), Inferenz (aus verwandten Daten abgeleitet) oder reine Überzeugung (keine unterstützenden Daten vorhanden).
4. Ordnen Sie jede Annahme in eine 2x2-Matrix aus Wichtigkeit (wie stark hängt das Ergebnis davon ab) und Konfidenz (wie gut ist sie belegt) ein. Das obere linke Quadrant — hohe Wichtigkeit, niedrige Konfidenz — ist der Ort echter Fragilität; priorisieren Sie alles andere zurück, unabhängig davon, wie unsicher es sich subjektiv anfühlt.
5. Bewerten Sie die Evidenz hinter jeder fragilen Annahme auf einer A-F-Skala: A/B ist durch direkte Daten oder Experimente validiert, C ist analoge Evidenz aus einer vergleichbaren Situation, D ist reines Expertenurteil, F ist ungeprüftes Wunschdenken. Vermeiden Sie die verbreitete Falle, überzeugten Tonfall mit Evidenz zu verwechseln — eine mit Nachdruck vertretene D-Annahme bleibt eine D-Annahme.
6. Entwerfen Sie für jede fragile, schwach belegte Annahme einen konkreten "Kill-Shot"-Test: das günstigste, schnellste Experiment, den Datenabruf oder die Expertenprüfung, die die Annahme widerlegen könnte. Legen Sie vor dem Test fest, welches Ergebnis sie widerlegen und welches sie bestätigen würde, um Bestätigungsfehler bei der Interpretation zu vermeiden.
7. Schreiben Sie ein kurzes Prä-Mortem: Nehmen Sie an, die Strategie sei in zwölf Monaten gescheitert, und erzählen Sie rückwärts, welche fragile Annahme gebrochen ist und wie sich das Scheitern fortgesetzt hat.
8. Sequenzieren Sie die Kill-Shot-Tests nach Kosten und Durchlaufzeit, und markieren Sie jede fragile Annahme, die sich vor der Entscheidung nicht günstig testen lässt — das ist ein Risiko, das explizit ins Gremium getragen werden muss, nicht verschwiegen werden darf.

## Inputs
- Die Strategie, der Business Case oder die Empfehlung im aktuellen Stand
- Vorhandene Marktforschung, Pilotdaten oder analoge Fallevidenz
- Benannte Verantwortliche des Plans, die zur Logik hinter zentralen Aussagen befragt werden können
- Der Entscheidungszeitplan (wie viel Zeit bleibt für Validierungstests vor der Festlegung)

## Output-Format
Ein Annahmenregister (Überzeugung, Kategorie, Wichtigkeit, Konfidenz, Evidenzgrad), sortiert nach Fragilität; eine geplottete Wichtigkeit-Konfidenz-2x2-Matrix mit namentlich benanntem fragilem Quadranten; ein Prä-Mortem-Absatz, der den wahrscheinlichsten Scheiterpfad erzählt; und ein priorisierter Testplan mit jedem Kill-Shot-Test, dessen Kosten/Zeit und der Go/No-Go-Schwelle zur Interpretation des Ergebnisses.

## Beispiel
Der Expansionsplan eines deutschen Einzelhändlers in einen neuen europäischen Markt beruht auf der Annahme, das bestehende Loyalitätsprogramm lasse sich unverändert auf neue Kunden übertragen, ohne dass lokale Wettbewerber reagieren. Das Audit zeigt: "Loyalitätsprogramm überträgt sich 1:1" wird mit D bewertet (reine interne Überzeugung, kein vergleichbarer Markt getestet) und liegt im Quadranten hohe Wichtigkeit/niedrige Konfidenz, während "Lagerkapazität reicht aus" mit A bewertet und sicher zurückgestuft wird. Der vorgeschlagene Kill-Shot-Test: das Loyalitätsangebot 60 Tage lang in einem vergleichbaren Nachbarmarkt testen, bevor der volle Rollout erfolgt. Das Prä-Mortem zeigt: Sollten lokale Wettbewerber den Rabatt innerhalb von 90 Tagen matchen, bricht der gesamte Margen-Case zusammen — genau das Szenario, das der Test aufdecken soll, bevor das Kapital gebunden ist.

## Häufige Fallstricke
- Alle Annahmen gleich intensiv prüfen, statt auf die wenigen zu triagieren, die zugleich wichtig und unbewiesen sind — das erzeugt ein langes, ungelesenes Dokument statt eines Entscheidungsinstruments.
- Überzeugungskraft oder Seniorität der vortragenden Person mit Evidenzqualität verwechseln; die Bewertung muss evidenzbasiert erfolgen, nicht autoritätsbasiert.
- Den Kill-Shot-Test durchführen, ohne vorab festzulegen, welches Ergebnis die Entscheidung ändern würde — das lässt Teams unbequeme Ergebnisse im Nachhinein wegrationalisieren.
