---
title: Datenschutzerklärung – Sara
lang: de
---

# Datenschutzerklärung – Sara

**Stand: 8. November 2026**

## 1. Verantwortlicher und Kontakt

Jan Sievers  
E-Mail: [shamyzen87@web.de](mailto:shamyzen87@web.de)

## 2. Was Sara macht

Sara ist eine KI-Sprachassistentin für einen privaten Discord-Freundeskreis. Der Betreiber kann Sara mit einem freigegebenen Discord-Sprachkanal verbinden und dort erzeugte Sprachantworten ausgeben lassen. Personen im Kanal können diese Antworten hören.

Eine frühere Desktop-Anbindung konnte Antworten der lokalen Sara-Desktop-Anwendung im verbundenen Sprachkanal ausgeben. Die neue, über den Discord-Knopf der Chat-App gesteuerte Bot-Laufzeit verwendet dagegen einen eigenen Discord-Gesprächskontext und greift nicht auf Desktop-Erinnerungen, Dateien oder PC-Steuerung zu. Beim Start wird die separate Desktop-Mikrofonerkennung beendet und während des Discord-Betriebs gesperrt.

Der Betreiber kann eine feste Nachricht zur Bestätigung der Serverregeln mit einem Knopf bereitstellen lassen. Beim Betätigen verarbeitet Sara die technische Interaktion und kann eine nur für die betätigende Person sichtbare Bestätigung senden.

Zusätzlich kann der Betreiber eine Text- und Bildfunktion aktivieren. In normalen, für @everyone sichtbaren Textkanälen von Sara-World bearbeitet sie ausschließlich neue Nachrichten mit einer echten direkten @Sara-Erwähnung. Zusätzlich beantwortet Sara private 1:1-Direktnachrichten an ihren Bot-Account auch ohne @Sara-Erwähnung. Gruppen-DMs, private Serverkanäle und Threads bleiben ausgeschlossen. Andere Servernachrichten werden nicht als Dialog ausgewertet; frühere Kanalnachrichten werden nicht automatisch abgerufen. Antworten werden immer nur im ursprünglichen Kontext gesendet: öffentlich im erwähnten Serverkanal oder privat im ursprünglichen 1:1-DM.

Private Gespräche sind strikt voneinander getrennt. Ein privater DM-Kontext kann ausschließlich innerhalb genau dieses 1:1-DMs und nur für dieselbe Person verwendet werden. Er bleibt flüchtig im Arbeitsspeicher, umfasst höchstens sechs Gesprächsrunden und wird weder in die lokale Discord-Erinnerungsdatenbank noch in den gemeinsamen Avatar-/öffentlichen Gesprächsfeed übernommen. Beim Beenden der Bot-Sitzung wird dieser Kontext gelöscht. Private Aussagen, Namen, Erlebnisse, Probleme oder Geheimnisse dürfen niemals in öffentliche Serverkanäle, andere DMs oder Gespräche mit anderen Personen übernommen, zitiert, bestätigt oder angedeutet werden. Wird Sara öffentlich nach einem privaten Gespräch gefragt, bestätigt sie weder ob noch was besprochen wurde, sondern verweist neutral auf den privaten Talk. Technische Nachrichtenmetadaten können über Discord dennoch anfallen.

Bei einer Text- oder Bildanfrage wird der Nachrichtentext und optional genau ein angehängtes PNG-, JPEG- oder WebP-Bild bis 5 MiB lokal verarbeitet. Das Bild wird aus Discords Anhangsdienst in den Arbeitsspeicher geladen, geprüft und für das lokale Bildmodell verkleinert. Beliebige externe Bildlinks werden nicht abgerufen. Eingebettete Metadaten werden nicht an das Modell weitergereicht. Öffentliche, direkt erwähnte Textanfragen und Saras Antworten werden in der separaten lokalen Discord-Datenbank gespeichert; die 30-Tage-Bereinigung erfolgt beim nächsten Datenbankzugriff. Frühere öffentliche Dialoge werden nur für denselben Server, Kanal und Sprecher sowie nur bei vorhandener Projektfreigabe als Verlauf geladen. Bilder werden nicht als Datei archiviert. Private 1:1-DMs verwenden ausschließlich den oben beschriebenen flüchtigen, getrennten DM-Kontext und werden nicht in dieser Datenbank gespeichert. Die Nachrichten selbst bleiben nach Discords Aufbewahrung und den dortigen Löschmöglichkeiten bestehen. Bitte nur Inhalte bereitstellen, zu deren Verarbeitung und Veröffentlichung Sie berechtigt sind.

