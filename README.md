## Anleitung zur Mitarbeit am Projekt

Wenn du zum ersten Mal mit GitHub im Team arbeitest, folge diesen Schritten:

1. **GitHub-Ordner anlegen**  
   Erstelle auf deinem Computer einen Ordner, z.B. `Github`.

2. **Projektordner anlegen**  
   Lege darin einen Ordner mit dem Namen `webprojekt-team` an.

3. **IDE öffnen**  
   Öffne deine IDE (z.B. PyCharm oder Visual Studio Code).

4. **Terminal öffnen**  
   Öffne das Terminal in deiner IDE.

5. **In den Projektordner wechseln**  
   Gib im Terminal ein:  
   ```
   cd /Pfad/zu/deinem/Github/webprojekt-team
   ```
   (Passe den Pfad an deinen Computer an.)

6. **Projekt von GitHub klonen**  
   Führe im Terminal aus:  
   ```
   git clone https://github.com/mariusErpenbach/webprojekt-team.git
   ```
   Dadurch wird das Projekt auf deinen Computer geladen.

7. **In den geklonten Projektordner wechseln**  
   ```
   cd webprojekt-team
   ```

8. **Eigene Branch erstellen**  
   Erstelle eine neue Branch mit deinem Namen oder Thema:  
   ```
   git checkout -b mein-name
   ```
   (Ersetze `mein-name` durch deinen eigenen Namen.)

9. **Änderungen machen und speichern**  
   Arbeite an den Dateien, speichere deine Änderungen.

10. **Änderungen zum Commit vormerken**  
    ```
    git add .
    ```

11. **Commit erstellen**  
    ```
    git commit -m "Kurze Beschreibung deiner Änderung"
    ```

12. **Branch auf GitHub hochladen**  
    ```
    git push origin mein-name
    ```

13. **Pull Request erstellen**  
    Diesen Schritt machen wir am Ende wenn wir fertig sind mit unseren Pages.
    Gehe auf GitHub zur Projektseite und erstelle einen Pull Request, damit deine Änderungen ins Hauptprojekt übernommen werden können.
    Danach wird die Branch geschlossen und das Feature ist fertig implementiert. In unserem Mini Projekt machen wir dies also zum Schluss (Montag Nachmittag ca)
**Tipp:**  
Wenn du Fragen hast, frage einfach im Team nach! Jeder hilft gerne weiter.
