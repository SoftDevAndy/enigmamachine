# enigmamachine
A quick Java implementation of the famous Enigma Machine

The Enigma Machine is worth reading about if you've stumbled onto this repo and don't know what it is! Here's the link to the [Enigma Machine](https://en.wikipedia.org/wiki/Enigma_machine).

**Brief Description**

The Enigma machine is comprised of a keyboard, plugboard, several rotors and a reflector board. 

Each keystroke on the enigma machine (or character in your encoded message). Goes through the following.

* Check the plugboard first to see if a letter is rewired. e.g A -> E
* Travel through the closest rotar (fastest because it turns **EVERY** keypress) mapping to the appropriate character
* In this implementation there is **3** rotors, once the character has hit the reflector plate it gets remapped and travels back through the rotors. This is where the encrypted letter would show on the lampboard
* Everytime a rotor makes a full rotation the next rotor down rotates by one shift.

Again I highly recommend reading the wikipedia article about the machine.

**Features**

* The rotors, plugboard and reflector are all customizable and kept in a very simple format in .csv files. This way you can substitute in your own wiring for the rotors, plugboard etc.

* Rotor positioning in the machine and starting position are configuarable

* Quick and easy implementation of the enigma machine. It can certainly be improved upon and extended quite easily, if you wish to, go for it! The EnigmaMachine class itself would be the best place to build upon e.g Add more rotors, read in a configuration file etc

**Notes**

Have fun with it, edit it, share it, configure all the rotors the way you wish. The current ones aren't the actual configurations used for the rotors and plugboard (and there was several of these). Add more rotors if you wish, it's pretty straight forward. Enjoy!
