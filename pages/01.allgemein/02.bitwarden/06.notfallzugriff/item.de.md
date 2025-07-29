---
title: "Bitwarden: Notfallzugriff"
slug: notfallzugriff
sitemap:
  changefreq: yearly
  priority: 0.5
  lastmod: 29-07-2025
date: 29-07-2025
taxonomy:
  tag: [ Bitwarden ]
---

!!! In diesem Artikel wird beschrieben, wie der Notfallzugriff in Bitwarden funktioniert.

===

Der Notfallzugriff in Bitwarden ermöglicht es auf eine sichere Weise, dass vertrauenswürdige Kontakte im Falle eines Notfalls Zugriff auf das Konto erhalten, ohne dabei das Master Passwort oder andere sensible Informationen kennen zu müssen.

## Wie funktioniert der Notfallzugriff?
Der Besitzer eines Bitwarden Kontos kann vertrauenswürdige Kontakte festlegen, die im Falle eines Notfalls Zugriff auf das Konto erhalten. Diese Kontakte müssen ebenfalls Bitwarden Nutzer auf dem gleichen Server sein, und im Voraus festgelegt werden. Dabei gibt es verschiedene Einstellungen, die der Kontoinhaber vornehmen kann, um den Zugriff zu steuern, diese werden hier beschrieben: [Notfallkontakt hinzufügen | Bitwarden: Funktionen im Detail](../funktionen-im-detail#notfallkontakt-hinzufuege).

Mit diesen Zugriffseinstellungen, kann ein Notfallkontakt nicht einfach so auf das Konto zugreifen, sondern muss zunächst eine Anfrage stellen. Der Kontoinhaber erhält dann eine Benachrichtigung per E-Mail und kann die Anfrage manuell genehmigen oder ablehnen. Erst nach Genehmigung hat der Notfallkontakt Zugriff auf das Konto. Ist der Notfallkontakt einmal genehmigt, hat dieser Zugriff auf das Konto, bis der Kontoinhaber den Zugriff widerruft.

ist der Kontoinhaber nicht in der Lage, die Anfrage zu genehmigen, beispielsweise weil er im Krankenhaus liegt oder verstorben ist, kann der Notfallkontakt nach einer festgelegten Wartezeit automatisch Zugriff auf das Konto erhalten. Diese Wartezeit kann in den Einstellungen des Notfallkontakts angepasst werden. So wird sichergestellt, dass der Notfallkontakt in einer Situation, in der der Kontoinhaber nicht reagieren kann, dennoch Zugriff auf wichtige Informationen erhält, aber nicht sofort, um Missbrauch zu verhindern, wenn der Kontoinhaber für einen Moment nicht erreichbar ist.

## Was muss ich beachten?
Wir empfehlen, mehrere Notfallkontakte festzulegen, um sicherzustellen, dass im Falle eines Notfalls immer jemand Zugriff auf das Konto hat. Dabei kann man festlegen, dass einige Kontakte früher Zugriff haben als andere. Zudem ist es wichtig, diese Liste an Notfallkontakten aktuell zu halten.

## Wie füge ich einen Notfallkontakt hinzu?
Um einen Notfallkontakt hinzuzufügen, gehe zu den Einstellungen deines Bitwarden Kontos und wähle den Bereich "Notfallzugriff". Dort kannst du einen neuen Notfallkontakt hinzufügen, indem du die E-Mail-Adresse des Kontakts eingibst und die gewünschten Einstellungen für den Zugriff festlegst. Der Kontakt muss ebenfalls ein Bitwarden Nutzer sein und auf dem gleichen Server registriert sein.

Anschliessend erhält der Kontakt eine Benachrichtigung über E-Mail, dass er als Notfallkontakt eingeladen wurde. Der Kontakt muss die Einladung annehmen, um als Notfallkontakt hinzugefügt zu werden.

Zuletzt muss dieser Notfallkontakt vom Kontoinhaber genehmigt werden, dann gilt er als aktiv und kann eine Anfrage stellen, um im Notfall Zugriff auf das Konto zu erhalten.

## Wie bekomme ich als Notfallkontakt Zugriff?
Wenn du als Notfallkontakt Zugriff auf das Konto benötigst, kannst du eine Anfrage stellen, indem du dich in dein Bitwarden Konto einloggst und den Bereich "Notfallzugriff" aufrufst. Dort findest du die Option, eine Anfrage zu stellen. Diese Anfrage wird an den Kontoinhaber gesendet, der dann manuell entscheiden kann, ob er dir den Zugriff gewährt oder nicht. 

Andernfalls wird die Anfrage nach Ablauf der festgelegten Wartezeit automatisch genehmigt.

Als Notfallkontakt mit Lesezugriff findest du die Einträge über den Notfallzugriff. Wenn du zur Übernahme berechtigt bist, wirst du dazu aufgefordert, ein neues Master Passwort zu setzen, um das Konto zu übernehmen. Danach kannst du dich mit dem neuen Master Passwort einloggen und das gesamte Konto verwalten.
