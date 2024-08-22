### Testaufgabe 1: VeloCity Plugin mit einem Command `/broadcast`

#### Aufgabe
Wir, das LocoBroko Netzwerk, möchten unsere Kommunikationsmöglichkeiten verbessern, indem wir einen globalen Broadcast-Befehl einführen, der Nachrichten an alle verbundenen Server sendet. Deine Aufgabe ist es, ein VeloCity-Plugin zu entwickeln, das einen solchen Befehl `/broadcast <nachricht>` bereitstellt.

#### Erwartungen

1. **Projektstruktur:**
   - Der Code muss gut strukturiert und ordentlich organisiert sein, wobei verschiedene Klassen und Pakete verwendet werden, um die Logik klar zu trennen.

2. **Versionskontrolle:**
   - Das Projekt soll in einem Git-Repository verwaltet werden, wobei auf saubere Commits und eine nachvollziehbare Commit-Historie geachtet wird.

3. **Build-Tools:**
   - Das Projekt muss mit einem gängigen Build-Tool wie Maven oder Gradle aufgebaut werden.

4. **Programmiersprache:**
   - Die Implementierung soll in Java erfolgen. Alternativ ist auch Kotlin möglich, jedoch nur nach vorheriger Absprache.

5. **Nachrichtenkonfiguration:**
   - Die Nachricht, die mit dem Broadcast-Befehl gesendet wird, muss anpassbar sein. Implementiere eine Konfigurationsdatei, in der der Präfix der Broadcast-Nachricht definiert werden kann.

6. **Beschreibung und Dokumentation:**
   - Füge zu jeder Klasse und Methode entsprechende Javadoc-Kommentare hinzu, die ihre Funktionalität und die Parameter beschreiben.

7. **Performance:**
   - Der Code muss effizient und performant ausgeführt werden, wobei die Ausführungsgeschwindigkeit und Ressourcennutzung optimiert werden sollen.

#### Wichtige Methoden

- `void onCommand(CommandSender sender, String command, String[] args)`: Handhabt den `/broadcast`-Befehl und sendet die Nachricht an alle Server.
- `void sendMessageToAllServers(String message)`: Sendet eine formatierte Nachricht an alle verbundenen Server.

#### Optional

- **Continuous Integration (CI):**
  - Richte einen GitHub Workflow (oder eine ähnliche CI-Lösung) ein, der das Plugin automatisch baut und testet, bevor es bereitgestellt wird.
