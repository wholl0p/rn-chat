# rn-chat

## Protokoll
UTF-8 kodierte Nachrichten, die mit einem Keyword beginnen. Es folgt ein Leerzeichen und der Inhalt der Nachricht.

| Message | Beschreibung |
| --------- | --------- |
| connect \<name\>    | Client meldet sich bei an |
| ack \<name\>        | Quittieren eines connect |
| end               | Client meldet sich ab |
| pm \<message\>\EOF  | private message |
| gm \<message\>\EOF  | general message |
