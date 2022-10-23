# DIY-Solid-State-Relay-module
This is the solid state relay which is same as sugar cube relays available in market, These SSR based on electronics switching.
Get more info from here: https://www.hackster.io/electroboy001/diy-solid-state-relay-module-e170f3

Relays are the most useful and stable AC power switching components. Relays provide complete  isolation of DC operating voltage from AC mains. The regular size of relays is big because of mechanical moving actuator and a coil. The coil forms an electromagnet which then used to attract the metal actuator points and thus turn on the AC power. The most popular relay SPDT (single pole double throw) has 5 terminals, 2 for the coil and 3 for the mains connections. NO (Normally open), NC (Normally closed) and COM (common point).

The main problem is that the takes a lot of current and due to mechanical action of actuators there is sparks in between of both terminals. Which cause serious problems like tear down, terminal welding and damaging. But there is one solution to all of these problems known as SSR (solid state relays). They are the electronic based switches which can be used for fast switching of AC appliances or to control the power ratings.

These electronic AC switches are known as TRIAC. In last we will build our own SSR module using 4 TRIAC and compare the same with the existing mechanical relays. I am using JLCPCB SMT assembly service, JLCPCB is the China’s leading PCB manufacturing company working in this field for more than 15 years. You can explore the all services from here. Sign-up https://jlcpcb.com/see
https://jlcpcb.com/see

Components Required:
1) BT136 (SMT package)
2) MOC3021 (TRIAC driver)
3) 10k, 1k Resistor
4) Pin headers and screw terminals
5) PCB prototypes from JLCPCB

Switching modes of TRIAC and Driver:
As stated above “Once triggered, SCRs and TRIACs continue to conduct, even if the gate current ceases, until the main current drops below a certain level called the holding current”. But here in our case we are using a dedicated TRIAC driver, this one helps in switching the TRIAC by AC cycle feedback. There are two types of TRIAC driver available in market one is Zero voltage switching and other one is random phase shift. You can see all info in the video given above about these drivers.

https://www.youtube.com/watch?v=kRrBL9sri10

Working of SSR:
This Solid-state relay is working in the same manner as mechanical sugar cube relays, but this time we have only two terminals. One is common and other one is NO (Normally open). Basically, the resistance is controlled at the output. When there is no trigger on the Gate pin the TRIAC output resistance in Mega-ohms which switch off the appliances connected to it. You can see the different TRIAC parameters directly from the datasheet. This module is working fine on +5volts and consuming just 10mA of current which is way lesser than old mechanical relays. You can also change the driver in order to make a dimmer AC circuit using the same TRIAC. A very thanks to JLCPCB SMT assembly service for the SSR prototypes.
https://jlcpcb.com/see
