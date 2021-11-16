# Gruppe Ostrich - KartaKarta 69187

## Aufgabenstellung
Dieses Projekt haben wir als Schularbeit in einer 4er Gruppe gemacht. Das Programm soll Wörter in einer anderen Sprache abfragen und man soll diese erraten, so wie ein Karteikarten-Spiel. Hier, bei diesem Portfolio, gehe ich mehr zu einem Spezifischen Vorgang, wie man abfragt, ob dieses Wort, jenes Wort hier heisst.

1. Der Leser lernt, wie man Zufallszahlen generiert.
2. Der Leser erfährt, wie man mit der Konsolenfarbe tüftelt.
3. Der Leser lernt, wie man prüfen kann, ob jenes Wort dieses Wort heisst.
4. Der Leser erfährt, was FiggleFonts ist.

## Inhalt
### Was ist FiggleFonts?
FiggleFonts ist eine NuGet extension für C# Konsol Applikationen, welches sehr nützlich für die Gestaltung der Konsole ist. Mit einem einfachen Text kommt eine grössere Variante des Textes heraus, welches man zum Beispiel als Titel nutzen kann oder als sonstige Gestaltungen, hier ein Beispiel mit C#:
`Console.WriteLine(Figgle.FiggleFonts.Standard.Render("Test"));`
### Raten
Stell dir vor, dass wir englische Wörter und die dazugehörigen deutsche Wörter beide in einer Liste haben. Nun muss man eine Zufallszahl erstellen um zu entscheiden, ob das richtige dazugehörige Wort zu jenem englischem Wort soll herausgeben oder das falsche dazugehörige Wort. Nun ist das shchwierigste schon gemacht, jetzt muss man nur noch schauen, dass es ein zufälliges englisches Wort abfragt, um dies zu machen brauchen wir die Zufallsfunktion, um zu entscheiden, welches Wort aus der Liste abgefragt werden soll. Mit der Funktion `int random = Random().Next(1,3)` -> Generiert Zahl 1 oder 2 und speichert diese im integer "random".
Zum Schluss muss man jetzt nur noch das Wort aus der Liste nehmen, wenn es bereits drangekommen ist, optional haben wir noch gemacht, dass es beide Wörter, also Deutsch und Englisch, aus der Liste nimmt.

### Bilder
"AND GO!" wurde mit FiggleFonts erstellt und die Farben mit Console.ForegroundColor:
![Programm](https://i.imgur.com/COBuhht.jpg)
### C# - Code
![Programm](https://i.imgur.com/onciX4X.jpg)
![Code1](https://i.imgur.com/EB0i6eV.jpg)
![Code2](https://i.imgur.com/9YVPzJS.jpg)
### Video
[![](https://i.imgur.com/8rlDCUI.jpg)](https://youtu.be/4-XPr_A8YWI)

## Reflexion / Verifikation
Ich fand gut, dass ich nicht zu viel Zeit mit einzelnen Funktionen verbracht habe und mir Hilfe bei den Teammitgliedern geholt habe, wenn ich sie bruachte. 
Nächstes Mal werde ich defenitiv schauen, dass ich mehr mit `static void BeispielGenerieren()` werde arbeiten, damit der Code übersichtlicher wird und keine Kommentare braucht.

Mein Banknachbar versteht wie man Konsolenfarben ändert, Zufallszahlen generiert und in einem Integer speichert. Er lernte aber auch was FiggleFonts ist und wie man es anwenden kann, um seine Konsole mit Titel zu beschmücken oder Ähnlichem.
