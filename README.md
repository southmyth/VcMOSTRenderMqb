# VcMOSTRenderMqb
Way to write custom data to Virtual cockpit for MQB platform

To make this work you need to install Python3.3 to MIB2.5 first using following package repositories: https://pkgsrc.mibsolution.one then save current version of VCRenderData.py to sd card or upload it via winSCP
To run the code then execute 

> python3.3 /fs/sda0/VCRenderData.py

This is what can be achieved for now

https://github.com/jilleb/mib2-toolbox/assets/320479/d625360f-629a-4b98-9ecd-61b4ec68585a

![image](https://user-images.githubusercontent.com/320479/280536425-d9cbde9c-9c01-4852-8c2f-9d4c5a4a7283.png)

Now font can be scaled and also some new characters/icons appeared
![image](https://raw.githubusercontent.com/OneB1t/VcMOSTRenderMqb/main/render.bmp)

My next goal is to get some usefull data from exlap channel and render them in theory it should be possible to also get data/image from AA/CP and render them onto VC. Any help or ideas are appreciated.

Also to be able to run Android Auto on main unit and data on virtual cluster it is needed to patch navigation in M.I.B. Navignore
