# Yet another (Rust) CHIP-8 emulator

This is a CHIP-8 emulator written in Rust. Done for emulation proof of concept in Orbital 2020!
This version is for Windows due to sdl2 incompatibility. For Linux/Mac OS version, refer [here](https://github.com/theodoreleebrant/YARC)

Tests with games show that it works as expected.

<a href="https://i.imgur.com/4l3gxNh.png"><img src="https://i.imgur.com/4l3gxNh.png" title="PONG Chip-8 Game" alt="PONG game test"></a>


## Requirements
You will need to install Rust. 
Instruction to install Rust can be seen at the [Rust installation guide](https://www.rust-lang.org/tools/install)  


## Run the program
Navigate to the folder in command prompt. [[Help]](https://www.digitalcitizen.life/command-prompt-how-use-basic-commands)  
You can now run any game included by
`````
cargo run filename
`````

For example:
`````
cargo run PONG
`````

### Game instructions:
> Pong 

Left bar up: 1

Left bar down: q  

Right bar up: 4

Right bar down: r


> Space invader

Move left: q

Shoot: w

Move right: e



