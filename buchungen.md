---
title: Buchführung
header-includes:
  - \usepackage{enumitem}
  - \setlistdepth{20}
  - \renewlist{itemize}{itemize}{20}
  - \renewlist{enumerate}{enumerate}{20}
  - \setlist[itemize]{label=$\cdot$}
  - \setlist[itemize,1]{label=\textbullet}
  - \setlist[itemize,2]{label=--}
  - \setlist[itemize,3]{label=*}
output:
  rmarkdown::pdf_document:
      keep_tex: yes
---


Firmengröße bzw. Größenklasse der GmbH
--------------------------------------

Für eine Einteilung der Firmengröße bzw. Größenklasse der GmbH dürfen
mindestens zwei der drei nachstehenden Merkmale nicht überschritten werden:

| **Größenklasse**      | Kleinst | Klein    | Mittel  | Groß   |
| :-----                | -----:  | :-----:  | :-----: | -----: |
| Bilanzsumme in Mio. € | ≤ 0,35  | 0,35 - 6 | 6 - 20  | > 20   |
| Umsatz in Mio. €      | ≤ 0,7   | 0,7 - 12 | 12 - 40 | > 40   |
| Mitarbeiter           | ≤ 10    | ≤ 50     | ≤ 250   | > 250  |

Dies wird in [§ 267 Abs. 1 HGB](https://www.gesetze-im-internet.de/hgb/__267.html)
und [§ 267a HGB](https://www.gesetze-im-internet.de/hgb/__267a.html) geregelt,
siehe auch [Wikipedia:Kapitalgesellschaft#Größenklassen](https://de.wikipedia.org/wiki/Kapitalgesellschaft#Größenklassen).

Beim Start einer neuen GmbH wird man voraussichtlich als Kleinstkapitalgesellschaft
eingestuft.

Größenabhängige Erleichterungen im HGB:

- Bilanz: [§ 266 HGB](https://dejure.org/gesetze/HGB/266.html) und [§ 274a HGB](https://dejure.org/gesetze/HGB/274a.html)
- GuV: [§ 276 HGB](https://dejure.org/gesetze/HGB/276.html)
- Anhang: [§ 288 HGB](https://dejure.org/gesetze/HGB/288.html)
   - kein Anlagespiegel im Anhang nach § 288 Abs. 1 Nr. 1 HGB
- Offenlegung: [§ 326 HGB](https://dejure.org/gesetze/HGB/326.html)


Jahresabschluss, Bilanz und Gewinn- und Verlustrechnung (GuV)
-------------------------------------------------------------

Der [Jahresabschluss](https://de.wikipedia.org/wiki/Jahresabschluss) besteht aus
(siehe [§ 242 ff. HGB](https://www.gesetze-im-internet.de/hgb/__242.html)
und [§ 264 ff. HGB](https://www.gesetze-im-internet.de/hgb/__264.html)):

- den Stammdaten des steuerpflichtigen Unternehmens
- einer [Bilanz](https://de.wikipedia.org/wiki/Bilanz)
- einer [Gewinn- und Verlustrechnung (GuV)](https://de.wikipedia.org/wiki/Gewinn-_und_Verlustrechnung)
- Kontoauszüge einiger Sachkonten

Die Bilanz und die GuV werden durch die doppelte
[Buchführung](https://de.wikipedia.org/wiki/Buchführung) erstellt.
Zudem muss eine Eröffnungsbilanz erstellt werden.

Links zur Bilanz:

- [Wikipedia: Konzernabschluss](https://de.wikipedia.org/wiki/Konzernabschluss)
- [Wikipedia: Buchhaltung](https://de.wikipedia.org/wiki/Buchhaltung)
- [Wikipedia: Grundsätze ordnungsmäßiger Buchführung GoB](https://de.wikipedia.org/wiki/Grunds%C3%A4tze_ordnungsm%C3%A4%C3%9Figer_Buchf%C3%BChrung)
- [Wikipedia: Grundsätze zur ordnungsmäßigen Führung und Aufbewahrung von Büchern, Aufzeichnungen und Unterlagen in elektronischer Form sowie zum Datenzugriff GoBD](https://de.wikipedia.org/wiki/Grunds%C3%A4tze_zur_ordnungsm%C3%A4%C3%9Figen_F%C3%BChrung_und_Aufbewahrung_von_B%C3%BCchern,_Aufzeichnungen_und_Unterlagen_in_elektronischer_Form_sowie_zum_Datenzugriff)
   - <https://www.rechnungswesen-portal.de/Fachinfo/Grundlagen/GoBD.html>
   - <https://www.ecodms.de/index.php/en/companies>
- <https://www.lexoffice.de/lexikon/bilanz/> und <https://www.lexoffice.de/lexikon/bilanzgliederung/>
- [Anhang](https://de.wikipedia.org/wiki/Anhang_(Jahresabschluss)) vom Jahresabschluss
- <https://www.haufe.de/finance/jahresabschluss-bilanzierung/hgb-bilanz-kommentar-gesamtkosten-oder-umsatzkostenverfahren_188_479200.html>
- <https://www.freefibu.de/blog/offenlegungsregeln-des-handelsrechtlichen-jahresabschlusses-2014-01-13.html>
- <https://www.bundesjustizamt.de/DE/Themen/Ordnungs_Bussgeld_Vollstreckung/Jahresabschluesse/Offenlegung/Offenlegungspflichten/Offenlegungspflichten_node.html>
- <https://de.wikipedia.org/wiki/Latente_Steuern>
- <https://de.wikipedia.org/wiki/Bilanzrechtsmodernisierungsgesetz>
- <https://www.rechnungswesenforum.de/>
- <https://www.rechnungswesen-portal.de/>
- <http://www.wirtschaftslexikon24.com/>


Bilanzgliederung
----------------

Die Gliederung der Bilanz ist im [§ 266 HGB](https://www.gesetze-im-internet.de/hgb/__266.html) vorgegeben.

- Aktivseite
   - Mittelverwendung: Wie werden die Passiva verwendet?
   - Werden unter Haben verbucht.
   - Einteilung in:
      - A. Anlagevermögen (AV): Zum Anlagevermögen werden alle Posten gezählt, die mindestens für einen bestimmten Zeitraum
        für den Geschäftsbetrieb verwendet werden, dazu zählen beispielsweise Maschinen, Büromöbel oder Computer.
      - B. Umlaufvermögen (UV): Zum Umlaufvermögen gehören alle Posten, die kurzfristig im Unternehmen genutzt werden,
        beispielsweise Druckerpapier oder Rohstoffe.
- Passivseite
   - Mittelherkunft: Herkunft der Mittel, die einem Unternehmen zur Verfügung stehen.
   - Werden unter Soll verbucht.
   - Einteilung in:
      - A. Eigenkapital
      - B. Rückstellungen
      - C. Verbindlichkeiten (bspw. Schulden)

Aktiva und Passiva der Bilanz ergeben in ihrer jeweiligen Summe den gleichen Wert.


Buchführung Kontenrahmen
------------------------

Die DATEV erstellt Standard-[Kontenrahmen](https://de.wikipedia.org/wiki/Kontenrahmen) (SKR) für die
Buchführung eines Betriebs in Deutschland. Dabei richtet sich SKR03 nach dem Prozessgliederungsprinzip
nach den Abläufen bzw. Prozessen im Unternehmen. SKR04 richtet sich nach dem Abschlussgliederungsprinzip
nach der Bilanz sowie der Gewinn- und Verlustrechnung (GuV).

Die Standard-Kontenrahmen (SKR) der DATEV können hier heruntergeladen werden:
[DATEV Standard-Kontenrahmen SKR](https://www.datev.de/web/de/m/ueber-datev/datev-im-web/datev-von-a-z/skr-standard-kontenrahmen/)
bzw. [DATEV Kontenrahmen 2020](https://apps.datev.de/dnlexka/document/0907811).
Siehe auch [SKR 04 E-Bilanz für Kapitalgesellschaft](https://www.datev.de/web/de/datev-shop/material/skr-04-e-bilanz-fuer-kapitalgesellschaft/).

Den verwendeten Kontenrahmen kann man frei wählen, sollte dies aber mit dem Steuerberater
absprechen und dann im Laufe der Jahre möglichst nicht mehr wechseln.

SKR03 wird wohl am meisten verwendet, aber SKR04 ist für eine GmbH zu empfehlen.


Übersicht SKR03
---------------

Nach dem Prozessgliederungsprinzip der Abläufe bzw. Prozesse im Unternehmen:

- 0xxx: Anlage- und Kapitalkonten
- 1xxx: Finanz- und Privatkonten
- 2xxx: Abgrenzungskonten
- 3xxx: Wareneingangs- und Bestandskonten
- 4xxx: Betriebliche Aufwendungen
- 5xxx: nicht belegt
- 6xxx: nicht belegt
- 7xxx: Bestände an Erzeugnissen
- 8xxx: Erlöskonten
- 9xxx: Vortrags- und statistische Konten


Übersicht SKR04
---------------

Nach dem Abschlussgliederungsprinzip der Bilanz:

- Bestandskonten
   - Aktiva
      - 0xxx: Anlagevermögen (AV)
      - 1xxx: Umlaufvermögen (UV)
   - Passiva
      - 2xxx: Eigenkapitalkonten
      - 3xxx: Fremdkapitalkonten
- Erfolgskonten (Erträge und Aufwendungen)
   - 4xxx: Betriebliche Erträge
   - 5xxx: Betriebliche Aufwendungen
   - 6xxx: Betriebliche Aufwendungen
   - 7xxx: Weitere Erträge und Aufwendungen
- 8xxx: nicht belegt
- 9xxx: Vortrags- und statistische Konten

Die Summe aller 9xxx-Konten muss zum Bilanzstichtag (Beginn und Ende) 0 ergeben.


Weitere Grundsätze für die Buchführung
--------------------------------------

- Keine Buchung ohne Beleg.
- Saldierungsverbot: auf einem Konto dürfen nicht Gewinne und Verluste gebucht werden.
  Ansonsten Unterkonten verwenden.
- Es wird davon ausgegangen, dass die Buchungen einmal monatlich auf den aktuellen Stand gebracht
  werden. Diese werden in der Buchhaltung "festgeschrieben" und können dann nicht mehr verändert
  werden. Für Korrekturen werden dann Storno-Buchungen angelegt.
   - Eine monatliche Bearbeitung ergibt sich spätestens mit monatlichen Vorauszahlungen der Umsatzsteuer.


Niederstwertprinzip für die Buchführung, Buchung von Wertpapieren
-----------------------------------------------------------------

Siehe [Wikipedia: Niederstwertprinzip](https://de.wikipedia.org/wiki/Niederstwertprinzip),
<https://www.rechnungswesen-portal.de/Fachinfo/Grundlagen/Niederstwertprinzip.html>
oder [sevdesk: Niederstwertprinzip](https://sevdesk.de/lexikon/niederstwertprinzip/).

- Gem. § 253 Abs. 4 HGB sind Wertpapiere des Umlaufvermögens nach dem strengen Niederstwertprinzip zu bewerten.
  Das bedeutet, dass zur kurzfristigen Anlage erworbene Wertpapiere immer zum niedrigsten Wert zu bilanzieren
  sind, auch wenn die Kursminderung am Abschlussstichtag nur vorübergehend ist.
- Für Wertpapiere des Anlagevermögens (Finanzanlagen) gilt dagegen das gemilderte (erweiterte) Niederstwertprinzip.
  Das bedeutet, dass sie bei nur vorübergehender Kursminderung mit dem niedrigeren Wert angesetzt werden können
  (Wahlmöglichkeit). Gem. §253 Abs. 2 wird aus "Kann-" eine "Mussbestimmung", wenn die Kurse dieser Anlagepapiere
  am Abschlussstichtag nachhaltig gesunken sind und von einer voraussichtlich dauernden Kursminderung auszugehen
  ist (strenges Niederstwertprinzip).

Mit dem Niederstwertprinzip wird aus Gründen der Vorsicht und zum Schutz der Gläubiger sichergestellt, das keine Gewinne
(Buchgewinne) ausgewiesen werden, die noch nicht durch Wertpapierverkäufe entstanden (realisiert) sind.

Aktien können sowohl im Umlaufvermögen (UV) wie auch im Anlagevermögen (AV) gebucht werden. Es ändert sich nur die
Abschreibung nach dem strengen oder gemilderten Niederstwertprinzip.

Ein Kursverlust aus dem Verkauf von Wertpapieren des Umlaufvermögens wird über das Konto "Verluste aus dem Abgang von
Wertpapieren des Umlaufvermögens" gebucht, ein Kursgewinn über das Konto "Erträge aus Wertpapieren des Umlaufvermögens".
Die Stückzinsen beim Ankauf festverzinslicher Wertpapiere werden auf dem Konto "Zinsaufwendungen" und beim Verkauf auf
dem Konto "Erträge aus Wertpapieren des Umlaufvermögens" erfasst. Erst nach Eintragung des durch die Inventur ermittelten
Schlussbestandes erhält man also als Saldo den Erfolg des Wertpapierkontos. Wertminderungen der Wertpapiere am
Bilanzstichtag sind als außerordentliche abzuschreiben. Abschreibungen auf einen niedrigeren Tageswert im Rahmen des
Jahresabschlusses erfolgen auf das Konto "Abschreibungen auf Wertpapiere des Umlaufvermögens".


Übertragung der E-Bilanz an das Finanzamt
-----------------------------------------

Die Eröffnungsbilanz und jede weitere Bilanz muss elektronisch an das Finanzamt
(zum Festsetzen der Ertragssteuern) übermittelt werden. Falls dies nicht bereits von der
Buchhaltungssoftware unterstützt wird, kann man den Stand aller Konten zu einem
Bilanzstichtag (per CSV) exportieren und mit folgenden Programmen an das Finanzamt
übertragen und gleichzeitig für eine Veröffentlichung im Bundesanzeiger vorbereiten:

- <https://www.ebilanzonline.de/>
- <https://www.myebilanz.de/>

Weitere Links:

- [Wikipedia: Elektronische Bilanz bzw. E-Bilanz](https://de.wikipedia.org/wiki/Elektronische_Bilanz)
   - [lexoffice: e-bilanz](https://www.lexoffice.de/lexikon/e-bilanz/)
- [Wikipedia: ELSTER](https://de.wikipedia.org/wiki/Elster_(Software)#Situation_f%C3%BCr_Softwarehersteller)
- [eBilanz-Taxonomien](http://www.esteuer.de/#finanzantrag)
- <http://www.taxonomie.hessen.de/#/home>
- <https://www.felfri.de/winston/> (Umsatzsteuervoranmeldungen, Lohnsteueranmeldungen)
- <http://www.webfibu.de/> (Webformular mit Umsatzsteuer- und Lohnsteueranmeldungen)


Veröffentlichung vom Jahresabschluss im Bundesanzeiger
------------------------------------------------------

Jährliche Veröffentlichung des Jahresabschlusses und der Bilanzen im Bundesanzeiger
ist in [§ 325 ff. HGB](https://www.gesetze-im-internet.de/hgb/__325.html) geregelt.
Bilanz nach eHUG.

Dies kostet ca. 60 € pro Jahr, für Kleinstkapitalgesellschaften 23 € pro Jahr.

[Wikipedia: Publizitätspflicht](https://de.wikipedia.org/wiki/Publizitätspflicht)

<https://www.gmbh-guide.de/jahresabschluss-bundesanzeiger.html>

Kleinstkapitalgesellschaften müssen folgende Unterlagen für den Bundesanzeiger einreichen
(siehe [§ 326 HGB](https://www.gesetze-im-internet.de/hgb/__326.html)):

- Verkürzte Bilanz (ohne [Anhang](https://de.wikipedia.org/wiki/Anhang_(Jahresabschluss)), sofern bestimmte Angaben unter der Bilanz ausgewiesen werden)
- keine GuV
- Angaben unter der Bilanz sind:
   - Angabe der Haftungsverhältnisse
   - Angaben zu gewährten Vorschüssen und Krediten unter Angabe der Zinssätze und Haftungsverhältnisse an und mit Mitgliedern des Geschäftsführungsorgans, eines Aufsichtsrates, eines Beirats u.ä.

Links:

- <https://publikations-plattform.de/>
- Übertragung Kleinstkapitalgesellschaft: <https://publikations-plattform.de/sp/i18n/doc//D091.pdf?document=D89&language=de>


Eröffnungsbilanz
----------------

- <https://www.haufe.de/recht/deutsches-anwalt-office-premium/ii-die-errichtung-der-gesellschaft-9-eroeffnungsbilanz-und-gruendungskosten_idesk_PI17574_HI1797791.html>

Was ist zu tun:

- Frist für die Eröffnungsbilanz für größere GmbHs ist 3 Monate nach der Gründung,
  für kleinere GmbHs und UGs ist die Frist 6 Monate nach der Gründung.
- Stichtag der Eröffnungsbilanz festlegen. Spätestens zum Eintrag in das Handelsregister ist es
  erforderlich, dass Sie eine entsprechende Gründungsbilanz erstellen.
  Meist wird die Geschäftstätigkeit bereits vorher aufgenommen.
- Zusätzlich kann auf den Zeitpunkt der Eintragung in das Handelsregister eine weitere Bilanz
  aufzustellen, um mit ihrer Hilfe feststellen zu können, ob und in welcher Höhe die
  Vorbelastungshaftung der Gründer eingreift.
- Die Bilanz muss auf der Passivseite den vollen Betrag des Stammkapitals als gezeichnetes Kapital
  nach § 42 Abs. 1 GmbHG ausweisen und auf der Aktivseite alle Einzahlungen der Gesellschafter.
  Etwa noch nicht eingebrachte Bareinlagen sind in der Bilanz zu aktivieren und ausdrücklich als
  ausstehende Einlagen zu bezeichnen.
- Zum Gründungsaufwand gehören alle Kosten, die im Zusammenhang mit der Errichtung der Gesellschaft
  sowie der Erbringung von Einlagen entstehen. Hierher gehören die Gebühren des Notars (§§ 32, 36 Abs. 2, §§ 39, 45, 141 KostO)
  und des Gerichts (§ 26 Abs. 1 Nr. 1, §§ 32, 79 KostO) sowie die Kosten der Bekanntmachung (§ 137 Nr. 5 KostO, ab 1.1.2008: § 137 Nr. 4 KostO)
  und auch etwaige Vergütungen für die Mitarbeit bei der Gründung, der sogenannte Gründerlohn.
  Es steht den Gesellschaftern frei zu vereinbaren, dass die Gründungskosten von der Gesellschaft
  übernommen werden, wie auch aus § 26 Abs. 2 AktG zu entnehmen ist. § 30 GmbHG steht dem nicht entgegen.
  Die Übernahme der Gründungskosten durch die Gesellschaft muss dann allerdings ausdrücklich im
  Gesellschaftsvertrag vereinbart und festgesetzt werden, wie es für die AG in § 26 Abs. 2 AktG
  ausdrücklich vorgeschrieben ist. Diese Vorschrift ist auf die GmbH entsprechend anzuwenden.
  Die Übernahme der Gründungskosten durch die Gesellschaft soll durch die Aufnahme in den Gesellschaftsvertrag
  offen gelegt werden. Die Notwendigkeit der Festsetzung der Gründungskosten im Gesellschaftsvertrag bei
  Übernahme durch die Gesellschaft folgt auch aus § 9a Abs. 1 GmbHG.
- Auf der Passivseite soll auch die Übernahme der Gründungskosten aufgeführt werden
- Die Gründungskosten können auch durch ein Aufgeld auf die Stammeinlagen, das sogenannte Agio, gedeckt werden.


Beispiel Eröffnungsbilanz einer GmbH nach SKR04
-----------------------------------------------

In einer Eröffnungsbilanz gibt es keinen Gewinn oder Verlust. Dort werden nur die Aktiva
und Passiva dargestellt. Die Eröffnungsbilanz sollte zum Zeitpunkt des Notartermins aufstellt
werden und da gibt es weder ein Bankkonto noch eine Einzahlung. Somit steht dort nur eine
ausstehende eingeforderte Einlage (Stammeinlage).

- Konten:
   - 9000: Saldenvorträge Sachkonten
   - 2900: Gezeichnetes Kapital
   - 2910: Ausstehende Einlagen auf das gezeichnete Kapital, nicht eingefordert
   - 1298: Ausstehende Einlagen auf das gezeichnete Kapital, eingefordert
- Buchungen:
   - 9000 an 2900: 25.000 Euro, gezeichnetes Kapital, Stammkapital
   - 2910 an 9000: 12.500 Euro, nicht eingefordertes Kapital
   - 1298 an 9000: 12.500 Euro, eingefordertes Kapital, Stammeinlage
- Gründungsbilanz/Eröffnungsbilanz:
   - Aktiva:
      - B. Umlaufvermögen
         - II. Forderungen und sonstige Vermögensgegenstände
            - 1298: Ausstehende Einlagen auf das gezeichnete Kapital: 12.500 Euro
      - Summe Aktiva: 12.500 Euro
   - Passiva:
      - A. Eigenkapital
         - I. gezeichnetes Kapital
            - 2900: Gezeichnetes Kapital: 25.000 Euro
            - 2910: Ausstehende Einlagen auf das gezeichnete Kapital: -12.500 Euro
         - V. Jahresüberschuss/Jahresfehlbetrag: 0 Euro
      - Summe Passiva: 12.500 Euro

Die Eröffnungsbilanz einer Kleinstkapitalgesellschaft könnte damit so aussehen:

| __Eröffnungsbilanz GmbH__ |            |                 |            |
| :-----                    | -----:     | :-----          | -----:     |
| __Aktiva__                |            | __Passiva__     |            |
| B. Umlaufvermögen         | 12.500 EUR | A. Eigenkapital | 12.500 EUR |
| Summe Aktiva              | 12.500 EUR | Summe Passiva   | 12.500 EUR |

Zum Übertragen der Öffnungsbilanz siehe auch Seite 150 [myebilanz-Handbuch](https://www.myebilanz.de/myebilanz.pdf#page=150).


Beispiel-Buchungen einer GmbH nach SKR04
----------------------------------------

Nach der Eröffnungsbilanz wird das Geschäftskonto eröffnet, die Stammeinlage eingezahlt,
die Rechnung für den Notar bezahlt und ein Darlehensvertrag geschlossen:

- Buchung für die Einzahlung der Stammeinlage auf das Geschäftskonto:
   - 1800 an 1298: 12.500 Euro, Einzahlung Stammeinlage
- Bezahlung der Notarkosten:
   - Rechnung Notar: 145,25 Euro + USt = 172,85 Euro
   - Anlegen: Kreditorkonto 70000 für den Notar.
   - Buchung:
      - 6825 Rechts- und Beratungskosten an 70000 Kreditorkonto Notar: 172,85 Euro, Erhalt der Rechnung vom Notar
      - 70000 Kreditorkonto Notar an 1800 Bank: 172,85 Euro, Überweisung vom Konto zum Notar
   - Werden im Gesellschaftsvertrag (Mustervertrag) von den Notarkosten z.B. bis zu 300 Euro von der GmbH
     übernommen, dann wird für die darüber hinaus entstehenden Kosten eine Forderung gegenüber den
     Gesellschaftern eingetragen:
      - Rechts- und Beratungskosten an Kreditor Notar: 417 Euro
      - Forderungen gegenüber Gesellschaftern an 6825 Rechts- und Beratungskosten: 117 Euro
      - Keine Buchung ohne Beleg, also wird eine Rechnung über 117 Euro (417 Euro - 300 Euro) an
        die Gesellschafter geschrieben.
- Gesellschafterdarlehen: Darlehensvertrag: Laufzeit von mindestens 10 Jahren, endfällige Tilgung und
  einem Zinssatz von 0,5 % pro Jahr. Jährliche Zinszahlung zum 31.12. des Jahres.
   - Konto 2020 Gesellschafter-Darlehen


Beispiel Darlehensvertrag nach SKR04
------------------------------------

Sammlung von Informationen zu einem Darlehensvertrag, um Geld in die GmbH einzubringen:

- Entscheidend ist stets die am Bilanzstichtag noch verbleibende Restlaufzeit.
- Gesellschafterdarlehen sind bei der GmbH als Verbindlichkeiten zu passivieren. Sie müssen nach § 42 Abs. 3 GmbHG
  gesondert unter den Verbindlichkeiten in der Bilanz mit arabischen Zahlen ausgewiesen oder im Anhang angegeben werden.
- § 285 Nr. 1 HGB verlangt für die in der Bilanz ausgewiesenen Verbindlichkeiten die Angabe des Gesamtbetrags der
  Verbindlichkeiten mit einer Restlaufzeit von mehr als 5 Jahren.
- Die in der Bilanz ausgewiesenen Verbindlichkeiten sind im Anhang anzugeben:
   - der Gesamtbetrag der Verbindlichkeiten mit einer Restlaufzeit von mehr als 5 Jahren und
   - der Gesamtbetrag der Verbindlichkeiten, die durch Pfandrechte oder ähnliche Rechte gesichert
     sind, unter Angabe von Art und Form der Sicherheiten.
- Kleine Kapitalgesellschaften brauchen nur eine verkürzte Bilanz aufzustellen, in die
  Darlehen nur gem. § 266 Abs. 3 C. „Verbindlichkeiten“ aufgenommen werden.
  Das Gleiche gilt für Kleinstkapitalgesellschaften.
- Forderungen und Verbindlichkeiten gegenüber Gesellschaftern sind in der Bilanz gesondert kenntlich zu
  machen oder im Anhang anzugeben. Darüber hinaus ist
   - bei Forderungen der GmbH gegenüber einem Gesellschafter nach § 268 Abs. 4 Satz 1 HGB der Betrag mit
     einer Restlaufzeit von mehr als einem Jahr anzugeben,
   - bei Verbindlichkeiten der GmbH gegenüber dem Gesellschafter nach § 268 Abs. 5 Satz 1 HGB der Betrag
     mit einer Restlaufzeit bis zu einem Jahr sowie nach § 285 Nr. 1 Buchst. a HGB der Betrag mit einer
     Restlaufzeit von mehr als 5 Jahren anzugeben. Das bedeutet letztlich, dass Geschäftsführer die
     Verbindlichkeiten in drei Fristengruppen aufteilen müssen.
   - Angaben über die nicht in der Bilanz auszuweisenden Haftungsverhältnisse nach § 251 HGB und § 268 Abs. 7 HGB
   - Angaben über gewährte Vorschüsse und Kredite unter Angabe der Zinssätze, wesentlichen Bedingungen usw.
     gegenüber Geschäftsführungsorgan und Aufsichtsrat u. Ä. nach § 285 Nr. 9 Buchst. c HGB
   - Angaben über den Bestand eigener Aktien im Falle von AG und KGaA nach § 160 Abs. 1 Nr. 2 AktG
      - Im Geschäftsjahr liegen keine angabepflichtigen Vorgänge vor.
- Also das 2020 ff. wird im EK dargestellt, sollte der Gesellschafter der GmbH ein Darlehen ohne weitere
  Beschränkungen, für die längerfr. Verwendung zur Verfügung stellen, dann wäre im Insolvenzfall diese
  Darlehen nicht rückzahlungsfähig und wird für die Bedienung der Gläubiger verwendet. Somit Konto 2020 ff.
- Wenn ein Gesellschafter der GmbH ein Darlehen gewährt, das eine Insolvenzabsicherung besitzt und somit
  dann nicht verloren geht, dann verwendet man eines der 3510 ff Konten.
- Im Gesellschafterdarlehen wird ein Rangrücktritt erklärt. Dies muss sowohl insolvenzrechtlich als
  auch steuerrechtlich bestand haben.
- 1 Prozent über [euribor](https://de.wikipedia.org/wiki/Euro_Interbank_Offered_Rate). Das sind ca. 0.55 Prozent.

Musterverträge zu einem Darehensvertrag:

- <https://www.wonder.legal/de/modele/gesellschafterdarlehensvertrag>
- <https://d23wdxoo51zvyp.cloudfront.net/wp-content/uploads/20180410121218/firmade_Muster-Darlehensvertrag.pdf>
- <https://media.seitenbox.de/p/480/files/MV_Darlehensvertrag.pdf>
- <https://www.lindenheim.de/media/darlehensv.pdf>
- <https://www.rechtsanwalt-brueggemann.de/downloads/darlehensvertrag_muster.pdf>

- SKR04 Konten:
   - 3340 Verbindlichkeiten aus Lieferungen und Leistungen gegenüber Gesellschaftern
      - 3348 Restlaufzeit größer 5 Jahre
   - 3500 Sonstige Verbindlichkeiten
      - 3510 Verbindlichkeiten gegenüber Gesellschaftern
         - 3517 Restlaufzeit größer 5 Jahre
      - 3530 Darlehen atypisch stiller Gesellschafter
         - 3537 Restlaufzeit größer 5 Jahre
      - 3560 Darlehen
         - 3567 Restlaufzeit größer 5 Jahre
      - 3640 Verbindlichkeiten gegenüber GmbH-Gesellschaftern
         - 3643 Restlaufzeit größer 5 Jahre
      - 3645 Verbindlichkeiten gegenüber persönlich haftenden Gesellschaftern
         - 3648 Restlaufzeit größer 5 Jahre
      - 3655 Verbindlichkeiten gegenüber stillen Gesellschaftern
         - 3658 Restlaufzeit größer 5 Jahre
   - 7316 Zinsen für Gesellschafterdarlehen
   - 7317 Zinsen an Gesellschafter mit einer Beteiligung von mehr als 25 % bzw. diesen nahe stehende Personen


Beispiel 1 SKR04 Buchungen
--------------------------

Beispiel von SKR04 Buchungen zusammengefasst von den folgenden Internet-Seiten:

- <http://mit-rueckenwind.info/die-9-wichtigsten-buchungskonten-fuer-deine-spardosen-gmbh/>
- <http://mit-rueckenwind.info/die-wichtigsten-buchungssaetze-fuer-deine-spardosen-gmbh/>

beteiligte SKR04 Konten:

- Aktiva
   - 1xxx Umlaufvermögen (UV)
      - eigentliche Konten
         - 1700: Geschäftskonto
         - 1710: Wertpapierverrechnungskonto
   - 0xxx Anlagevermögen (AV)
      - Aktien
         - 0900: Wertpapiere des Anlagevermögens
      - anderes
         - 0670: Geringwertige Wirtschaftsgüter
- Erträge und Aufwendungen
   - Aktien
      - 4900: Erträge aus dem Abgang von Anlagevermögen
      - 6903: Verluste aus dem Abgang von Anlagevermögen
   - Zinsen
      - 7020: Zins- und Dividendenerträge
   - anderes
      - 6260: Sofortabschreibung geringwertige Wirtschaftsgüter
      - 6024: Geschäftsführergehälter GmbH-Gesellschafter

Beispielbuchungen:

- Kauf von Aktien:
   - Anschaffungskosten (Kurswert + Gebüren) gebucht auf Soll 0900 und Haben 1710
- Verkauf von Aktien
   - Soll 1710: Nettoerlös = Kurswert – Gebühren
   - Haben 0900: Anschaffungskosten
   - Bei Gewinn:
      - Haben 4900: Gewinn = Nettoerlös – Anschaffungskosten
   - Bei Verlust:
      - Haben 6903: Verlust = Anschaffungskosten – Nettoerlös
- Dividenden:
   - Soll 1710: Dividendenzahlung – Steuern
   - Haben 7020: Dividendenzahlung – Steuern
- geringwertige Wirtschaftsgüter:
   - Bruttokaufpreis gebucht auf Soll 0670 und Haben 1700
   - Bei Sofortabschreibung geringwertige Wirtschaftsgüter:
      - Soll 6260: Bruttokaufpreis
      - Haben 0670: Bruttokaufpreis
- Geschäftsführergehalt:
   - Soll 6024: Nettogehalt Geschäftsführer
   - Haben 1700: Nettogehalt Geschäftsführer


Beispiel 2 SKR04 Buchungen
--------------------------

Beispiel von SKR04 Buchungen zusammengefasst aus dem Pdf-Dokument <http://pmpod.de/TradingBuchhaltungWIP.pdf>.

beteiligte SKR04 Konten:

- Aktiva
   - 1xxx Umlaufvermögen (UV)
      - Konten
         - 1810: Bank Eurobestand
         - 181x: Bank/Handelswährung
      - Aktien
         - 1510: Wertpapiere des Umlaufvermögens
      - Futures und CFDs
         - 1301: Sonstige Vermögensgegenstände
- Passiva
   - 3xxx Fremdkapital
      - Optionen
         - 3501: Sonst. Verbindlichkeiten
         - 3902: Rückstellungen für drohende Verluste aus schwebenden Geschäften
- Erträge (4xxx, 7xxx) und Aufwendungen (6xxx, 7xxx)
   - Aktien
      - 6905: Verluste aus dem Abgang Umlaufvermögen
      - 4906: Erträge aus dem Abgang von Gegenständen des Umlaufvermögens
      - 6210: Außerplanmäßige Abschreibungen auf Imm. Vermggs.
   - Dividenden
      - 7000: Erträge aus Beteiligungen
      - 7639: Anzurechnende ausl. Quellensteuer, Anrechnung/Abzug ausländischer Quellensteuer
   - Devisen
      - 6880: Aufwände aus Währungsumrechnung
      - 4840: Erträge aus Währungsumrechnung
   - Optionen
      - 7010: Erträge aus anderen Wertpapieren
      - 6300: Sonstige betriebliche Aufwendungen
      - 4830: Sonstige betriebliche Erträge
   - Zinsen
      - 7110: Sonstige Zinserträge
      - 7310: Sonstige Zinsaufwendungen

Beispielbuchungen:

- Aktien: werden als Wertpapiere im Umlaufvermögen gekauft oder verkauft. Keine Leerverkäufe.
   - Kauf: 1510 an 181x
   - Verkauf: 6905 an 1510, 181x an 4906
   - Falls am Bilanzstichtag der Kurs der offenen Aktienpositionen unterhalb des Kaufkurses liegt,
     sind Abschreibungen vorzunehmen: 6210 an 1510
      - Wenn die Aktien wieder steigen werden Zuschreibungen bis zu den ursprünglichen Anschaffungskosten gemacht.
         - Wertpapiere des AV an sonst. betriebliche Erträge
   - Zu klären: Ist 4906 wirklich richtig für HGB 8b? Wie sind Verluste zu buchen?
- Dividenden:
   - Erhalt einer Dividende: 181x an 7000
   - Zahlung der Quellensteuer: 7639 an 181x
   - Zu klären: Teilweise Rückforderung von Quellensteuer
- Devisen
   - aktiver Kauf einer Fremdwährung: 181x an 1810
   - aktive Veräußerung einer Fremdwährung: 1810 an 181x
   - Währungsgewinn: 1810 an 4840
   - Währungsverlust: 6880 an 1810
- Optionen
   - gekaufte Optionen werden wie Aktien gebucht:
      - Kauf: 1510 an 181x
      - Verkauf, Ausbuchen von Optionen: 6905 an 1510
         - Falls noch ein Wert besteht: 181x an 7010
   - verkaufte Optionen (Schreiben von Optionen, Stillhaltergeschäft, Prämie ist ein schwebendes Geschäft):
      - Erhalt einer Stillhalterprämie (Verkauf von Optionen): 181x an 3501
      - Verfall oder Glattstellung von verkauften Optionen:
         - 3501 an 4830
         - Restwert der Option: 6300 an 181x
         - Rückstellungen am Bilanzstichtag: 6300 an 3902
- Futures/CFDs
   - Erhalt einer Margin Variation Zahlung: 181x an 3501
   - Abbuchung einer Margin Variation Zahlung: 1301 an 181x
   - Bei Glattstellung
      - Auflösen von Verbindlichkeiten: 3501 an 4830
      - Auflösen der sonstigen Vermögensgegenstände: 6300 an 1301
- Zinsen
   - Erhaltene Zinsen: 181x an 7110
   - Gezahlte Zinsen: 7310 an 181x


Beispiel 3 SKR04 Buchungen
-----------------------

verwendete SKR04 Konten:

- Steuern:
   - Bestandskonten Umsatzsteuer
      - 3805 Umsatzsteuer 19%
      - 3806 Umsatzsteuer 7%
      - 1400 Anrechenbare Vorsteuer 19% und 7%
   - Bestandskonten - Verbindlichkeiten
      - 3730 Lohnsteuerschuld
      - 3731 Solisteuerschuld
   - 7600 Körperschaftsteuer
   - 7620 Gewerbeertragssteuer
   - 7650 Sonstige Steuern
- Bank:
   - 6855 Nebenkosten des Geldverkehrs
   - 7300 Zinsen und ähnliche Aufwendungen
- Büro:
   - Bestandskonten Anlagevermögen:
      - 0620 Werkzeuge
      - 0650 Büroeinrichtung
      - 0670 Geringwertige Wirtschaftsgüter
   - Aufwandskonten:
      - 6800 Porto
      - 6805 Telefon
      - 6805 Telefongebühren
      - 6810 Telefax und Internetkosten
      - 6815 Bürobedarf
      - 6820 Zeitschriften, Bücher (Fachliteratur)
      - 6821 Fortbildungskosten
      - 6830 Buchführungskosten
- Jahresabschluss:
   - 2970 Gewinnvortrag vor Verwendung
   - 2975 Gewinnvortrag vor Verwendung
   - 2977 Verlustvortrag vor Verwendung
   - 2978 Verlustvortrag vor Verwendung


Beispiel 4 SKR04 Lohnzahlung
----------------------------

- Siehe [textbuch-Dokumentation#page=33](http://www.textbuch.de/archiv/tbuch-doku.pdf#page=33)
- zu zahlende Lohnsteuer: <https://www.bmf-steuerrechner.de/>
- beteiligte Konten: 60xx
   - Nettogehalt
   - Lohnsteuer
   - Solisteuer
   - Kirchensteuer evangelisch/katholisch u.a.
   - Arbeitgeberzuschüsse an die Krankenkasse
- Im Folgejahr müssen Sie dann für jeden Arbeitnehmer separat eine Lohnsteuerbescheinigung des vergangenen
  Jahres elektronisch ans Finanzamt übermitteln.

