<h1 align="center">﷽</h1>
<h1 align="center">
<font size="48"><b>🛦 X-26 GREYWOLF PT-1</b></font>
</h1><br>

<h4 align="center">
  <b>An experimental prototype of <i>X-26 GREYWOLF</i></b>
</h4>
<p align="center">
<a href="#breif interview of the ">Breif interview of The WOLF</a>•
  <a href="#visual looks">Viusal Look</a>•
  <a href="#materials list">Materials List</a>•
  <a href="#electronics list">Electronics List</a>•
<a href="#credits">Credits</a>•
<a href="#lincense">License</a>
</p>
<br>

> **Status:** PT-1 finished  
> **Design:** Fusion 360  , Kicad
> **Platform:** [Hack Club Blueprint](https://blueprint.hackclub.com/projects/2458)

---<br>

 <br><br>                        
                        
## Breif Interview Of THE WOLF🐺

This WOLF, not a literal one, is the first PT(prototype) of the experimental plane series **GREY WOLF** 
The PT-1 is single engine (not a literal engine could be in future)powered ,running about **1.3-1.5**meters long ,standing almost **30 cm**tall . 
The WOLF has a wingspan of almost **a meter** and a wing area of a **meter** too. Has a total of **8 control surfaces** Two of 'em are flaps,two ailerons ,two stabilators, and two rudders ,not rudders but whole moving tails.Also features three landing gears all of 'em with openning and closing bays.Also in this prototype i've designed my own type of somewhat lookin like S-duct ,Just to study the effects of air in turbulence while flying at low altitudes at high speeds.Expected speeds are like 150-250 mph ,result of edfs 3.4-4kg thrust and planes empty weight being 1.5-2 kgs ,looks a big number but thts a rough guess and the weight can be reduced in real life development.  
Abt the electronic part .This beast has a spotter board and an on-board RADAR .<br><br>
***THE SPOTTER BOARD***<br><br>                        
                            The spotter board collectd info abt the plane ,like the current co-ordinates ,speed and altitude of the plane .The current specs are just collecting basic info ,but i plan to add more sensors like pressure sensing at tht altitude ,Measuring the temperature of the Engine (EDF) and the front facing parts of the plane tht can get heated while flying at high speeds.
                            It consists of two parts the transmitter board and the reciever board . SO the transmitter board is called **THE SPOTTER BOARD** and the reciever board is**THE SNIPPER BOARD **.The transmitter uses:
                            - ESP32-DEVKIT-M1
                            - MAX-M10S
                            - LORA SX1278 
                            - PE4259 RF SWITCH 
                            - 2x SMA CONNECTORS FOR SMA ANTENNAS.
  THE SCHEMATIC DIAGRAM WITH NET LABELS FOR THE TRANSMITTER BOARD IS <img width="1366" height="768" alt="Screenshot (388)" src="https://github.com/user-attachments/assets/1e88453c-8f71-475e-b65f-611be99637a6" />

The reciver part on the hand shows all of the info recived on a dual display ,so the major components list is as follows:
                                                                                                         - ESP32-DEVKIT-M1
                                                                                                         - LORA SX1278
                                                                                                         - 2x ILI9341 320x240 DISPLAY
                                                                                                         - PE4259 RF SWITCH.
                                                                                                         
<br>
                        So it collects the info sends it back to the ground where on an oled display all the info is shown ,also it can allow the ground crew to monitor the planes location on googlemaps as it can be codded to show the location on google maps.<br><br>
***RADAR***(maybe in future not currently ! also reviewers payattention here)<br><br>
           The work of radar is to detect objects within its range . The objects can be like upcomming hurdels ,other planes or even birds. It can and is planned to serve as an **eagle eye** while the visual range is pretty much reduced ,also it can be made to detect the controller of the plane .i mean the person piloting the plane and in case help in doing some radar type landing 😁<br><br>                        
So as u've read this project ,Resembles a Symbol of my creativity and curiosty in Aviation .

## Visual Looks
|<img width="947" height="758" alt="X-26 PT-1" src="https://github.com/user-attachments/assets/47d1a2f4-ce30-4493-bc2f-2670a803b911" />|<img width="947" height="758" alt="Screenshot (184)" src="https://github.com/user-attachments/assets/5548facd-ced2-4b21-abdb-d9beb347fd87" />
|<img width="947" height="758" alt="Screenshot (183)" src="https://github.com/user-attachments/assets/38e28f34-7f14-44f3-b3ca-d8c9660d7a83" />|


<br><br>
## Materials List
The list of materials used is as follows:-
- **DEPRON** for surface covering and making inner supports maybe.
- **CARBONFIBRE** for making spars,ribs,and frames whih are going to hanlde some aerodynamic stress.
- **PLYWOOD** suplmentary material in case of not usin the carbon fibre. maybe i wont use this.
- **PCB's** for the Spotter board and the radar .
<br><br>
## Electronics List🔌
The lsit of electronics used are:-
- **Sg-90 Servo** 180 degree rotating servo, for gaining control over control surfaces.
- **80mm Edf**  The power unit thats gonna pwerup the whole jet.
- **Fpv CAM**(for future use)not currently deployed.
- **22.2v 6000mah Lipo**for running these heavy electronics.
- **PCB** for the spotter board.
- **Max-M10s gps chip**
- **SX1278 lora chips**
- **PE4259 rf switches**
- **TPS 79333 voltage regulator**for extra safe voltage input
- **Small LED lights** for night flight and night landing purpose
- **5v lipo** for spotter and radar modules
- **Henry inductors, capacitors,resistors**
- **SMA antennas**
<br><br>
**📣AN IMPORTANT NOTICE**<br>
                         Many of the veiwers may resemble it with **F-35**or**F-22** ,but its not ,Its a blend of **F-35,F-22&F-16**
                         u may find some parts similar but lemme tell u if u look at the intakes they are similar to F-22's ,
                         If u look at the vertical tails and engine u'll find them similar to F-35,And If someone may look at
                         The airframes they are enhanced form of F-16's Air frames.
                         Therefore PLZ do not mix it with Any other Aircraft,I shall be thankful to u.

## Credits💼📜
First of all I'm gonna Credit my **Father** he taught me almost everything about the aircrafts
He's a professional in his feild ,and He is the who encouraged me to build this project..

Secondly My **Big Bro** he was the atual reason i built it ,cuz he challenged me to make my own one
And hes the one who told me about **Blueprint**.So if he wouldnt have challenged me ,my mind  wouldnt have accelerated those ideas that 
led me to design this beast.

Thirdly **Hackclub Blueprint**
I wanna thank the team for starting this type of projects ,that enables many teenagers to enhance thier skills
Also because of **Blueprint** the project that was only a cad file ,is going to come to life.

## License🔐

The owner of this Project is Muhammad Abdullah (me)
And do not allow any change or coppying of files.




