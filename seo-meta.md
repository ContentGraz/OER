---
generator: pandoc
title: |
    SEO META in 1 Click - Die Google Chrome Extension für eine schnelle
    SEO-Analyse
bibliography: seo-meta.bib
csl: apa.csl
link-citations: true

---

Die SEO META in 1 Click Extension ermöglicht es, Websites schnell und
unkompliziert auf „Fehler" zu untersuchen. Analysiert werden im
Wesentlichen die Meta-Daten und grundsätzliche SEO Informationen, welche
für eine schnelle und optimierte Website relevant sind.

Google Chrome Extension
-----------------------

SEO Browser Plugins gibt es viele. Neben dem [META SEO
Inspector](https://chrome.google.com/webstore/detail/meta-seo-inspector/ibkclpciafdglkjkcibmohobjkcfkaef "META DEO Inspektor im Chrome Webshop")
eignet sich vor allem das Plugin SEO META in 1 Click sehr gut für die
Analyse der Meta-Daten. Im Gegensatz zu *META SEO Inspector* wirkt *SEO
META in 1 Click* sehr aufgeräumt und übersichtlich.

Voraussetzung für die Anwendung ist die Verwendung von [Google
Chrome](https://www.google.de/chrome/?brand=CHBD&gclid=EAIaIQobChMI8cme9e6Y5gIVCLLtCh0vzw60EAAYASAAEgLiTfD_BwE&gclsrc=aw.ds "Download-Link für Google Chrome")
als Browser und in weiterer Folge die Installation der [Extension als
Plugin](https://chrome.google.com/webstore/detail/seo-meta-in-1-click/bjogjfinolnhfhkbipphpdlldadpnmhc)

![Das Interface von SEO META in 1
CLICK](https://oer.fh-joanneum.at/contentstrategy/wp-content/uploads/2016/07/seo-meta-1-click-interface.jpg "Das Interface von SEO META in 1 CLICK")

Bei der Analyse der Website konzentriert sich das Plugin auf folgende
wesentliche Punkte:

-   Titel und Länge des Titels
-   Description und Länge der Description
-   URLs (Analyse der Meta-Canonical URL)
-   Meta-Robots
-   Headlines (für die Darstellung in HTML, H1-H6)
-   Bilder auf der Seite (Anzahl, Bilder mit und ohne ALT-Attribute)
-   Anzahl der Links (intern und extern)
-   `robots.txt`-Datei
-   Open Graph

Alles auf einen Blick in der Summary
------------------------------------

Ist das Plugin installiert, reicht das Eintippen einer URL
beziehungsweise der Besuch einer Website. Hier benutzen wir als Beispiel
\<www.fh-joanneum.at\> . In der Übersicht zeigt das Chrome-Plugin
zusammengefasst alle analysierten Bereiche.

Title
-----

Betrachtet man die Information beim Punkt *Title*, so wird einem
angezeigt, dass die Angabe von „FH Joanneum" zwar dass Mindestkriterium
erfüllt, dass ein Titel vorhanden ist, dass dieser aber mit 11
Characters zu kurz gewählt wurde. Lässt man als Vergleich die Seite
\<www.derstandard.at \> analysieren, so sieht man, dass der Titel dort
mit 52 Charakters die richtige Länge hat (und in diesem Fall auch die
richtige Information bietet). Bei einem Klick auf das
Fragezeichen-Symbol werden Details angezeigt, welche die Anforderungen
an den Titel noch stärker verdeutlichen [zu den Anforderungen an den
Title siehe @googleAussagekraeftigeTitelUnd2019]. So steht hier
beispielsweise Folgendes:

> Defines a title for:
>
> -   the document
> -   in the browser toolbar
> -   the page when it is added to favorites
> -   for the page in search-engine results

![Zusammenfassung der Informationen in SEO Meta 1
Click](https://oer.fh-joanneum.at/contentstrategy/wp-content/uploads/2016/07/seo-meta-1-click-overview-derstandard.jpg "Zusammenfassung der Informationen in SEO Meta 1 Click")

Description
-----------

Die sogenannte *Meta Description* ist eine kurze und präzise
Zusammenfassung des Seiteninhalts im Kopf der Seite, welche nicht im
Browserfenster dargestellt wird, aber von der Suchmaschine für die
Darstellung der Suchergebnisse in den *Snippets* [siehe auch dazu
@googleAussagekraeftigeTitelUnd2019 und @selfhtml-wikiHTMLKopfdatenMeta2019] genutzt werden kann.
Wichtig bei der Erstellung der *Meta Description* ist in erster Linie,
dass schnell erkennbar ist, worum es in der Seite geht. Dazu sollten
wichtige Keywords am Anfang stehen. Die *Meta Description* kann darüber
entscheiden, ob jemand von einem Suchergebnis weiterklickt oder nicht.

### Beispiel: Auszug Meta Description „FH Joanneum"

„Als anwendungsorientierte Hochschule bietet Ihnen die FH JOANNEUM
praxisbezogene Lehre, Forschung und Weiterbildung mit interdisziplinärer
Ausrichtung.

### Beispiel: Optimierte Meta Description

„Die FH JOANNEUM bietet Ihnen als anwendungsorientierte Hochschule in
Graz praxisbezogene Lehre, Forschung und Weiterbildung mit
interdisziplinärer Ausrichtung."

Keywords -- zusätzlich zur Meta Description
-------------------------------------------

Keywords im Element`meta` im `head` einer Seite sind nicht mehr relevant
[siehe @selfhtml-wikiHTMLKopfdatenMeta2019], wohingegen
themenspezifische Keywords im Inhalt der Website immer wichtiger werden.

URL und Canonical -- zur Vermeidung von Duplicate Content
---------------------------------------------------------

Wichtig ist hier vor allem die Angabe einer kanonischen URL für die
Seite [@googleDoppelteURLsZusammenfassen2019]. Kanonische URLs, oft
einfach *canonicals* genannt, werden eingesetzt um „Duplicate Content"
zu vermeiden, sprich um bei mehrfach verwendetem Inhalt die
Originalressource auszuweisen, die Google als Suchergebnis verwendet.

`robots`-Tag -- für Indexierung bei Suchmaschinen
-------------------------------------------------

Mit dem Inhalt des `robots`-Tag (`index` oder `no-index`) können
Webseiten-Eigentümer bestimmen, ob Suchmaschinen die Seite indexieren
sollen oder nicht. Technische Zudem wird in weiterer Folge u.a.
festgelegt, ob eine Suchmaschine Links auf der Seite folgen darf oder
nicht (`follow` / `no-follow`). Diese Informationen werden grundsätzlich
im „Head" einer HTML-Seite hinzugefügt. [@googleSpezifikationenFurRobotsMetaTags2019]. Nach dem
aktuellen und umfangreichen Google-Update im Oktober 2019 gibt es für
die Inhalte der Robots-Meta-Tags neue Optionen [siehe @spriestersbachGoogleFuehrtNeue2019]:

 `nosnippet`
:   Dies ist eine bereits bestehende Option, mit der man festlegen kann,
    dass kein Textausschnitt für die jeweilige URL angezeigt wird.

 `max-snippet:[number]`
:   Hiermit lässt sich angeben, wie lang der Text für ein Snippet
    maximal sein soll. Durch eine solche Angabe kann z.B. ein
    Zeitungsverlag verhindern, dass Inhalte auf der Such-Ergebnisseite
    angezeigt werden.

 `max-video-preview:[number]`
:   Hiermit kann man die maximale Dauer in Sekunden für eine animierte
    Videovorschau angeben.

 `max-image-preview:[setting]`
:   Damit kann man die maximale Größe der Bildvorschau angeben, die für
    Bilder auf dieser Seite angezeigt werden soll. Mögliche Werte sind
    "none", "standard", oder "large".

Diese Verwendung der Robots-Tags sieht man beispielsweise schon unter
www.derstandard.at

![Inhalt des robots-Tag in SEO Meta 1
Click](https://oer.fh-joanneum.at/contentstrategy/wp-content/uploads/2016/07/seo-meta-1-click-robots.jpg "Inhalt des robots-Tag in SEO Meta 1 Click")

Lang -- Definition der Website-Sprache
--------------------------------------

SEO Meta 1 Click zeigt hier an, welche Sprache im `head` angegeben ist.
Aus dieser Angabe kann eine Suchmaschine entnehmen, ob es sinnvoll ist,
eine Seite für UserInnen und User mit einer bestimmten Sprache
anzuzeigen. Deshalb ist die Sprachangabe für die Optimierung einer Seite
wichtig [siehe dazu @googleGoogleUeberLokalisierte2019].

Überschriften -- die Hierarchie der Inhalte
-------------------------------------------

Hier wird übersichtlich dargestellt, welche Headlines verwendet werden
und wie oft sie vorkommen. Zudem gibt das Plugin die Zahl der Images und
Links auf der Website an.

![Überblick über die Header in SEO Meta 1
Click](https://oer.fh-joanneum.at/contentstrategy/wp-content/uploads/2016/07/seo-meta-1-click-headers.jpg "Überblick über die Header in SEO Meta 1 Click")

Klickt man auf *Headers*, werden detailliert alle Headlines des
Dokuments gezeigt. Die Elemente für Überschriften (`h1`-`h6`) dienen im
HTML-Code dazu, den Inhalt einer Seite hierarchisch zu strukturieren.
Wie diese Struktur auf dem Bildschirm präsentiert wird, wird mit CSS
festgelegt. Die Header-Struktur beeinflusst die Indexierung der Website
und hilft den Suchmaschinen die Seite zu „lesen". Headlines werden durch
das SEO Meta 1 Click Plugin wie folgt aufgelistet:

![Übersicht über die Header in SEO Meta 1
Click](https://oer.fh-joanneum.at/contentstrategy/wp-content/uploads/2016/07/seo-meta-1-click-show-headers.jpg "Übersicht über die Header in SEO Meta 1 Click")

Images -- für Suchmaschinen relevante Informationen im HTML-Code
----------------------------------------------------------------

Bei der Analyse der Bilder auf der Website geht es in erster Linie um
das `title`- und das `alt`-Attribut. Diese sind wie auch schon die
Header, für die Indexierung durch die Suchmaschine und auch für die
Barrierefreiheit wichtig. Die „Suche" bei Google konzentriert sich
nämlich nicht nur auf die Suche von passenden Websites sondern eben auch
auf Bilder; gute einführende Informationen dazu erhält man durch @googleBestPracticesFuer2019. Mit dem richtigen `title`-
und `alt`-Attribut können Unternehmen daher auch in der Bilder-Suche
gefunden werden. Vielleicht noch wichtiger ist, dass diese Angaben die
Qualität der Seite insgesamt verbessern und damit zu einem besseren
Ranking beitragen. Der Reiter *Images* innerhalb des Plugins zeigt nun
also im Falle der URL \<www.fh-joanneum.at\> , dass es 88 Bilder gibt,
keines davon ein definiertes Alt-Attribut besitzt und nur 7 davon einen
Titel.

![Überblick über unvollständig ausgezeichnete Bilder in SEO Meta 1
Click](https://oer.fh-joanneum.at/contentstrategy/wp-content/uploads/2016/07/seo-meta-1-click-images.jpg "Überblick über unvollständig ausgezeichnete Bilder in SEO Meta 1 Click")

Außer den Inhalten des `title`- und des `alt`-Attributs interpretiert
Google auch die URL eines Bildes. Im Falle der FH Joanneum wäre es also
sinnvill, eine URL wie `Logo_FH_Joanneum_Graz.svg` zu verwenden.

![Übersicht zu unvollständig ausgezeichneten Links in SEO Meta 1
Click](https://oer.fh-joanneum.at/contentstrategy/wp-content/uploads/2016/07/seo-meta-1-click-show-links.jpg "Übersicht zu unvollständig ausgezeichneten Links in SEO Meta 1 Click")

Links -- interne und externe Linksetzung
----------------------------------------

Ebenso wie bei den Bildern und Überschriften, gibt SEO META 1 CLICK auch
hier eine allgemeine Übersicht über die Anzahl und die korrekte
Auszeichnung der Links auf der analysierten Seite.

![Überblick über die Links in SEO Meta 1
Click](https://oer.fh-joanneum.at/contentstrategy/wp-content/uploads/2016/07/seo-meta-1-click-links.jpg "Überblick über die Links in SEO Meta 1 Click")

SEO META 1 CLICK eignet sich perfekt als schnelles Analyse-Tool, welches
direkt beim Besuch der Website und beim „Durchklicken" angewendet werden
kann. Es informiert über einige der für Suche und
Suchmaschinenoptimierung wichtigsten Eigenschaften einer Seite. Vor
allem erschließt es Informationen im Header und im Markup, die man sonst
mühsam im Quelltext suchen müsste. Man erfährt mit einem Klick viel über
das Optimierungs-Potenzial einer Seite.

[Außer den Hinweisen bei den einzelnen Elementen hilfreich: @googleStartleitfadenZurSuchmaschinenoptimierung2019]

------------------------------------------------------------------------

Dieser Artikel ist eine eine offene Lernressource des [Studiengangs
Content
Strategy](https://www.fh-joanneum.at/content-strategie-und-digitale-kommunikation/master/en/programme/ "Content-Strategie / Content Strategy")
der FH Joanneum.

::: {.section .oer-info}

 URL:
:   https://oer.fh-joanneum.at/contentstrategy/seo-meta-in-1-click-die-google-chrome-extension-fur-eine-schnelle-seo-analyse

 Version:
:   1.0

 Autor:
:   Markus Fritz

 Lehrveranstaltung:
:   Schreiben, Redigieren und Kuratieren im Web

 Letzte Aktualisierung:
:   2019-12-06

 Rechte:
:   [![Creative Commons
    Lizenzvertrag](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)\
    Dieses Werk ist lizenziert unter einer [Creative Commons
    Namensnennung 4.0 International
    Lizenz](http://creativecommons.org/licenses/by/4.0/).
:::

------------------------------------------------------------------------

Literatur {#literatur .unnumbered}
---------
