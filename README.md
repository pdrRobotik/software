# 🤖 pdrRobotik: Einstieg in die Softwareentwicklung!



### Inhalt
- [🛫 Los geht's!](#-los-gehts)
- [📖 GitHub Repository erstellen](#-github-repository-erstellen)
- [💾 Code Datei erstellen und auf GitHub speichern](#-code-datei-erstellen-und-auf-github-speichern)
- [💻 Programmieren in Arduino C++](#-programmieren-in-arduino-c)



## 🛫 Los geht's!

Wir wollen nun unsere gebaute Hardware mit ein bisschen Code zum Laufen bringen. Zuerst sollten wir einmal ein letztes Mal unsere Kabel überprüfen. Wir müssen bedenken, dass es mehr Aufwand ist, die Verkabelung nachträglich zu ändern. Sind wir schließlich zufrieden, sollten wir uns einmal vor Augen führen, was unser Programm tun soll, welchen Motoren oder Schalter benötigt werden, und wie wir das Ansteuern der jeweiligen Komponenten verwirklichen. Erst dann sollten wir mit dem Programmieren beginnen. Um programmieren zu können brauchen wir verschiedene Programme und Libarys. Über die Installation der Programme und Libarys müssen wir uns aber nicht kümmern. Diese wurden schon installiert und eingerichtet. Zu Beginn werden wir die **Arduino IDE** <img src="https://i.imgur.com/fuFUsjx.png" width="25"/> verwenden. Dort können wir das Programm schreiben und direkt kompilieren. In Zukunft können wir bei persönlichem Bedarf auch auf **Visual Studio Code** <img src="https://i.imgur.com/OttW3og.png" width="25"/> wechseln.



## 📖 GitHub Repository erstellen

1) Als erstes wollen wir ein neues Repository anlegen. Das ist praktisch ein neues Projekt. Um dies anzustellen verwenden wir **GitHub**. Damit können wir den geschriebenen Code zwischen verschiedenen Geräten synchronisieren und bearbeiten.

2) Wir öffnen als erstes **GitHub Desktop** <img src="https://miro.medium.com/max/600/1*p6exlg2Jrl3pimjPy7R-sA.png" width="25"/>, welches sich schon für uns auf dem Desktop befindet. Alternativ können wir das Programm auch über die Windows Suche öffen.

3) Nachdem sich **GitHub Desktop** öffnet, werden wir mit folgender Oberfläche begrüßt und klicken wie markiert auf den **_"kleinen Pfeil"_**.
<img src="https://i.imgur.com/o1PRydl.png" width=""/>

4) Es öffnet sich eine Übersicht mit allen Repositorys die wir schon angelegt haben. Hier klicken wir auf **"Add"** und anschließend auf **_"Create new repository..."_**

5) Es öffnet sich ein neues Fenster. Hier geben wir dem Projekt einen Namen. **_WICHTIG: Die Namen schreiben wir immer klein!_** Wenn wir wollen, können wir noch eine Beschreibung hinzufügen, was aber nicht nötig ist.
<img src="https://i.imgur.com/337z80g.png" width=""/>

6) Der nächste Schritt ist ebenfalls Wichtig. Wir müssen nun einstellen, wo wir die Datei speichern wollen. Dazu klicken wir auf **_"Choose..."_**. Es öffnet sich ein Fenster. Hier müssen wir zuerst auf der linken Seite auf **_"Dokumente"_**, und dann auf den Ordner **_"GitHub"_** klicken. Mit **_"Ornder auswählen"_** bestätigen wir unsere Auswahl.
_(Kleiner Tipp für's nächste Mal: Wenn der Pfad schon richtig eingestellt ist können wir diesen Schritt überspringen)_
<img src="https://i.imgur.com/LeeABPu.png" width=""/>

7) Nachdem wir den Pfad eingestellt haben, können wir mit **_"Create repository"_** das Projekt erstellen. Die restlichen Optionen müssen wir nicht beachten.
<img src="https://i.imgur.com/WH9efnf.png" width=""/>

