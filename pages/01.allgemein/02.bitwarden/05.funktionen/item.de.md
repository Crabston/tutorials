---
title: "Bitwarden: Funktionen im Detail"
slug: funktionen-im-detail
sitemap:
  changefreq: yearly
  priority: 0.5
  lastmod: 29-07-2025
date: 29-07-2025
taxonomy:
  tag: [ Bitwarden ]
---

!!! In diesem Artikel zeigen wir, wie all die Funktionen von Bitwarden im Detail funktionieren und wie du sie nutzen kannst.

===

! Je nachdem, ob du unseren Server nutzt oder den von Bitwarden, kann es leichte Unterschiede geben. Das Gleiche gilt für verschiedene Plattformen. In diesem Artikel gilt primär die Webversion des aktuellen Crabston Servers als Referenz.

## Übersicht
![Übersicht Bitwarden Webversion von Crabston](overview.png?lightbox)
1. **Tresor**: Hier findest du alle deine gespeicherten Daten
2. **Send**: Hier kannst du Dateien und Notizen sicher teilen
3. **Werkzeuge**: Hier findest du verschiedene nützliche Tools
4. **Berichte**: Hier findest du Berichte zu deinen Passwörtern
5. **Einstellungen**: Hier kannst du deine Einstellungen anpassen
6. **Konto**: Hier findest du Informationen zu deinem Konto

## Tresor
Im Tresor sind alle deine gespeicherten Einträge wie Passwörter, Kreditkarten, Identitäten und Notizen gespeichert. Du kannst diese Daten sortieren und filtern, um sie leichter zu finden:  
![Tresor Übersicht](vault-overview.png?lightbox)
1. **Tresore**: Hier kannst du zwischen verschiedenen Tresoren wechseln, falls du mehrere hast. Weitere Tresore können Gruppentresore (Organisationen) sein, oder von Personen, deren Notfallzugriff aktiv sind.
2. **Einträge**: Hier findest du alle deine gespeicherten Einträge, die du nach Typ filtern kannst.
3. **Ordner**: Hier kannst du deine Einträge nach Ordnern sortieren, um sie leichter zu finden.
4. **Papierkorb**: Hier findest du alle gelöschten Einträge, die du wiederherstellen oder endgültig löschen kannst. Einträge im Papierkorb werden automatisch nach einiger Zeit gelöscht.
5. **Neuer Eintrag**: Hier kannst du einen neuen Eintrag erstellen.
6. **Neu**: Hier kannst du einen neuen Eintrag erstellen, oder einen neuen Ordner anlegen.

### Zugangsdaten erstellen
Zugangsdaten sind Anmeldeinformationen für eine Website oder App. Dies ist die beliebteste Art von Einträgen in Bitwarden.  
![Zugangsdaten erstellen](create-login.png?lightbox&resize=400)
1. **Typ**: Hier kannst du den Typ des Eintrags auswählen, den du erstellen möchtest. Wähle «Zugangsdaten» aus.
2. **Name**: Dies ist der Name des Eintrags, der in der Übersicht angezeigt wird.
3. **Ordner**: Hier kannst du den Ordner auswählen, in dem der Eintrag gespeichert werden soll.
4. **Benutzername**: Hier kannst du den Benutzernamen für den Eintrag eingeben. Dies ist in vielen Fällen die E-Mail-Adresse, die du für die Anmeldung verwendest.
5. **Passwort**: Hier kannst du das Passwort für den Eintrag eingeben. Du kannst auch den Generator verwenden, um ein sicheres Passwort zu generieren und die Komplexität des Passworts überprüfen sowie auf Kompromittierungen prüfen.
6. **TOTP (2FA)**: Hier kannst du einen TOTP-Code (Time-based One-Time Password) hinzufügen, der für die Zwei-Faktor-Authentifizierung verwendet wird. Dies ist optional, aber empfohlen, um die Sicherheit zu erhöhen.
7. **TOTP Code**: Hier wird der TOTP Code angezeigt und wie lange er noch gültig ist. In der Regel ist dieser 30 Sekunden gültig.
8. **URI**: Hier kannst du die URL der Website oder App eingeben, für die du den Eintrag erstellst. So kann dieser bei der Autofill Funktion angezeigt werden.
9. **Notizen**: Hier kannst du Notizen zum Eintrag hinzufügen, wenn es weitere wissenswerte Informationen gibt, die du festhalten möchtest.
10. **Benutzerdefinierte Felder**: Hier kannst du benutzerdefinierte Felder hinzufügen, um weitere Informationen zum Eintrag zu speichern. Dies ist optional und kann für spezielle Anforderungen nützlich sein.
11. **Master Passwort abfragen**: Wenn du diese Option aktivierst, musst du dein Master Passwort eingeben, um den Eintrag anzuzeigen, zu ändern oder auszufüllen. Dies ist optional, aber empfohlen, um die Sicherheit zB bei E-Banking Logins zu erhöhen.
12. **Favorisieren**: Ein Eintrag kann mit einem Stern markiert werden, damit du ihn schneller findest. Bitwarden bietet zudem eine Filterfunktion, und Einträge werden vor allen anderen angezeigt.