Beim separaten Sprachbot kann der Betreiber Spracheingang ausdrücklich aktivieren und die Discord-Nutzerkennungen zustimmender Personen freigeben. Nur für diese freigegebenen Personen im eingestellten Sprachkanal werden Sprachabschnitte zur lokalen Transkription ausgewertet. Standardmäßig ist der Spracheingang aus. Sara kann auf direkte Ansprachen am Anfang oder Ende reagieren, etwa „Sara, was meinst du?“ oder „Was sagst du dazu, Sara?“. Eine bloße Erwähnung ihres Namens soll keine Antwort auslösen.

Davon getrennt besitzt die Desktop-Anwendung eine Mikrofon-Spracherkennung über das Windows-Standardmikrofon. Ein Mikrofon kann auch über Lautsprecher wiedergegebene Umgebungsgeräusche erfassen.

## 3. Daten und Zwecke

Für die Discord-Verbindung werden insbesondere Server- und Sprachkanalkennungen sowie die von Discord bereitgestellten Server-, Teilnehmer- und Sprachstatusinformationen verarbeitet. Dies dient dem Aufbau, Betrieb und der Fehlerbehandlung der Sprachverbindung. Ausgehende Sprachantworten werden als Audiodaten an Discord übertragen.

Die lokale Desktop-Anwendung verarbeitet eingegebene oder per Mikrofon erkannte Texte, daraus erzeugte Antworten und Gesprächskontext. Gesprächseinträge werden mit Zeitangaben lokal gespeichert, damit Sara frühere Gesprächsinhalte berücksichtigen kann. Erkannte Sprachtexte und bestätigte Textkorrekturen werden außerdem für die lokale Verbesserung der Spracherkennung gespeichert. Emoji-Reaktionen können mit einem Ausschnitt der zugehörigen Nachricht gespeichert werden. Ausdrücklich gewünschte Erinnerungen werden getrennt vom Gesprächsverlauf gehalten.

Die Desktop-Anwendung kann zusätzlich freiwillig ausgewählte Dateien lokal indexieren und personenbezogene Angaben etwa in Vorlieben, Wissenseinträgen oder Zielen enthalten. Diese Speicher sind von der automatischen Löschung des Gesprächsverlaufs zu unterscheiden. Technische Diagnoseprotokolle können Fehlermeldungen und lokale Dateipfade enthalten. Diese Datenschutzerklärung beschreibt den bestätigten lokalen Betrieb und die Discord-Ausgabe; zusätzliche Funktionen oder externe Dienste müssen vor einer entsprechenden Erweiterung neu geprüft werden.

Beim aktivierten separaten Discord-Spracheingang werden empfangene Sprachabschnitte freigegebener Teilnehmer lokal transkribiert. Roh-Audio wird nicht als Datei gespeichert. Ein kurzer Textpuffer aus höchstens zehn Abschnitten und ungefähr 60 Sekunden im Arbeitsspeicher hilft Sara, Bezüge wie „Was meinst du dazu?“ zu verstehen. Nicht direkt an Sara gerichtete Äußerungen werden nicht als dauerhafter Gesprächsverlauf gespeichert. Sie können während der kurzen Pufferzeit in eine Antwort einfließen; die Antwort kann Informationen daraus enthalten.

Direkt per Sprache an Sara gerichtete Discord-Anfragen und ihre Antworten werden mit Server-, Kanal-, Sprecherkennung und Zeitangabe als separater Discord-Verlauf lokal gespeichert. Frühere Sprachdialoge werden nur für denselben Server, Kanal und Sprecher als Kontext abgerufen. Technisch erforderliche Teilnehmer- und Verbindungsinformationen anderer Personen können durch Discord auch anfallen, wenn deren Sprache nicht zur Transkription abonniert wird.

Bei der optionalen Regelbestätigung werden Server-, Kanal-, Nachrichten- und Nutzerkennung sowie die Knopfbetätigung verarbeitet, um der bestätigenden Person die vorgesehene Mitgliedsrolle in Discord zuzuweisen. Diese Rolle bildet den Bestätigungsstatus in Discord ab. Ein zusätzliches lokales Register der bestätigenden Personen wird dafür nicht angelegt. Die Regelbestätigung gibt Saras Spracheingang nicht frei.

