---
title: "Die Kommmandozeile und du"
date: 2020-11-18T16:24:58+01:00
draft: false
---
## Die Kommandozeile und du

Wenn du im Kino eine Film siehst, in dem Computerspezialisten irgendetwas Geheimnisvolles erledigen, klicken sie meist nicht mit der Maus herum, sondern arbeiten mit Fenstern mit vielen Textausgaben, die am Bildschirm durchlaufen, nachdem sie kryptische Kommandos eingegeben haben. Das sieht spektakulär und kompliziert aus. Im echten Leben ist es meist nicht so geheimnisvoll. Die durchlaufenden Texte sind meist Statusmeldungen von Systemen und das Tastaturgeklapper kommt von der Eingabe von Befehle auf der so genannten Kommandozeile ein, wodurch die Profis ein Anwendungsprogramm oder eine bestimmte Datenverarbeitung starten.

Wieso gibt es überhaupt noch Kommondozeilen? Ist nicht die Arbeit mit der Maus viel einfacher und effizienter?  Programme mit grafischen Benutzeroberflächen sind  erst einmal intuitiver zu bedienen. Wer aber viele verschiedene Aufgaben durchführen muss und zudem viel schreibt, wird feststellen, dass es viel Zeit kostet, die Hände von der Tastatur zu nehmen und mit der Maus Aktionen durchzuführen. Und wenn zu viele Fenster verschiedener Apps geöffnet sind, wird es schnell unübersichtlich. 

Daher benutzen viele Software-Arbeiter die Kommandozeile. Ein Befehl ist schnell getippt und die Liste vergangener Aktionen kann schnell abgerufen und erneut genutzt werden. Man erreicht alle Kommandos von der selben Stelle und kann bei einem geteilten Bildschirm schnell hin und her wechseln. Vielleicht am allerwichtigsten sind aber zwei weitere Eigenschaften: 

1. Kommandos lassen sich verknüpfen. Die Ausgabe eines Programms kann direkt als Eingabe des nächsten Programms genutzt werden und so können ganze Workflows auf einer Zeile ablaufen. Diese Pipeline-Verarbeitung trifft man vor allem auf Linuxsystemen, die heute einen Großteil der Cloud-Computer ausmachen.

```
tr -cs A-Za-z ' ' | tr A-Z a-z | sort | uniq -c | sort -rn | sed ${1}q 
```

2. Kommandos kann man nicht nur auf der Kommandozeile aufrufen, sondern in einer Textdatei sammeln und als Script immer wieder ablaufen lassen. so entstehen ganz einfach mächtige Programme, die viele Aufgaben automatisieren können - ähnlich wie Office-Makros, nur viel klarer strukturierbar.

Mit diesen Konzepten ist es in den letzten 50 Jahren gelungen, unsere weltumfassende digitale Vernetzung aufzubauen und weiterzuentwickeln. Auch deine Redaktionsaufgaben kannst du mit Kenntnissen aus diesem Bereich besser, einfacher und schneller erledigen. Nur Mut, es ist einfacher als es zunächst aussieht!

> "Knowledge of these tools is perhaps the main dividing line between “technical” and “non-technical” people (or, to put it in magical terms, between magicians and Muggles)" -- Michael Hartl

Dieses Zitat kommt aus dem Selbstlern-Text "Learn Enough Command Line to be Dangerous", der zwar leider nicht kostenfrei zugänglich ist, dessen offene erste Kapitel jedoch einen guten Einstieg in das Thema Kommoandozeile geben.

    Tipp: Wenn ihr einen Windows-Rechner habt, installiert euch git bash. Das ist eine Kommondozeilen-App, die viele Linux-Befehle ohne großen Aufwand auch auf Windows-Rechnern zur Verfügung stellt. Die Windows-Tools "cmd" oder "Powershell" sind eher Exoten im Bereich der Kommandozeilen.




