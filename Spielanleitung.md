# Testmethodik - Szenario basiertes Testen
### Einleitung

Beim Szenario basierten Testen werden produktspezifische Testfälle aus Sicht verschiedener Anwendungsfälle ermittelt. 
Dabei steht das Nutzerverhalten im Vordergrund und berücksichtigt folgende Fragestellungen:

    Wie verwendet der Nutzer das Feature bzw. die Anwendung primär?
    Welche anderen Möglichkeiten hat der Nutzer diese zu verwenden, um zum gleichen Ergebnis zu kommen?
    Welche seltenen Anwendungsfälle gibt es?
    Welche Anwendungsfälle sind nicht gültig?
    Wie kann der Nutzer durch eine beabsichtigte Fehlhandlung ein Fehlverhalten provozieren?

# Szenarien #
Aus den oben genannten Fragestellungen sind 5 verschiedene Szenarientypen abgeleitet, diese können unter [Definitionen](./Definitionen.md) nachgelesen werden.

# Anwendung
Die Ermittlung von Testfällen anhand von Szenarien ist eine schnelle und einfache Methode. Sie eignet sich besonders, wenn man mit "Nichttestern" zusammen Testfälle ermitteln möchte. Dies kommt häufig vor, wenn man mit Vertreten der Fachbereiche End-to-Endtests oder User Acceptance Tests plant.

Ebenso eignet sich die Methode, um Anforderungen wie z.B. User Storys auf Vollständigkeit der Abnahmekriterien zu prüfen.

In beiden Fällen kann es hilfreich sein, die Szenariokarten zu verwenden und die Interaktionen gegen diese 5 Szenarien zu prüfen und ggf. zu ergänzen.

Mit Hilfe der Szenarien kann ebenfalls eine Priorisierung der Testfälle erfolgen: Standard- und Alternativszenrien werden zuerst getestet, danach folgen Ausnahme- und Negativszenarien.


## Varianten
Es gibt verschiedene Varianten für das Spiel. Je nach Zielgruppe und Zweck kann dieses mit Einzelpersonen oder mehreren Gruppen parallel gespielt werden. Der Zeitaufwand ist mit maximal einer Stunde überschaubar.

Das Spiel eignet sich auch gut für Nichttester, um ihnen einen schnellen Einstieg in die verschiedenen Interaktionsmöglichkeiten aus Sicht eines Nutzers zu geben. 

### Kartenset
Kartenspiele mit je 8 Kartensätzen.

### Spiel mit einer Gruppe

Die Gruppengröße sollte max. 5 nicht übersteigen, da sonst nur ein oder zwei Gruppenmitglieder Entscheidungen treffen und die übrigen nur passiv teilnehmen. 
Nach einer kurzen Einführung in die verschiedenen Szenarien werden verschiedene Anwendungsfälle eines Kaffeevollautomaten gezeigt.

Jeder Teilnehmer erhält einen Satz Szenariokarten. Für jede Szene wählt er eine Karte aus, die er der Gruppe zeigt. Die Gruppe muss sich dann gemeinsam auf ein Szenario einigen. Es gibt dabei nicht immer ein richtig oder falsch. Ziel ist es, dass alle Gruppenmitglieder das gleiche Verständnis dafür bekommen, was mit den einzelnen Szenarien gemeint ist.

Um das Spiel zusätzlich zu verschärfen, können die einzelnen Szenarien zeitlich begrenzt angezeigt werden. Idealerweise nicht länger als 30 Sekunden, bis das nächste Szenario erscheint. Das setzt die Gruppe unter Druck, sich schnell zu einigen.

Am Ende des Spiels haben alle die Möglichkeit, ihre Eindrücke und möglichen Schwierigkeiten der Gruppe zu schildern.

In der Regel "beschweren" sich die Teilnehmer, dass die dargestellten Szenarien zum Teil nicht klar zu erkennen sind und daher nicht zugeordnet werden können. Meist gibt es auch unterschiedliche Auffassungen darüber, um welches Szenario es sich eigentlich handelt: ist es ein Standardfall oder eine Ausnahme? Ebenso wird angemerkt, dass die ursprünglichen Anforderungen an das System nicht bekannt sind: kann man Tee mit einem Kaffeevollautomaten kochen (Alternative oder Ausnahme) oder kann Soja- anstelle von Kuhmilch verwenden (Alternative oder bereits Missbrauch)? Ein Hinweis darauf, dass man die Perspektive eines Nutzers einnimmt, der keine Anforderungen kennt und keine Ahnung von der Funktionsweise hat (wer liest schon die Gebrauchsanweisung?), hilft meist beim nachträglichen Verständnis.

### Spiel mit mehreren Gruppen

Der Spielablauf ist identisch. Die Gruppen sollten die gleiche Größe haben. Wenn man mit mehreren agilen Teams spielt, sollte man die Teamstruktur beibehalten. 
Allerdings große Gruppen teilen. Wichtig ist, dass die einzelnen Szenarien zeitlimitert angezeigt werden, da sonst eine Gruppe lange diskutiert, während die anderen sich langweilen.

Interessant ist es die Gruppen zu beobachten. Manche Gruppen arbeiten als Team zusammen und kommen schnell zu einem gemeinsamen Ergebnis. Andere teilen sich auf: ein oder zwei diskutieren, die übrigen nehmen die Entscheidung ohne Widerspruch an.
Testfallermittlung mit Vertretern der Fachbereiche

Möchte man zusammen mit den Fachbereichen Testfälle für z.B. End-to-Endtests oder User Acceptance Tests ableiten, hilft es oft das Spiel als Einstieg zu verwenden. Danach kann man die Szenariokarten als Hilfestellung verwenden und alle Testfälle gegen diese prüfen. Bis auf das Missbrauchsszenario sollten alle Szenarien abgedeckt sein.


