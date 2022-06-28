# Exposé

## Aufgabe 
Als Hausarbeit soll ein Problem aus meinem beruflichen Alltag, in dem Prozesse automatisiert oder Daten analysiert werden, mit Python als Script oder Jupyter Notebook gelöst werden.

## Problemstellung
In meinem Arbeitsalltag gibt es nicht viele Situatuionen, in dem Prozesse automatisiert werden können oder Daten anaylsiert werden müssen.
Eine Aufgabe, die diesen Kriterien entspricht, ist das monatliche Analysieren der Nutzung des Online-Angebots der Teaching Library der Badischen-Landesbibliothek auf Moodle.
Dies möchte ich in meiner Hausarbeit automatisieren.
Der Vorgang stellt sich wie folgt dar:
Es muss monatlich eine Analyse der Nutzung unserer Online-Angebote auf Moodle durchgeführt werden. Hierzu werden die Logdaten der einzelnen Kurse runtergeladen und dann ausgewertet. Die Logdaten werden in einer Excel-Tabelle ausgegeben. Es gibt jedoch auch die Möglichkeit, die Daten in anderen Dateiformaten auszugeben. Herauszufinden, welches Dateiformat sich am besten für mein Vorhaben eignet, wird Bestandteil der Hausarbeit sein. Zu der Auswertung gehört es, die Daten des entsprechenden Monats zu selektieren, da in der ausgegebenen Datei immer die Logdaten aller Zugriffe seit der Freischaltung des Online-Kurses angezeigt werden. Aus dieser selektierten Tabelle werden bisher nun alle Spalten entfernt, die nicht benötigt werden. Dies sind zum Beispiel die Spalten, in denen angezeigt wird, welche Schritte ein Nutzer durchgeführt hat oder ob es sich um einen Gastnutzer oder einen angemeldeten Nutzer handelt. Es werden nun nur noch die IP-Adressen der Nutzer angezeigt. Bei diesem Schritt werde ich vom bisherigen Vorgehen abweichen und die Spalte, in der der Status der Nutzer (also Gast oder angemeldet) angezeigt wird, behalten. Der Grund dafür wird später ausgeführt.
Diese IP-Adressen werden in dieser Liste jedoch mehrmals angezeigt, da jeder Schritt, der von den Nutzern im Online-Kurs durchgeführt wird, als eigene Zeile angezeigt wird. Dies verfälscht das Ergebnis der Auswertung und muss deshalb bereinigt werden. Es müssen also die Dubletten rausgefiltert werden.
Die Zahl an IP-Adressen, die nun angezeigt wird, ist die Anzahl an Nutzern, die den Online-Kurs im aufgewählten Monat genutzt haben.
Zusätzlich möchte ich die Daten getrennt nach Gastnutzern und angemeldeten Nutzern anzeigen lassen. Dies wird bisher noch nicht statistisch erfasst, aber ich denke, das dies eine sinnvolle Erweiterung der Statistik ist.
Dieser Vorgang muss monatlich und für jeden Kurs einzeln durchgeführt werden. Dies ist nötig, da die Direktion eine monatliche Nutzungsstatistik führt und auch die IT über die Nutzung des Angebots informiert werden will.
Da dieser Vorgang jeden Monat nach dem gleichen Schema durchgeführt werden muss und ich denke, dass er sich gut automatisieren lässt, möchte ich dies in meiner Hausarbeit durchführen.

## Arbeitsschritte
- Daten des aktuellen Monats herausfiltern
- Nur die relevanten Spalte der Tabelle anzeigen lassen
- Dubletten in den IP-Adressen bereinigen
- Nutzerzahlen der Gastnutzer und angemeldeten Nutzer getrennt anzeigen lassen
 

## Ergebnis
Durch die Automatisierung kann die monatliche Analyse der Nutzung der Online-Angebote ressourcenschonend durchgeführt werden. Dies ist besonders wichtig, da aktuell viele neue Kurse in Moodle durch die Teaching-Library entwickelt werden und diese regelmäßig analysiert werden müssen. Einerseits möchte die Direktion und die IT die Zahlen für ihre Statistiken, andererseits sind diese Zahlen auch wichtig, um die Kurse weiter zu entwickeln und zu beobachten, wie sich die Nutzung im Laufe der Zeit entwickelt. 
Eine Automatisierung wird hier viel Zeit einsparen.


