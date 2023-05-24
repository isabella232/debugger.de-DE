---
description: Ausführen von Adobe Experience Cloud Debugger
keywords: debugger;experience cloud debugger extension;chrome;extension;summary;clear;requests;summary screen;solution;information;analytics;target;dtm;audience manager;launch;id service
seo-description: Running Experience Cloud Debugger
seo-title: Summary Screen
title: Zusammenfassungsbildschirm - Experience Cloud Debugger
uuid: 46b17eaa-b611-43cf-8c6a-67b2e9b9d940
exl-id: 0ee0314b-1611-4581-ae54-2c784e0e56ff
source-git-commit: 2778ba78de3350ed1da01d452e303476b04c0303
workflow-type: tm+mt
source-wordcount: '1066'
ht-degree: 99%

---

# Zusammenfassungsbildschirm{#summary-screen}

Um Adobe Experience Cloud Debugger auszuführen, klicken Sie in der Erweiterungsleiste auf das entsprechende Symbol und öffnen Sie die Seite, die Sie untersuchen möchten, in Chrome.

![](assets/start-icon.jpg)

Hierdurch wird der Bildschirm „Summary“ von Experience Cloud Debugger angezeigt.

![](assets/summary.jpg)

Dieser Bildschirm enthält eine Miniaturansicht der Seite sowie ihre URL und ihren Titel. Darüber hinaus werden hier Informationen zu den verschiedenen Adobe Experience Cloud-Lösungen angezeigt. Die angezeigten Informationen unterscheiden sich je nach Lösung. In der Regel sind jedoch Details wie Lösungsbibliothek und -version (z. B. „AppMeasurement v2.9“) sowie Konto-IDs (wie z. B. die Analytics Report Suite ID, der Target-Kundencode, die Audience Manager-Partner-ID usw.) enthalten.

Die blauen Zahlen neben den Registerkarten oben im Fenster geben die Anzahl der durchgeführten Server-Aufrufe an. Sie können diese Anzahl zurücksetzen, indem Sie auf der entsprechenden Registerkarte auf **[!UICONTROL Clear All Requests]** klicken.

