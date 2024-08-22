### Aufgabe 2: Eine Simple CoinAPI

#### Aufgabe
Das LocoBroko Netzwerk benötigt eine einfache und flexible API zur Verwaltung von Ingame-Währungen. Deine Aufgabe ist es, eine CoinAPI zu entwickeln, die es ermöglicht, die Coins eines Spielers zu setzen, abzurufen, hinzuzufügen und zu entfernen.

#### Erwartungen

1. **Projektstruktur:**
   - Der Code muss gut strukturiert und ordentlich organisiert sein, wobei verschiedene Klassen und Pakete verwendet werden, um die Logik klar zu trennen.

2. **Versionskontrolle:**
   - Das Projekt soll in einem Git-Repository verwaltet werden, wobei auf saubere Commits und eine nachvollziehbare Commit-Historie geachtet wird.

3. **Build-Tools:**
   - Das Projekt muss mit einem gängigen Build-Tool wie Maven oder Gradle aufgebaut werden.

4. **Programmiersprache:**
   - Die Implementierung soll in Java erfolgen. Alternativ ist auch Kotlin möglich, jedoch nur nach vorheriger Absprache.

5. **Währungskonfiguration:**
   - Die Währung des Systems muss über eine Konfigurationsdatei änderbar sein.

6. **Beschreibung und Dokumentation:**
   - Füge zu jeder Klasse und Methode entsprechende Javadoc-Kommentare hinzu, die ihre Funktionalität und die Parameter beschreiben.

7. **Performance:**
   - Der Code muss effizient und performant ausgeführt werden, wobei die Speicheroperationen optimiert werden sollen.

#### Wichtige Methoden

- `void setCoins(UUID player, int coins)`: Setzt die Anzahl der Coins eines Spielers.
- `int getCoins(UUID player)`: Gibt die aktuelle Anzahl der Coins eines Spielers zurück.
- `void addCoins(UUID player, int coins)`: Fügt dem Coin-Konto eines Spielers Coins hinzu.
- `void removeCoins(UUID player, int coins)`: Entfernt Coins vom Coin-Konto eines Spielers.

#### Optional

- **Continuous Integration (CI):**
  - Richte einen GitHub Workflow (oder eine ähnliche CI-Lösung) ein, der die API über eine Maven Registry verfügbar macht und sicherstellt, dass das Projekt automatisch gebaut und getestet wird.
