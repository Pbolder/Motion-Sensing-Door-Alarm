<h1>Motion-Sensing-Door-Alarm</h1>

 ### [YouTube Demonstration](https://youtube.com/shorts/Vd2loeKt7lI?feature=share)


<h2>Description</h2>
Created a motion-sensing door alarm using components from the school makerspace and a custom PCB. The system detected motion and played audio files stored on an SD card when triggered. The project was developed for an introductory engineering course and was well received by the professor, who kept the device to demonstrate to future classes.  
<br />


<h2>Languages and Utilities Used</h2>

- <b>EasyEDA</b>

- <b>Arduino</b>
  
- <b>Tinkercad</b>


<h2>Design and Build Process:</h2>

<p align="center">
Code: <br/>
<img src="images/CodeDA.png" width="60%" alt="Motion-sensing door alarm Arduino code"/>

The Arduino code continuously monitors an accelerometer for movement while the system is armed. When motion above a set threshold is detected, the alarm sequence is triggered, causing audio to play. The program also includes an arming countdown sequence and a timed cooldown period displayed on LCD before the system automatically rearms itself.


<br />
<br />
<p align="center">
Breadboard Prototype:
<br />
<br />
<img src="images/PwireAD.png" width="50%" alt="Prototype wiring for motion-sensing door alarm"/>
 
The device used a speaker, MP3 player module, audio amplifier, and LCD screen to play alarm audio and display system status information. A MPU6050 sensor was used to detect door motion and trigger the alarm. A battery pack and buck converter powered the system, while onboard buttons allowed the user to arm and control the device.
<br />
<br />
<p align="center">
EasyEDA PCB:
<br />
<br />
<img src="images/PCBDA.png" width="80%" alt="Custom PCB design for motion-sensing door alarm"/>


<br />
<br />
<p align="center">
completed project:
<br />
<br />
<img src="images/FwireDA.JPG" width="40%" alt="Final wiring inside motion-sensing door alarm"/>
<img src="images/FinalDA.jpeg" width="40%" alt="Completed motion-sensing door alarm project"/>
<br />
<br />

<h1>Author</h1>

Designed and built by [Paul Bolder](https://github.com/Pbolder).
