# <span size=200> Gesture Controlled Robot </span>


<span style="color: olive;"> My project is a small car that can be controlled with the movement of your hand. The user wears a glove which senses movement, giving different inputs based on which gesture you make. These inputs move the car in different directions. </span>

<!---Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!-->

<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->


| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Norrel A | Dougherty Valley High School | Mechanical Engineering | Incoming Freshman

<!---  **Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg) 
-->
<!---# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 
-->
# First Milestone


<iframe width="560" height="315" src="https://www.youtube.com/embed/634PnCNzBaU" title="Norrel A. First Milestone" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

My project is the Gesture Controlled Robot. I chose this project as its unique method of input piqued my interest. I've finished assembling the hardware for both the car and the glove. I also connected the Bluetooth modules together through following a series of tutorials. The first challenge I encountered was a confusing plethora of tutorials offering me different ways to connect the H-bridge motor driver to the Arduino UNO. I ended up rewiring my setup as I decided to follow the original, long-winded tutorial instead. The second challenge I encountered was a lack of power: I needed to add a second power supply to keep all four DC motors running. When I connected the Bluetooth modules together, I had to stray away from the main tutorial once again. I used this <a href="https://www.instructables.com/Arduino-Two-Way-Communication-Via-Bluetooth-HC-05/"> Tutorial </a> here, showing me how to configure each module as a master or slave.


# Starter Project Milestone

<!---**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**-->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nfM3Oaaae1E" title="Norrel A. Starter Project" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

My starter project was the calculator. I chose this project as I thought it was a great way to practice soldering and assembly while also being useful. The first challenge I encountered was a lack of instructions, but the build was otherwise straightforward. I also damaged the STC chip during construction, so I had to repair it by soldering a small piece of wire to it. Moving forward, I will use the knowledge and experience I gained from this project to streamline the making of my main project. I highly recommend this starter project to incoming BlueStamp engineers as it nurtures critical thinking and proves an elegant desk piece. 


<!--- # Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```
-->
# Bill of Materials


| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Arduino UNO | Contains the code for the vehicle | $29 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Arduino Nano R3 | Contains the code for the glove | $25.10 | <a href="https://www.amazon.com/Arduino-A000005-ARDUINO-Nano/dp/B0097AU5OU/ref=sr_1_3?dib=eyJ2IjoiMSJ9.DuUAPNKOZx3V-ph33HzyN0M-73jcP_H0KcW1aHgUufhQ1KYdLDGa-NFC9DqAKMKBXhyIzngMftHvp0kBuo-NYOnbrtgpFBmZBW_-VRPz5TK1i2y1XPyp4i_CLeZ_SHYukLGyGIhA--MhDtuKa0-ytIkKxs9kwW5bmdW93o9_KWoPshi1meFCONTIBwBengTx1XTSiLjzTx8GnGs0Ez0p3ZzANtbdtbT1Qn2Hl5OHyvk.Z-zVstCWTJN8kdU7cRPxa7Je_gALYjIonkaAI9x956s&dib_tag=se&keywords=arduino+nano+r3&qid=1718407538&sr=8-3"> Link </a> |
| SparkFun Dual H-Bridge motor drivers L298 | Controls the motors' direction | $6.49 | <a href="https://www.amazon.com/Diymall-Module-Stepper-Modules-Arduino/dp/B00NJOTBOK/ref=asc_df_B00NJOTBOK/?tag=hyprod-20&linkCode=df0&hvadid=693611984328&hvpos=&hvnetw=g&hvrand=5328556088157619807&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9032183&hvtargid=pla-2062985254553&psc=1&mcid=170f1bbf2f773d04a1c0254ec6413a12&gad_source=1"> Link </a> |
| Solderless Breadboard Half Size | Base for the glove's electronics | $6.75 | <a href="https://www.amazon.com/BB400-Solderless-Plug-BreadBoard-tie-points/dp/B0040Z1ERO/ref=asc_df_B0040Z1ERO/?tag=hyprod-20&linkCode=df0&hvadid=693601911085&hvpos=&hvnetw=g&hvrand=15606954069564620041&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9032183&hvtargid=pla-638906394402&psc=1&mcid=df8a82d513d937b38ac19209b20d38be&gad_source=1"> Link </a> |
| HC-05 Bluetooth Module "(x2)" | Transmits signals between the glove and car | $10.39 | <a href="https://www.amazon.com/HiLetgo-Wireless-Bluetooth-Transceiver-Arduino/dp/B071YJG8DR"> Link </a> |
| DC Motor, 12 V and Wheels"(x4)" | Moves the vehicle | $10 | <a href="https://www.amazon.com/Gebildet-DC3V-12V-Four-Wheel-Robotic-Aircraft/dp/B08D39MFN1/ref=asc_df_B08D39MFN1/?tag=hyprod-20&linkCode=df0&hvadid=693361699609&hvpos=&hvnetw=g&hvrand=8936357447354879100&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9032043&hvtargid=pla-937905506568&mcid=e05d649e88bd3b5e8e847eb902e02f8b&gad_source=1&th=1"> Link </a> |
| Rocker Switch "(x2)" | Controls the flow of power | $2.75 | <a href="https://www.amazon.com/Switch-Black-Rocker-Rectangular-Opening/dp/B085XD1YQC/ref=asc_df_B085XD1YQC/?tag=hyprod-20&linkCode=df0&hvadid=693270340065&hvpos=&hvnetw=g&hvrand=18279408580620259037&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9032043&hvtargid=pla-2202285594162&psc=1&mcid=b63be441320c3457875ee1a1d02757de&gad_source=1"> Link </a> |

<!--
# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here. 
-->
