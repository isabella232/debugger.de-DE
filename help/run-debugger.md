---
description: 'null'
keywords: Debugger;Erweiterung des Experience Cloud-Debuggers;Chrome;Erweiterung;Zusammenfassung;Löschen;Anforderungen;Zusammenfassungsbildschirm;Lösung;Informationen;Analyse;Ziel;DTM;Zielgruppen-Manager;Start;ID-Dienst
seo-description: 'null'
seo-title: Zusammenfassungsbildschirm
title: Zusammenfassungsbildschirm
uuid: 46b17eaa-b611-43cf-8c6a-67b2e9b9d940
translation-type: tm+mt
source-git-commit: 3fd50cde86f0dfc5f66d8faf63112adf24beeac0

---


# Zusammenfassungsbildschirm{#summary-screen}

Um den Experience Cloud-Debugger auszuführen, klicken Sie auf das Erweiterungssymbol in der Erweiterungsleiste und öffnen Sie dann die Seite, die Sie in Chrome untersuchen möchten.

![](assets/start-icon.jpg)

Der Bildschirm "Adobe Experience Cloud-Debugger-Zusammenfassung"wird angezeigt.

![](assets/summary.jpg)

Dieser Bildschirm zeigt eine Miniaturansicht der Seite sowie die URL und den Titel der Seite. Außerdem werden Informationen zu den einzelnen Adobe Experience Cloud-Lösungen angezeigt. Die angezeigten Informationen variieren je nach Lösung, beinhalten jedoch in der Regel Informationen wie die Lösungsbibliothek und Version (z. B. "AppMeasurement v2.9") und Kontokennungen (z. B. die Analytics Report Suite-ID, den Target-Client-Code, die Audience Manager-Partner-ID usw.)

Die Zahlen in blau neben den Registerkarten oben im Fenster zeigen die Anzahl der Serveraufrufe an, die durchgeführt wurden. Sie können diese auf null zurücksetzen, indem Sie auf der entsprechenden Registerkarte auf Alle Anforderungen **[!UICONTROL löschen]** klicken.

Die folgende Abbildung zeigt beispielsweise Informationen zu Adobe Target. Um die unten abgebildeten Aktivitätsdetails ohne Authentifizierung verfügbar zu machen, müssen Sie den Debugging-Ereignis-Listener in Ihren Code- oder Tag-Manager implementieren und die erforderlichen [Antworttokens](https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html) in der Target-Benutzeroberfläche aktivieren.

![](assets/summary-target2.jpg)

## Durchführen einer Prüfung im Auditor {#section-82bc57440406461ebf27a16855b71655}

Sie können Adobe Auditor verwenden, um eine Reihe von Prüfungen auf Ihrer Seite durchzuführen. Um Auditor auszuführen, klicken Sie im oberen Menü auf **[!UICONTROL Auditor]** und dann auf Seite jetzt **[!UICONTROL prüfen]**. Um Adobe Auditor zu öffnen, klicken Sie auf "Mehrseitige Prüfung jetzt **[!UICONTROL ausführen"]**.

## Im Debugger angezeigte Informationen {#section-88a95ba53dca43d9b96a585e75e5f5cf}

Der Debugger zeigt die folgenden Informationen für jede Lösung an:

**Seiteninformationen**

<table id="table_FF3B9083524244D29AF350978A0AC236"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Seitenbildschirm </p> </td> 
   <td colname="col2"> <p>Miniaturansicht der Seite </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>URL </p> </td> 
   <td colname="col2"> <p>URL der Seite </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Titel </p> </td> 
   <td colname="col2"> <p>Der im Tag <span class="codeph"> &lt;TITEL&gt;</span> angegebene Name </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Analytics**

