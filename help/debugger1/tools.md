---
description: Bildschirm der Experience Cloud Debugger-Werkzeuge
keywords: debugger;experience cloud debugger extension;chrome;extension;tools;dtm;target
seo-description: Bildschirm der Experience Cloud Debugger-Werkzeuge
seo-title: Werkzeuge
title: Werkzeuge
uuid: ea3fe1ea-e936-4c5a-8a43-b830d1b75038
translation-type: tm+mt
source-git-commit: e5f85bb78ad818d3507ca48eee27bb1e44f4e1a7
workflow-type: tm+mt
source-wordcount: '392'
ht-degree: 92%

---


# Tools {#tools}

Auf dem Bildschirm „Tools“ können Sie verschiedene Tools für die installierte Lösung (de-)aktivieren. Sie können beispielsweise Informationen aus dem Target-Konsolen-Debugging aktivieren oder die DTM-Staging-Bibliothek verwenden. Diese Tools sind nur verfügbar, wenn Target und DTM auf Ihrer Seite installiert sind.

![](assets/tools.jpg)

Sie können Adobe Experience Platform Launch oder DTM auf einer beliebigen Seite dynamisch einfügen, um etwas auf einer Seite zu testen, auf der kein Plattformstart oder DTM installiert ist. Klicken Sie auf das Symbol **[!UICONTROL Embed Code]**, geben Sie Ihren [Einbettungscode](https://docs.adobe.com/content/help/de-DE/dtm/using/client-side/deployment.html) ein und klicken Sie auf **[!UICONTROL Save]**.

![](assets/tools-embedcode.jpg)

## DTM-Informationen {#section-c3d43040440449e5a050170843a600b7}

<table id="table_04625C3319134E169A35DB74C1D1FB31"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Tool </th> 
   <th colname="col2" class="entry"> Beschreibung </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p> DTM Console Logging </p> </td> 
   <td colname="col2"> <p>Dieses Tool zeigt DTM-spezifische Debugging-Informationen in der Browserkonsole an. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Staging-Bibliothek verwenden </p> </td> 
   <td colname="col2"> <p>Dieses Tool verwendet die Staging-Bibliothek für DTM-Debugging-Informationen. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>DTM deaktivieren </p> </td> 
   <td colname="col2"> <p>Dieses Tool blockiert die Überprüfung von DTM-Informationen. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> DTM dynamisch einfügen </p> </td> 
   <td colname="col2"> <p> Dieses Tool fügt DTM-Code auf Ihrer Seite ein. Verwenden Sie den Einbettungscode-Editor, um den eingefügten Code zu bearbeiten. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Target-Informationen {#section-31090d95f50e455692b672c26e6a2051}

<table id="table_A71D269B49F4417599EBACA44D5CCF4F"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Tool </th> 
   <th colname="col2" class="entry"> Beschreibung </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Target-Konsolenprotokollierung </p> </td> 
   <td colname="col2"> <p>Dieses Tool zeigt Target-spezifische Debugging-Informationen in der Browserkonsole an, die allesamt mit dem Präfix <span class="codeph">AT:</span> beginnen. Hierzu wird Ihrem Browser ein Cookie namens <span class="codeph"> mboxDebug=true</span> hinzugefügt. Zu diesem Zeitpunkt werden die Konsoleninformationen nicht auf dem Debugger-Bildschirm „Logs“, sondern in der browsernativen Debugging-Konsole angezeigt. </p> <p> Dieses Tool erfordert at.js-Version 0.9.6 oder höher. Wenn Sie eine ältere Version von at.js verwenden, können Sie Ihrer URL den Parameter <span class="codeph">?mboxDebug=true</span> hinzufügen, um die Konsolenprotokollierung zu aktivieren. Wenn Sie mbox.js verwenden, können Sie den Parameter <span class="codeph">?_AT_Debug=console</span> hinzufügen, um die Konsolenprotokollierung beschränkt auf VEC-Aktivitäten (Visual Experience Composer) zu aktivieren. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Aktivieren von Mbox Trace </p> </td> 
   <td colname="col2"> <p>Dieses Tool fügt ausführliche Informationen zu Target-Antworten hinzu, die daraufhin auf dem Debugger-Bildschirm <span class="uicontrol">Target &gt; Mbox Trace</span> angezeigt werden können. </p> <p> Sie müssen in einem der Chrome-Tabs bei Experience Cloud angemeldet sein, um dieses Tool zu aktivieren. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Target deaktivieren </p> </td> 
   <td colname="col2"> <p>Dieses Tool deaktiviert alle Target-Anfragen, indem Ihrem Browser ein Cookie namens <span class="codeph"> mboxDisable=true</span> hinzugefügt wird. </p> <p> Dieses Tool erfordert at.js-Version 0.9.6 oder höher. Wenn Sie eine ältere Version verwenden, können Sie Ihrer URL den Parameter <span class="codeph">?mboxDisable=true</span> hinzufügen, um Mboxes zu deaktivieren. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Mbox-Highlight </p> </td> 
   <td colname="col2"> <p> Dieses Tool zeichnet eine rote Markierung um veraltete Zeilenumbruch-Mboxes. </p> </td> 
  </tr> 
 </tbody> 
</table>

Im folgenden Video wird die Verwendung der Debugger-Erweiterung mit Adobe Target erläutert.

>[!VIDEO](https://video.tv.adobe.com/v/23115t2/)