8) Das eben erstellte Projekt finden wir jetzt unter **"Other"**. Mit einem Klick auf den Namen werden wir in das Projekt reingeworfen.
<img src="https://i.imgur.com/6MEily0.png" width=""/>

9) Jetzt müssen wir nur noch das Projekt veröffentlichen! Dazu klicken wir entweder, wie oben markiert, auf **_"Publish repository"_**, oder auf den gleichnamigen, blauen Knopf auf der rechten Seite.
<img src="https://i.imgur.com/XomxG0s.png" width=""/>

10) Es öffnet sich ein weiteres Fenster bei dem wir, ohne etwas zu verändern, auf **_"Publish repository"_** klicken.
<img src="https://i.imgur.com/d6M84Ei.png" width=""/>

So. Geschafft! Das Repository ist nun auf unserem GitHub veröffentlicht. Jetzt können wir schon fast mit dem programmieren loslegen. Alles dazu im nächsten Verlauf. GitHub sollten wir während des programmieren im Hintergrund geöffnet lassen.



## 💾 Code Datei erstellen und auf GitHub speichern

1) Zunächst öffnen wir die **Arduino IDE** <img src="https://i.imgur.com/fuFUsjx.png" width="25"/>. Diese befindet sich schon für uns auf dem Desktop. Alternativ können wir auch über die Windows Suche das Programm öffen.

2) Das Programm schmeißt uns direkt in eine neue Datei. Aussehen tut das dann ca. so:
<img src="https://i.imgur.com/U5cVgm8.png" width=""/>

3) Bevor wir aber loslegen können, wollen wir die Datei erstmal ordentlich speichern. Dazu klicken wir in der IDE oben links auf **_"File"_** und dann auf **_"Save As..."_**. _(Kleiner Tip: Wir können hier auch die Tastenkombination **STRG+S** nutzen)_

4) Es öffnet sich ein kleines Fenster, wo wir der Datei einen Namen geben, und einen Speicherort auswählen müssen. Als erstes wählen wir wieder links **_"Dokumente"_**, und öffnen dann unseren **_"GitHub"_** Ordner. Dort müssen nach einem Ordner suchen, der den gleichen Namen hat wie das Projekt beim erstellen des GitHub Repositorys. Nachdem wir den Ordner gefunden haben öffnen wir diesen ebenfalls. Nun geben wir der Datei unten bei **_"Dateiname"_** den gleichen Namen wie der Ordner den wir als letztes geöffnet haben _(also den Projektnamen)_. **Auch hier müssen wir beachten das der Name kleingeschrieben ist!** Zum Schluss bestätigen wir alles mit **_"Speichern"_**.
<img src="https://i.imgur.com/pnNBM4I.png" width=""/>

5) Nachdem die **IDE** <img src="https://i.imgur.com/fuFUsjx.png" width="25"/> kurz neulädt schließen wir diese über das **_"X"_** oben rechts in der Ecke. Wir navigieren jetzt zur der Datei die wir grade erstellt haben. Der Pfad zur Datei sollte etwa so aussehen.
<img src="https://i.imgur.com/fRJwgKX.png" width=""/>

6) Nun ziehen wir die Datei nach oben in den ersten Ordner, der unseren Projektnamen trägt. Zu Demonstration ist er hier **_"repository-name"_**.
<img src="https://i.imgur.com/2i2DOi8.png" width=""/>

7) Anschließend gehen wir in den Ordner, in den wir eben die Datei verschoben haben. Das können wir machen indem wir oben auf den ersten Ordner mit unserem Projektnamen drücken.
<img src="https://i.imgur.com/7ZRCwAP.png" width=""/>

8) Hier müssen wir jetzt den markierten Ordner löschen. Er trägt ebenfalls den Namen unseres Projekts.
<img src="https://i.imgur.com/n3InPwp.png" width=""/>

9) Nun können wir mit einem Doppelklick unsere Code-Datei öffnen.
<img src="https://i.imgur.com/aPAtrOt.png" width=""/>

