---
description: 'null'
keywords: debugger;experience cloud debugger extension;chrome;extension;release notes
seo-description: 'null'
seo-title: Versionshinweise
title: Versionshinweise
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
translation-type: tm+mt
source-git-commit: 28e5681a3a2f58350348d4b9bc5b7e1bd979e749

---


# Versionshinweise {#release-notes}

## Versionshinweise {#topic-a92c3eb799b74e7fa404af8af5efb215}

## Version 0.0.817 17. Mai 2019 {#topic-5dc9026cac864330b04361b1da8309a8}

## Neue Funktionen {#section-71352536e6894ad08f307535529394cd}

<table id="table_7EFCAF456B14404FAF3715FC56519AAF"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funktion </th> 
   <th colname="col2" class="entry"> Beschreibung </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Trefferdaten nach der Verarbeitung </p> </td> 
   <td colname="col2"> <p> Es wurde die Möglichkeit hinzugefügt, <a href="solutions.md#section-f71dfcc22bb44c86bec328491606a482" format="dita" scope="local">Werte zu Analytics-Treffern anzuzeigen, nachdem die Verarbeitungsregeln ausgeführt wurden</a>. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Version 0.0.810 6. März 2019 {#topic-83bb7ddd68594177be9fd7826b650b80}

## Neue Funktionen {#section-0a2f6fcb0045464fa11f0586c69f7ffd}

<table id="table_96AEBFF29F3D40CAA859133B22756B0C"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funktion </th> 
   <th colname="col2" class="entry"> Beschreibung </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Auditor-Tests </p> </td> 
   <td colname="col2"> <p> Es wurden <a href="summary.md#section-82bc57440406461ebf27a16855b71655" format="dita" scope="local">Auditor-Tests</a> zum Debugger hinzugefügt. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Adobe Audience Manager </p> </td> 
   <td colname="col2"> <p>Der Debugger zeigt jetzt AAM-Antworten an. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Fehlerkorrekturen {#section-f5e9d54e9d2546afb97972cdb6d8a093}

* Es wurde ein Problem behoben, bei dem die Fußzeile Inhalte unten auf der Seite nicht anzeigte.

* Die Debugger-Fußzeile wurde aktualisiert.
* Es wurde ein Problem mit veralteter Terminologie für Target behoben.

## Version 0.0.809 28. Februar 2019 {#topic-6241de45fa9e4a23a95ad4d3a73f7348}

## Neue Funktionen {#section-14036b9f2c0144fdac5e292ea42ce564}

<table id="table_66E255E9BA8845CAA92779F580D14EB4"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funktion </th> 
   <th colname="col2" class="entry"> Beschreibung </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Einbettungscode-Funktionen </p> </td> 
   <td colname="col2"> <p> Sie können Einbettungscode-Funktionen teilen, ersetzen und einfügen. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Verbesserungen {#section-e9e8a6ddedde4c029b1d3d69c009cbad}

* Es wurde eine potenzielle Schwachstelle durch unbereinigte Benutzereingaben behoben.

## Fehlerkorrekturen {#section-556417ff055848c1bf037354dd43cbd0}

* Es wurde ein Problem behoben, bei dem AAM DIL-Ereignisse nicht auf der AAM-Registerkarte erfasst wurden.

* Es wurde ein Problem in „Dynamically Insert Launch“ behoben, bei dem die Benutzeroberfläche scheinbar einem anderen Einbettungscode zugeordnet war, obwohl dies nicht der Fall war.
* Es wurde ein Problem in „Dynamically Insert Launch“ behoben, bei dem eine falsche URL weiterhin angezeigt wurde.
* Es wurde ein Problem behoben, bei dem der Debugger weiterhin Einbettungscodes ersetzte, auch wenn das Debugger-Fenster bereits geschlossen wurde.

## Version 0.0.806 10. September 2018 {#topic-a41c9d1969ff4d06ac3bb4e7d6b6d18a}

## Neue Funktionen {#section-4eb2a6ed26a44abc96623384a7e94b0f}

<table id="table_9AC6DE90AF4345DFA707BFBA1E58C328"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funktion </th> 
   <th colname="col2" class="entry"> Beschreibung </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Analytics-Link auf der Registerkarte „Tools“ </p> </td> 
   <td colname="col2"> <p>Zeigen Sie per Analytics-API und IMS-Anmeldung aussagekräftige Namen für eVars/Props an. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Dynamically Insert Launch </p> </td> 
   <td colname="col2"> <p>Über die Registerkarte „Tools“ können Sie Launch dynamisch auf beliebigen Seiten einfügen, um Elemente auf Seiten zu testen, auf denen Launch nicht installiert ist. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Target-Verbesserungen </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_5FCD61733462495D8FB421DE7C813001"> 
      <li id="li_2E8E9AAE5D0D41DC8C42592AFDFA3377">Es wurden Performance-Timings für Target-Anfragen hinzugefügt. </li> 
      <li id="li_98A56E71D72542D694A76DF84CE26AFA">adobe.target.trackEvent wird erfasst. </li> 
     </ul> </p> </td> 
  </tr> 
 </tbody> 
</table>

## Verbesserungen {#section-56003a12c32f4998bf1cf2a25a518592}

* Die Anzeige auf der Registerkarte „Network“ wurde verbessert, damit die Tabelle nicht zu hoch wird und Benutzer nicht mehr vertikal scrollen müssen, um horizontal scrollen zu können. Zuvor wurden die Scrollleisten am unteren Rand der Tabelle angezeigt. Da die Tabelle sehr groß werden konnte, mussten Benutzer erst nach unten scrollen, um die Leisten sehen zu können.
* Der Link zu ObservePoint auf der Registerkarte „Tools“ wurde aktualisiert.

## Fehlerkorrekturen {#section-d9231f5c77254d0888347e5f569a8b1d}

* Es wurde ein Problem behoben, bei dem die Registerkarte „Experience Cloud“ nicht aktualisiert wurde.

* Es wurde ein Problem behoben, bei dem in der Zeile „Solution“ der Netzwerkregisterkarte „Media Optimizer“ statt des aktuellen Namens „Advertising Cloud“ angezeigt wurde.
* Es wurde ein Problem behoben, bei dem der Debugger _satellite auf jeder Seite einfügte.

## Version 0.0.803 10. August 2018 {#topic-d2901fb70ce04a5586f6c7a994fce875}

Version 0.0.803 enthält keine kundengerichteten Änderungen.

## Version 0.0.802 1. August 2018 {#topic-b93cd396af5e49dc97cd86264871aeb4}

## Neue Funktionen {#section-e6699fb9c9b24035ace56d6a84c9d09b}

<table id="table_E847A9D6711F4CF59E98806FA7AF8379"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funktion </th> 
   <th colname="col2" class="entry"> Beschreibung </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Auditor-Link auf der Registerkarte „Tools“ </p> </td> 
   <td colname="col2"> <p>Der Debugger enthält jetzt einen Link zu Auditor. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Reduzierte Registerkarten </p> </td> 
   <td colname="col2"> <p>Reduzierte Registerkarten bleiben auch auf den Registerkarten „Summary“ und „Tool“ reduziert. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Zum Anzeigen klicken </p> </td> 
   <td colname="col2"> <p> Allen Registerkarten wurde die Funktion „Click to view“ hinzugefügt. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Verbesserungen {#section-0e7090e3e6a645f085d4553b983ecff8}

* Der Name wurde von „Media Optimizer“ zu „Advertising Cloud“ geändert.
* Es wurden Lösungen von der Registerkarte „Network“ entfernt, wenn diese nicht gefunden wurden.

## Fehlerkorrekturen {#section-7c0e4cc4b00a428489bed4a0a27c9501}

* Es wurde ein Problem behoben, bei dem die Funktion „Click cell to view“ nicht aktualisiert wurde.
* Es wurde ein Problem behoben, bei dem AAM-Treffer nicht auf der AAM-Registerkarte angezeigt wurden.

## Version 0.0.798 14. Juni 2018 {#topic-3b2d44277f2f4c0295d82724c34bf467}

## Neue Funktionen {#section-0d73ae8b7ced417e9039f986fafaa102}

<table id="table_8FDED5A7B7F7430A88AE441336F9C714"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funktion </th> 
   <th colname="col2" class="entry"> Beschreibung </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Excel-Exportoption </p> </td> 
   <td colname="col2"> <p>Der Registerkarte „Network“ wurde eine Option für Excel-Exporte hinzugefügt. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Verbessertes Erscheinungsbild </p> </td> 
   <td colname="col2"> <p>Die Schrift der Chrome-Erweiterung wurde zu Adobe Clean geändert. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Trackpad-Wischfunktion </p> </td> 
   <td colname="col2"> <p>Die Vorwärts-/Rückwärts-Wischfunktion von Trackpads wurde deaktiviert. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Indikator für Rohserveraufruf </p> </td> 
   <td colname="col2"> <p>Es wurde ein Indikator hinzugefügt, der angibt, dass die Rohzeichenfolge des Serveraufrufs kopiert wurde. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Verbesserte Registerkarte „Logs“ </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_D1EB0BE3A01C494983DAAF625562AC62"> 
      <li id="li_2696D26320F54A089D3CC99962EC9670">Lösungen werden im Filter „Solutions“ ausgeblendet, wenn in den Protokollen keine Zeilenelemente für die jeweilige Lösung gefunden werden. </li> 
      <li id="li_D4586A6AB2AD42BB9F0FA3E7A01382C6">Der Filter „Level“ wird ausgeblendet, wenn keine DTM-Aufrufe gefunden werden, da er nur DTM betrifft. </li> 
      <li id="li_E2AF179037DC4C63B960013AB1F9AD6A">Die Symbole in der Spalte „Level“ wurden geändert, damit sie nicht interaktiv wirken, obwohl sie es nicht sind. </li> 
      <li id="li_3DB6682D6C9040D99F04C688E208CE1F">Die Formatierung der Funktion „Show Code“ bei DTM-Zeilenelementen wurde standardisiert. </li> 
     </ul> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Aktualisierter Hilfelink in der Fußzeile </p> </td> 
   <td colname="col2"> <p>Der Hilfelink in der Fußzeile wurde zu <a href="https://marketing.adobe.com/resources/help/en_US/experience-cloud-debugger/" format="https" scope="external">https://marketing.adobe.com/resources/help/en_US/experience-cloud-debugger/</a> geändert. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Fehlerkorrekturen {#section-c292cf7dcb17463bb1928de73bd55121}

* Es wurde ein Problem behoben, bei dem die Zeichennummer nicht gelöscht wurde.
* Es wurde ein Problem behoben, bei dem bei Kunden leere Zusammenfassungsdetails angezeigt wurden.

## Version 0.0.797 25. Mai 2018 {#topic-51490f4f42aa40eb879663fad9d62916}

## Neue Funktionen {#section-bbf8ff7e000e4b5592d348e0870471f6}

<table id="table_8CF872DC245A46C38FE21490C842D47A"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funktion </th> 
   <th colname="col2" class="entry"> Beschreibung </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Mbox-Schalter Umschalter </p> </td> 
   <td colname="col2"> <p>Es wurden Mbox-Schalter zur Target-Registerkarte hinzugefügt. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Fixierte Filtereinstellungen </p> </td> 
   <td colname="col2"> <p>Filtereinstellungen werden jetzt auf den Registerkarten „Network“ und „Logs“ oben am Bildschirm fixiert. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Anzeigen und Kopieren von Netzwerkwerten </p> </td> 
   <td colname="col2"> <p>Sie können die Werte beliebiger Zellen der Registerkarte „Network“ anzeigen und kopieren. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Fußzeilenlinks zu Rechtshinweis und Copyright </p> </td> 
   <td colname="col2"> <p>Der Benutzeroberfläche wurden Links zu Rechtshinweisen sowie Copyrightinformationen hinzugefügt. </p> </td> 
  </tr> 
 </tbody> 
</table>

