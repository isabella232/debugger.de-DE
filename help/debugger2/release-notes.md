---
title: Versionshinweise
description: Die neuesten Versionshinweise für Adobe Experience Platform Debugger.
keywords: Debugger;Experience Platform Debugger-Erweiterung;Chrome;Erweiterung;Versionshinweise
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
exl-id: 3eed44da-5f85-413e-a783-3a0df03a2baf
source-git-commit: a442fa56589003dad4ca9896ef601349fb93d280
workflow-type: tm+mt
source-wordcount: '287'
ht-degree: 91%

---

# Versionshinweise

## Version 1.3.0 – 28. Januar 2022

* Es wurde ein „Info über“-Link hinzugefügt, um die aktuelle Version und Hinweise anzuzeigen.
* Es wurde ein Umschalter hinzugefügt, um Nachbearbeitungstreffer für Analytics-Anfragen anzuzeigen. Der Umschalter ist im Analytics-Abschnitt verfügbar.
* Es wurde ein Remote-Debugging-Sitzungsfehler behoben, der auftrat, wenn die Sitzung außerhalb des Debuggers geschlossen wurde.
* Es wurde ein Fehler bei einer Fehlerbenachrichtigung behoben, der auf der Web SDK-Registerkarte für Edge-Transaktionen angezeigt wurde.
* Es wurden Adobe-Tags bei Warnungen für veraltete Seiten korrigiert, wenn der Debugger auf das _satellite-Objekt zugegriffen hat.
* Es wurden einige Fälle korrigiert, bei denen eine AppMeasurement-Instanz auf der Seite nicht gefunden wurde.
* Es wurde ein Problem mit der Seitenverbindung behoben, das beim ersten Öffnen des Debugger-Fensters auftrat.

## Version 1.2.0 – 26. Oktober 2021

* Es werden Ereignisse von allen Browser-Registerkarten in der Netzwerkansicht angezeigt. Um nur die Ereignisse von der aktuellen Registerkarte anzuzeigen, wählen Sie das Schlosssymbol unten rechts im Debugger aus.
* Das Branding wurde aktualisiert.

## Version 1.1.0 – 5. Oktober 2021

* Visualisierung für Remote-Debugging: Remote-Debugging-Ereignisse werden in einem visuellen Flussdiagramm unter „Adobe Experience Platform Web SDK > Edge-Transaktionen“ organisiert.
* Die auf der Seite verwendete Adobe Experience Platform Web SDK-IMS-Organisation muss mit der angemeldeten Organisation übereinstimmen, wenn eine neue Remote-Debugging-Sitzung gestartet wird.
* Es werden nur die Edge-Transaktionen für die Registerkarte „Verbunden“ angezeigt. Target-Trace-Protokolle sind weiterhin unter „Protokolle“ > „Edge“ verfügbar.
* Das Überschreiben separater Datenstrom-ID-Konfigurationen für jede Instanz des Adobe Experience Platform Web SDK auf der Seite ist jetzt zulässig. Ein Debugging-fähiger Umschalter wurde hinzugefügt.
* Es wurde ein Problem behoben, durch das das Adobe Target-Trace-Token nicht immer mit Remote-Debugging-Sitzungen für das Adobe Experience Platform Web SDK gesendet wurde.

## Version 1.0.0 – 5. Mai 2021

* Erste Hauptversion von Experience Platform Debugger. Soll Experience Cloud Debugger ersetzen.