<table id="table_BEB9CC58E59D4D86BC895A8A51D84A2C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Report Suite(s) </p> </td> 
   <td colname="col2"> <p>Eine <a href="https://experiencecloud.adobe.com/resources/help/en_US/reference/report_suites_admin.html" format="html" scope="external">Report Suite</a> definiert die vollständige, unabhängige Berichterstellung über eine bestimmte Website, eine Gruppe von Websites oder eine Untergruppe von Seiten einer Webseite </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version  </p> </td> 
   <td colname="col2"> <p>Die für die Seite definierte <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/appmeasure_mjs.html" format="html" scope="external"> AppMeasurement</a> -Version </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Besucherversion </p> </td> 
   <td colname="col2"> <p>Die Version der <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/visid_analytics.html" format="html" scope="external"> Besucher-ID</a> -Bibliothek. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Seitenname </p> </td> 
   <td colname="col2"> <p>Die <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/pageName.html" format="html" scope="external"> Variable "pageName</a> ", die an Analytics gesendet wird und einen benutzerfreundlichen Namen der Site enthält. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Module </p> </td> 
   <td colname="col2"> <p>Die von Adobe Analytics geladenen Module </p> </td> 
  </tr> 
 </tbody> 
</table>

**Audience Manager**

<table id="table_784AEABADBDA4D14BB9A7A9CB9EF07C3"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Partner </p> </td> 
   <td colname="col2"> <p>Der <a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_dil_get_partner.html" format="html" scope="external"> Partnername</a> für die DIL-Instanz </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version  </p> </td> 
   <td colname="col2"> <p>Die<a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_api_return_versions_dil.html" format="html" scope="external"> Versionsnummer</a> der DIL-Instanz </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>UUID </p> </td> 
   <td colname="col2"> <p>Die mit der DIL-Instanz verknüpfte <a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/ids-in-aam.html" format="html" scope="external"> eindeutige Benutzer-ID</a> </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Launch**

<table id="table_E9574975444A407887E26514D1BB1601"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Name </p> </td> 
   <td colname="col2"> <p>Der Name der Adobe Launch- <a href="https://docs.adobelaunch.com/administration/companies-and-properties" format="https" scope="external"> Eigenschaft</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version  </p> </td> 
   <td colname="col2"> <p>Die Version von <a href="https://developer.adobelaunch.com/guides/extensions/turbine-free-variable/" format="https" scope="external"> Turbine</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Erstellungsdatum </p> </td> 
   <td colname="col2"> <p>Erstellungsdatum der <a href="https://docs.adobelaunch.com/publishing/libraries" format="https" scope="external"> Bibliothek</a> starten </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Umgebung </p> </td> 
   <td colname="col2"> <p>Die von der Startbibliothek verwendete <a href="https://docs.adobelaunch.com/administration/environments" format="https" scope="external"> Umgebung</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Skriptverzeichnis </p> </td> 
   <td colname="col2"> <p>Der Ordner, in dem das Startskript gespeichert ist </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe DTM**

<table id="table_DC76D63FA6EF4891906B9E1D3E4A8A6C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Bibliotheksname </p> </td> 
   <td colname="col2"> <p>Name der Adobe DTM<a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/library_management.html" format="html" scope="external"> -Bibliothek</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version  </p> </td> 
   <td colname="col2"> <p>Die Version von Turbine </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Erstellungsdatum </p> </td> 
   <td colname="col2"> <p>Erstellungsdatum der <a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/library_management.html" format="html" scope="external"> Bibliothek</a> starten </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Umgebung </p> </td> 
   <td colname="col2"> <p>Die von der DTM-Bibliothek verwendete Umgebung </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Skriptverzeichnis </p> </td> 
   <td colname="col2"> <p>Der Ordner, in dem das DTM-Skript gespeichert wird </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Experience Cloud ID-Dienst**

<table id="table_274CFCEFA8F34D16BB546B4669EC0209"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Experience Cloud-Organisations-ID </p> </td> 
   <td colname="col2"> <p>Your <a href="https://experiencecloud.adobe.com/resources/help/en_US/mcvid/" format="https" scope="external"> Organization ID</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version  </p> </td> 
   <td colname="col2"> <p>Die Version der<a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/visid_analytics.html" format="html" scope="external"> Besucher-ID</a> -Bibliothek </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Target**

