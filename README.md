<div align="center">
  <h1>DIY Fuzz Face Guitar Pedal</h1>
</div>

<p align="center">
  <img src="https://github.com/user-attachments/assets/32115e2c-53b3-4af6-b9a8-7ad629ea09f8" width=40% height=40%>
</p>

<h1>About</h1>
  <h6> &emsp;  The Fuzz Face was one of the first commercially successful distortion pedals released in 1996 by Arbitrer Electronics Ltd. This pedal gained its fame for the asymmetrical clipping fuzz tone that was different from previous fuzz models. Used by the likes of Jimi Hendrix, this pedal quickly gained popularity for the aggressive fuzz tone used on many Hendrix records and shows. With this success, more artists like Deep Purple’s Ritchie Blackmore, Pink Floyd’s David Gilmour, and Beatle’s Keith Richards were incorporating this Fuzz Face pedal into their music. After that, the rest is history and is now known as one of the most influential guitar pedals.
<br/>
<br/>
 &emsp;  The design is known for its simplicity and it’s textbook design. This made the pedal easy to mass produce and replicate with only 11 components. The Fuzz Face was originally designed with germanium PNP transistors, but soon was moved to silicon as silicon versions of the transistors were released. The reason for the switch was because of the sensitivity of germanium components to heat, humidity, and other issues that made the pedal sound different or not work altogether. Germanium tends to have a warmer rounder tone with less aggressive fuzz, with silicon having a more aggressive fuzz sound with higher gain. Both transistor materials have their pros and cons and are sought after for a certain desired tone.<h6>

<p align="left">
  <img src="https://github.com/user-attachments/assets/e813de84-a580-4ab7-9b75-7c9c72f48f73" width="40%" height="40%" alt="Left Image">
  <img src="https://github.com/user-attachments/assets/3579c1e7-0285-4244-b2e0-2b88686eec85" width="48%" height="48%" alt="Right Image">
</p>
  
<h1>Parts List</h1>
<h6> &emsp;Originally the Fuzz Face incorporated PNP germanium transistors. This was because PNP germanium transistors were easier to make consistently and didn’t have any major leakage current like their NPN germanium counterpart. PNP was not an issue back then, since the pedal ran off a 9V battery. The problem comes from the standard center negative power supplies used for guitar pedals not being able to work with PNP without a major redesign of the circuit. This issue was fixed with NPN transistors being put in the circuit, making no difference sonically.
<br/>
<br/>
 &emsp; The design implemented in this repository is made with silicon NPN transistors as I wouldn’t have to worry about inconsistent germanium transistors and anything power supply wise to be able to run the Fuzz Face clone. If you swapped power polarity on a PNP circuit to work with common pedal power supplies, it causes more noise, hiss, motorboating, and more issues. In the circuit design section there will be a additional MAX1044 circuit listed that will provide clean negative ground power for use with the original circuit.<h6>

## Parts List:

- 2 BC109C NPN Transistors (BC108C, BC109, BC183L, BC209C, 2n2222, 2n3904 are also commonly used)
- 1 2.2µF electrolytic capacitor
- 1 22µF electrolytic capacitor
- 1 47µF electrolytic capacitor
- 1 10nF capacitor
- 1 100Ω resistor
- 1 33kΩ resistor
- 1 330Ω resistor
- 1 8.4kΩ resistor
- 1 100kΩ resistor
- 1 1kΩ Linear Potentiometer
- 1 500kΩ Logarithmic Potentiometer

# Circuit Diagrams and Common Mods

## NPN Fuzz Face
<img src="https://github.com/user-attachments/assets/05958d95-4a8d-43b0-9759-f8c560bb8416" width="80%" height="80%" alt="NPN Fuzz Face Diagram" />
<br/>


## PNP Fuzz Face with Power Supply Mod 
<h5>This is the original design of the fuzz face pedal, but with a power supply addition to create a clean isolated positive ground to work with standard pedal power supplies.<h5>
<img src="https://github.com/user-attachments/assets/09956a67-bba3-4ba9-bd93-aef5b9e4e280" width="80%" height="80%" alt="PNP Fuzz Face with Power Supply Mod Diagram" />
<br/>

## 40-100pf Capacitor Across Transistor Base and Collector Mod
<h5>The effect of adding a 40-100pf capacitor across the base and collector of Q2 is a reduction in high frequency gain. This is normally done to silicon transistors to add warmth similar to how germanium transistors sound in a fuzz face.<h5>

<img src="https://github.com/user-attachments/assets/aacce2ef-8cc2-4876-b021-cf631884eceb" width="80%" height="80%" alt="PNP Fuzz Face with Power Supply Mod Diagram" />
<br/>

# Closing Remarks
<h6> &emsp; As you can see, the fuzz face's iconic tone can be created and modified with a very simple circuit. There are countless more mods out there on the internet done by different companies and guitarists alike to add something new to the iconic fuzz face. As I test and discover new fuzz face mods, I will update the repository as nessesary.
