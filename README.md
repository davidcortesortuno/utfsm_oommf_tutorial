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

# References

Checkout the slides of the MuMAx3 Workshop !(https://github.com/davidcortesortuno/alma_tutorials_mumax3_workshop)[https://github.com/davidcortesortuno/alma_tutorials_mumax3_workshop] as a reference for exercises and examples

## Micromagnetic Theory

- Abert, C. Micromagnetics and spintronics: models and numerical methods. Eur. Phys. J. B 92, 120 (2019). ![https://link.springer.com/article/10.1140/epjb/e2019-90599-6](https://link.springer.com/article/10.1140/epjb/e2019-90599-6)

- Exl, L., Suess, D., Schrefl, T. (2021). Micromagnetism. In: Coey, M., Parkin, S. (eds) Handbook of Magnetism and Magnetic Materials. Springer, Cham. ![https://doi.org/10.1007/978-3-030-63101-7_7-1](https://doi.org/10.1007/978-3-030-63101-7_7-1)

- Aharoni, A. (1996) Introduction to the Theory of Ferromagnetism. Clarendon Press. 
