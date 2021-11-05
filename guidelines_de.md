# Richtlinien für Deutsch
Dies sind die generellen Richtlinien für die deutsche Übersetzung von Revolt.  
Du kannst diese mehr als eine empfehlung sehen.

## Verwende die Du-form
Übersetzungen, welche eine Person (Den Benutzer) ansprechen sollten in der Du-form verfasst sein.  
Revolt ist mehr persöhnlich als formal und höflich.

Beispiel:  
```patch
# You don't have permission to send messages in this channel.

+ Du hast nicht die nötigen Berechtigungen, Nachrichten in diesem Kanal zu versenden.
- Sie haben nicht die nötigen Berechtigungen, Nachrichten in diesem Kanal zu versenden.
```

## Verwende nur ein geschlecht
Wenn ein Wort sowohl eine männliche als auch eine weibliche Variante hat, sollte nur eine verwendet werden.  
Begriffe wie `Benutzer:in` machen nur das lesen schwerer und bringen keinen nutzen. Niemand wird sich aufregen wenn nur `Benutzer` steht statt `Benutzer:in` und wenn doch, dann müsste man sich auch über das fehlen von `Benutzenden` aufregen, was eh keiner tut.

Beispiel:  
```patch
# User

+ Benutzer
- Benutzer:in
```

## Bleib der Übersetzung treu
Versuch nicht wörter hinzuzufügen oder gar welche wegzunehmen. Wenn das original `<Unknown User>` sagt sollte die Übersetzung nicht einfach `<Unbekannt>` sein, da dadurch verloren geht, wer oder was gemeint ist.

Beispiel:  
```patch
# <Unknown User>

+ <Unbekannter Benutzer>
- <Unbekannt>
```
