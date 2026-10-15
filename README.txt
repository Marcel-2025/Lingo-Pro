LINGO PRO – PREMIUM LANDINGPAGE (DE/EN)
====================================

Enthalten:
- index.html          Landingpage, responsive, DE/EN, interaktive Beispielübung
- privacy.html        Datenschutz-ENTWURF, DE/EN, eigene öffentlich erreichbare URL
- delete-account.html  Kontolöschungs-Anfrageseite (Verfahren unbedingt prüfen)
- impressum.html      Impressum-ENTWURF
- styles.css / site.js
- assets/lingo-owl.webp, assets/favicon.png

WICHTIG: DIE RECHTLICHEN SEITEN SIND NOCH NICHT FERTIG / COMPLIANCE-VERIFIZIERT.
Die HTML-Quellen der bisherigen Datenschutzerklärung nennen Firebase Authentication,
Firestore und Firebase Analytics. Ob diese Dienste in der relevanten veröffentlichten
Version tatsächlich eingebunden sind, wurde NICHT überprüft. Ebenso ist die
Wirksamkeit einer Account-Löschung noch nicht verifiziert.

VOR EINER VERÖFFENTLICHUNG VERBINDLICH PRÜFEN:
[x] Adresse und angegebener Name (Marcel S. / Flondy) sind in
    privacy.html und impressum.html auf Deutsch und Englisch eingetragen.
[ ] Vor Veröffentlichung überprüfen, ob „Marcel S.“ durch den vollständigen
    bürgerlichen Namen ersetzt werden muss. Nur die Initiale ist für
    rechtliche Anbieterangaben möglicherweise nicht ausreichend.
[ ] Datenschutzseite gegen tatsächliche Android-App-Version und Firebase-Konfiguration
    prüfen: erfasste Daten, Zwecke, Anbieter, Rechtsgrundlagen, Einwilligung,
    internationale Transfers, Aufbewahrungs-/Backup-Fristen, Deletion, SDKs.
[ ] Firebase Analytics/Crashlytics, AdMob, Google Sign-In, Logs nur erwähnen,
    sofern sie tatsächlich aktiv sind; ggf. präzise Informationen ergänzen.
[ ] Account-Erstellung? Wenn ja: funktionierende Kontolöschung (auch innerhalb der
    App und über Webweg) nach Google-Richtlinien sicherstellen; Firestore + Auth
    und zugehörige personenbezogene Daten berücksichtigen.
[ ] Datenschutzerklärung im Browser öffentlich ohne Login abrufbar machen und
    in der App selbst an geeigneter Stelle verlinken (z. B. Einstellungen).
[ ] Data safety / Datensicherheit in der Play Console konsistent ausfüllen.
[ ] Homepage-Funktionsbeschreibungen gegen reale APK testen. Website-Demo ist
    ausdrücklich nur ein Website-Beispiel und kein Android-Screenshot.
[ ] Keine erfundenen Bewertungen, Nutzerzahlen, Leistungsclaims, Premium-Preise.
[ ] Google-Play-Link erst einbauen, wenn es eine tatsächlich verfügbare neue
    App nach erfolgter Prüfung gibt. Derzeit ist die alte App gesperrt.
[ ] Rechtliche Texte ggf. professionell prüfen lassen.

GITHUB PAGES:
1. Alle Dateien und den Ordner assets/ ins ROOT des Lingo-Pro GitHub-Repos hochladen.
2. In GitHub Settings > Pages die Bereitstellung für den richtigen Branch + Root
   aktivieren bzw. bestehende GitHub Pages Veröffentlichung abwarten.
3. Die Website liegt voraussichtlich unter:
   https://marcel-2025.github.io/Lingo-Pro/
4. Die Datenschutz-URL (erst NACH Veröffentlichung testen!) lautet:
   https://marcel-2025.github.io/Lingo-Pro/privacy.html
5. Die Anfrageseite für Kontolöschung lautet:
   https://marcel-2025.github.io/Lingo-Pro/delete-account.html
6. Nach dem Deploy URLs in normalem Browser/Inkognito ohne GitHub-Anmeldung testen.
7. NICHT bloß die Landingpage als Datenschutz-URL in Play Console eintragen.

Technisch: Reine statische HTML/CSS/JS-Dateien. Keine npm-Installation nötig.
Keine Browser-Analytics, Cookies oder externen Schriftarten in der neuen Seite.
Das verwendete Lingo-Eulenbild stammt aus den vorhandenen Lingo-Bilddateien.

Google-Richtlinien, Nachlesen:
https://support.google.com/googleplay/android-developer/answer/10144311?hl=de
https://support.google.com/googleplay/android-developer/answer/10787469?hl=de