### Kreditkarte erstellen
Kreditkarten sind eine weitere Art von Einträgen, die du in Bitwarden speichern kannst. Diese können für Online Zahlungen verwendet werden.  
![Kreditkarte erstellen](create-card.png?lightbox&resize=400)
1. **Typ**: Hier kannst du den Typ des Eintrags auswählen, den du erstellen möchtest. Wähle «Kreditkarte» aus.
2. **Name**: Dies ist der Name des Eintrags, der in der Übersicht angezeigt wird.
3. **Name des Karteninhabers**: Hier kannst du den Namen des Karteninhabers eingeben, der auf der Kreditkarte steht.
4. **Marke**: Hier kannst du die Marke der Kreditkarte auswählen, z.B. Visa, Mastercard, American Express usw. Wird automatisch ausgefüllt, wenn du die Kartennummer eingibst.
5. **Nummer**: Hier kannst du die Kartennummer eingeben.
6. **Ablaufmonat**: Hier kannst du den Ablaufmonat der Kreditkarte eingeben.
7. **Ablaufjahr**: Hier kannst du das Ablaufjahr der Kreditkarte eingeben.
8. **CVV**: Hier kannst du den CVV-Code der Kreditkarte eingeben. Dies ist der Sicherheitscode, der idR. auf der Rückseite der Kreditkarte steht.

### Identität erstellen
Identitäten sind eine weitere Art von Einträgen, die du in Bitwarden speichern kannst. Diese können für Online Formulare verwendet werden, um deine persönlichen Informationen automatisch auszufüllen, wie Name, Adresse, Telefonnummer usw.  
![Identität erstellen](create-identity.png?lightbox&resize=400)
1. **Typ**: Hier kannst du den Typ des Eintrags auswählen, den du erstellen möchtest. Wähle «Identität» aus.
2. **Name**: Dies ist der Name des Eintrags, der in der Übersicht angezeigt wird.
3. Die restlichen Felder können nach Belieben ausgefüllt werden.

### Notiz erstellen
Notizen sind eine weitere Art von Einträgen, die du in Bitwarden speichern kannst, wenn kein Typ passt. Beispiele dafür können Lizenzschlüssel, Seriennummern, Wiederherstellungsschlüssel, Crypto Wallet Adressen, oder andere wichtige Informationen sein, die du sicher speichern möchtest.  
![Notiz erstellen](create-note.png?lightbox&resize=400)
1. **Typ**: Hier kannst du den Typ des Eintrags auswählen, den du erstellen möchtest. Wähle «Notiz» aus.
2. **Name**: Dies ist der Name des Eintrags, der in der Übersicht angezeigt wird.
3. **Notiz**: Hier kannst du die Notiz eingeben, die du speichern möchtest. Dies ist ein freies Textfeld, in dem du beliebige Informationen eingeben kannst.

## Send
Mit Send können Dateien und Text sicher an andere Personen gesendet werden. So müssen Passwörter nicht ungesichert in Klartext an andere Personen weitergegeben werden, sondern können sicher über Bitwarden gesendet werden:
![Send Übersicht](send-overview.png?lightbox)
1. Liste aller aktiven Sends
2. Filter nach Send Typ (Datei oder Text)
3. Neues Send erstellen

