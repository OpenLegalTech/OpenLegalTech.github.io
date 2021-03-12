---
layout: post
title:  "Meine Einreichung beim Prototype Fund"
date:   2020-09-30 15:07:00 +0100
categories: update
---
Am 30.09.2020 habe ich die Idee zu Open Legal Tech beim [Prototype Fund](https://prototypefund.de/) eingereicht. Aus Transparenzgründen aber auch als Hilfestellung für zukünftige Antragssteller*innen veröffentliche hier meinen Einreichung.

## GitHub/BitBucket/etc. Accounts: ##
https://github.com/MagdaN

## An welchen Open-Source Projekten hast Du/habt Ihr bisher gearbeitet? ##
- Adhocracy: [https://github.com/liqd/adhocracy-plus](https://github.com/liqd/adhocracy-plus)
- meinBerlin: [https://github.com/liqd/a4-meinberlin](https://github.com/liqd/a4-meinberlin)
- FragDenStaat: [https://github.com/okfde/fragdenstaat_de](https://github.com/okfde/fragdenstaat_de)



## Bewerbt Ihr Euch als Team um die Förderung? ##
nein

## Namen der Teammitglieder: ##
Magdalena Noffke - selbstständige Softwareentwicklerin

## Projekttitel: ##
Open Legal Tech

## Ordne das Projekt einem Bereich zu: ##
Civic Tech


## Beschreibe Dein Projekt kurz. ##
Im Rahmen des Projektes Open Legal Tech wird ein System entwickelt, das Menschen im Umgang mit deutschen Verwaltungen und Behörden unterstützt. Grundidee ist, dass Nutzer*innen des Systems Behördenbriefe oder andere staatliche Texte hochladen können und das System auf Basis des Textes sowie weiterer Fragen entsprechende Antwortmöglichkeiten oder sonstige mögliche Reaktionen empfiehlt. Die Empfehlungen können direkt über ein Interface eingesehen werden oder per API in andere Systeme integriert werden. Die Empfehlungen werden auf Basis von Regeln generiert, die zuvor über ein spezielles Interface erstellt wurden.

## Welches gesellschaftliche Problem willst Du mit dem Projekt lösen? ##
Kommunikation von Behörden mit Bürger\*innen orientiert sich regelmäßig an Erfordernissen der Verwaltungen, nicht an den Bürger\*innen selbst. Dies führt dazu, dass beispielsweise Bescheide von Arbeitsämtern oder Ordnungsämtern für die Betroffenen häufig unverständlich und ohne Jura-Studium kaum zu beantworten sind. Behördenkommunikation muss für die Öffentlichkeit zugänglicher sein.

## Wie willst Du Dein Projekt technisch umsetzen? ##
Das Projekt wird als regelbasierter Chatbot umgesetzt. Das heißt in einer Datenbank werden  Regeln in einer Baumstruktur gespeichert auf Basis dessen das System dann die Empfehlungen generiert. Das funktioniert dann wie folgt: Ein Brief wird als PDF hochgeladen der Text mittels OCR (z.B. mit Rückgriff auf das vom PTF geförderte Projekt “Deutsche Dokumente Digitalisieren”) extrahiert und mittels Natural Language Processing (NLP) ein Startpunkt der in der Datenbank ermittelt. Anhand der angelegten Regeln wird entweder direkt eine Empfehlung generiert oder das System stellt weitere Fragen und kann dann auf Basis der von den Nutzer*innen gegebenen Antworten eine Empfehlung geben.
Die Software kann als Web Service selbst gehostet werden und mit den entsprechenden Daten befüllt werden. Der Softwarecode wird gut dokumentiert als Open-Source-Software auf Github, unter einer freien Lizenz (z.B. MIT) verfügbar sein. Zudem wird mit Python, Django und react auf weitverbreitete, gut dokumentierte Technologien aufgesetzt.

## Welche ähnlichen Lösungen gibt es schon, und was wird dein Projekt anders bzw. besser machen? ##
Die Produkte im Bereich Legal Tech sind in den vergangenen Jahren stark gewachsen. Sie sind allerdings größtenteils profitorientiert und nicht offen. Eine Ausnahme ist das Projekt Sanktionsfrei, das sehr spezifisch für Hartz IV-Bescheide Antworten vorfertigt. Open Legal Tech soll eine technische Basis schaffen, auf der verschiedene Initiativen ihre gemeinnützigen Angebote aufbauen können.

## Wer ist die Zielgruppe, und wie soll Dein Tool sie erreichen? ##
Zielgruppe sind Initiativen, die für ihre gemeinnützigen Angebote technische Unterstützung suchen. Dazu gehören beispielsweise ehrenamtliche Beratungen von Geflüchteten, Sozialberatungen und Verbraucherzentralen. Open Legal Tech kann ihnen vor allem dann weiterhelfen, wenn Betroffene in den jeweiligen Bereichen oft gleichlautende standardisierte Briefe erhalten, auf die regelmäßig ähnliche Antworten erfolgen sollen.

## Hast Du schon an der Idee gearbeitet? Wenn ja, beschreibe kurz den aktuellen Stand und erkläre die Neuerung. ##
Ich habe bisher das Konzept verfasst und den Markt der vorhandenen Legal-Tech-Lösungen gesichtet. Zudem habe ich Kontakt zu verschiedenen Jurist*innen, die an dem Thema sehr interessiert sind und mir Daten, also z.B. relevante Behörden-Dokumente als auch juristisches Know-how zur Erstellung erster Empfehlungen zur Verfügung stellen wollen und bereit sind, die Software regelmäßig zu testen.

## Link zum bestehenden Projekt (falls vorhanden): ##
-

##  Wie viele Stunden willst Du (bzw. will das Team) insgesamt in den 6 Monaten Förderzeitraum an der Umsetzung arbeiten?* ##
700

## Skizziere kurz die wichtigsten Meilensteine, die Du (bzw. das Team) im Förderzeitraum umsetzen willst. ##
[Monat 2] Bis Anfang Mai wird es darum gehen, gemeinsam mit den Jurist\*innen, Daten zu sammeln und geeignete erste Use Cases zu erstellen. Zudem wird geplant, wie die verschiedenen User Interfaces gestaltet werden.
[Monat 5] Ab Mai startet die Entwicklung des Prototyps. Dies passiert in einem iterativen Prozess d.h. Zwischenergebnisse werden in kurzen Abständen Nutzer\*innen präsentiert, Feedback aufgenommen und ggf. eingearbeitet. Die technisch Abbildung der ersten Uses Cases ist nun - Ende Juli - möglich.
[Monat 6] Der verbleibende Monat wird dazu genutzt, die Software so zu dokumentieren, dass sie einfach zu installieren ist und erweitert werden kann.


## Wenn meine Projektidee nicht gefördert wird, darf sie trotzdem auf prototypefund.de und in wissenschaftlichen Publikationen rund um das Programm veröffentlicht werden? ##
ja
