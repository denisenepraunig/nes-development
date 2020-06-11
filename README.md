# NES Development
Ressources for NES development. Currently focusing on assembly language, nesasm and development on Mac.

The NES uses the 6502 processor and was programmend in assembly.

# Getting Started Assembly
* [Easy6502](https://skilldrick.github.io/easy6502/) - Start writing 6502 assembly in the browser.
* [Assembly in One Step](http://nesdev.com/6502guid.txt) - This is a nice and short quickstart guide for assembly and I really like the explanation of the different addressing modes. Combine this with the [Easy6502](https://skilldrick.github.io/easy6502/) and you are good to go. 
* [Programming the 6502](https://archive.org/details/Programming_the_6502_OCR/page/n51/mode/2up) - This is an ebook which you can read online or download about 6502 programming. It is a full fledged book and not a quickstart guide.

# 6502 Opcodes
The commands for the 6502 are called **opcodes**. An example opcode is ```INX```which increases the value in the X register. Don't worry if this sentence doesn't make sense. After reading [Easy6502](https://skilldrick.github.io/easy6502/) it will make sense 😊.
* [6502 Opcodes](http://www.6502.org/tutorials/6502opcodes.html)
* [6502 Opcodes - Instruction Reference](http://www.obelisk.me.uk/6502/reference.html)

# Getting Started NES Development
* [NES Basics and Our First Game](http://thevirtualmountain.com/nes/2017/03/06/getting-started-with-nes-game-development.html) - assembly and nesasm
* [Nerdy Nights](https://nerdy-nights.nes.science/) - assembly and nesasm

# Videos
* [How video games were made - part 1: Graphics](https://www.youtube.com/watch?v=jqyC_S56B3k) - This is a nice overview video about the components of the NES and stuff like pattern tables and alike. Other systems are covered at the end of the video. I highly recommend watching this video!
* [How video games were made - part 2: Workflow](https://www.youtube.com/watch?v=Yo7UkkGC1AY) - This video features different consoles and techniques and it is very informative. Really interesting to see the development setup many years ago.
* [Writing NES games! With Assembly!!](https://www.youtube.com/watch?v=kXbMCKMJXXQ) - This is a very cool overview talk about the NES components you need to know for programming and the excitement of this guy of his first sprite on the screen is really amazing!!
* [Programming the Nintendo Entertainment System](https://www.youtube.com/watch?v=XT95C4fT6zA) - This is a dry run of a talk and this guy goes over the basics of the NES and assembly and he niecly compares assembly code and with high level language coding. Also the audio examples of the different channels are really cool

# Development Setup
## Sublime Text 3
I am currently using Sublime Text 3 to write my code and compile the game on the command line with the ```nesasm```command (see the [NES Basics and Our First Game](http://thevirtualmountain.com/nes/2017/03/08/nes-basics-and-our-first-game.html) for the setup of ```nesasm```). 

I found a nice Sublime Text assembly syntax highlighter from [nesrocks.com](https://nesrocks.com/blog/nes-homebrew-source-code/#more-412) inside their demo game. I copied the file to my repo with credits inside the file (.sublime-syntax file).

## Sprite Editor
I am using a Mac and did not setup wine yet. The recommended editor seems to be [YY-CHR](https://www.smwcentral.net/?p=section&a=details&id=22338). 

I am currently doing my first steps with this [online NES Sprite Editor](https://erikonarheim.com/NES-Sprite-Editor/) written in JavaScript which is also open source and he [blogged about it](https://erikonarheim.com/posts/nes-sprite-editor). You can upload CHR files or create your own files.