### Send erstellen
![Send erstellen](send-create.png?lightbox&resize=400)
1. **Name**: Dies ist der Name des Sends, der in der Übersicht angezeigt wird
2. **Send Art**: Hier kannst du auswählen, ob du eine Datei oder einen Text senden möchtest
3. **Datei auswählen**: Wenn du eine Datei senden möchtest, kannst du hier die Datei auswählen, die du senden möchtest. Beim Text wird hier ein Textfeld angezeigt
4. **Link kopieren**: Wähle aus, ob beim Speichern der Link in die Zwischenablage kopiert werden soll
5. **Löschdatum**: Wie lange das Send gespeichert werden kann, anschliessend wird es gelöscht
6. **Ablaufdatum**: Hier kannst du ein Ablaufdatum für den Send festlegen, nach dem der Send nicht mehr verfügbar ist. Anschliessend kann es bis zum Löschdatum nur noch in der Übersicht angezeigt werden, nicht mehr über den Link.
7. **Max. Zugriffsanzahl**: Hier kannst du die maximale Anzahl an Zugriffen festlegen, bevor der Send nicht mehr verfügbar wird.
8. **Passwort**: Hier kannst du ein Passwort festlegen, das benötigt wird, um den Send zu öffnen. Dies ist optional, aber empfohlen, um die Sicherheit zu erhöhen.
9. **Notizen**: Hier kannst du Notizen zum Send hinzufügen, die nur für dich sichtbar sind.
10. **E-Mail Adresse ausblenden**: Wenn du diese Option aktivierst, wird deine E-Mail Adresse nicht angezeigt.
11. **Send deaktivieren**: Wenn du diese Option aktivierst, wird der Send deaktiviert und kann nicht mehr geöffnet werden. Kann nur noch in der Übersicht angezeigt werden.

## Werkzeuge
Nutze die Werkzeuge, um deine Passwörter und andere Daten zu verwalten und zu generieren.

### Generator
Der Generator kann genutzt werden, um sichere, zufällige Passwörter generieren zu lassen. Es gibt verschiedene Optionen, welche Zeichen verwendet werden sollen, wie Gross- und Kleinbuchstaben, Zahlen und Sonderzeichen. Zudem kann die Länge des Passworts angepasst werden. 

Neben Passwörter kann der Generator auch Benutzernamen und E-Mail Adressen generieren, sogar mit Anbindungen an Drittanbieter, die Adressweiterleitungen bereitstellen.

### Daten importieren
Auf dieser Seite kannst du Daten in deinen Tresor importieren, um beispielsweise von einem anderen Passwort-Manager zu Bitwarden zu wechseln. Du kannst verschiedene Formate importieren, darunter CSV, JSON und andere. 

### Tresor exportieren
Auf dieser Seite kannst du deinen Tresor exportieren, um eine manuelle Sicherungskopie deiner Daten zu erstellen.

**Diese Daten sind nicht verschlüsselt und beinhalten sensible Informationen wie Passwörter in Klartext. Sollte nur in Ausnahmefällen verwendet werden, wenn du beispielsweise deinen Tresor auf einen anderen Bitwarden Server importieren möchtest oder zu einem anderen Passwort Manager wechselst. Anschliessend sollte die Datei sicher gelöscht werden.**

## Berichte
Berichte ist eine Funktion, welche deine Passwörter und weitere Daten analysiert und überprüft, um dir zu helfen, deine Sicherheit zu verbessern. Es gibt folgende Berichte:
- **Kompromittierte Passwörter**: Überprüft, ob deine Passwörter in einem Datenleck gefunden wurden. Wenn ja, solltest du diese Passwörter ändern, um deine Konten zu schützen.
- **Wiederverwendete Passwörter**: Zeigt identische Passwörter an, die du für mehrere Konten verwendest. Es ist wichtig, dass du für jedes Konto ein einzigartiges Passwort verwendest, um die Sicherheit zu erhöhen.
- **Schwache Passwörter**: Zeigt Passwörter an, die leicht zu erraten sind. Diese Passwörter sollten geändert werden, um die Sicherheit deiner Konten zu erhöhen.
- **Ungesicherte Websites**: Zeigt Websites an, die du mit `http://` anstelle von `https://` gespeichert hast. Websites, die mit `http://` beginnen, werden nicht verschlüsselt und Daten können abgefangen werden.
- **Inaktive Zwei-Faktor-Authentifizierung**: Überprüft, ob gespeicherte Websites Zwei-Faktor-Authentifizierung unterstützen und du keinen Passkey oder TOTP aktiviert hast.
- **Datendiebstahl**: Überprüft, ob deine E-Mail Adresse in einem Datenleck gefunden wurde und wenn ja, welche Websites betroffen sind. Falls ja, solltest du deine Passwörter umgehend ändern, um deine Konten zu schützen.