Für eine automatische Sprachfreigabe kann eine separate freiwillige Zustimmung mit einem Widerrufsknopf angeboten werden. Die Zustimmung weist ausschließlich der betätigenden Person eine eigene Discord-Rolle ohne Serverberechtigungen zu. Diese Rolle dient als Freigabestatus und wird vor dem Auswerten ihrer Sprache geprüft. Der Server kann auch ohne Sprachfreigabe genutzt werden. Der Widerruf entfernt die Rolle und eine etwaige manuelle Freigabe in der laufenden Sitzung. Sara wird dabei vorsorglich vollständig getrennt, damit auch eine laufende Verarbeitung beendet wird. Ein erneuter Start durch den Betreiber ist anschließend nötig. Bereits zuvor gespeicherte Dialoge werden dadurch nicht automatisch gelöscht; hierfür stehen Löschanfragen zur Verfügung.

## 4. Lokale Verarbeitung und Empfänger

Nach Bestätigung des Betreibers laufen Sprachmodell, Mikrofon-Spracherkennung und Sprachausgabe auf seinem PC. Der geprüfte Aufbau verwendet Ollama, faster-whisper und Pocket TTS. Im bestätigten Betriebsumfang werden dafür keine externen KI- oder Sprachdienste eingesetzt.

Die optionale Bildauswertung verwendet ebenfalls ein lokal installiertes Modell über Ollama. Bilder und direkt adressierte Texte werden nicht an externe KI-Anbieter gesendet. Der Download eines Discord-Bildanhangs und das Senden der Antwort erfolgen über Discord.

Der Bot-Token kann in Saras Chat-App mit dem Windows-Schutz des angemeldeten Benutzerkontos verschlüsselt lokal gespeichert und über die Einstellungen ersetzt werden. Es gibt keinen Klartext-Speicherersatz bei fehlender Verschlüsselung. Der Token wird nicht in den Gesprächsverlauf oder das öffentliche Datenschutz-Repository übernommen. Zur Anmeldung muss die Anwendung ihn im Arbeitsspeicher entschlüsseln und an Discord übermitteln.