10) Es öffnet sich wieder die **Arduino IDE** <img src="https://i.imgur.com/fuFUsjx.png" width="25"/>. Hier sollten nun an den markierten Stellen unser Projektname stehen.
<img src="https://i.imgur.com/p4qcjh9.png" width=""/>

11) Als letzten Schritt öffnen wir **GitHub Desktop** <img src="https://miro.medium.com/max/600/1*p6exlg2Jrl3pimjPy7R-sA.png" width="25"/>. Hier sollte das nun ungefähr so aussehen.
<img src="https://i.imgur.com/F55wVr5.png" width=""/>

12) Wir überprüfen ob hier (pinke Markierung) unser Projektname steht. Falls nicht, können wir mit einem drücken auf den dort stehenden Namen unser Projekt auswählen. Danach drücken wir auf **_"Fetch origin"_**. Dies bewirkt, dass alle Änderungen an der Datei abgerufen werden.
<img src="https://i.imgur.com/F55wVr5.png" width=""/>

13) Zum Schluss bereiten wir das Projekt, mit einem Klick auf **_"Commit to main"_**, zum speichern auf unserem **GitHub** vor.
<img src="https://i.imgur.com/qQZHRH2.png" width=""/>

14) Schließlich können wir die Änderungen entgültig hochladen. Dazu klicken wir entweder, wie oben markiert, auf **_"Push origin"_**, oder auf den gleichnamigen, blauen Knopf auf der rechten Seite.
<img src="https://i.imgur.com/swGdnJZ.png" width=""/>

15) Fertig! Nach dem Hochladen sollte das Programm wieder so aussehen. Nun können wir endlich mit dem Programmieren beginnen.
<img src="https://i.imgur.com/ymSfzoF.png" width=""/>



## 💻 Programmieren in Arduino C++

Um unsere Hardware steuern zu können, brauchen wir logischerweise die entsprechende Software. Wenn wir die oberen Schritte schon abgearbeitet haben, können wir damit auch endlich loslegen. Die Grundlegenden Funktionen lernen wir hier.

1) Wir beginnen mit dem Öffnen von **GitHub Desktop** <img src="https://miro.medium.com/max/600/1*p6exlg2Jrl3pimjPy7R-sA.png" width="25"/>. Dort wählen wir über den Pfeil oben links das Projekt aus, an dem wir nun arbeiten möchten.  
  
(**_WICHTIG: Folgende zwei Schritte wiederholen wir zu Beginn von jedem Start des Arbeitens an einem Projekt._**)  

2) Haben wir das getan, drücken wir oben auf **_"Fetch origin"_**.
<img src="https://i.imgur.com/K6I44bX.png" width=""/>

3) Wir achten nun, ob es Änderungen am Projekt gibt. Hier zwei Beispiele wie eine Änderung, und wie keine Änderung von GitHub angezeigt wird. <img src="https://i.imgur.com/v3eeAji.png" width=""/>  
_(↑ Eine Änderung ist vorhanden.)_ <img src="https://i.imgur.com/6ZE5zpO.png" width=""/>  
_(↑ Keine Änderung ist vorhanden.)_

4) Ist keine Änderung vorhanden können wir weiter machen. Falls doch, klicken wir oben auf **_"Pull origin"_** oder auf den gleichnamigen, blauen Knopf auf der rechten Seite. Nun wurde das Projekt synchronisiert und wir können fortfahren.

5) **GitHub Desktop** <img src="https://miro.medium.com/max/600/1*p6exlg2Jrl3pimjPy7R-sA.png" width="25"/> lassen wir einfach geöffnet und starten nun die **Arduino IDE** <img src="https://i.imgur.com/fuFUsjx.png" width="25"/>.

6) Wir kontrollieren, ob hier (rote Markierung) unser Projektname steht.
<img src="" width=""/>


<sup> Created with ❤️ by [@Matewoo](https://github.com/Matewoo) </sup>
