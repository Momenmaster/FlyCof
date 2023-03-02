1.Describe a logging system with your own words:

Ein Logging-System ist ein Mechanismus, der es erlaubt, Ereignisse und Informationen über das Verhalten von Software und Systemen zu sammeln, aufzuzeichnen und zu speichern. 
Es handelt sich hierbei um eine wichtige Methode zur Fehlerbehebung und zur Verbesserung der Leistung von Software und Systemen.

Ein Logging-System besteht aus einer Sammlung von Log-Nachrichten, die von der Software oder dem System generiert werden, sowie einem Mechanismus zur Aufzeichnung dieser Nachrichten. 
Die Log-Nachrichten können unterschiedliche Informationen enthalten, wie z.B. Fehlermeldungen, Warnungen, Debug-Informationen oder Metriken zur Leistungsmessung.

Das Logging-System ermöglicht es Entwicklern und Systemadministratoren, die Log-Nachrichten zu sammeln und zu analysieren, um Probleme zu diagnostizieren, Fehler zu beheben und das System zu optimieren. 
Eine gut gestaltete Logging-Strategie kann auch dazu beitragen, die Sicherheit von Systemen zu verbessern, indem sie Angriffe auf das System erkennen und Warnungen ausgeben kann.

Insgesamt ist ein Logging-System ein wichtiger Bestandteil von Software- und Systementwicklung, um die Leistung, Sicherheit und Zuverlässigkeit von Anwendungen und Systemen zu gewährleisten.



2.What is the difference between git submodules and git subtrees?

Git Submodules und Git Subtrees sind zwei Möglichkeiten, um in einem Git-Repository ein anderes Git-Repository zu integrieren.

Git Submodules ermöglichen es, ein externes Repository als Unterverzeichnis innerhalb des Hauptrepositories hinzuzufügen. 
Dabei wird ein Verweis auf das externe Repository im Hauptrepository gespeichert, aber keine Dateien des externen Repositories selbst. 
Beim Klonen des Hauptrepositories müssen die Submodule separat initialisiert und aktualisiert werden.

Git Subtrees ermöglichen es, ein externes Repository in ein Unterverzeichnis innerhalb des Hauptrepositories zu integrieren und dessen gesamten Inhalt in das Hauptrepository zu importieren. 
Dadurch wird das externe Repository zu einem Teil des Hauptrepositories.
Beim Klonen des Hauptrepositories werden auch alle Subtrees mitgeklont.

Der Hauptunterschied zwischen Git Submodules und Git Subtrees besteht darin, dass Git Submodules einen Verweis auf das externe Repository speichern und somit unabhängig von diesem bleiben, während Git Subtrees das externe Repository in das Hauptrepository integrieren und somit von diesem abhängig machen. 
Git Subtrees eignen sich daher besser für Fälle, in denen das externe Repository regelmäßig aktualisiert werden soll und Änderungen daran eng mit dem Hauptrepository verknüpft sind. 
Git Submodules sind dagegen besser geeignet, wenn das externe Repository unabhängig bleiben soll und nicht regelmäßig aktualisiert werden muss.



3.What is a build system in C++? Name 3 build systems: 

Ein Build-System in C++ ist ein Tool, das es ermöglicht, C++-Code automatisiert zu kompilieren, zu linken und in ausführbare Binärdateien oder Bibliotheken zu verwandeln. Ein Build-System kann auch Aufgaben wie die Erstellung von Dokumentation, die Ausführung von Tests und die Bereitstellung von Softwarepaketen übernehmen.

Einige Beispiele für Build-Systeme in C++ sind:

CMake: Ein plattformübergreifendes Build-System, das eine einfache Konfiguration von Builds ermöglicht, indem es eine CMake-Datei verwendet, um die erforderlichen Compiler- und Linker-Einstellungen zu definieren.

Make: Ein Klassiker unter den Build-Systemen, das auf vielen Unix-Systemen standardmäßig installiert ist. Make verwendet Makefiles, um zu definieren, wie Quelldateien zu Objektdateien kompiliert und zu ausführbaren Binärdateien oder Bibliotheken gelinkt werden sollen.

Bazel: Ein Build-System von Google, das eine deklarative Konfiguration von Builds ermöglicht. Es kann verschiedene Programmiersprachen unterstützen, darunter C++ und Java, und ist auf die Skalierbarkeit von Builds in großen Code-Basen ausgelegt.

4.What is a package manager in C++? Name 3 package manager:

Ein Paketmanager ist ein Tool, das es Entwicklern ermöglicht, Bibliotheken und andere Abhängigkeiten in ihren Projekten zu verwalten. Es automatisiert die Installation, Aktualisierung und Deinstallation von Bibliotheken und bietet eine zentrale Möglichkeit, auf eine große Anzahl von Bibliotheken zuzugreifen.

Einige der bekanntesten Paketmanager für C++ sind:

Conan: Ein dezentraler Paketmanager für C++ mit Schwerpunkt auf C++-Bibliotheken und Binärdateien. Conan ist plattformübergreifend und kann auf Windows, Linux und macOS verwendet werden.

vcpkg: Ein Paketmanager von Microsoft, der auf Windows, Linux und macOS verwendet werden kann. Er unterstützt eine breite Palette von Bibliotheken und Tools für C++.

Hunter: Ein weiterer dezentralisierter Paketmanager für C++, der auf Windows, Linux und macOS läuft. Hunter unterstützt auch eine breite Palette von Bibliotheken und Tools für C++.
