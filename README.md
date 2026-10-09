## Jon Seidmann

I write firmware for medical devices. I'm a Principal Software Engineer at Fractyl Health, where I built the firmware for our next-generation console: three Cortex-M7 boards talking to each other over Ethernet, a signed bootloader, and the IEC 62304 paperwork that goes with all of it. Before Fractyl I did lighting control at Philips Color Kinetics and process instruments at Cambridge Viscosity.

Most of what's here is small tools I wanted for myself, plus a growing pile of games and practice apps I build with my kids.

How to reach me: [Email me](mailto:seidmann@gmail.com)

---
### Tools
- Hex Flex [(application)](https://seidleroni.github.io/Hex-Flex-Web/) [(source code)](https://github.com/seidleroni/Hex-Flex-Web)
    - This application is something I’d been thinking about building for many years. In embedded applications, I work with Intel Hex files all the time, but the best way I was able to view files was by using Segger's J-Flash utility. That tool is okay, but I also wanted a way to compare different hex files. After working with ChatGPT and Gemini, I put this application together. It allows users to view the contents of an Intel Hex file and also compare two different files. When viewing a file, it also shows a map that provides an overview of where data segments are and where memory is blank or erased.
- Linear Actuator Motion Calculator [(application)](https://seidleroni.github.io/Linear-actuator/) [(source code)](https://github.com/seidleroni/Linear-actuator)
    - I built this tool to help with a work task. I wanted the ability to calculate how long it would take a linear actuator to move a certain distance, given a maximum velocity, acceleration, and deceleration. It also graphs position and velocity over time to provide a clearer picture of what the motor is doing along the way.
- Library Codabar Barcode Generator [(application)](https://seidleroni.github.io/library-codabar-generator/) [(source code)](https://github.com/seidleroni/library-codabar-generator)
    - My wife and I frequently go to the library to pick up reserved books for ourselves, each other, or our children. Often we need each other’s library cards, and it was annoying to keep screenshots and dig through photo albums. For fun, I spent about an hour putting this application together, both to solve our problem and to understand barcode formatting better. A user can generate a barcode using the Codabar format used by the Minuteman Library Network (and presumably many other libraries) and add a label. Both the label and card numbers are encoded in the URL, so users can bookmark a specific barcode and view it later.
- Pelohard [(site)](https://pelohard.com/)
    - I really love using my Peloton but found it annoying to find classes of appropriate difficulty. This site sorts rides by difficulty and allows users to click on a class and add it to their stack. The project has two parts: first, a Python script that uses my Peloton credentials and the unofficial Peloton REST API to get the 50 most recent rides and save the class information in a JSON file. The second part takes that JSON file and renders the site. The Python script and site automatically update twice a day.
---
### Built with my kids
Lately most of my evenings-and-weekends coding has been with my two boys (7 and 9) and AI coding tools. They come up with the game or the thing they want to practice, we work out the rules together, and then we see how far we can push the tools to build it. They've learned that "make it more fun" is not a spec, and I've learned a lot about what these tools can and can't do. A few of the results:

- Fort Wars [(source code)](https://github.com/seidleroni/FortWarsLaneDefense)
    - A silly, bright lane-defense game in pygame. You build a fort out of cannons, freezers, boomers and gold mines, then defend your Cookie Keep from waves of Grumbles that want to eat your cookies. This one was designed by committee, where the committee was 7 and 9 years old.
- Garden Guard [(source code)](https://github.com/seidleroni/PvZTurnBased)
    - The turn-based answer to Fort Wars, for the kid who doesn't like timers. Plants-vs-Zombies-style lanes, but every move is shown before you end your turn, so you can think it through.
- Piano Sheet Music Reader [(application)](https://seidleroni.github.io/PianoSheetMusic/) [(source code)](https://github.com/seidleroni/PianoSheetMusic)
    - A phone-friendly way to learn to read sheet music. It shows a beginner piece on the staff, plays it on a sampled piano at whatever tempo you want, and a cursor follows along so you know which note you should be playing. Tap a bar to loop it.
- Grammar Quiz [(application)](https://seidleroni.github.io/GrammarGame/) [(source code)](https://github.com/seidleroni/GrammarGame)
    - Twenty parts-of-speech questions for a third grader, built in Blazor WebAssembly so it runs entirely in the browser.
- Newton Math
    - Daily math practice that follows the Newton, MA elementary curriculum, with a mastery and spaced-repetition scheduler so each kid gets the problems he actually needs. Everything is generated and graded by plain deterministic Python; no AI at runtime.
---
### Patents
- [Tissue Treatment System With Fluid Delivery Console](https://patents.google.com/patent/US20230346451A1/en?oq=20230346451)
- [System and method for distribution of electrical power and control data in temporary lighting installations](https://patents.google.com/patent/US10079506B2/en?oq=10079506)
- [Smooth dimming of solid state light source using calculated slew rate](https://patents.google.com/patent/US8975820B2/en?oq=8975820)
