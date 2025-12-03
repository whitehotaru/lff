---
title: Wieviel Hardware braucht der Mensch?
description: Braucht man immer einen aktuellen Rechner, um gut arbeiten zu können? Ich denke, dass das nicht nötig ist. Linux ist läuft auch auf alter Hardware flüssig.
date: 2024-09-23T22:49:00.000Z
media_subpath: /images
image: banner-wieviel-hardware.1200.webp
tags:
    - hardware
    - philosophie
    - endof10
categories:
    - Umsteigen
draft: false
---


Bevor ihr euch überlegt, ob ihr mit Linux einsteigen wollt, benötigt ihr natürlich erst einmal einen Computer, auf dem es installiert werden soll. Häufig ist ein Grund Linux zu installieren das Wiederbeleben älterer Computer, da Linux auch ältere Hardware unterstützt und kontinuierlich mit Sicherheitsaktualisierungen versorgt wird. So war es auch in unserem Fall.

Auslöser dieses Blogs war der Wunsch meiner Partnerin, ihr [Microsoft Surface 2017](https://de.wikipedia.org/wiki/Microsoft_Surface_Pro_2017) wieder auf eine annehmbare Arbeitsgeschwindigkeit zu bringen. Sieben Jahre ist für PC Hardware eine recht lange Zeit und das Gerät benötigt inzwischen ziemlich lange, um nach dem Anschalten arbeitsfähig zu werden.

Linux ist für solche Fälle eine gute Lösung, da auch ältere Hardware unterstützt und kontinuierlich mit Updates versorgt wird.

Hinzu kommt noch, dass Windows 10 so langsam das Supportende erreicht und Windows 11 deutlich höhere Hardwareanforderungen hat. Vor allem die beiden Technologien [Secure Boot](https://de.wikipedia.org/wiki/Unified_Extensible_Firmware_Interface#Secure_Boot) und das [Trusted Platform Module (TPM)](https://de.wikipedia.org/wiki/Trusted_Platform_Module) können eine Hürde für die Nutzung von Windows 11 bei älteren Systemen darstellen.

## Unsere Anwendungsfälle

Wenn wir unsere Computer nutzen, dann vor allem für die folgenden Dinge (ohne eine spezielle Reihenfolge):
- im Internet surfen
- E-Mails lesen und schreiben
- Dokumente bearbeiten
- Blogs schreiben (😉)
- Finanzen verwalten
- Videos schauen
- kreativ sein (Einladungskarten entwerfen, Videos schneiden, …)
- die Familienfotos verwalten und Fotobücher erstellen
- Spielen

Das Thinkpad T410, auf dem meine ersten Testinstallationen stattfanden, kann noch viele dieser Anwendungsfälle ohne Probleme abdecken und das Modell ist 2010 von IBM veröffentlicht worden! Die Hardware ist:

Prozessor
: Intel Core i5-540M (2.53GHz/3.07GHz Turbo)

Arbeitsspeicher
: 4 GB DDR3-1066

Grafikkarte
: Eingebaute Intel HD

Display
: 14.1" LED Display mit WXGA (1280x800) Auflösung.

Festplatte
: 250 GB SSD (wurde nachträglich eingebaut)

Installiert habe ich ein aktuelles Linux Mint. [Dessen Anforderungen](https://www.linuxmint.com/faq.php#collapse-103) sind im Gegensatz [der von Windows 11](https://support.microsoft.com/de-de/windows/windows-11-systemanforderungen-86c11283-ea52-4782-9efd-7674389a7ba3) etwas bescheidener:

|                     | Linux Mint                 | Windows 11                                           |
| :------------------ | :------------------------- | :--------------------------------------------------- |
| Arbeitsspeicher     | 2 GB (4 GB sind empfohlen) | 4 GB                                                 |
| Prozessor           | keine Mindestanforderung   | 1 GHz mit 2 Kernen                                   |
| Festplattenspeicher | 20 GB (100 GB empfohlen)   | 64 GB                                                |
| Monitor             | Auflösung von 1024×768     | Auflösung von 1024×768                               |
| Sonstiges           |                            | TPM, Secure Boot, Microsoft Konto, Internetanschluss |

Nach ein paar ersten Tests kann man zusammenfassen, dass die meisten Anforderungsfälle abgedeckt werden.

- im Internet surfen ✅
- E-Mails lesen und schreiben ✅
- Dokumente bearbeiten ✅
- Blogs schreiben (😉) ✅
- Finanzen verwalten (mit etwas Aufwand ✅)
- Videos schauen (je nach Hardware ✅. Der T410 schafft 720p, also DVD-Auflösung ohne Probleme)
- kreativ sein (Einladungskarten entwerfen, Videos schneiden, …) (werde ich aktualisieren, sobald ich es getestet habe)
- die Familienfotos verwalten und Fotobücher erstellen (werde ich aktualisieren, sobald ich es getestet habe)
- Spielen (✅ kommt auf das Alter des Spiels an)

### Im Internet surfen

Webseiten aufrufen ist inzwischen selbst mit dem kleinsten Computer im Haus kein Problem mehr.

### E-Mails lesen

Als eine der ältesten Technologien des Internets ist auch das Lesen von Mails keine technische Herausforderung mehr. Man sollte sich aber Gedanken darüber machen, mit welcher Software man die Mails lesen möchte. Bisher nutzt die Dame des Hauses Thunderbird und ist damit zufrieden. Mehr Informationen zu den verschiedenen Programmen gibt es in einem gesonderten Artikel zum Thema „[[Ich möchte meine E-Mails lesen]]“.

### Videos schauen

Wir haben keinen Fernseher oder Beamer und der externe Monitor steht im Arbeitszimmer. Also schauen wir die Sendung mit der Maus, Netflix oder Ähnliches auf unseren Rechnern.

### Spielen

Dieser Wunsch geht vor allem von den Kindern aus. Minecraft, Worms W.D.M., Supertux, Commander Keen und Ähnliches. Details zum Thema gibt es im Artikel [[Ich möchte Spiele spielen]].

### Finanzen verwalten

Wir wollen unsere Steuererklärung abgeben, unsere Konten verwalten und eventuell die Übersicht über unsere Geldanlagen behalten.

### Blogs schreiben

😉

### Die Familienfotos verwalten und Fotobücher erstellen

Unsere Fotobibliothek zählt inzwischen über 25.000 Fotos, die irgendwie sortiert, durchsucht und auch gelegentlich präsentiert werden wollen. Bisher findet die zentrale Verwaltung der Fotos vor allem über meinen Mac und die recht einfach zu bedienende App „Fotos“ statt. Das hat den Nachteil, dass nur mein Rechner auf die Fotos zugreifen kann und wir keine gemeinsame Ablage haben. 

Private Fotos in eine der vielen Cloud-Dienste hochzuladen, kommt für uns nicht infrage.
