
# wplinux 

**Version: 1.2.0, 2023-09-24**

## Projektbeschreibung:
Zeigt Informationen über Unix- und Linux-Befehle aus deutschen Wikipedia-Artikeln in der Bash-Shell an. Dieses Skript liest und analysiert Wikipedia-Seiten und versucht, den Anfang der Artikel zu den entsprechenden Befehlen im Textmodus direkt im Terminal anzuzeigen.

## Anforderungen

Die folgenden Programme **müssen** installiert sein:

### Externe Programme, die verwendet werden

| Programmname   | &nbsp;&nbsp;&nbsp;Aufgabe / Programmkategorie            | &nbsp;&nbsp;&nbsp;Standardmäßig installiert |
|:---------------|:---------------------------------------------------------|:---------------------------------------|
| wikipedia2text | &nbsp;&nbsp;&nbsp;Wandelt Wikipedia-Artikel in Text um   | &nbsp;&nbsp;&nbsp;nein                 |
| sed            | &nbsp;&nbsp;&nbsp;Manipuliert (löscht oder ersetzt) Text | &nbsp;&nbsp;&nbsp;ja                   |
| less           | &nbsp;&nbsp;&nbsp;Pager zum Anzeigen von Textdateien     | &nbsp;&nbsp;&nbsp;ja                   |
| wget           | &nbsp;&nbsp;&nbsp;Holt Dateien von Internetservern       | &nbsp;&nbsp;&nbsp;ja                   |
| grep           | &nbsp;&nbsp;&nbsp;Filtert Zeilen anhand von Mustern      | &nbsp;&nbsp;&nbsp;ja                   |

## Installation

Um dieses Programm zu installieren, kopieren Sie die Datei `wplinux` in ein Verzeichnis Ihrer Wahl und machen Sie die Skriptdatei mit dem folgenden Befehl ausführbar:

```bash
chmod +x wplinux
```

Wollen Sie das Skript aus jedem Verzeichnis heraus aufrufen können, so muss es in einem Verzeichnis gespeichert sein, das Teil des Suchpfads ist. Sie können den Suchpfad mit dem Befehl `echo "$PATH"` anzeigen und bei Bedarf oder Wunsch erweitern, indem Sie die Datei `~/.bashrc` oder die Datei `/etc/bash.bashrc` bearbeiten. Die Datei `~/.bashrc` definiert den Suchpfad für einen speziellen Benutzer und liegt in seinem persönlichen Verzeichnis; `/etc/bash.bashrc` definiert den Suchpfad systemweit für alle Benutzer.

## Verwendung

Öffnen Sie ein Terminal und führen Sie einen der folgenden Befehle aus.

### Wenn das Skript im Suchpfad ist:

```bash
wplinux
```

### Wenn das Skript im aktuellen Verzeichnis ist, aber nicht im Suchpfad:

```bash
./wplinux
```

## Autor

Bernd Storck: Ich bin ein zertifizierter Webmaster/Webentwickler und Linux-Liebhaber aus Berlin. Ich hatte meine ersten Programmiererfahrungen um 1984 mit einem ATARI 800XL. Seitdem habe ich eine Reihe von Programmiersprachen ausprobiert oder gelernt. Insbesondere bin ich als JavaScript-Entwickler, PHP-Programmierer und Webentwickler zertifiziert. Ich habe umfangreiche Erfahrung in Bash-Programmierung.

Kontakt: [Facebook: Linux-Infos von Bernd Storck](https://www.facebook.com/BStLinux/), [www.facebook.com/BStLinux](https://www.facebook.com/BStLinux/)

&nbsp;

---

## Lizenz

Dieses Programm ist freie Software: Sie können es unter den Bedingungen der GNU General Public License, wie von der Free Software Foundation veröffentlicht, weiterverbreiten und/oder modifizieren, entweder gemäß Version 3 der Lizenz oder (nach Ihrer Wahl) jeder späteren Version.

Dieses Programm wird in der Hoffnung verteilt, dass es nützlich sein wird, aber **ohne jede Gewährleistung**; auch ohne die implizite Gewährleistung der Marktgängigkeit oder Eignung für einen bestimmten Zweck. Weitere Einzelheiten finden Sie in der GNU General Public License.

Sie finden die GNU General Public License unter <http://www.gnu.org/licenses/>.