Discord erhält die für seine Verbindung erforderlichen Daten und Saras ausgehende Audiodaten. Die Verarbeitung durch Discord richtet sich zusätzlich nach der [Datenschutzerklärung von Discord](https://discord.com/privacy). Die für Saras lokale Datenbank festgelegte Löschfrist bestimmt nicht die Aufbewahrung durch Discord.

Diese Seite wird über GitHub Pages bereitgestellt. Beim Abruf verarbeitet GitHub insbesondere technische Verbindungs- und Zugriffsdaten nach seiner [Datenschutzerklärung](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). Diese Website-Verarbeitung ist von Saras lokalem Sprachmodellbetrieb getrennt. Die Seite enthält keine eingebetteten Medien, Analyse-Skripte oder Formulare.

## 5. Rechtsgrundlagen

Soweit die DSGVO anwendbar ist, stützt sich die notwendige technische Verarbeitung für Saras Discord-Verbindung auf Art. 6 Abs. 1 Buchst. f DSGVO. Das berechtigte Interesse besteht darin, die angekündigte KI-Sprachausgabe im privaten Freundeskreis zu ermöglichen und die Verbindung sicher zu betreiben. Die Mitglieder werden vor der Nutzung informiert und können widersprechen. Der Betreiber kann Saras Verbindung bei einem Widerspruch beenden. Diese Grundlage umfasst keine beliebige Aufzeichnung oder Veröffentlichung von Gesprächsinhalten.

Die optionale lokale Transkription, der kurze Gesprächspuffer und die Speicherung direkt adressierter Discord-Dialoge werden nur nach vorheriger informierter, freiwilliger Einwilligung der betroffenen Person aktiviert (Art. 6 Abs. 1 Buchst. a DSGVO). Auch freiwillig gespeicherte personenbezogene Langzeiterinnerungen werden darauf gestützt. Eine Zustimmung wird weder aus dem bloßen Beitritt zu einem Sprachkanal noch aus der Bestätigung allgemeiner Serverregeln abgeleitet. Bei Widerruf beendet der Betreiber zunächst den Spracheingang und entfernt die Freigabe vor einem erneuten Start. Auch die Ausgabe personenbezogener Inhalte anderer Personen über Discord erfordert eine entsprechende Berechtigung.

Die Bearbeitung gesetzlicher Datenschutzanfragen erfolgt, soweit entsprechende Pflichten bestehen, nach Art. 6 Abs. 1 Buchst. c DSGVO. Die Bearbeitung sonstiger Kontaktanfragen und die technisch erforderliche Bereitstellung dieser Informationsseite dienen den berechtigten Interessen an Kommunikation und zugänglichen Datenschutzhinweisen nach Art. 6 Abs. 1 Buchst. f DSGVO. Die eigenständige Verarbeitung durch Discord, GitHub und beteiligte E-Mail-Anbieter richtet sich zusätzlich nach deren jeweiligen Informationen; sie kann auch eine Verarbeitung außerhalb des Europäischen Wirtschaftsraums umfassen.

Die technische Regelbestätigung und Rollenfreigabe dienen dem berechtigten Interesse an einem geregelten Zugang zum privaten Server und der Durchsetzung der veröffentlichten Regeln (Art. 6 Abs. 1 Buchst. f DSGVO). Verarbeitet werden dafür nur die notwendigen Interaktions- und Rollendaten. Daraus wird keine Einwilligung in andere Verarbeitungen abgeleitet.

Die freiwillige direkte Anfrage per @Sara mit Text oder Bild in einem öffentlichen Serverkanal sowie eine private 1:1-Direktnachricht an Saras Bot dienen der vom anfragenden Mitglied gewünschten Antwort. Soweit die DSGVO anwendbar ist, erfolgt diese begrenzte Verarbeitung auf Grundlage des berechtigten Interesses an der Beantwortung ausdrücklich an Sara gerichteter Anfragen (Art. 6 Abs. 1 Buchst. f DSGVO). Es wird kein allgemeiner Textkanalverlauf als Kontext erfasst. Private DM-Inhalte bleiben auf das jeweilige 1:1-DM beschränkt und werden nicht in andere Gespräche übernommen. Bei einem Widerspruch kann der Betreiber die Funktion beenden. Die freiwillige Sprachfreigabe bleibt hiervon getrennt und beruht auf der oben beschriebenen Einwilligung.

## 6. Speicherdauer und Löschung

Für Gesprächsverläufe einschließlich separat gespeicherter Discord-Dialoge, gespeicherte Desktop-Spracherkennungstexte und nachrichtenbezogenes Emoji-Feedback gilt eine Aufbewahrungsfrist von 30 Tagen ab Erstellung. Die lokale Bereinigungsaufgabe prüft diese Einträge stündlich und bei der Windows-Anmeldung und löscht fällige Einträge aus der aktiven Datenbank. Zusätzlich werden fällige Discord-Dialoge beim Dialogzugriff bereinigt. Aus gelöschten Desktop-Spracherkennungseinträgen abgeleitete Wortkorrekturen werden nicht beibehalten, sofern sie nicht auch durch verbleibende Einträge gestützt werden.

Der flüchtige Discord-Gesprächspuffer wird nach ungefähr 60 Sekunden bzw. beim Beenden des zugehörigen Prozesses verworfen. Roh-Audio wird nur vorübergehend für die Verarbeitung des begrenzten Sprachabschnitts im Arbeitsspeicher gehalten. Es wird kein Archiv der Kanal-Audiodaten angelegt.

Die Bereinigung läuft bei angemeldetem Betreiber und eingeschaltetem PC. Zwischen Ablauf der Frist und dem nächsten erfolgreichen Lauf kann technisch eine Verzögerung entstehen. Bei ausgeschaltetem PC, fehlender Anmeldung oder Fehlern erfolgt die Bereinigung erst beim nächsten erfolgreichen Lauf. Die Aufgabe erfasst keine außerhalb der aktiven Datenbank liegenden Kopien.

Personenbezogene Langzeiterinnerungen werden nur mit ausdrücklicher Zustimmung der betroffenen Person für den vereinbarten Zweck aufbewahrt. Sie unterliegen nicht der automatischen Bereinigung des Gesprächsverlaufs. Der Betreiber prüft monatlich, ob Zweck und Zustimmung weiterhin vorliegen, und löscht nicht mehr erforderliche Einträge. Bei Widerruf wird die weitere Speicherung gesondert geprüft und ohne tragfähige andere Grundlage beendet. Die monatliche Prüfung ist ein manueller Betreiberablauf, keine automatische Einwilligungserkennung.

Freiwillig ausgewählte Dateien, daraus erzeugte lokale Indizes, technische Protokolle und etwaige Sicherungen werden nicht pauschal nach der Gesprächsfrist gelöscht. Sie sind gesondert nach ihrem Zweck und im Rahmen betroffener Löschanfragen zu prüfen. Dem Betreiber sind derzeit keine weiteren Kopien der Gesprächsdatenbank bekannt. Löschungen müssen bei einer späteren Wiederherstellung berücksichtigt werden.

Löschanfragen können an [shamyzen87@web.de](mailto:shamyzen87@web.de) gerichtet werden. Bitte beschreiben Sie, auf welche Nutzung oder Inhalte sich die Anfrage bezieht. Senden Sie keine Passwörter oder Zugangstokens. Der Verantwortliche bearbeitet die Anfrage und prüft, welche personenbezogenen Daten zugeordnet und gelöscht werden können. Dazu werden erforderlichenfalls Gesprächseinträge, Sprachlerntexte, Emoji-Feedback, Erinnerungen, weitere personenbezogene Speicher und bekannte Kopien geprüft. Eine automatische eindeutige Zuordnung aller lokal gespeicherten Inhalte zu einer Discord-Nutzerkennung besteht nicht.

Bei Kontaktaufnahme werden Absenderadresse und die mitgeteilten Inhalte zur Bearbeitung der Anfrage verarbeitet; an der Übermittlung sind die verwendeten E-Mail-Anbieter beteiligt. Anfrageunterlagen werden nach Abschluss auf weitere Erforderlichkeit geprüft. Eine Löschung bei Sara ersetzt keine gesonderte Anfrage an Discord oder GitHub hinsichtlich deren eigener Verarbeitung.

Der Bestätigungsstatus der Serverregeln wird durch die Mitgliedsrolle in Discord abgebildet, solange diese Rolle besteht. Discord verarbeitet außerdem die technischen Interaktions- und gegebenenfalls Audit-Daten nach seinen eigenen Vorgaben. Es gibt hierfür keine zusätzliche lokale 30-Tage-Bestätigungsdatei. Bei Löschanfragen werden auch selbst kontrollierte Rollenzuweisungen und Interaktionsnachrichten geprüft.

Für die freiwillige Sprachfreigabe wird ebenfalls die entsprechende Rolle in Discord als Status verwendet. Lokal werden nur technische Nachrichten- und Rollenkennungen zur Wiederverwendung der Knöpfe gespeichert, kein zusätzliches Teilnehmerverzeichnis. Bei öffentlichen, direkt erwähnten Textanfragen werden Nachrichtentext und Saras Antwort in der lokalen Discord-Datenbank gespeichert und beim nächsten Datenbankzugriff nach Ablauf der 30-Tage-Frist bereinigt. Ein älterer Verlauf wird nur im gleichen Server-/Kanal-/Sprecher-Kontext und nur bei vorhandener Projektfreigabe geladen. Bilddateien werden nicht dauerhaft gespeichert. Private 1:1-DMs werden ausschließlich im flüchtigen RAM-Kontext des jeweiligen DM verarbeitet (höchstens sechs Gesprächsrunden); dieser Kontext wird nicht in die lokale Datenbank oder den gemeinsamen Avatar-Gesprächsfeed übernommen und beim Beenden der Bot-Sitzung gelöscht. Private Inhalte werden nicht mit anderen Personen oder öffentlichen Gesprächen geteilt. Saras Antworten bleiben als Discord-Nachrichten den Aufbewahrungs- und Löschmöglichkeiten von Discord unterworfen.

## 7. Rechte

Soweit die DSGVO anwendbar ist und die jeweiligen gesetzlichen Voraussetzungen erfüllt sind, bestehen insbesondere Rechte auf Auskunft, Berichtigung, Löschung, Einschränkung der Verarbeitung, Datenübertragbarkeit und Widerspruch. Eine erteilte Einwilligung kann für die Zukunft widerrufen werden. Betroffene können sich außerdem bei einer zuständigen Datenschutzaufsichtsbehörde beschweren.

Anfragen können an die oben genannte E-Mail-Adresse gerichtet werden. Soweit die DSGVO gilt, wird über ergriffene Maßnahmen ohne unnötige Verzögerung und grundsätzlich innerhalb eines Monats nach Eingang informiert. Eine gesetzlich zulässige Verlängerung wird innerhalb dieser Frist begründet mitgeteilt.
