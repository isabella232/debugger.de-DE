---
description: 'null'
keywords: debugger;Experience Cloud-Debugger-Erweiterung;chrome;extension;tools;dtm;target
seo-description: 'null'
seo-title: Werkzeuge
title: Werkzeuge
uuid: ea3fe1ea-e936-4c5a-8a43-b830d1b75038
translation-type: tm+mt
source-git-commit: 3fd50cde86f0dfc5f66d8faf63112adf24beeac0

---


# Tools{#tools}

Im Anzeigebereich "Tools"können Sie verschiedene Werkzeuge für die installierte Lösung aktivieren oder deaktivieren. Sie können beispielsweise die Debug-Anweisungen für die Konsole in Target aktivieren oder die DTM-Staging-Bibliothek verwenden. Diese Tools sind nur verfügbar, wenn Target und DTM auf Ihrer Seite installiert sind.

![](assets/tools.jpg)

Sie können Launch oder DTM auf einer beliebigen Seite dynamisch einfügen, um etwas auf einer Seite zu testen, auf der nicht Launch oder DTM installiert ist. Klicken Sie auf das Symbol **[!UICONTROL Einbettungscode]** , geben Sie dann Ihren [Einbettungscode](https://experiencecloud.adobe.com/resources/help/en_US/dtm/deployment.html) ein und klicken Sie auf **[!UICONTROL Speichern]**.

![](assets/tools-embedcode.jpg)

## DTM-Informationen {#section-c3d43040440449e5a050170843a600b7}

<table id="table_04625C3319134E169A35DB74C1D1FB31"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Werkzeug </th> 
   <th colname="col2" class="entry"> Beschreibung </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p> DTM-Konsolenprotokollierung </p> </td> 
   <td colname="col2"> <p>Dieses Tool stellt DTM-spezifische Debugging-Anweisungen in der Browser-Konsole bereit. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Staging-Bibliothek verwenden </p> </td> 
   <td colname="col2"> <p>Dieses Tool verwendet die Staging-Bibliothek für DTM-Debugging-Informationen. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>DTM deaktivieren </p> </td> 
   <td colname="col2"> <p>Dieses Tool verhindert, dass DTM-Informationen überprüft werden. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Dynamisches Einfügen von DTM </p> </td> 
   <td colname="col2"> <p> Dieses Tool fügt DTM-Code auf Ihrer Seite ein. Bearbeiten Sie den eingefügten Code im Einbettungscode-Editor. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Zielinformationen {#section-31090d95f50e455692b672c26e6a2051}

<table id="table_A71D269B49F4417599EBACA44D5CCF4F"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Werkzeug </th> 
   <th colname="col2" class="entry"> Beschreibung </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Protokollierung der Target-Konsole </p> </td> 
   <td colname="col2"> <p><span class="codeph"> Dieses Tool stellt Target-spezifische Debugging-Anweisungen für die Browser-Konsole bereit, die alle mit </span> AT beginnen: Präfix, indem Sie Ihrem Browser ein Cookie namens <span class="codeph"> mboxDebug=true</span> hinzufügen. Derzeit werden die Konsolenanweisungen nicht im Bildschirm "Debugger-Protokolle"angezeigt, sondern in der nativen Debugging-Konsole des Browsers. </p> <p> Dieses Tool erfordert at.js 0.9.6+. Wenn Sie eine ältere Version von at.js verwenden, können Sie den Abfragezeichenfolgenparameter <span class="codeph"> ?mboxDebug=true</span> zu Ihrer URL hinzufügen, um die Konsolenprotokollierung zu aktivieren. Wenn Sie mbox.js verwenden, können Sie den Parameter <span class="codeph"> ?_AT_Debug=console</span> hinzufügen, um die Konsolenprotokollierung zu aktivieren, die auf Visual Experience Composer-Aktivitäten beschränkt ist. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Mbox-Spuren aktivieren </p> </td> 
   <td colname="col2"> <p>Mit diesem Tool werden Target-Antworten detaillierte Informationen hinzugefügt, die im Bildschirm " <span class="uicontrol"> Target &gt; Mbox Trace</span> "des Debuggers untersucht werden können. </p> <p> Sie müssen auf einer Ihrer Chrome-Registerkarten bei der Experience Cloud angemeldet sein, um dieses Tool zu aktivieren. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Target deaktivieren </p> </td> 
   <td colname="col2"> <p>Dieses Tool deaktiviert alle Target-Anforderungen, indem Sie Ihrem Browser ein Cookie namens <span class="codeph"> mboxDisable=true</span> hinzufügen. </p> <p> Dieses Tool erfordert at.js 0.9.6+. Wenn Sie eine ältere Version verwenden, können Sie den <span class="codeph"> </span>Abfragezeichenfolgen-Parameter ?mboxDisable=true zu Ihrer URL hinzufügen, um mboxes zu deaktivieren. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Mbox-Hervorhebung </p> </td> 
   <td colname="col2"> <p> Dieses Tool zeichnet eine rote Box um ältere, umbruchartige Mboxes. </p> </td> 
  </tr> 
 </tbody> 
</table>

Im folgenden Video wird die Verwendung der Debugger-Erweiterung mit Adobe Target erläutert.

>[!VIDEO](https://video.tv.adobe.com/v/23115t2/?captions=ger)
