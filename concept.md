# Konzept zur Präsentation

**Name:** Max Mustermann  
**Position:** Software Engineer  
**Unternehmen:** Musterfirma  
**Thema der Präsentation:** Clean Code – Einführungseinheit in das Erstellen von wartbarem Code  
**Ausbildungsberuf:** Fachinformatiker für Anwendungsentwicklung  
**Ausbildungsmethode:** Modifizierte Vier-Stufen-Methode  

## Lernziele

1. **Richtlernziel gemäß Ausbildungsordnung:**  
   Programmerstellung und -dokumentation (§ 10 Abs. 1 Nr. 6.2)

2. **Groblernziel gemäß Ausbildungsrahmenplan:**  
   Programme unter der Berücksichtigung der Wartbarkeit und Wiederverwendbarkeit erstellen (§ 10 Abs. 1 Nr. 6.2 e)

3. **Abgeleitetes Feinlernziel:**  
   Der Auszubildende soll innerhalb einer Stunde eigenständig ein kleines bestehendes Programm überarbeiten und dabei die Prinzipien „Kurze, fokussierte Funktionen“, „Aussagekräftige Namen“ und „Sinnvolle Kommentare“ fachgerecht anwenden.

## Auszubildender

Der Auszubildende befindet sich am Übergang vom ersten zum zweiten Ausbildungsjahr im Beruf Fachinformatiker für Anwendungsentwicklung. Er verfügt über Grundkenntnisse in der Programmierung und hat bereits erste eigene kleinere Projekte erfolgreich umgesetzt. Sein Code ist jedoch noch unsauber und wenig strukturiert.

## Lerntyp

Der Auszubildende bevorzugt eine visuelle und auditive Lernweise. Daher wird die modifizierte Vier-Stufen-Methode angewendet, um theoretische Grundlagen mit praktischer Umsetzung zu verknüpfen.

## Vorkenntnisse

Der Auszubildende kann grundlegenden Code schreiben, hat jedoch noch Schwierigkeiten mit Struktur, Lesbarkeit und Wartbarkeit. Erste Programmiererfahrungen sind vorhanden, jedoch fehlen Kenntnisse über Best Practices für sauberen Code.

## Dauer der Unterweisung

**30 Minuten** gemeinsames Erarbeiten + **60 Minuten** Lernzielkontrolle

## Unterweisungsort

Am Arbeitsplatz des Auszubildenden in einem Büro für 4–6 Personen mit Zugriff auf einen PC und eine geeignete Entwicklungsumgebung.

## Lernzielbereiche – Didaktische Analyse der Unterweisung

### Kognitive Lernziele

Der Auszubildende lernt, bestehenden Quellcode kritisch zu analysieren und Verbesserungspotenziale zu erkennen. Es wird vermittelt, warum eine saubere Code-Struktur wesentlich ist und welche negativen Folgen unübersichtlicher Code für Wartbarkeit, Zusammenarbeit und langfristige Softwarequalität haben kann. Zudem werden die grundlegenden Prinzipien des Clean Code – wie „kurze, fokussierte Funktionen“, „aussagekräftige Namen“ und „sinnvolle Kommentare“ – erläutert.

### Psychomotorische Lernziele

Obwohl das Programmieren überwiegend als kognitive Tätigkeit gilt, schult es auch feinmotorische Fähigkeiten – etwa den sicheren Umgang mit der Tastatur, den Einsatz von Tastenkombinationen und die schnelle Navigation in der Entwicklungsumgebung. Im Rahmen der praktischen Übung lernt der Auszubildende, den vorliegenden Code eigenständig zu überarbeiten. Dabei wird das Refactoring geübt – das gezielte Umstrukturieren von Funktionen und das präzise Einfügen von Kommentaren. Durch wiederholtes Anwenden dieser Techniken wird nicht nur das methodische Vorgehen zur Codeverbesserung gefestigt, sondern auch die Fähigkeit, effizient und präzise mit den Entwicklungswerkzeugen und Eingabegeräten zu arbeiten.

### Affektive Lernziele

Der Auszubildende erfährt, welche Auswirkungen unsauberer Code auf das gesamte Projekt und die Teamarbeit haben kann. Er wird für die Bedeutung von Qualität und Wartbarkeit im Softwareentwicklungsprozess sensibilisiert. Gleichzeitig wird ihm verdeutlicht, dass die Einhaltung von Clean Code-Prinzipien nicht nur die Fehleranfälligkeit reduziert, sondern auch die Zusammenarbeit und den langfristigen Erfolg von Softwareprojekten fördert.

## Unterweisungsmethode: Vier-Stufen-Methode

### Stufe 1: Vorbereiten (Zeit: 6 Minuten)

Zunächst wird der Arbeitsbereich vorbereitet, indem die Entwicklungsumgebung sowie das zu überarbeitende Codebeispiel eingerichtet werden. Anschließend begrüßt der Ausbilder den Auszubildenden und erkundigt sich kurz nach seinem Befinden, um eine angenehme Lernatmosphäre zu schaffen. Danach werden die Lernziele der Unterweisung vorgestellt. Durch gezielte Fragen wird das bereits vorhandene Wissen abgefragt, woraufhin der Ausbilder im Lehrgespräch nahtlos in das Thema „Clean Code – Sinn und Zweck“ überleitet. Der Auszubildende erhält eine kurzen, prägnanten Einführung, der ihm die Relevanz einer strukturierten Codegestaltung näherbringt und bietet die Gelegenheit, offene Fragen zu klären.

**Arbeitsmittel:**  
PC mit installierter Entwicklungsumgebung, vorbereitete Codebeispiele, Code-Editor

**Medieneinsatz:**  
Code-Beispiel

