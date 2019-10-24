---
description: Verwenden der Registerkarten "Lösung"im Adobe Debugger
keywords: Debugger;Erweiterung des Experience Cloud-Debuggers;Chrome;Erweiterung;Zusammenfassung;clear;Anforderungen;Lösungen;Lösung;Informationen;Analyse;Ziel;Zielgruppen-Manager;Medienoptimierung;AMO;ID-Dienst
seo-description: Verwenden der Registerkarten "Lösung"im Adobe Debugger
seo-title: Lösungsregisterkarten in Adobe Debugger
title: Lösungsregisterkarten
uuid: 5e999ef2-6399-4ab5-a841-3a839d081728
translation-type: tm+mt
source-git-commit: 3fd50cde86f0dfc5f66d8faf63112adf24beeac0

---


# Lösungsregisterkarten{#solution-tabs}

Klicken Sie auf die Registerkarte Lösung, um die Ergebnisse für bestimmte Adobe Experience Cloud-Lösungen anzuzeigen.

## Analytics {#section-f71dfcc22bb44c86bec328491606a482}

Auf der Registerkarte "Analyse"finden Sie Informationen zu Ihrer [Analytics](https://experiencecloud.adobe.com/resources/help/en_US/reference/) -Implementierung.

**Hits**

Standardmäßig werden alle Serveraufrufe, die an dieselbe Report Suite gesendet werden, reduziert.

![](assets/analytics-hits.jpg)

**** Herunterladen: Laden Sie Informationen zu allen angezeigten Report Suites als Excel-Tabelle herunter.

**** Alle Anforderungen löschen: Entfernen Sie alle angezeigten Anforderungen aus der Analytics-Ansicht. Nach dem Löschen der Anforderungen werden neue Anforderungen angezeigt, sobald sie auftreten.

Klicken Sie auf die Report Suite-ID, um die Ansicht zu erweitern:

![](assets/analytics-hits-expand.jpg)

In diesem Bildschirm werden alle Anforderungen angezeigt, seit der Debugger geöffnet oder die Anforderungen gelöscht wurden. Standardparameter werden Anzeigenamen automatisch zugeordnet. [Eigenschafts- und eVar](https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/props_eVars.html) -Variablen können Ihren benutzerspezifischen Anzeigenamen zugeordnet werden (z. B. könnte "prop1"als "Benutzertyp"angezeigt werden), wenn Sie sich mit der Funktion "Link-Analyse"authentifizieren (siehe unten). Anforderungen werden nacheinander von links nach rechts angezeigt.

**** Herunterladen: Speichern Sie alle an der Report Suite gestellten Anforderungen als Excel-Tabelle.

**** Anforderungen löschen: Entfernen Sie alle Anforderungen, die an diese Report Suite gesendet wurden. Neue Anforderungen werden sofort angezeigt.

**Verknüpfte Konten (alt)**

Klicken Sie auf **[!UICONTROL Link Account]** und geben Sie die angeforderten Informationen ein, um ein Analytics-Konto mit dem Debugger zu verknüpfen.

>[!NOTE]
>
>Diese Funktion wird derzeit nur für ältere Analytics-Benutzeranmeldedaten unterstützt.

![](assets/analytics-link-account.jpg)

**Abrufen von Treffern nach der Verarbeitung**

Aktivieren Sie die Option "Nach der Verarbeitung ausgeführte Treffer abrufen", wenn Sie die Werte für Analytics-Treffer nach Ausführung der Verarbeitungsregeln anzeigen möchten. Sie müssen bei Adobe Experience Cloud angemeldet sein, damit diese Funktion funktioniert.

Wenn diese Option aktiviert ist, wird Ihren Analytics-Anforderungen ein Debugging-Parameter hinzugefügt. Treffer werden weiterhin wie alle anderen Treffer verarbeitet. Der Debugger fragt die Analytics-Debugging-API ab, um Werte von Regeln für die Nachbearbeitung für Treffer abzurufen, die über eine ursprüngliche Treffer-ID verfügen. Nachbearbeitete Treffer haben einen violetten Hintergrund und werden neben dem ursprünglichen Treffer angezeigt.

Bei den meisten Analytics-Implementierungen sind die Informationen zu den Regeln nach der Verarbeitung innerhalb weniger Minuten verfügbar. Die Implementierung von Analytics for Target (A4T) dauert erheblich länger.

## Target {#section-988873ba5ede4317953193bd7ac5474c}

Auf der Registerkarte "Ziel"können Sie [Target](https://docs.adobe.com/content/help/en/target/using/target-home.html) -Anforderungen oder [Mbox Trace](https://docs.adobe.com/content/help/en/target/using/activities/troubleshoot-activities/content-trouble.html) -Antwortdetails anzeigen.

Klicken Sie auf **[!UICONTROL Requests]** und erweitern Sie dann die Umgebung, um Informationen zu Target anzuzeigen.

![](assets/target-requests.jpg)

Klicken Sie auf **[!UICONTROL Clear All Requests]** , um die aktuell angezeigten Anforderungen zu entfernen. Es werden weitere Anforderungen angezeigt, während sie gestellt werden.

Sie können auch den Target-Filter verwenden, um MBox Trace für die Zieldebuggung zu [aktivieren](https://docs.adobe.com/content/help/en/target/using/activities/troubleshoot-activities/content-trouble.html).

Sie müssen über eine offene Chrome-Registerkarte verfügen, die in der Experience Cloud authentifiziert ist, um Mbox Trace zu aktivieren. Nach der Aktivierung wird Ihr Adobe ID-Benutzername angezeigt. Erweitern Sie Ihren Benutzernamen, um die Target-Clientcodes anzuzeigen, die den Experience Cloud-Organisationen zugeordnet sind, auf die Sie Zugriff haben. Klicken Sie auf den Clientcode, für den Sie Mbox Trace aktivieren möchten, und bestätigen Sie, dass das grüne Häkchen angezeigt wird. Alle Target-Anforderungen mit Mbox-Trace-Informationen werden jetzt angezeigt, gruppiert nach Clientcode. Um die Mbox-Trace-Informationen zu untersuchen, erweitern Sie die Anforderung, um die Registerkarten anzuzeigen:

* [Aktivitäten](https://docs.adobe.com/content/help/en/target/using/activities/activities.html) Die Registerkarte "Aktivitäten"zeigt alle Aktivitäten an, die mit dem Target-Anforderungsnamen verbunden sind, unabhängig davon, ob Sie für die Aktivität qualifiziert sind. "Angepasste Aktivitäten"sind Aktivitäten, für die Sie qualifiziert sind und deren Angebote in der Antwort bereitgestellt wurden. Sie können den Aktivitätsnamen erweitern, um das Erlebnis zu bestätigen, in dem Sie sich befinden, und um zu bestätigen, welche Zielgruppen und Targeting-Bedingungen Sie für die Aktivität qualifiziert haben. "Evaluierte Aktivitäten"sind alle ausgewerteten Aktivitäten, unabhängig davon, ob Sie qualifiziert sind. Um zu beheben, warum Sie sich nicht für eine Aktivität qualifizieren, die "bewertet", aber nicht "Übereinstimmung"war, erweitern Sie den Aktivitätsnamen und lesen Sie den Abschnitt "Nicht übereinstimmende Zielgruppen".

* Anfrage

   Die Registerkarte "Anforderung"von [Mbox Trace](https://docs.adobe.com/content/help/en/target/using/activities/troubleshoot-activities/content-trouble.html) ähnelt der Registerkarte "Hauptanforderung". Sie können neben den Anforderungsheader alle von der Target-Anforderung weitergeleiteten Parameter anzeigen.
* Profil

   Erweitern Sie den Abschnitt "Profilüberblick", um [Profilinformationen](https://docs.adobe.com/content/help/en/target/using/audiences/visitor-profiles/variables-profiles-parameters-methods.html) anzuzeigen, die über Sie als Besucher in der Target-Profildatenbank gespeichert wurden. Alle In-mbox- und Skriptprofile sowie einige Systemprofile werden hier bereitgestellt. Die Spalte Status zeigt an, welche Profile innerhalb des Anwendungsbereichs dieser Anforderung geändert wurden, sowie deren Werte vor und nach der Anforderung im Profilsystem.
* Audience Manager

   Die Abschnitte "segmentIds"und "cachedSegmentIds"auf der Registerkarte "Audience Manager"enthalten die IDs von [Zielgruppen](https://docs.adobe.com/content/help/en/target/using/audiences/target.html) , die über Experience Cloud für Target freigegeben wurden und für die Sie sich qualifiziert haben. Dies können Zielgruppen sein, die in Audience Manager, Analytics oder im Audience Builder im People Core Service erstellt wurden. Diese IDs können in der Benutzeroberfläche von Audience Manager nachgeschlagen werden, um den Zielgruppennamen zu finden.

Das folgende Video zeigt die allgemeine Target-Funktion:

>[!VIDEO](https://video.tv.adobe.com/v/23115t2/?captions=ger)

Das folgende Video zeigt Mbox Trace:

>[!VIDEO](https://video.tv.adobe.com/v/23113t2/?captions=ger)

## Audience Manager {#section-1d4484f8b46f457f859ba88039a9a585}

Auf der Registerkarte [Audience Manager](https://experiencecloud.adobe.com/resources/help/en_US/aam/) können Sie Details zu [Ereignissen](https://experiencecloud.adobe.com/resources/help/en_US/aam/dcs-event-calls.html)anzeigen. Klicken Sie auf die Organisation, um sie zu erweitern und die Informationen anzuzeigen.

![](assets/audience-manager.jpg)

Klicken Sie auf **[!UICONTROL Clear All Events]** , um die angezeigten Informationen zurückzusetzen. Neue Ereignisse werden beim Auftreten angezeigt.

**ID-Synchronisierung**

Die ID-Synchronisierung ist der erste Schritt im Prozess der asynchronen Datenübertragung. In diesem Schritt vergleichen Audience Manager und der Anbieter IDs für die jeweiligen Site-Besucher und stimmen sie damit überein.

![](assets/aam-idsync.jpg)

Weitere Informationen finden Sie unter [ID-Synchronisierung für eingehende Datenübertragungen](https://experiencecloud.adobe.com/resources/help/en_US/aam/c_id_sync_in.html) in der Produktdokumentation zu Audience Manager.

## Advertising Cloud {#section-ee80a9c509f2462c89c1e5bd8d05d7c8}

Auf der Registerkarte "Advertising Cloud"können Sie Advertising Cloud-Anforderungen anzeigen.

Klicken Sie auf **[!UICONTROL Requests]** und erweitern Sie dann die Umgebung, um Informationen zur Advertising Cloud anzuzeigen.

Klicken Sie auf **[!UICONTROL Clear All Requests]** , um die aktuell angezeigten Anforderungen zu entfernen. Es werden weitere Anforderungen angezeigt, während sie gestellt werden.

## Experience Cloud ID-Dienst {#section-a96c32f8e63a4991abb296f6e8ea01cf}

Auf der Registerkarte "Experience Cloud ID-Dienst"können Sie [Experience Cloud ID-Dienstanforderungen](https://experiencecloud.adobe.com/resources/help/en_US/mcvid/) anzeigen.

Klicken Sie auf **[!UICONTROL Requests]** und erweitern Sie dann die Umgebung, um Informationen zum Experience Cloud ID-Dienst anzuzeigen.

Klicken Sie auf **[!UICONTROL Clear All Requests]** , um die aktuell angezeigten Anforderungen zu entfernen. Es werden weitere Anforderungen angezeigt, während sie gestellt werden.
