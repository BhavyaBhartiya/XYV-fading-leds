# Fading Led Screen
 
The goal of this project is to build a led screen using only capacitors and resistors that first when turned off fades in the following order X -> Y -> V -> .

## 31/3/26 - Initial Design
 ![image](Initial_Design.png)
 Today I tried creating a 5x5 screen with each led having its own capacitor and resistor.
 The led was fading together even though each had different size of capacitor.
 I found out that it was because of the current flowing to each led as they were all connected.
 ![image](Second_design.png)
 Then I tried using different batteries but still they were interconnected.
### Time Spent: 1.25 Hours

## 2/4/26 - Final Design
 After searching on google I found out that to fix this issue I would have to use diodes and create groups of leds where all the leds in one group would fade out together.
 Then I created an X with 7 leds to test it. It was succeesful.
 Now I added more leds and connected it in a more symetrical way to make it look better. I did not create a complete screen as it did not look good due to the amount of wires connect each of the leds in different groups. 
 ![image](Final_Design.png)
### Time Spent: 0.75 Hours