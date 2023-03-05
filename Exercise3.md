What is the difference between a dynamic linked library and a static library?

Eine statische Bibliothek ist eine Sammlung von vorkompiliertem Code, die zusammen mit dem ausführbaren Code in eine ausführbare Datei eingebettet wird. 
Das bedeutet, dass alle Funktionen und Abhängigkeiten in der ausführbaren Datei vorhanden sind, was sie portabel und einfach zu verteilen macht. 
Allerdings können Änderungen an der Bibliothek nicht ohne eine Neu-Kompilierung der gesamten ausführbaren Datei vorgenommen werden.
Eine dynamische Bibliothek ist eine Datei, die zur Laufzeit des Programms geladen wird, wenn die Funktionen benötigt werden. 
Dies reduziert die Größe der ausführbaren Datei und ermöglicht es, die Bibliothek separat zu aktualisieren, ohne die ausführbare Datei neu zu kompilieren. 
Allerdings müssen die notwendigen Bibliotheken zur Laufzeit verfügbar sein, was manchmal eine Herausforderung sein kann.


Describe a logging system with your own words:
Ein Logging-System ist ein Programmteil, der Informationen über das Verhalten und den Status eines Programms aufzeichnet und speichert. 
Es kann dabei helfen, Fehler und Probleme im Programm zu identifizieren und zu beheben, da es Informationen darüber liefert, was während der Ausführung passiert ist.
Es gibt verschiedene Arten von Informationen, die in einem Log-System gespeichert werden können, wie beispielsweise Fehlermeldungen, Warnungen, Debugging-Informationen oder Benutzeraktionen. 
Diese Informationen können in verschiedenen Formaten gespeichert werden, wie zum Beispiel Textdateien oder Datenbanken.
Ein Logging-System kann auch konfiguriert werden, um nur bestimmte Arten von Informationen zu protokollieren oder auf bestimmte Ereignisse zu reagieren. 
Zum Beispiel kann es so eingestellt werden, dass es eine Benachrichtigung sendet, wenn ein schwerwiegender Fehler auftritt.
Einige Beispiele für Logging-Systeme in der Programmierung sind Log4j, Logback und Boost.Log.


What is a Design Pattern?
Ein Design Pattern ist eine bewährte Lösung für ein wiederkehrendes Problem in der Softwareentwicklung. 
Es ist wie eine Vorlage oder ein Bauplan, der bei der Erstellung von Software verwendet werden kann. 
Es beschreibt die Struktur, die Beziehungen und die Interaktionen zwischen den verschiedenen Komponenten eines Systems. 
Durch die Verwendung von Design Patterns können Entwickler Zeit sparen, indem sie bereits erprobte Lösungen verwenden, anstatt jedes Mal von Grund auf neu zu beginnen.


Name and describe 2 Design Patterns (except façade or adapter):
Singleton Pattern: Dieses Muster wird verwendet, um sicherzustellen, dass eine Klasse nur eine einzige Instanz hat, die global verfügbar ist. Es wird oft für Objekte verwendet, die nur einmal erstellt werden sollten, wie z.B. für eine Konfigurationsdatei.
Ein Beispiel dafür wäre eine Klasse, die Zugriff auf eine Datenbank hat. Hier möchte man sicherstellen, dass immer nur eine Verbindung zur Datenbank besteht und nicht versehentlich mehrere Instanzen der Verbindungsklasse erzeugt werden.

Observer Pattern: Dieses Muster wird verwendet, um eine "ein-zu-viele"-Beziehung zwischen Objekten herzustellen. Ein Objekt, das den Status ändert, informiert alle seine abhängigen Objekte darüber, dass sich der Status geändert hat.
Ein Beispiel wäre ein System, das Wetterdaten erfasst. Die "Observable"-Klasse könnte hier die Wetterstation sein, die bei Änderungen der Messdaten alle "Observer" informiert, die beispielsweise die Wettervorhersage berechnen oder Grafiken aktualisieren.
