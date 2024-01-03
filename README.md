## A fully-tested, fully-modular version of space invaders built with Racket, a modern dialect of Lisp.

### Preview

<img src="https://i.imgur.com/817QbYT.gif" title="" alt="2024-01-02 16-41-10.gif" width="215">

### Getting Started

1. Install racket from [here](https://download.racket-lang.org/).
2. Open _.rkt_ file
3. Press Run
   ![Imgur](https://i.imgur.com/lDFHgRD.png)
4. Start the game by typing `(main GAME-START)` in the DrRacket console and press `Enter`
   ![Imgur](https://i.imgur.com/jmp7ENz.png)

If you need any additional info for installation you could check the docs from [here](https://docs.racket-lang.org/pollen/Installation.html).

### Project Structure

`domain-analysis.pdf`: the domain analysis of the program.
`functions.txt`: a list of the program functions.
`starter.rkt`: the source code.

### Domain Analysis

![domain analysis according to type of information_page-0001.jpg](https://i.imgur.com/fTMC4Ct.jpg)

![domain analysis according to type of information_page-0002.jpg](https://i.imgur.com/6ntqsp9.jpg)

![domain analysis according to type of information_page-0003.jpg](https://i.imgur.com/n8uSol8.jpg)

### Reflection

Few areas that could be further enhanced for an improved gaming experience:

1. Limit rate of missile fire so it would require some accuracy hitting invaders.
2. Add a pause of 3 seconds when the invader reaches the base and make the tank blink (indicating death) so the user can look at his failure better 😈.
3. Increase invade rate as time goes by. Display a level number with each invade rate increment. Start the gameplay with 'Level 1'.

### Disclaimer

This program represents the culminating project of the ` How to code - simple data` course, the 1st of 6 of `Software Development Micromasters Program` offered by `UBC`. Check it out [here](https://www.edx.org/masters/micromasters/ubcx-software-development).
