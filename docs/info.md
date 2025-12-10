DE:
Dieses Projekt ist durch TinyTapeout zustande gekommen. Im Zuge dieses Aufbaus haette ich ein 10-kHz-Clock-Signal in der Schaltung verwenden koennen, welches durch einen Oszillator auf dem TinyTapeout-PCB bereitgestellt worden waere.
Da ich die Spielschwierigkeit variieren wollte, plante ich jedoch einen externen Taktgeber ein. Die Verwendung dieses Taktgebers wird auch in der folgenden Anleitung erklaert.

1.) Zuerst den Schalter oben links in die linke Stellung bringen, damit das Signal vom 10-kHz- bzw. 2-Hz-Taktgeber uebernommen wird.
2.) Beim Start der Simulation den Reset-Taster druecken, um alle Zaehler zurueckzusetzen.
3.) Ueber den Schalter (ID7, !!!Funktionsweise: Taster!!!) zwischen dem internen Prescaler und einem externen Taktgeber umschalten.

Ist der Q-Ausgang(leuchtet grün) des Flip-Flops rechts vom Input-Board = 0 → interner Prescaler
Ist der Q-Ausgang des Flip-Flops rechts vom Input-Board = 1 → externer Taktgeber

Um einen externen Taktgeber in Wokwi zu simulieren, muss man in der Seitenleiste links von der README.md auf die Datei "diagram.json" umschalten. Wenn man dort mit STRG+F nach "wokwi-clock-generator" oder "frequency" sucht, findet man eine Zeile, bei der man die Frequenz aendern kann – beispielsweise von 1 Hz bis 5 Hz.

4.) Wenn die aktuell leuchtende LED oberhalb der zuletzt gespeicherten LED liegt und der "Step"-Taster im richtigen Moment gedrueckt wird, wird diese LED ebenfalls gespeichert.
Anstatt den Step-Taster immer mit der Maus zu betaetigen, kann man auch die Leertaste am PC druecken. Das ist einfacher, wenn man auf kleinen Bildschirmen arbeiten muss.

Hinweis zu den Wokwi-Links:
Die folgenden beiden Wokwi-Projekte dienen als Beispiele fuer geaenderte Taktfrequenzen eines externen Taktgebers in Wokwi.
Das 10-kHz-Projekt entspricht dem Hauptprojekt, waehrend die 2-Hz-Version eine alternative Einstellung zeigt.


---Clock 10 kHz (Hauptprojekt)---
https://wokwi.com/projects/448606094166973441

---Clock 2 Hz (Beispiel fuer Externe Taktgeber)---
https://wokwi.com/projects/448609406409498625




____________________________________________________________________________________




EN:
This project came about through TinyTapeout. During this setup, I could have used a 10-kHz clock signal in the circuit, which would have been provided by an oscillator on the TinyTapeout PCB.
However, since I wanted to vary the game difficulty, I planned to include an external clock generator. The use of this clock generator is also explained in the following instructions.

1.) First, move the switch at the top left into the left position so that the signal from the 10-kHz or 2-Hz clock generator is used.
2.) When starting the simulation, press the reset button to reset all counters.
3.) Use the switch (ID7, !!!Functionality button!!!) to switch between the internal prescaler and an external clock generator.

If the Q output (lights green) of the flip-flop to the right of the input board = 0 → internal prescaler
If the Q output of the flip-flop to the right of the input board = 1 → external clock generator

To simulate an external clock generator in Wokwi, you need to switch to the file "diagram.json" in the sidebar to the left of the README.md. If you search for "wokwi-clock-generator" or "frequency" using CTRL+F, you will find a line where the frequency can be changed — for example from 1 Hz to 5 Hz.

4.) If the currently lit LED is above the last stored LED and the "Step" button is pressed at the right moment, this LED will also be stored.
Instead of clicking the Step button with the mouse every time, you can also press the space bar on your PC. This is easier when working on small screens.

Note on the Wokwi links:
The following two Wokwi projects serve as examples for modified clock frequencies of an external clock generator in Wokwi.
The 10-kHz project corresponds to the main project, while the 2-Hz version shows an alternative setting.

---Clock 10 kHz (Main Project)---
https://wokwi.com/projects/448606094166973441

---Clock 2 Hz (Example for External Clock Generators)---
https://wokwi.com/projects/448609406409498625