<table id="table_D30E0CD20FB04E41862B22655136E043"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Clientcode </p> </td> 
   <td colname="col2"> <p>Your Target <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/deploy-at-js/implementing-target-without-a-tag-manager.html" format="html" scope="external"> Client Code </a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version  </p> </td> 
   <td colname="col2"> <p>Ihre aktuelle Version von <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/target-atjs-versions.html" format="html" scope="external"> at.js</a> oder mbox.js </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Globaler Mbox-Name </p> </td> 
   <td colname="col2"> <p>Die<a href="https://docs.adobe.com/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> globale Mbox</a> bezieht sich auf den Einzelserveraufruf, der oben auf jeder Webseite in Ihrer Target-Implementierung erfolgt </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Mbox-Name </p> </td> 
   <td colname="col2"> <p>Der Name einer Mbox um eine <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> Position</a> auf der Seite. Ohne Authentifizierung verfügbar, wenn Sie den Debugging-Ereignis-Listener in Ihren Code- oder Tag-Manager implementieren und die erforderlichen <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> Antworttokens</a> in der Target-Benutzeroberfläche aktivieren. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Aktivitätsname </p> </td> 
   <td colname="col2"> <p>Der Name der Target- <a href="https://docs.adobe.com/content/help/en/target/using/activities/activities.html" format="html" scope="external"> Kampagne oder -Aktivität</a>. Ohne Authentifizierung verfügbar, wenn Sie den Debugging-Ereignis-Listener in Ihren Code- oder Tag-Manager implementieren und die erforderlichen <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> Antworttokens</a> in der Target-Benutzeroberfläche aktivieren. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Aktivitäts-ID </p> </td> 
   <td colname="col2"> <p>Die ID der Target-Aktivität. Ohne Authentifizierung verfügbar, wenn Sie den Debugging-Ereignis-Listener in Ihren Code- oder Tag-Manager implementieren und die erforderlichen <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> Antworttokens</a> in der Target-Benutzeroberfläche aktivieren. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Rezeptname </p> </td> 
   <td colname="col2"> <p>Der Name des Target- <a href="https://docs.adobe.com/content/help/en/target/using/experiences/experiences.html" format="html" scope="external"> Erlebnisses</a>. Ohne Authentifizierung verfügbar, wenn Sie den Debugging-Ereignis-Listener in Ihren Code- oder Tag-Manager implementieren und die erforderlichen <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> Antworttokens</a> in der Target-Benutzeroberfläche aktivieren. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Rezept-ID </p> </td> 
   <td colname="col2"> <p>Die ID des Target-Rezepts. Ohne Authentifizierung verfügbar, wenn Sie den Debugging-Ereignis-Listener in Ihren Code- oder Tag-Manager implementieren und die erforderlichen <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> Antworttokens</a> in der Target-Benutzeroberfläche aktivieren. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Angebot </p> </td> 
   <td colname="col2"> <p>Der Name des Target- <a href="https://docs.adobe.com/content/help/en/target/using/experiences/offers/manage-content.html" format="html" scope="external"> Angebots</a>. Ohne Authentifizierung verfügbar, wenn Sie den Debugging-Ereignis-Listener in Ihren Code- oder Tag-Manager implementieren und die erforderlichen <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> Antworttokens</a> in der Target-Benutzeroberfläche aktivieren. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Angebots-ID </p> </td> 
   <td colname="col2"> <p>Die ID des Target-Angebots. Ohne Authentifizierung verfügbar, wenn Sie den Debugging-Ereignis-Listener in Ihren Code- oder Tag-Manager implementieren und die erforderlichen <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> Antworttokens</a> in der Target-Benutzeroberfläche aktivieren. </p> </td> 
  </tr> 
 </tbody> 
</table>

