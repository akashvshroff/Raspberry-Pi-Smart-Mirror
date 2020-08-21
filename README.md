# Outline:

- I've always wanted to learn how to use Linux and therefore I purchased a Raspberry Pi 4 and started tinkering around. After spending a few days understanding the Linux file system, having gotten accustomed to the Windows setup, I wanted to build a fun project that would allow me to dive deeper into the pi whilst also building something that could be useful. That was when I came across [Gremson's Magic Mirror YouTube Video](https://www.youtube.com/watch?v=aa3VVZA0e5Y) and was instantly intrigued. I loved the idea of a mirror - an everyday commonplace item - being extended and made more useful by some seemingly simple tech! I had found my project and wanted to design the mirror as a gift.
- After some more research into the whole world of Magic Mirrors, I thought I would capitalise on the excellent base software already built by Michael Teeuw and a host of other enthusiasts who have made the process extremely trivial for novices like me. A comprehensive introduction to their software can be [found here](https://magicmirror.builders/). Their software essentially runs a continuous webpage that refreshes periodically and sits below a one-way mirror (more info on the hardware to follow) and the most useful part of the software is the fact that it is perfectly customizable and there is a whole host of third party modules (which can be found in the MagicMirror documentation above) that can be used to fashion a mirror based on the users needs.
- A more detailed description about the software and hardware lies below!

# Description:

- First, I'll address the hardware. Please note that I am not going in depth into the construction of the frame and other hardware components as there is an abundance of better tutorials, one of which can be found [here](https://www.howtogeek.com/414647/how-to-build-a-smart-mirror/). I took to paper to draw out the frames and measurements, which I based around an old BenQ monitor that was laying around and arrived at the following initial plans - please excuse my handwriting.

![alt-text](https://github.com/akashvshroff/Raspberry_Pi_Smart_Mirror/blob/master/Footage/Initial_Plan_1.jpg)

- I also fashioned a 2"x2" hole in the inner frame in order to run the wiring through neatly. I found it much easier to visualise the whole process as a stack and starting from bottom to top, the build consisted of the outer frame, followed by the inner frame, then the one-way mirror, the monitor, opaque board (which replaced the opaque film) - to block light where the monitor didn't cover the mirror finally followed by the pi and the wiring (the regular power and HDMI cables).

![alt-text](https://github.com/akashvshroff/Raspberry_Pi_Smart_Mirror/blob/master/Footage/Initial_Plan_2.jpg)

- Note that this layout did change in the end, here are some pictures of what the final build looked like.
