Release: 2.1

IMPORTANT:
You need to copy the _content_ of the folder "ToInterface" (just the content, not the folder itself!) to the "Interface" folder in your Warcraft installation directory. 
On most machines that target "Interface" folder should be under "C:\Program Files (x86)\World of Warcraft\_classic_\Interface"
Caution: The target needs to be the "Interface" folder. NOT to the "AddOns" folder!

----------------------------------------------------------------------------------------

1. What is the script doing? (German version below)

The script has two modes: "Login" and "Play". You can switch between them with ALT + F1.
In "Login" mode, you can select characters and enter the game world with them, create new characters, switch to another server or delete characters.
In "Play" mode, you can use the NUMPAD 7-8 keys to do right-clicks at tree different positions in the game. This function is used for looting in the game.
Use ALT + ESCAPE to unload/end the script (there's no audio feedback on that action!).


2. Usage

Start the script by launching the correct file for your language and region:
- If you are playing on US servers: wow-menu_EN_US.ahk
- If you are playing on EU servers in English: wow-menu_EN_EU.ahk
- If you are playing on EU servers in German: wow-menu_DE_EU.ahk
The script starts in "Login" mode. It gets active only after you started WoW and the WoW window gets the focus.
Then it tries to detect the character selection page, or it waits until you are logged in to WoW and the character selection page is loaded. As long as the script is doing any recognition or waits, you will hear a sound. The sound means that you have to wait.
Don't press any key, don't switch the window and don't do anything else while the sound is playing. Never. Nowhere in the menu. Raise your hands in the air while the sound is playing.
Once you get to the character selection page, the audio menu opens. It says "Main Menu." You can navigate to the submenu with options using the RIGHT ARROW key. The use DOWN and UP keys to choose menu options in that submenu.
To log in with a character, you first need to select that character, and then log in with the selected character.
There are no character names recognized or read out. The script only reads "1, 2, 3 to 10" for the character slots. You have to remember what character is in each slot (just take a note for every new character you're creating).
Newly created chars always end up in the next free slot. If you already have 3 characters and you create a new one, it will be in slot 4.
After logging in, the script automatically switches to "Play" mode. When logging out it automatically switches to "Login" mode. If that doesn't work, you can use ALT + F1 to manually switch.

3. Requirements:

- The script is only working with WoW TBC on Windows. No Mac, no Retail.
- Do not move the script file and its folder. Create a shortcut to the script file, if you would like to access it more easily.
- The script requires that you are playing in fullscreen mode. (This is the default).
- The script requires the same screen resolution in WoW as the Windows screen resolution is (this is the default).

----------------------------------------------------------------------------------------

DEUTSCHE VERSION

WICHTIG:
Du muss die _Inhalte_ des Ordners "ToInterface" (nur die Inhalte, nicht den ordner selbst!) in den "Interface"-Ordner in deinem Warcraft-Installationsverzeichnis kopieren.
Auf den meisten Computern findest du den "Interface"-Ordner unter "C:\Program Files (x86)\World of Warcraft\_classic_\Interface"
Achtung: Du musst in den Ordner "Interface" kopieren. Nicht in den "AddOns"-Ordner!

1. Was macht das Skript?

Das Skript hat zwei Modi: "Login" und "Spielen", zwischen denen du mit ALT + F1 umschalten kannst.
Im Modus "Login" kannst du über ein Audio-Menü auf der Charakterauswahl-Seite von WoW Chars auswählen und mit diesen die Spielwelt betreten, neue Chars erstellen, zu einem anderen Server wechseln oder Chars löschen.
Im Modus "Spielen" kannst du über die Tasten NUMMERNBLOCK 7-8 zwischen drei Kameraperspektiven im Spiel umschalten und gleichzeitig einen Rechtsklick im Spiel durchführen. Diese Funktion dient dem Plündern im Spiel.
Mit ALT + ESCAPE kannst du das Skript vollständig beenden (es gibt kein Audiofeedback dabei!).

2. Verwendung

Du startest das Skript indem du die Datei für deine Sprache und Region ausführst:
- Wenn du auf US-Servern spielst: wow-menu_EN_US.ahk
- Wenn du auf EU-Servern in English spielst: wow-menu_EN_EU.ahk
- Wenn du auf EU-Servern in Deutsch spielst: wow-menu_DE_EU.ahk
Das Skript startet im Modus "Login". Es wird erst aktiv, wenn du WoW gestartet hast und das WoW-Fenster den Fokus bekommt.
Dann versucht es die Charauswahlseite zu erkennen, bzw. es warte so lange, bist du in WoW angemeldet bist und die Charakterauswahlseite geladen ist. Solange das Skript irgendeine Erkennung durchführt oder wartet, hörst du einen Sound. Der Sound bedeutet, dass du warten musst.
Achtung: Drücke keine Taste, wechsel nicht das Fenster und mach keine anderen Dinge solange der Sound läuft. Niemals. Nirgendwo im Menü. Selbst dann nicht, wenn sonst die Welt untergeht. Hebe deine Hände in die Luft, solange der Sound läuft.
Sobald du auf der Charakterauswahlseite angekommen bist, öffnet sich das Audio-Menü. Es sagt "Hauptmenü". Du kannst im Menü nach rechts gehen, und die einzelnen Optionen verwenden.
Wenn du dich mit einem Char einloggen möchtest, musst du diesen erst auswählen und dich dann mit dem ausgewählen Char einloggen.
Charkternamen werden dabei nicht erkannt oder vorgelesen. Dir wird nur "1, 2, 3 bis 10" für die Charakterplätze vorgelesen. Was sich für ein Char auf dem jeweiligen Platz befindet musst du dir selbst notieren.
Neu erstellte Chars landen immer auf dem nächsten freien Platz. Wenn du also schon 3 Chars hast, und einen neuen erstellst, dann ist dieser auf Platz 4.
Nach dem Einloggen schaltet das Skript automatisch auf "Spielen". Beim Ausloggen schaltet es automatisch auf "Login". Sollte das nicht funktionieren, kannst du mit ALT + F1 selbst umschalten.

3. Voraussetzungen:

- Das Skript funktioniert nur unter Windows, nur mit WoW TBC und nur mit dem deutschen WoW-Client.
- Du darfst das Skript und seinen Ordner nicht verschieben. Wenn du es einfacher starten möchtest, kannst du dir eine Verknüpfung zu deinem Skript erstellen.
- Das Skript erfordert, dass du WoW im Vollbildmodus spielst. (Das ist standardmäßig so.)
- Das Skript erfordert, dass du in WoW dieselbe Auflösung wie in Windows verwendest (das ist standardmäßig so).

----------------------------------------------------------------------------------------

RELEASE NOTES

Todo/bugs:
	- add "delete character" feature
	- add server type to server names

Release notes:
	2.1
		- Re-designed the script to be more reliable and much faster.
		- The script stops auto switching between gaming/login mode if you do use ALT + F1 to manually switch the mode. You need to restart the script to turn auto switching on again.
		- Changed the "script is processing" sound to something (water drop) that is better to hear is there's ingame music playing.
		- The script now is replacing a lot of textures on login and char selection screens. If a sighted person asks why the UI looks that "broken", that is the reason. It's a feature, not a bug.

	1.7
		- Added addition gaming mode detection pixel at lower left corner of the screen, just in case that the upper left corner is covered by overlays from streaming software (requires Sku r25.9).
		- Optimized the detection. Script shouldn't unintentionally click on "Delete character" anymore.

	1.6
		- Added English TTS audio data
		- Added EN EU and EN US region / realm lists
		- Splitted the script into separate script for EN_EU, EN_US, DE_EU.
		- Optimized the recognition of "Login" and "Game" mode
		- Fixed a bunch of issues with mode detection

	1.5
		- fixed an issue with not working enter key in menus after char creation

	1.4
		- the script is not anymore incorrectly detecting anything with the string "World of Warcraft" in a window title as the game window

	1.3
		- the volume of the "load" sound was decreased
		- new output "paused" if the wow window lost the focus
		- script now automatically detects and switches the mode (login, play, paused); ctrl + f1 to manually switch modes is still available, but shouldn't be required anymore

	1.2
		- new shortcut alt + esc to exit the script
		- script stops all activies in login mode and switches to play mode if wow has lost the focus.
		- script ignores arrow, enter, and esc keys if wow hasn't the focus

	1.1
		- hotkey to switch modes changed from numpadsub to alt+f1
		- script now considers all 10 character slots per server instead of 9
		- numpad8 testing keybind removed
		- testing tooltip removed
		- code cleanup