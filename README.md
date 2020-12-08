# Java Einstieg
## Programmcode
Sie benötigen eine Klasse mit einer Main-Methode, um ein Hello World Programm zu schreiben. Darin sollte dann auch die Ausgabe von Hallo Welt stehen.

```javascript
public class HelloWorld {
    public static void main (String[] args) {
        System.out.println("Hallo Welt!");
    }
}
```
Nachdem Sie dies in einer Datei Namens HelloWorld.java gespeichert haben, können Sie es kompilieren. Wichtig ist, dass die Dateiendung .java ist.
Mit der Konsole gelangen Sie (mittels cd) in den Ordner in dem die Datei liegt. Nun geben Sie `javac` gefolgt von dem Dateinamen (mit Endung), also `javac HelloWorld.java` ein. Nun ist eine zweite Datei entstanden, die HelloWorld.class heißt. Das Programm führen Sie nun mit dem Befehl `java` gefolgt mit dem Namen (ohne Dateiendung): `java HelloWorld`.

Nun sollte in der Konsole die Ausgabe: Hallo Welt! angezeigt werden.