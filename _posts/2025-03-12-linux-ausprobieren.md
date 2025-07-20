---
title: Linux ausprobieren
description: Wie bekomme ich Linux auf meinen Rechner? Dieser Beitrag zeigt Dir Schritt für Schritt, wie Du Deinen Rechner mit Linux Mint von einem USB-Stick startest.
date: 2024-10-01T21:20:42.000Z
preview: ""
tags: []
categories:
    - Umsteigen
media_subpath: /images
image: /Startseite Distrosea.webp
---

Im letzten Artikel hast Du Dir Dein Linux ausgesucht. Als nächstes solltest Du es einmal anfassen und etwas damit spielen, um besser zu verstehen, wie das System funktioniert und wie Du damit zurechtkommst. Großartiger Weise lassen sich alle Linux Distributionen als „Live-Systeme“ starten. Das bedeutet, dass Du Dein Linux auf einen USB-Stick kopierst, Deinen Rechner startest und Linux startet, ohne dass etwas auf Deine Festplatte installiert wird. Du musst Dich also nicht sofort für einen Umstieg entscheiden, sondern kannst Dich langsam herantasten.

Wenn Du Dir einen allerersten Eindruck verschaffen willst, ohne irgendetwas auf Deinem lokalen Rechner zu starten oder zu installieren, kannst Du [https://distrosea.com/](Distrosea) nutzen. Die Webseite bietet die Möglichkeit die Live-Versionen vieler Linux-Distributionen über den Browser auszuprobieren. Damit das System nich überrannt wird, gibt es eine Warteschlange, bis man die gewünschte Linuxdistribution starten kann. Du wartest aber normalerweise unter einer Minute.

Wer lieber eine Videoanleitung ansehen will, in der erklärt wird, wie ein Live-USB-Stick vorbereitet wird, dem sei das Video von Linux Guides empfohlen.

{% include embed/youtube.html id='itcOTdTLInQ' %}

## Den Umstieg vorbereiten

Um Linux auszuprobieren, benötigst Du:

- einen USB-Stick der mindestens 4 GB groß sein sollte
- Deinen Rechner
- ein ISO-Abbild Deiner Linux Distribution

*Achtung! Wenn Du Dein Linux auf den USB-Stick kopierst, werden alle anderen Daten gelöscht.*

Lade nun Deine Distribution herunter. Linux Mint findest Du unter https://www.linuxmint.com/download.php. Hier kannst Du in den meisten Fällen die „Cinnamon Edition“ nehmen. Diese läuft auch auf meinem Testrechner, einem Thinkpad T410 aus dem Jahr 2010 ohne Probleme.

Die meisten Distributionen werden als [ISO-Abbild](https://de.wikipedia.org/wiki/ISO-Abbild) bereitgestellt. Dabei handelt es sich um ein Abbild einer CD-Rom oder DVD, da vor der USB-Zeit die Rechner von einem CD-Laufwerk gestartet wurden. Diese Abbilder sind normalerweise zwischen zwei und drei Gigabyte groß, und enthalten alle Dateien, die für das Starten des Systems nötig sind.

> Dokumentation
>
> - Die offizielle englische Dokumentation findest du unter https://www.linuxmint.com/documentation.php
> - Der deutsche Teil des offiziellen Forums ist unter https://forums.linuxmint.com/viewforum.php?f=64 zu finden 
> - Linux Mint Users ist eine große deutsche Community: https://www.linuxmintusers.de/index.php
{: .prompt-info }

Die meisten Distributionen werden als ISO-Abbild bereitgestellt. Dabei handelt es sich um ein Abbild einer CD-Rom oder DVD, da vor der USB-Zeit die Rechner von einem CD-Laufwerk gestartet wurden. Diese Abbilder sind normalerweise zwischen zwei und drei Gigabyte groß und enthalten alle Dateien, die für das Starten des Systems nötig sind.

Um das Abbild auf den USB-Stick zu schreiben, nimmst Du am besten die Software Balena Etcher, die entwickelt wurde, um leicht Daten auf Wechselmedien zu schreiben. Du kannst diese unter https://etcher.balena.io/#download-etcher herunterladen. Es gibt sie für alle gängigen Betriebssysteme.

![Ein Teil der Balena Etcher Download-Seite, die die verschiedenen Optionen zeigt](Downloadoptionen für Balena Etcher.webp)

## Die ISO-Datei auf den USB-Stick schreiben

Zusammengefasst geht es folgendermaßen:

- Installiere Balena Etcher und führe das Programm aus.
- Stecke Deinen USB-Stick, auf den das Abbild geschrieben werden soll, ein.
- Wähle ein Abbild, das auf den USB-Stick geschrieben werden soll.
- Drück nun „Flash!“ und die Datei wird geschrieben.

### Die Schritt-für-Schritt-Anleitung für das Schreiben des ISO-Abbilds auf einen USB-Stick

Wenn du das Programm öffnest, erwartet Dich der folgende Auswahlbildschirm:

![Das Balena Etcher Hauptmenü auf Windows 11](Balena Etcher Hauptfenster.webp)

Wähle „Flash from file“ und gib das ISO-Abbild an, das du heruntergeladen hast.

![](Dateiauswahl%20Windows%2011.webp)

Nachdem Du die ISO-Datei gewählt hast, wählst Du noch den passenden USB-Stick aus, auf den die Datei geschrieben werden soll.

![Balena Etcher Auswahlfenster für das zu beschreibende Medium](USB-Stick%20auswählen.webp)

Balena Etcher zeigt alle Laufwerke an, verbirgt aber die Systemlaufwerke und kennzeichnet diese deutlich.

> Wähle nie ein Systemlaufwerk! Überschreibst du es, verlierst du dein Betriebssystem und kannst deinen Rechner nicht mehr nutzen.
{: .prompt-danger }

Drück nun „Flash!“ und die Datei wird geschrieben

![](Balena%20Etcher%20schreibt%20Abbild.webp)

Herzlichen Glückwunsch! Du hast nun einen Linux Mint USB-Stick, mit dem Du Deinen Rechner starten kannst.

## Ein Live-System starten

Um Dein Linux Mint als Live-System zu starten, muss Dein Computer erst von seinem USB-Laufwerk starten, bevor er die Festplatte nach einem installierten Betriebssystem durchsucht. Wie das genau funktioniert, ist von Computer zu Computer verschieden. Hier sind einige Anleitungen, die Dir dabei helfen, die passenden Einstellungen zu finden:

- [Libe.net: Den Computer von USB oder DVD starten](https://www.libe.net/von-USB-oder-DVD-starten)
- [Heise: Booten von USB-Laufwerken Antworten auf die häufigsten Fragen](https://www.heise.de/select/ct/2018/24/1542617598175392)
- [PCtipp.ch: Windows 10: Wie boote ich ab USB-Stick](https://www.pctipp.ch/praxis/zubehoer/windows-10-wie-boote-ich-ab-usb-stick-2018256.html)

Wenn Du Dein Linux Mint erfolgreich gestartet hast, sollte Dich der folgende Bildschirm begrüßen

![](Linux%20Mint%20Start%20Screen.webp)

Prima! Du kannst jetzt anfangen, Dein System kennenzulernen.
