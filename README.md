OOMMF TUTORIAL
==============

# Installation

- From the official OOMMF  ![website](https://math.nist.gov/oommf/software-20.html)

- Windows users: you need a C++ compiler such as Visual Studio C++ or MinGW. You also need ![TCL](https://www.tcl.tk/software/tcltk/).

- Linux users: you need `gcc`, `tcl` and `tk`, which you can obtain from the official repositories of your Linux distribution. 

- OOMMF installation instructions are here : ![https://math.nist.gov/oommf/doc/userguide20b0/userguide/Check_Your_Platform_Configu.html](https://math.nist.gov/oommf/doc/userguide20b0/userguide/Check_Your_Platform_Configu.html). 

  In a console/terminal run:
  
  ```terminal
      tclsh oommf.tcl +platform
      tclsh oommf.tcl pimake distclean
      tclsh oommf.tcl pimake
  ```

- If you use git, you can also follow these instructions ![https://github.com/fangohr/oommf](https://github.com/fangohr/oommf)
- Alternatively, you can register at ![https://nanohub.org](https://nanohub.org), where you can use OOMMF from a virtual machine in the browser.

# Documentation

OOMMF has an excellent documentation. The `2.0b` version of the manual can be found in ![https://math.nist.gov/oommf/doc/userguide20b0/userguide/userguide.html](https://math.nist.gov/oommf/doc/userguide20b0/userguide/userguide.html)

# OOMMF Workshop

In 2020, an OOMMF workshop was developed, where basic and advanced techniques were shown. The tutorial slides and videos are specified in ![https://math.nist.gov/oommf/oommf_tutorial/tutorial.html](https://math.nist.gov/oommf/oommf_tutorial/tutorial.html)

The skyrmion tracking example has useful information to process OOMMF snapshot files using the `avf2odt` tool.

The tutorial videos are hosted in Youtube. The first part is shown on ![https://www.youtube.com/watch?v=DYyx9wdiO_A](https://www.youtube.com/watch?v=DYyx9wdiO_A)
