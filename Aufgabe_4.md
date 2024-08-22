### Aufgabe 4: Speicherung von Nutzerdaten im Speicher

#### Aufgabe
Das LocoBroko Netzwerk benötigt eine effiziente Methode zur Speicherung von Nutzerdaten im Arbeitsspeicher, um schnelle Zugriffszeiten und eine reibungslose Spielerfahrung zu gewährleisten. Deine Aufgabe ist es, eine Methode zu entwickeln, die die Nutzerdaten eines Spielers (UUID, Name, FirstJoinDatum) im Speicher speichert.

#### Erwartungen

1. **Projektstruktur:**
   - Der Code muss gut strukturiert und ordentlich organisiert sein, wobei verschiedene Klassen und Pakete verwendet werden, um die Logik klar zu trennen.

2. **Versionskontrolle:**
   - Das Projekt soll in einem Git-Repository verwaltet werden, wobei auf saubere Commits und eine nachvollziehbare Commit-Historie geachtet wird.

3. **Build-Tools:**
   - Das Projekt muss mit einem gängigen Build-Tool wie Maven oder Gradle aufgebaut werden.

4. **Programmiersprache:**
   - Die Implementierung soll in Java erfolgen. Alternativ ist auch Kotlin möglich, jedoch nur nach vorheriger Absprache.

5. **Beschreibung und Dokumentation:**
   - Füge zu jeder Klasse und Methode entsprechende Javadoc-Kommentare hinzu, die ihre Funktionalität und die Parameter beschreiben.

6. **Performance:**
   - Der Code muss effizient und performant ausgeführt werden, wobei die Speicheroperationen optimiert werden sollen.

#### Wichtige Methoden

- `void savePlayerData(UUID player, String name, LocalDateTime firstJoinDate)`: Speichert die Nutzerdaten im Speicher.
- `PlayerData getPlayerData(UUID player)`: Ruft die gespeicherten Daten eines Spielers ab.
- `void updatePlayerData(UUID player, String name, LocalDateTime firstJoinDate)`: Aktualisiert die gespeicherten Daten eines Spielers im Speicher.

#### Optional

- **Continuous Integration (CI):**
  - Richte einen GitHub Workflow (oder eine ähnliche CI-Lösung) ein, der das Projekt automatisch baut und testet, bevor es bereitgestellt wird.