**Motivation:**  
Bereits zu Beginn wird dem Auszubildenden vermittelt, dass er sämtliche Schritte der Code-Optimierung später eigenständig umsetzen wird. Am Ende der Unterweisung soll er in der Lage sein, unsauberen Code selbstständig zu überarbeiten. Darüber hinaus wird betont, dass das Erlernen dieser Techniken einen direkten Mehrwert für seine tägliche Arbeit und berufliche Entwicklung darstellt. Die Fähigkeit, Code systematisch zu verbessern, stärkt sein Selbstvertrauen und ermöglicht ihm, effektiver an Teamprojekten mitzuwirken. Sauber strukturierter Code kommt nicht nur ihm persönlich zugute, sondern verbessert auch die Zusammenarbeit im gesamten Team, da er die Wartbarkeit und Weiterentwicklung gemeinsamer Softwarelösungen erleichtert.

### Stufe 2: Vormachen und Erklären (Zeit: 3 x 3 Minuten)

Um den Auszubildenden nicht zu überfordern, wird zu Beginn gezielt ein einzelnes Clean Code-Prinzip ausgewählt – beispielsweise die Verwendung aussagekräftiger Namen. Zunächst führt der Ausbilder ein kurzes Gespräch, um das vorhandene Wissen zu aktivieren. Anschließend demonstriert er anhand eines vorbereiteten Codebeispiels, wie dieses Prinzip systematisch umgesetzt wird:

- Der Ausbilder identifiziert problematische Namen oder unklare Bezeichnungen im Code.  
- Er erläutert, wie durch klare und präzise Benennung die Lesbarkeit und Wartbarkeit verbessert werden kann.  
- Ein Codeabschnitt wird schrittweise überarbeitet, indem unübersichtliche Namen durch aussagekräftige ersetzt werden.  
- Nach der Demonstration des ersten Prinzips erfolgt eine detaillierte Übersicht, bei der alle Änderungen hinsichtlich Verständlichkeit und Wartbarkeit überprüft werden.  
- Alle Schritte werden langsam vorgeführt und ausführlich erklärt, sodass der Auszubildende die zugrunde liegende Logik nachvollziehen kann.  
- Zwischenfragen sind jederzeit erwünscht, um Unklarheiten sofort zu klären.

### Stufe 3: Nachmachen und Erklären Lassen (Zeit: 3 x 5 Minuten)

Nachdem das erste Clean Code-Prinzip demonstriert wurde, übernimmt der Auszubildende ein weiteres Codefragment und wendet das Gelernte eigenständig an. Ziel ist es, dass er alle zuvor vorgestellten Schritte – von der Identifikation der Problembereiche bis zur abschließenden Dokumentation – konsequent umsetzt.

- Während der praktischen Übung achtet der Ausbilder darauf, dass das ausgewählte Prinzip korrekt angewendet wird, und steht unterstützend zur Seite, falls Schwierigkeiten oder Fragen auftreten.  
- Sobald der Auszubildende das erste Prinzip sicher beherrscht, wird das Vorgehen schrittweise mit dem nächsten Clean Code-Prinzip wiederholt.

So wird gewährleistet, dass der Auszubildende die drei Prinzipien nacheinander und in überschaubaren Schritten erlernt, ohne überfordert zu werden.

**Begründung:**  
Durch die anschauliche Demonstration werden alle Lernkanäle aktiviert:

- **Visuell:** Durch die direkte Code-Demonstration werden Verbesserungen sofort sichtbar.  
- **Auditiv:** Die ausführlichen Erklärungen des Ausbilders unterstützen das Verständnis der einzelnen Schritte.  
- **Kommunikativ:** Der Auszubildende kann während der Demonstration aktiv Fragen stellen und Unklarheiten klären.

So lernt er, die Prinzipien des Clean Code in der Praxis zu erkennen und später eigenständig anzuwenden.

### Stufe 4: Lernefolgskontrolle (Zeit: 1 Stunde)

Um das Gelernte zu festigen, wiederholt der Auszubildende eigenständig die einzelnen Schritte zur Code-Optimierung an einem kleinen Projekt von ihm. Dabei wurde bewusst ein Beispiel aus seinem eigenen Code gewählt, sodass er sich nicht erst in eine neue Codebasis einarbeiten muss und sich vollständig auf die Anwendung der Clean Code-Prinzipien konzentrieren kann. Er wendet dabei Techniken wie das Zerlegen in kurze, fokussierte Funktionen, die Verwendung aussagekräftiger Namen und den gezielten Einsatz von Kommentaren an. Durch das wiederholte Üben gewinnt er an Routine und Sicherheit im Umgang mit Clean Code.

Im Anschluss fasst der Auszubildende die vorgenommenen Änderungen und die zugrundeliegenden Prinzipien in einem mündlichen Feedbackgespräch zusammen. Dabei lenkt der Ausbilder das Gespräch mit gezielten W-Fragen, um das Verständnis des Auszubildenden zu überprüfen. Der Ausbilder lobt die gelungenen Ansätze, gibt konstruktives Feedback zu Verbesserungsmöglichkeiten. Dadurch verfügt der Auszubildende nun über eine dokumentierte Vorher-Nachher-Gegenüberstellung, die ihm jederzeit als Referenz dient.

Zum Abschluss wird der Auszubildende gebeten, die Ausbildungseinheit in den Ausbildungsnachweis sowie das Berichtsheft einzutragen. Der Ausbilder informiert zudem über das nächste Thema sowie den ungefähren Zeitpunkt der folgenden Unterweisung. Abschließend bedankt sich der Ausbilder für den engagierten Einsatz und verabschiedet den Auszubildenden.
