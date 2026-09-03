---
name: business-case-entwicklung
description: Baut ein treiberbasiertes Wirtschaftlichkeitsmodell für eine Entscheidung mit NPV/IRR, Sensitivitäten und vollständig offengelegten Bedingungen, unter denen der Case trägt.
---

# Business-Case-Entwicklung

## Wann einsetzen
Nutzen Sie dieses Vorgehen, wenn eine Entscheidung — eine Neuinvestition, ein Produktlaunch, eine Make-or-Buy-Frage, ein Kostenprogramm — vor Kapitalfreigabe wirtschaftlich begründet werden muss, insbesondere wenn der aktuelle "Case" nur aus einer einzigen Top-Line-Zahl ohne erkennbare Logik dahinter besteht. Es ist auch das richtige Werkzeug, wenn ein Case bereits existiert, sich aber fragil anfühlt: Niemand kann sagen, welche zwei oder drei Inputs eigentlich darüber entscheiden, ob die Zahl positiv oder negativ ist. Der Auslöser: Ein Sponsor fragt "wovon hängt das eigentlich ab?" und erhält nur ein Achselzucken. Ohne einen treiberbasierten Aufbau werden Business Cases entweder aus Optimismus durchgewunken oder aus Misstrauen abgelehnt — beides vermeidbar mit einem transparenten Modell.

## Was es leistet
Dieser Skill konstruiert ein vollständig treiberbasiertes Finanzmodell für eine Entscheidung — jede Umsatz-, Kosten-, Kapital- und Timing-Annahme wird als expliziter, editierbarer Input dargestellt statt in eine Black-Box-Summe eingebacken — und berechnet darauf die üblichen Investitionskennzahlen. Das Ergebnis erlaubt jedem Prüfer, die Endzahl bis zu den zwei oder drei tatsächlich ausschlaggebenden Annahmen zurückzuverfolgen, und benennt klar, was zutreffen müsste, damit die Investition ihre Hürde nimmt.

## Vorgehen
1. Definieren Sie die Entscheidung präzise: Was wird investiert, über welchen Zeithorizont, gegen welche Alternative (einschließlich der "Nichts-tun"-Basislinie, die oft übersprungen wird, aber das Ergebnis materiell verändert).
2. Bauen Sie den Treiberbaum: Zerlegen Sie Umsatz in Menge x Preis x Mix, Kosten in fix versus variabel und einmalig versus wiederkehrend, und Kapital in Anfangsinvestition und Instandhaltungsbedarf. Formulieren Sie jeden Treiber als benannten, belegten Input statt als fest codierte Zahl.
3. Legen Sie das Basisszenario mit dem am besten belegbaren Wert für jeden Treiber fest — greifen Sie, wo verfügbar, auf historische Ist-Werte oder vergleichbare Launches zurück, und markieren Sie jeden rein subjektiven Treiber.
4. Berechnen Sie NPV, IRR und Amortisationsdauer aus dem Treiberbaum und zeigen Sie den Aufbau Jahr für Jahr, damit ein Prüfer jede Zeile nachvollziehen kann, statt nur dem Endergebnis zu vertrauen.
5. Identifizieren Sie die zwei oder drei Treiber mit der größten Wirkung auf den NPV mittels Sensitivitäts-/Tornado-Analyse: Variieren Sie jeden Treiber einzeln in einer realistischen Bandbreite (z. B. ±30 %) bei sonst konstanten Werten und ranken Sie nach NPV-Ausschlag.
6. Führen Sie für die beiden unsichersten Treiber eine kombinierte Sensitivität durch (eine einfache Datentabelle oder ein Szenarioraster), um den Break-even-Schwellenwert zu finden — den konkreten Wert, unter dem der Case negativ wird. Formulieren Sie dies als harte Zahl ("der Case erfordert eine Take-up-Rate über 18 %"), nicht als vagen Vorbehalt.
7. Listen Sie die zentralen Risiken des Plans auf und ordnen Sie jedes einem konkreten Treiber im Modell zu; vermeiden Sie die verbreitete Schwäche, generische Risiken ("Umsetzungsrisiko", "Marktrisiko") losgelöst vom Modell aufzulisten — jedes Risiko sollte auf eine konkrete Zeile zurückführbar sein.
8. Formulieren Sie die Entscheidungslogik explizit: Empfehlung Umsetzen, Umsetzen unter Bedingungen, oder Zurückstellen, und benennen Sie exakt, welche Schwelle oder Evidenzlücke die Empfehlung schließen muss.

## Inputs
- Beschreibung der Investition/Initiative und ihr Zeithorizont
- Umsatztreiber: erwartetes Volumen, Preisgestaltung, Mix und Ramp-up-Annahmen
- Kostentreiber: Fixkosten, variable Stückkosten und einmalige Implementierungskosten
- Kapitalbedarf und der unternehmenseigene Diskontierungs-/Hurdle-Satz
- Vergleichbare historische Launches oder Benchmarks zur Verankerung der Basisannahmen

## Output-Format
Eine Zusammenfassung des treiberbasierten Modells (Annahmentabelle mit Quellenangaben), der jahresweise NPV-/IRR-/Amortisations-Aufbau, ein Tornado-Chart mit Ranking der Treiber nach Sensitivität, eine Break-even-Aussage für die beiden unsichersten Treiber, sowie eine Risikoliste mit Zuordnung zu konkreten Modellzeilen und einer abschließenden Umsetzen/Zurückstellen-Empfehlung.

## Beispiel
Ein deutscher Softwareanbieter, der ein nutzungsbasiertes Preismodell einführen will, baut ein Fünf-Jahres-Modell mit Volumen, durchschnittlichem Umsatz pro Kunde und Infrastrukturkosten als den drei Kerntreibern. Das Basisszenario zeigt einen NPV von 6,2 Mio. € bei 12 % Diskontsatz, doch die Tornado-Analyse zeigt, dass die Take-up-Rate der neuen Preisstufe (nicht die Infrastrukturkosten, wie das Team annahm) 70 % des NPV-Ausschlags treibt. Die Break-even-Analyse zeigt, dass der Case erst oberhalb einer Take-up-Rate von 18 % innerhalb von 18 Monaten die Hürde nimmt, gegenüber historisch 14 % bei einem vergleichbaren Launch — die Empfehlung lautet daher Umsetzen mit einem bedingten Gate bei einem Take-up-Rate-Checkpoint im neunten Monat, nicht bedingungslose Freigabe.

## Häufige Fallstricke
- Nur den finalen NPV/IRR präsentieren, ohne den Treiberaufbau — das macht den Case nicht prüfbar und lädt zu Misstrauen ein, unabhängig von seiner tatsächlichen Genauigkeit.
- Sensitivitäten für alle Inputs gleichermaßen durchführen statt die wenigen Treiber zu isolieren, die das Ergebnis tatsächlich bewegen — das verschleiert das eigentliche Risiko im Rauschen.
- Das Basisszenario als Erwartungswert behandeln statt die konkreten Schwellenbedingungen zu benennen, unter denen es trägt.
