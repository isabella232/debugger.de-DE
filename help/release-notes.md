---
description: 'null'
keywords: Debugger;Erweiterung des Experience Cloud-Debuggers;Chrome;Erweiterung;Versionshinweise
seo-description: 'null'
seo-title: Versionshinweise
title: Versionshinweise
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
translation-type: tm+mt
source-git-commit: 3fd50cde86f0dfc5f66d8faf63112adf24beeac0

---


# Versionshinweise{#release-notes}

## Versionshinweise {#topic-a92c3eb799b74e7fa404af8af5efb215}

## Version 0.0.817 May 17, 2019 {#topic-5dc9026cac864330b04361b1da8309a8}

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
   <td colname="col1"> <p>Daten zu Treffern nach der Verarbeitung </p> </td> 
   <td colname="col2"> <p> Es wurde die Möglichkeit hinzugefügt, Werte für Analytics-Treffer nach Ausführung<a href="solutions.md#section-f71dfcc22bb44c86bec328491606a482" format="dita" scope="local"></a> der Verarbeitungsregeln anzuzeigen. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Version 0.0.810 6. März 2019 {#topic-83bb7ddd68594177be9fd7826b650b80}

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
   <td colname="col2"> <p> Auditor-Tests<a href="run-debugger.md#section-82bc57440406461ebf27a16855b71655" format="dita" scope="local"> </a> zum Debugger hinzugefügt </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Adobe Audience Manager </p> </td> 
   <td colname="col2"> <p>Debugger zeigt jetzt AAM-Antworten an </p> </td> 
  </tr> 
 </tbody> 
</table>

## Fehlerkorrekturen {#section-f5e9d54e9d2546afb97972cdb6d8a093}

* Es wurde ein Problem behoben, bei dem die Fußzeile Inhalt am unteren Seitenrand ausblendete.

* Die Debugger-Fußzeile wurde aktualisiert
* Es wurde ein Problem behoben, bei dem veraltete Terminologie für Target verwendet wurde

## Version 0.0.809, 28. Februar 2019 {#topic-6241de45fa9e4a23a95ad4d3a73f7348}

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
   <td colname="col2"> <p> Ersetzen und Einfügen von Einbettungscode durch Teilung. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Verbesserungen {#section-e9e8a6ddedde4c029b1d3d69c009cbad}

* Potenzielle Verwundbarkeit behoben, die durch nicht bereinigte Benutzereingaben verursacht wurde.

## Fehlerkorrekturen {#section-556417ff055848c1bf037354dd43cbd0}

* Problem behoben, bei dem AAM DIL-Ereignisse nicht auf der Registerkarte AAM erfasst wurden

* Es wurde ein Problem beim dynamischen Einfügestart behoben, bei dem die Benutzeroberfläche einem anderen Einbettungscode zugeordnet zu sein schien, obwohl dies nicht der Fall war
* Es wurde ein Problem beim dynamischen Einfügevorgang behoben, bei dem eine schlechte URL weiterhin angezeigt wurde
* Es wurde ein Problem behoben, bei dem der Debugger weiterhin Einbettungscodes ersetzt hat, selbst wenn das Debug-Fenster geschlossen wurde

## Version 0.0.806, 10. September 2018 {#topic-a41c9d1969ff4d06ac3bb4e7d6b6d18a}

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
   <td colname="col1"> <p>Link "Analyse"auf der Registerkarte "Tools" </p> </td> 
   <td colname="col2"> <p>Anzeigenamen für evars/props über die Analytics-API über die IMS-Anmeldung anzeigen. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Dynamischer Start einfügen </p> </td> 
   <td colname="col2"> <p>Auf der Registerkarte Tools können Sie Launch dynamisch auf jeder Seite einfügen, um etwas auf einer Seite zu testen, auf der Launch nicht installiert ist. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Target-Verbesserungen </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_5FCD61733462495D8FB421DE7C813001"> 
      <li id="li_2E8E9AAE5D0D41DC8C42592AFDFA3377">Leistungszeitpunkte für Target-Anforderungen hinzugefügt. </li> 
      <li id="li_98A56E71D72542D694A76DF84CE26AFA">Capture adobe.target.trackEvent </li> 
     </ul> </p> </td> 
  </tr> 
 </tbody> 
</table>

## Verbesserungen {#section-56003a12c32f4998bf1cf2a25a518592}

* Die Anzeige der Registerkarte "Netzwerk"wurde verbessert, sodass die Höhe der Tabelle nicht zu groß wird und der Benutzer einen vertikalen Bildlauf durchführen muss, bevor er horizontal blättern kann. Zuvor wurden die Bildlaufleisten unten in der Tabelle angezeigt. Da die Tabelle ziemlich groß werden konnte, mussten Benutzer vertikal scrollen, um sie zu sehen.
* Link zu ObservePoint wurde auf der Registerkarte "Tools"aktualisiert.

## Fehlerkorrekturen {#section-d9231f5c77254d0888347e5f569a8b1d}

* Es wurde ein Problem behoben, bei dem die Registerkarte Experience Cloud nicht aktualisiert wurde

* Es wurde ein Problem behoben, bei dem "Media Optimizer"in der Lösungszeile auf der Registerkarte "Netzwerk"anstelle des aktuellen Namens "Advertising Cloud"angezeigt wurde
* Es wurde ein Fehler behoben, der dazu führte, dass der Debugger _satellite auf jeder Seite injizierte

## Version 0.0.803, 10. August 2018 {#topic-d2901fb70ce04a5586f6c7a994fce875}

Version 0.0.803 enthält keine kundenrelevanten Änderungen.

## Version 0.0.802, 1. August 2018 {#topic-b93cd396af5e49dc97cd86264871aeb4}

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
   <td colname="col1"> <p>Auditor-Link auf der Registerkarte "Werkzeuge" </p> </td> 
   <td colname="col2"> <p>Hinzufügen eines Links zum Auditor über den Debugger </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Reduzierte Registerkarten </p> </td> 
   <td colname="col2"> <p>Reduzierte Registerkarten bleiben auf den Registerkarten "Zusammenfassung"und "Werkzeug"erhalten </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Zum Anzeigen klicken </p> </td> 
   <td colname="col2"> <p> Neue Funktion zum Anzeigen von Klicks zu allen Registerkarten </p> </td> 
  </tr> 
 </tbody> 
</table>

## Verbesserungen {#section-0e7090e3e6a645f085d4553b983ecff8}

* Name von Media Optimizer in Advertising Cloud geändert
* Entfernte Lösungen aus der Registerkarte Netzwerk, wenn sie nicht gefunden wurden

## Fehlerkorrekturen {#section-7c0e4cc4b00a428489bed4a0a27c9501}

* Korrektur des Problems, bei dem die Funktion "Zu angezeigende Zelle anklicken"nicht aktualisiert wurde
* Es wurde ein Problem behoben, bei dem AAM-Treffer nicht auf der Registerkarte AAM angezeigt wurden

## Version 0.0.798, 14. Juni 2018 {#topic-3b2d44277f2f4c0295d82724c34bf467}

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
   <td colname="col2"> <p>Excel-Exportoption zur Registerkarte "Netzwerk"hinzugefügt. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Verbessertes Erscheinungsbild </p> </td> 
   <td colname="col2"> <p>Die Chrome-Erweiterungsschrift wurde auf Adobe Clean aktualisiert. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Trackpad-Blätterfunktion </p> </td> 
   <td colname="col2"> <p>Die Funktion zum Blättern auf dem Trackpad vor-/zurück wurde deaktiviert. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Indikator für unformatierten Serveraufruf </p> </td> 
   <td colname="col2"> <p>Es wurde ein Indikator hinzugefügt, dass die Zeichenfolge für unformatierte Serveraufrufe kopiert wurde. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Registerkarte "Protokolle bereinigen" </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_D1EB0BE3A01C494983DAAF625562AC62"> 
      <li id="li_2696D26320F54A089D3CC99962EC9670">Lösungen im Lösungsfilter ausblenden, wenn keine Zeilenelemente für diese Lösung in den Protokollen gefunden wurden </li> 
      <li id="li_D4586A6AB2AD42BB9F0FA3E7A01382C6">Blenden Sie den Stufenfilter aus, wenn keine DTM-Aufrufe gefunden wurden, da er nur für DTM gilt. </li> 
      <li id="li_E2AF179037DC4C63B960013AB1F9AD6A">Ändern Sie die Symbole in der Spalte "Ebene", sodass sie nicht anklickbar aussehen, wenn beim Klicken nichts passiert </li> 
      <li id="li_3DB6682D6C9040D99F04C688E208CE1F">Formatierung von "Code anzeigen"für DTM-Zeilenelemente standardisieren </li> 
     </ul> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Link zur Hilfe in Fußzeile aktualisieren </p> </td> 
   <td colname="col2"> <p>Link zur Hilfe in Fußzeile aktualisieren zu <a href="https://marketing.adobe.com/resources/help/en_US/experience-cloud-debugger/" format="https" scope="external"> https://marketing.adobe.com/resources/help/en_US/experience-cloud-debugger/</a> </p> </td> 
  </tr> 
 </tbody> 
</table>

## Fehlerkorrekturen {#section-c292cf7dcb17463bb1928de73bd55121}

* Es wurde ein Problem behoben, bei dem die Kennzeichennummer nicht gelöscht wurde
* Es wurde ein Problem behoben, bei dem ein Kunde eine leere Zusammenfassung meldete

## Version 0.0.797 May 25, 2018 {#topic-51490f4f42aa40eb879663fad9d62916}

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
   <td colname="col1"> <p>mbox Umschalter </p> </td> 
   <td colname="col2"> <p>Mbox-Umschalter wurden zur Registerkarte "Ziel"hinzugefügt </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Filtereinstellungen sind jetzt fixierbar </p> </td> 
   <td colname="col2"> <p>Die Filtereinstellungen bleiben jetzt oben auf dem Bildschirm auf den Registerkarten "Netzwerk"und "Protokolle"erhalten. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Netzwerkwerte anzeigen und kopieren </p> </td> 
   <td colname="col2"> <p>Sie können auf der Registerkarte "Netzwerk"Details anzeigen und den Wert einer beliebigen Zelle kopieren. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Rechtliche Fußzeilenlinks und Copyright </p> </td> 
   <td colname="col2"> <p>Der Benutzeroberfläche wurden legale Fußzeilenlinks und Copyright-Informationen hinzugefügt. </p> </td> 
  </tr> 
 </tbody> 
</table>

