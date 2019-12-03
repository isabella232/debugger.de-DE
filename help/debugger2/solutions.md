---
description: Verwenden der Lösungsregisterkarten im Adobe Debugger
keywords: debugger;experience cloud debugger extension;chrome;extension;summary;clear;requests;solutions;solution;information;analytics;target;audience manager;media optimizer;amo;id service
seo-description: Verwenden der Lösungsregisterkarten im Adobe Debugger
seo-title: Lösungsregisterkarten im Adobe Debugger
title: Lösungsregisterkarten
uuid: 5e999ef2-6399-4ab5-a841-3a839d081728
translation-type: tm+mt
source-git-commit: b9147536b8312599dd3144cac31dea9f0f1c3625

---


# Lösungsregisterkarten {#solution-tabs}

Klicken Sie auf die Lösungsregisterkarten, um die Ergebnisse für bestimmte Adobe Experience Cloud-Lösungen anzuzeigen.

## Analytics {#section-f71dfcc22bb44c86bec328491606a482}

Die Analytics-Registerkarte enthält Informationen zu Ihrer [Analytics](https://experiencecloud.adobe.com/resources/help/en_US/reference/)-Implementierung.

**Hits**

Standardmäßig werden alle Serveraufrufe derselben Report Suite reduziert.

![](assets/analytics-hits.jpg)

**Download:** Laden Sie Informationen zu allen angezeigten Report Suites als Excel-Tabelle herunter.

**Clear All Requests:** Entfernen Sie alle angezeigten Anfragen aus der Analytics-Ansicht. Nachdem Sie die Anfragen gelöscht haben, werden neue Anfragen angezeigt, sobald sie auftreten.

Klicken Sie auf die Report Suite ID, um die Ansicht zu erweitern:

![](assets/analytics-hits-expand.jpg)

Auf diesem Bildschirm werden alle Anfragen angezeigt, seit der Debugger zum letzten Mal geöffnet oder die Anfragen gelöscht wurden. Die Standardparameter werden automatisch benutzerfreundlichen Namen zugeordnet. [Props und eVars](https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/props_eVars.html) können eigenen benutzerfreundlichen Namen zugeordnet werden (z. B. „Benutzertyp“ für „prop1“), wenn Sie sich über die Funktion „Link Analytics“ authentifizieren (siehe unten). Anfragen werden von links nach rechts sortiert.

**Download:** Speichern Sie alle Anfragen an die Report Suite als Excel-Tabelle.

**Clear Requests:** Entfernen Sie alle Anfragen an diese Report Suite. Neue Anfragen werden angezeigt, sobald sie auftreten.

**Linked Accounts (veraltet)**

Klicken Sie auf **[!UICONTROL Link Account]** und geben Sie die angeforderten Informationen ein, um ein Analytics-Konto mit dem Debugger zu verknüpfen.

>[!NOTE]
>
>Diese Funktion wird derzeit nur für alte Analytics-Anmeldedaten unterstützt.

![](assets/analytics-link-account.jpg)

**Retrieve Post-Processed Hits**

Aktivieren Sie die Option „Retrieve Post-Processed Hits“, wenn Sie die Werte zu Analytics-Treffern anzeigen möchten, nachdem die Verarbeitungsregeln ausgeführt wurden. Sie müssen bei Adobe Experience Cloud angemeldet seit, um diese Funktion zu nutzen.

Wenn die Option aktiviert ist, werden die Debugging-Parameter zu Ihren Analytics-Anfragen hinzugefügt. Treffer werden weiterhin genau wie andere Treffer verarbeitet. Der Debugger ruft bei der Analytics-Debugging-API für alle Treffer, die über eine ursprüngliche Treffer-ID verfügen, die Werte nach der Verarbeitung ab. Treffer nach der Verarbeitung sind lila hinterlegt und werden neben dem ursprünglichen Treffer angezeigt.

Bei den meisten Analytics-Implementierungen sind die Informationen nach Ausführen der Verarbeitungsregeln innerhalb weniger Minuten verfügbar. Die A4T-Implementierung (Analytics for Target) erfordert deutlich mehr Zeit.

## Target {#section-988873ba5ede4317953193bd7ac5474c}

Verwenden Sie die Target-Registerkarte, um [Target](https://docs.adobe.com/content/help/en/target/using/target-home.html)-Anfragen oder [Mbox Trace](https://docs.adobe.com/content/help/en/target/using/activities/troubleshoot-activities/content-trouble.html)-Antwortdetails anzuzeigen.

Klicken Sie auf **[!UICONTROL Requests]** und erweitern Sie die Umgebung, um Informationen zu Target anzuzeigen.

![](assets/target-requests.jpg)

Click **[!UICONTROL Clear All Requests]** to remove the currently displayed requests. Neue Anfragen werden angezeigt, sobald sie auftreten.

Sie können auch den Target-Filter verwenden, um [Mbox Trace für Target-Debugging zu aktivieren](https://docs.adobe.com/content/help/en/target/using/activities/troubleshoot-activities/content-trouble.html).

Sie müssen auf einem Chrome-Tab bei Experience Cloud angemeldet sein, um Mbox Trace zu aktivieren. Einmal aktiviert, wird Ihr Adobe ID-Benutzername angezeigt. Erweitern Sie Ihren Benutzernamen, um die Target-Kundencodes anzuzeigen, die den Ihnen verfügbaren Experience Cloud-Organisationen zugeordnet sind. Klicken Sie auf den Kundencode, für den Sie Mbox Trace aktivieren möchten, und überprüfen Sie, ob das grüne Häkchen angezeigt wird. Hierdurch werden alle Target-Anfragen mit Mbox Trace-Informationen angezeigt, gruppiert nach Kundencode. Um die Mbox Trace-Informationen abzurufen, erweitern Sie die Anfrage. Hierdurch werden folgende Registerkarten angezeigt:

* [Activities](https://docs.adobe.com/content/help/en/target/using/activities/activities.html): Die Registerkarte „Activities“ zeigt alle Aktivitäten an, die dem Target-Anfragenamen zugeordnet sind, unabhängig davon, ob Sie sich für die Aktivität qualifizieren. „Matched Activities“ sind Aktivitäten, für die Sie sich qualifizieren und deren Angebote in der Antwort bereitgestellt wurden. Sie können den Aktivitätsnamen erweitern, um zu ermitteln, in welchem Erlebnis Sie sich befinden und durch welche Zielgruppen und Targeting-Bedingungen Sie sich für die Aktivität qualifiziert haben. „Evaluated Activities“ sind alle bewerteten Aktivitäten, unabhängig davon, ob Sie sich qualifiziert haben. Um herauszufinden, warum Sie sich nicht für eine Aktivität qualifiziert haben, die bewertet wurde, aber keine Übereinstimmung ergeben hat, erweitern Sie den Aktivitätsnamen und überprüfen Sie den Abschnitt „Unmatched Audiences“.

* Anfrage

   Die Anfragenregisterkarte von [Mbox Trace](https://docs.adobe.com/content/help/en/target/using/activities/troubleshoot-activities/content-trouble.html) ähnelt der Haupt-Anfragenregisterkarte. Sie können alle von der Target-Anfrage übergebenen Parameter anzeigen, zusätzlich zu den Anfrageheadern.
* Profil

   Erweitern Sie den Abschnitt „Profile Snapshot“, um die [Profilinformationen](https://docs.adobe.com/content/help/en/target/using/audiences/visitor-profiles/variables-profiles-parameters-methods.html) anzuzeigen, die zu Ihnen als Besucher in der Target-Profildatenbank gespeichert sind. Alle All In-Mbox- und Skriptprofile werden hier angezeigt – neben einigen Systemprofilen. Die Statusspalte zeigt an, welche Profile im Rahmen dieser Anfrage geändert wurden, und enthält die jeweiligen Werte vor und nach Eingang der Anfrage im Profilsystem.
* Audience Manager

   Die Abschnitte „segmentIds“ und „cachedSegmentIds“ zeigen die IDs der [Zielgruppen](https://docs.adobe.com/content/help/en/target/using/audiences/target.html) an, die von der Experience Cloud für Target freigegeben werden und für die Sie sich qualifiziert haben. Hierbei kann es sich um Zielgruppen handeln, die in Audience Manager, Analytics oder dem Audience Builder im Core Service „Personen“ erstellt wurden. Diese IDs sind in der Audience Manager-Benutzeroberfläche verfügbar, um den Zielgruppennamen zu ermitteln.

Im folgenden Video werden die allgemeinen Target-Funktionen vorgestellt:

>[!VIDEO](https://video.tv.adobe.com/v/23115t2/?captions=ger)

Im folgenden Video wird Mbox Trace vorgestellt:

>[!VIDEO](https://video.tv.adobe.com/v/23113t2/?captions=ger)

## Audience Manager {#section-1d4484f8b46f457f859ba88039a9a585}

Über die Registerkarte [Audience Manager](https://experiencecloud.adobe.com/resources/help/en_US/aam/) können Sie Details von [Ereignissen](https://experiencecloud.adobe.com/resources/help/en_US/aam/dcs-event-calls.html) anzeigen. Klicken Sie auf eine Organisation, um sie zu erweitern und detaillierte Informationen anzuzeigen.

![](assets/audience-manager.jpg)

Click **[!UICONTROL Clear All Events]** to reset the displayed information. Neue Ereignisse werden angezeigt, sobald sie auftreten.

**ID Sync**

Die ID-Synchronisierung ist der erste Schritt bei der Verarbeitung eingehender asynchroner Datenübertragungen. In diesem Schritt gleichen Audience Manager und Anbieter IDs für den jeweiligen Sitebesucher ab.

![](assets/aam-idsync.jpg)

Weitere Informationen hierzu finden Sie unter [ID-Synchronisierung für eingehende Datenübertragungen](https://experiencecloud.adobe.com/resources/help/en_US/aam/c_id_sync_in.html) in der Audience Manager-Produktdokumentation.

## Advertising Cloud {#section-ee80a9c509f2462c89c1e5bd8d05d7c8}

Über die Registerkarte „Advertising Cloud“ können Sie Advertising Cloud-Anfragen anzeigen.

Klicken Sie auf **[!UICONTROL Requests]** und erweitern Sie die Umgebung, um Informationen zu Advertising Cloud anzuzeigen.

Click **[!UICONTROL Clear All Requests]** to remove the currently displayed requests. Neue Anfragen werden angezeigt, sobald sie auftreten.

## Experience Cloud ID-Dienst {#section-a96c32f8e63a4991abb296f6e8ea01cf}

Über die Registerkarte „Experience Cloud ID Service“ können Sie [Experience Cloud ID-Dienst](https://experiencecloud.adobe.com/resources/help/en_US/mcvid/)-Anfragen anzeigen.

Klicken Sie auf **[!UICONTROL Requests]** und erweitern Sie die Umgebung, um Informationen zum Experience Cloud ID-Dienst anzuzeigen.

Click **[!UICONTROL Clear All Requests]** to remove the currently displayed requests. Neue Anfragen werden angezeigt, sobald sie auftreten.
