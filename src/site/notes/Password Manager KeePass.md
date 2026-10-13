---
{"dg-publish":true,"permalink":"/Password Manager KeePass/","created":"2026-08-23T16:25:56.424+02:00","updated":"2026-10-08T10:38:09.531+02:00","dg-note-properties":{}}
---

Bitwarden enshittifies, erwähnt hier: [[Enshittification explained\|Enshittification explained]]

---
Der Bund empfielt KeePass [Link](https://www.bit.admin.ch/de/keepassxc-de-81)

KeePass ist ein open source Ökosystem mit verschiedensten Clients für alle gebräuchlichen OS sowie verschiedensten Plugins. Der "offizielle" Client ist "KeePass", bzw. "KeePass 2". 
KeePassXC ist der beliebteste und reichhaltigste Community-Client. (Hier eine [Liste](https://github.com/lgg/awesome-keepass) mit Clients (ev. veraltet).)

Die KeePass Datenbanken aus Clients der Version 2.x haben die Dateiendung **.kdbx**. Die veralteten 1.x Clients machem .kbd Datenbanken, die wollen wir nicht.

Alles in allem praktisch eine perfekte Alternative für Bitwarden. 
Ausser dass... 
KeePass keine zentralen Server hat, man sich also selber um die Synchronisation kümmern muss. 

## Synchronisation
Jedes Gerät hat eine lokale Version der Datenbank (C:/ordner/etwas.kdbx). Auf deiner Cloud liegt die Datenbank ebenfalls. Die lässt man vom Cloud-Client auf das Gerät synchronisieren (C:/dropbox/etwas.kdbx), KeePass synct dann die beiden Versionen. Je nach Client in bestimmten Zeit-Abständen oder immer beim Öffnen/Schliessen des Clients. 

Da KeePass ursprünglich als lokale Lösung gedacht ist, funktioniert es auch gut, wenn man mal kein Internet hat und nur sporadisch synct. 
KeePass kann dann selber die [Datenbanken mergen](https://keepass.info/help/v2/sync.html). 

Falls zusätzlich noch eine Schlüsseldatei genutzt wird, muss die natürlich auch noch gesynct werden. Schlüsseldateien sind jedoch optional.

Somit bleibt der einzige Nachteil zu Bitwarden das Einloggen auf einem neuen Gerät. Man muss zusätzlich zum Herunterladen des Passwortmanagers nämlich auch noch die .kdbx Datei herunterladen (sozusagen dann read only) oder den Cloud-Client installieren um es zu syncen.
Bei solchen Use-Cases ist es ein Downgrade. -> Internet-Lounge (Erupt), in einer VM oder sonst einer Testumgebung wo man die Passwörter braucht aber die ganze Cloud Synchronisation nicht einrichten möchte.
Ein Workaround wäre, einen Snapshot des Tresors auf einem Stick mitzunehmen.

## Umzug von Bitwarden zu KeePass

Von [Redditor](https://www.reddit.com/r/Bitwarden/comments/17t6d0f/my_summary_of_bitwarden_backup_options/?solution=b267499ca4ce5f3fb267499ca4ce5f3f&js_challenge=1&token=bbbe4bf1c9a2b5160829c4be34da58612506e2774efa6931790929be7e910277&jsc_orig_r=&share_id=f6Z6tNmUAZoncoZR5l5j3&utm_medium=android_app&utm_name=androidcss&utm_source=share&utm_term=1): Bitwarden unencrypted export und dann das bei KeePass importieren.
Je nach KeePass Client entweder json oder csv. Wobei die KeePassXC, der wohl beste Community-Client, den Bitwarden *.json (encrypted)* möchte und den einwandfrei importieren kann. 


#tech #guide #kampagnen/FOSS 