In der folgenden Abbildung werden beispielsweise Informationen zu Adobe Target angezeigt. Um die unten abgebildeten Aktivitätsdetails ohne Authentifizierung abzurufen, müssen Sie den Debugging-Ereignis-Listener in Ihren Code oder Tag-Manager implementieren und die erforderlichen [Antwort-Tokens](https://docs.adobe.com/content/help/de-DE/target/using/administer/response-tokens.html) in der Target-Benutzeroberfläche aktivieren.

![](assets/summary-target2.jpg)

## Durchführen einer Prüfung in Adobe Experience Platform Auditor {#section-82bc57440406461ebf27a16855b71655}

Sie können Plaform Auditor verwenden, um eine Reihe von Audits auf Ihrer Seite auszuführen. Um Platform Auditor auszuführen, klicken Sie im oberen Menü auf **[!UICONTROL Auditor]** und anschließend auf **[!UICONTROL Audit Page Now]**. Um Platform Auditor zu öffnen, klicken Sie auf **[!UICONTROL Run Multi-Page Audit Now]**.

## In Experience Cloud Debugger angezeigte Informationen {#section-88a95ba53dca43d9b96a585e75e5f5cf}

Experience Cloud Debugger zeigt die folgenden Informationen zu den verschiedenen Lösungen an:

**Seiteninformationen**

<table id="table_FF3B9083524244D29AF350978A0AC236"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Webseitenscreenshot </p> </td> 
   <td colname="col2"> <p>Miniaturansicht der Seite </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>URL </p> </td> 
   <td colname="col2"> <p>URL der Seite </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Titel </p> </td> 
   <td colname="col2"> <p>Der im Tag <span class="codeph">&lt;TITLE&gt;</span> angegebene Name </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Analytics**

<table id="table_BEB9CC58E59D4D86BC895A8A51D84A2C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Report Suite(s) </p> </td> 
   <td colname="col2"> <p>Eine <a href="https://docs.adobe.com/content/help/de-DE/analytics/admin/manage-report-suites/report-suites-admin.html" format="html" scope="external">Report Suite</a> definiert die vollständige, unabhängige Berichterstellung über eine bestimmte Website, eine Gruppe von Websites oder eine Untergruppe von Seiten einer Webseite. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Die für die Seite definierte <a href="https://docs.adobe.com/content/help/de-DE/analytics/implementation/js/overview.html" format="html" scope="external"> AppMeasurement</a>-Version. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Besucherversion </p> </td> 
   <td colname="col2"> <p>Die Version der <a href="https://docs.adobe.com/content/help/de-DE/analytics/components/metrics/unique-visitors.html" format="html" scope="external">Besucher-ID</a>-Bibliothek. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Webseitenname </p> </td> 
   <td colname="col2"> <p>Die Variable <a href="https://docs.adobe.com/content/help/de-DE/analytics/implementation/vars/page-vars/page-variables.html" format="html" scope="external">pageName</a>, die an Analytics gesendet wird und einen benutzerfreundlichen Namen der Seite enthält. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Module </p> </td> 
   <td colname="col2"> <p>Die von Adobe Analytics geladenen Module. </p> </td> 
  </tr> 
 </tbody> 
</table>

**Audience Manager**

<table id="table_784AEABADBDA4D14BB9A7A9CB9EF07C3"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Partner </p> </td> 
   <td colname="col2"> <p>Der <a href="https://docs.adobe.com/content/help/de-DE/audience-manager/user-guide/dil-api/dil-instance-methods.html#getpartner" format="html" scope="external">Partnername</a> für die DIL-Instanz. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Die <a href="https://docs.adobe.com/content/help/de-DE/audience-manager/user-guide/api-and-sdk-code/rest-apis/aam-api-dil-methods.html#return-version-dil" format="html" scope="external">Versionsnummer</a> für die DIL-Instanz. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>UUID </p> </td> 
   <td colname="col2"> <p>Die <a href="https://docs.adobe.com/content/help/de-DE/audience-manager/user-guide/reference/ids-in-aam.html" format="html" scope="external">eindeutige Benutzer-ID</a>, die der DIL-Instanz zugeordnet ist. </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Experience Platform Launch**

<table id="table_E9574975444A407887E26514D1BB1601"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Name </p> </td> 
   <td colname="col2"> <p>Der Name der Platform Launch-<a href="https://docs.adobe.com/content/help/de-DE/launch/using/reference/admin/companies-and-properties.html" format="https" scope="external">Ressource</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Die <a href="https://developer.adobelaunch.com/extensions/reference/turbine-free-variable/" format="https" scope="external">Turbine</a>-Version. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Build-Datum </p> </td> 
   <td colname="col2"> <p>Das Build-Datum der Platform Launch-<a href="https://docs.adobe.com/content/help/de-DE/launch/using/reference/publish/libraries.html" format="https" scope="external">Bibliothek</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Umgebung </p> </td> 
   <td colname="col2"> <p>Die von der Platform Launch-Bibliothek verwendete <a href="https://docs.adobe.com/content/help/de-DE/launch/using/reference/publish/environments.html" format="https" scope="external">Umgebung</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Skriptverzeichnis </p> </td> 
   <td colname="col2"> <p>Das Verzeichnis, in dem das Platform Launch-Skript gespeichert wurde. </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe DTM**

<table id="table_DC76D63FA6EF4891906B9E1D3E4A8A6C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Bibliotheksname </p> </td> 
   <td colname="col2"> <p>Der Name der Adobe DTM-<a href="https://docs.adobe.com/content/help/de-DE/dtm/using/library-management.html" format="html" scope="external">Bibliothek</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Die Turbine-Version. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Build-Datum </p> </td> 
   <td colname="col2"> <p>Das Build-Datum der Platform Launch-<a href="https://docs.adobe.com/content/help/de-DE/dtm/using/library-management.html" format="html" scope="external">Bibliothek</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Umgebung </p> </td> 
   <td colname="col2"> <p>Die von der DTM-Bibliothek verwendete Umgebung. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Skriptverzeichnis </p> </td> 
   <td colname="col2"> <p>Das Verzeichnis, in dem das DTM-Skript gespeichert wurde. </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Experience Cloud ID-Dienst**

<table id="table_274CFCEFA8F34D16BB546B4669EC0209"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Experience Cloud Org ID </p> </td> 
   <td colname="col2"> <p>Ihre <a href="https://docs.adobe.com/content/help/de-DE/id-service/using/home.html" format="https" scope="external"> Organisations-ID</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Die Version der <a href="https://docs.adobe.com/content/help/de-DE/analytics/components/metrics/unique-visitors.html" format="html" scope="external">Besucher-ID</a>-Bibliothek. </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Target**

<table id="table_D30E0CD20FB04E41862B22655136E043"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Clientcode </p> </td> 
   <td colname="col2"> <p>Ihr Target-<a href="https://docs.adobe.com/content/help/de-DE/target/using/implement-target/client-side/deploy-at-js/implementing-target-without-a-tag-manager.html" format="html" scope="external"> Kundencode</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Version </p> </td> 
   <td colname="col2"> <p>Ihre aktuelle <a href="https://docs.adobe.com/content/help/de-DE/target/using/implement-target/client-side/target-atjs-versions.html" format="html" scope="external"> at.js</a>- oder mbox.js-Version. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Globaler Mbox-Name </p> </td> 
   <td colname="col2"> <p>Die<a href="https://docs.adobe.com/help/de-DE/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> globale Mbox</a> bezieht sich auf den einzelnen Server-Aufruf, der oben auf jeder Webseite in Ihrer Target-Implementierung durchgeführt wird. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Mbox-Name </p> </td> 
   <td colname="col2"> <p>Der Name einer Mbox an einer <a href="https://docs.adobe.com/content/help/de-DE/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external">Position</a> auf der Seite. Ist nur dann ohne Authentifizierung verfügbar, wenn Sie den Debugging-Ereignis-Listener in Ihren Code oder Tag-Manager implementieren und die erforderlichen <a href="https://docs.adobe.com/content/help/de-DE/target/using/administer/response-tokens.html" format="html" scope="external">Antwort-Tokens</a> in der Target-Benutzeroberfläche aktivieren. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Aktivitätsname </p> </td> 
   <td colname="col2"> <p>Name der Target-<a href="https://docs.adobe.com/content/help/de-DE/target/using/activities/activities.html" format="html" scope="external"> Kampagne oder -Aktivität</a>. Ist nur dann ohne Authentifizierung verfügbar, wenn Sie den Debugging-Ereignis-Listener in Ihren Code oder Tag-Manager implementieren und die erforderlichen <a href="https://docs.adobe.com/content/help/de-DE/target/using/administer/response-tokens.html" format="html" scope="external"> Antwort-Tokens</a> in der Target-Benutzeroberfläche aktivieren. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Activity ID </p> </td> 
   <td colname="col2"> <p>Die ID der Target-Aktivität. Ist nur dann ohne Authentifizierung verfügbar, wenn Sie den Debugging-Ereignis-Listener in Ihren Code oder Tag-Manager implementieren und die erforderlichen <a href="https://docs.adobe.com/content/help/de-DE/target/using/administer/response-tokens.html" format="html" scope="external">Antwort-Tokens</a> in der Target-Benutzeroberfläche aktivieren. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Rezeptname </p> </td> 
   <td colname="col2"> <p>Name des Target-<a href="https://docs.adobe.com/content/help/de-DE/target/using/experiences/experiences.html" format="html" scope="external"> Erlebnisses</a>. Ist nur dann ohne Authentifizierung verfügbar, wenn Sie den Debugging-Ereignis-Listener in Ihren Code oder Tag-Manager implementieren und die erforderlichen <a href="https://docs.adobe.com/content/help/de-DE/target/using/administer/response-tokens.html" format="html" scope="external">Antwort-Tokens</a> in der Target-Benutzeroberfläche aktivieren. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Rezept-ID </p> </td> 
   <td colname="col2"> <p>Die ID des Target-Rezepts. Ist nur dann ohne Authentifizierung verfügbar, wenn Sie den Debugging-Ereignis-Listener in Ihren Code oder Tag-Manager implementieren und die erforderlichen <a href="https://docs.adobe.com/content/help/de-DE/target/using/administer/response-tokens.html" format="html" scope="external">Antwort-Tokens</a> in der Target-Benutzeroberfläche aktivieren. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Angebot </p> </td> 
   <td colname="col2"> <p>Name des Target-<a href="https://docs.adobe.com/content/help/de-DE/target/using/experiences/offers/manage-content.html" format="html" scope="external"> Angebots</a>. Ist nur dann ohne Authentifizierung verfügbar, wenn Sie den Debugging-Ereignis-Listener in Ihren Code oder Tag-Manager implementieren und die erforderlichen <a href="https://docs.adobe.com/content/help/de-DE/target/using/administer/response-tokens.html" format="html" scope="external"> Antwort-Tokens</a> in der Target-Benutzeroberfläche aktivieren. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Offer ID </p> </td> 
   <td colname="col2"> <p>Die ID des Target-Angebots. Ist nur dann ohne Authentifizierung verfügbar, wenn Sie den Debugging-Ereignis-Listener in Ihren Code oder Tag-Manager implementieren und die erforderlichen <a href="https://docs.adobe.com/content/help/de-DE/target/using/administer/response-tokens.html" format="html" scope="external"> Antwort-Tokens</a> in der Target-Benutzeroberfläche aktivieren. </p> </td> 
  </tr> 
 </tbody> 
</table>
