- 👋 Hi, I’m @Belisarius63

<!---
Belisarius63/Belisarius63 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

Hello, world.

In 1980 when most of my high-school contemporaries were working on rusty, smokey, loud cars, I bought an Atari 800.
I've been coding ever since.

I'm currently working on a Raspberry Pi based LIN master for industrial machine controls and testing.

I dabble in science, including chemistry, physics, and astronomy.

Thanks for reading!


Coding History Details:

In the USAF (IBM 370 assembler mostly), then after I got out I did 8-bit video games (6502 assembler) and machine
controls for robotic material-handling vehicles (8085 assembler). After that C under DOS for Computer Telephony Integration
(commonly called voice-mail), then I got back to embedded real-time doing code for a fiber-optic SONET telephony bandwidth
mux/demux.

Then 9/11 happened and my employer folded.

Later I was picked up at a new company when my former boss called me. I did Simulink embedded target development - basically,
creating blocksets which allowed code generation support for various microcontrollers (interrupts, peripherals, etc.). This
position was really an eye opener for me because I worked with some really brilliant model-based designers who did things
like gas turbine FADECs, etc. One really cool application was a docking assistant for yachts; specifically, for yachts with twin
screws and no bow thrusters. The application worked by taking joystick inputs from the pilot which indicated translation and
yaw requests (the stick's forward/back/left/right were translation and the stick twist was yaw). It turned those inputs (plus
inertial and gyroscopic sensors) into commands for each screw using a physics model of the boat. Voila! Slide an 80 foot yacht
sideways into the berth like a pro, even on a windy day! This was in the early 90's, LONG before cheap 6-axis sensor platforms.

The company was purchased by a big corporation and I was laid off - but immediately picked up by a Japanese company who had
contracted with my former employer for a target blockset for a prototype 16/32 bit microcontroller. I was the developer, and
it wasn't done yet. I finished it under my new employer. I went to Japan to present everything to the customer. They were so
careful about their IP that they demanded that the chip I used for development was returned to them personally. I (secretly)
enjoyed telling the customer's electrical engineers that their chip design didn't meet the data sheet specifications, but that
I had successfully developed a hardware work-around to test it anyway.

I continued working for the Japanese company and eventually lived in Tokyo for 9 months working on a project supporting Honda
R&D who were working on the H-120 engine and FADEC for the Honda Jet. Seriously cool. I couldn't believe I was at Honda's
world R&D headquarters working with Japanese engineers doing jet engine control software!

Then 2009 happened. I came back to the U.S. Finding work was challenging. Eventually I signed on as a contracter doing software
testing. It was good to get experience in CMMI/SPICE compliant formal software testing, but it was like being an art critic
instead of an artist.

Eventually I got another contract position doing embedded real-time software. It was a production automotive mechatronics
application with safety requirements. It was for a new generation "smart" actuator which used hard real-time closed-loop
controls. Because the team was small, people wore a lot of hats. I learned a *HUGE amount about manufacturing engineering,
mechanical engineering, and electrical engineering. I also learned a lot about the physics basis for the controls I was
implementing. This allowed my to identify a major blunder in the original controls specification which was causing non-
compliant behavior by the actuator under extreme conditions. I re-wrote the controls and the gross non-compliant behavior
was eliminated, along with some subtle annoyances (poor transient response / inadequately damped oscillations when upset)
that had plagued the project for years.

...continuing...