## Einstellungen
In den Einstellungen findest du folgende Funktionen:
- [Kontoeinstellungen](#kontoeinstellungen)
- [Sicherheit](#sicherheit)
	- [Master Passwort](#master-passwort)
	- [Zwei Faktor Authentifizierung](#zwei-faktor-authentifizierung)
	- [Geräte](#geraete)
	- [Schlüssel](#schluessel)
- [Einstellungen](#einstellungen)
- [Domainregeln](#domainregeln)
- [Notfallzugriff](#notfallzugriff)
  - [Notfallkontakt hinzufügen](#notfallkontakt-hinzufuegen)

### Kontoeinstellungen
In den Kontoeinstellungen kannst du deine Kontodaten verwalten und wichtige Sicherheitsoperationen durchführen:  
![Konto Einstellungen](settings-account.png?lightbox)  
1. **Name**: Hier kannst du deinen Namen ändern, der in Bitwarden angezeigt wird
2. **E-Mail-Adresse**: Dies ist die E-Mail-Adresse, die mit dem Konto verknüpft ist.
3. **Profil**: Hier kannst du die Profilfarbe ändern
4. **Fingerabdruck**: Dies ist die ID deines Kontos und wird für diverse Sicherheitsfunktionen verwendet
5. **E-Mail Adresse ändern**: Hier kannst du deine E-Mail-Adresse ändern, die mit dem Konto verknüpft ist
6. **Sitzungen abmelden**: Über diesen Knopf wirst du von allen Geräten abgemeldet. Nützlich, wenn du Zugriff auf ein Gerät verloren hast oder dein Konto kompromittiert wurde.
7. **Tresor leeren**: Hier kannst du deinen Tresor leeren, was alle gespeicherten Daten löscht. _Dies ist eine irreversible Aktion und sollte nur durchgeführt werden, wenn du sicher bist, dass du deine Daten nicht mehr benötigst._
8. **Konto löschen**: Hier kannst du dein Konto löschen, was ebenfalls alle gespeicherten Daten löscht. _Dies ist eine irreversible Aktion und sollte nur durchgeführt werden, wenn du sicher bist, dass du dein Konto nicht mehr benötigst._

### Sicherheit
In den Sicherheitseinstellungen kannst du verschiedene Sicherheitsfunktionen aktivieren und verwalten.

#### Master Passwort
Auf dieser Seite kannst du dein Master Passwort ändern, das du bei der Anmeldung verwendest:  
![Master Passwort ändern](settings-security-masterpw.png?lightbox)
1. **Master Passwort ändern**: Hier kannst du dein Master Passwort ändern, das du bei der Anmeldung verwendest. Dazu benötigst du dein aktuelles und das neue, welches du zur Sicherheit zweimal eingeben musst.
2. **auf Diebstähle prüfen**: Diese Option kannst du aktivieren, dass du benachrichtigt wirst, wenn dein Master Passwort in einem Datenleck gefunden wurde. Dies ist eine nützliche Funktion, um sicherzustellen, dass dein Konto nicht kompromittiert werden könnte.
3. **Verschlüsselung erneuern**: Damit wird ein geheimer Schlüssel verändert, mit dem deine Daten verschlüsselt werden. Dies ist eine nützliche Funktion, wenn du dein Master Passwort geändert hast und sicherstellen möchtest, dass deine Daten mit dem neuen Passwort verschlüsselt sind.
4. **Hinweis**: Hier kannst du einen Hinweis zu deinem Master Passwort ändern, der dir hilft, dich an dein Passwort zu erinnern, falls du es vergessen hast. Dieser Hinweis wird an die E-Mail des Kontos gesendet, wenn du diesen anforderst.

#### Zwei Faktor Authentifizierung
Auf dieser Seite kannst du die Zwei Faktor Authentifizierung (2FA) für dein Konto aktivieren:  
![Zwei Faktor Authentifizierung](settings-security-2fa.png?lightbox)
1. **Wiederherstellungs-Schlüssel anzeigen**: Dies ist ein geheimer Schlüssel, den du benötigst, um dein Konto wiederherzustellen, falls du den Zugriff auf dein 2FA Gerät verlierst. Dieser sollte sicher aufbewahrt werden.
2. **Anbieter**: Hier kannst du den Anbieter auswählen, den du für die Zwei Faktor Authentifizierung verwenden möchtest. Bitwarden unterstützt verschiedene Methoden wie E-Mail, Authenticator Apps (TOTP), Passkeys (digitaler Sicherheitsschlüssel) und physische Sicherheitsschlüssel.

#### Geräte
Auf dieser Seite findest du eine Liste von allen Geräten, auf denen du angemeldet bist:  
![Geräte](settings-security-devices.png?lightbox)

#### Schlüssel
! Nur für fortgeschrittene Benutzer, die wissen, was sie tun. Andernfalls kann dies zu Problemen und Datenverlust führen.
Auf dieser Seite können Einstellungen für den Schlüssel getätigt werden, die für die Sicherheit deines Kontos verwendet werden:  
![Schlüssel](settings-security-key.png?lightbox)

### Einstellungen
In diesen Einstellungen kannst du das Verhalten und Aussehen von Bitwarden anpassen:  
![Einstellungen](settings-settings.png?lightbox)
1. **Timeout**: Hier kannst du die Zeit einstellen, nach der die Timeout Aktion ausgeführt wird, wenn du inaktiv bist.
2. **Timeout Aktion**: Hier kannst du die Aktion auswählen, die ausgeführt wird, wenn das Timeout erreicht ist. Du kannst zwischen "Sperren", "Abmelden" wählen.
3. **Sprache**: Hier kannst du die Sprache von Bitwarden ändern.
4. **Website Symbole**: Hier kannst du die Anzeige von Website-Symbolen in der App aktivieren oder deaktivieren.
5. **Design**: Hier kannst du das Design von Bitwarden ändern, um es an deine Vorlieben anzupassen.

### Domainregeln
In den Domainregeln kannst du festlegen, welche Domains von Websites gleich behandelt werden sollen, um beispielsweise Passwörter automatisch auszufüllen:  
![Domainregeln](settings-domainrules.png?lightbox)
1. Füge eine neue Domainregel hinzu, indem du auf den Button "Neue Domainregel" klickst

### Notfallzugriff
Über den Notfallzugriff kannst du konfigurieren, wer Zugriff auf dein Konto erhält, falls du nicht mehr in der Lage bist, darauf zuzugreifen:  
![Notfallzugriff](settings-emergencyaccess.png?lightbox)
1. **Vertrauenswürdige Kontakte**: Hier werden Personen angezeigt, für die du den Notfallzugriff aktiviert hast.
2. **Als Notfallkontakt bekannt**: Hier werden Personen angezeigt, die dich als Notfallkontakt festgelegt haben.

!!! _weitere Informationen findest du auf der Seite [Bitwarden: Notfallzugriff](../notfallzugriff)_

#### Notfallkontakt hinzufügen
Um einen Notfallkontakt hinzuzufügen, klicke auf den Button "Notfallkontakt hinzufügen":  
![Notfallkontakt hinzufügen](settings-emergencyaccess-add.png?lightbox)
1. **E-Mail-Adresse**: Hier gibst du die E-Mail-Adresse des Notfallkontakts ein, der Zugriff auf dein Konto erhalten soll. Muss ein Bitwarden Konto auf demselben Server haben.
2. **Benutzerzugriff**: Hier kannst du festlegen, ob der Notfallkontakt die Einträge nur anzeigen kann oder ob er das volle Konto übernehmen kann und dein Master Passwort zurücksetzen kann.
3. **Wartezeit**: Hier kannst du die Wartezeit festlegen, nach der der Notfallkontakt Zugriff auf dein Konto erhält.

## Profil
Klicke auf dein Profil, um auf weitere Funktionen zuzugreifen:  
![Profil](profile.png?lightbox)
1. **Server URL**: Dies ist die Server URL, die du bei der Anmeldung nutzen musst
2. **Kontoeinstellungen**: Hier kannst du deine Kontodaten verwalten
3. **Apps herunterladen**: Über diesen Link gelangst du zur Downloadseite von Bitwarden, wo du die Apps für verschiedene Plattformen herunterladen kannst
4. **Sperren**: Hier kannst du Bitwarden sperren, um es vor unbefugtem Zugriff zu schützen. Anschliessend muss das Master Passwort eingegeben werden, um Bitwarden wieder zu entsperren.
5. **Abmelden**: Hier kannst du dich von deinem Bitwarden Konto abmelden.

