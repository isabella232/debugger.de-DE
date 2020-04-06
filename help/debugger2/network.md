---
description: 'null'
keywords: debugger;experience cloud debugger extension;chrome;extension;network;information
seo-description: 'null'
seo-title: Netzwerkinformationen
title: Netzwerkinformationen
uuid: 839686c9-6e4f-4661-acf6-150ea24dc47f
translation-type: tm+mt
source-git-commit: 3dc1876c0516b7a81f68a207c6a1651bc95b17ab

---


# Netzwerk {#network}

>[!IMPORTANT]
>
>Adobe Experience Cloud Debugger 2.0 ist aktuell in der Betaversion verfügbar. Die Dokumentation und Funktionalität können sich ändern.

Um Netzwerkinformationen anzuzeigen, klicken Sie auf **[!UICONTROL Network]**.

Auf dem Bildschirm „Network“ werden Informationen zu allen Aufrufen zusammengefasst, die Adobe Experience Cloud-Lösungen auf der jeweiligen Seite durchführen – sortiert von links nach rechts. Standardparameter werden automatisch mit benutzerfreundlichen Namen versehen und so angeordnet, dass gemeinsame Parameter derselben Rolle zusammenstehen.

![](assets/network.jpg)

Auf diesem Bildschirm können Schlüsselwertpaare von Treffern verglichen werden. Hier können Sie außerdem überprüfen, ob die für Integrationen verwendeten Parameter, wie z. B. die Experience Cloud-Besucher-ID oder die Ergänzende-Daten-ID, für alle Integrationen einheitlich sind.

>[!NOTE]
>
>Aktuell werden nicht alle innerhalb der Lösungsaufrufe übergebenen Parameter auf dem Netzwerkbildschirm angezeigt (z. B. Analytics-Kontextvariablen, benutzerdefinierte Target-Parameter oder die Kunden-IDs des Experience Cloud ID-Dienstes).

Um die entsprechenden Informationen einer Lösung anzuzeigen, wählen Sie die gewünschte Lösung aus der Liste im linken Navigationsbereich aus. Im folgenden Beispiel wird der Filter so gewählt, dass nur Analytics angezeigt wird:

![](assets/network-analytics.jpg)

Wenn Sie wieder alle Lösungen anzeigen möchten, klicken Sie auf **[!UICONTROL Network]**

Klicken Sie auf ein Element in der Netzwerkansicht, um es zu erweitern. In der erweiterten Ansicht können Sie die angezeigten Informationen in die Zwischenablage kopieren.

![](assets/network-expand.jpg)

<!--Use the icon at the top of each column to copy the server call URL to your clipboard, where you can paste it into another document for reference or debugging purposes.

![](assets/copy.jpg)-->

Um die Liste zu löschen, klicken Sie auf **[!UICONTROL Remove Events]**.

Um eine Excel-Datei mit den auf diesem Bildschirm angezeigten Informationen herunterzuladen, klicken Sie auf **[!UICONTROL Download]**.