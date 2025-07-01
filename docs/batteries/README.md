# Battery Installation  

## Contents:  

 - [3D Printables for PS3 Controller Battery Pack](https://github.com/Timception/3d-printables/tree/main/v3/battery-pack) - Takes you to the 3D printables page for these parts
 
 - [Batteries](#batteries-tested-to-work-with-the-keyboard) - Some batteries you can use for this keyboard  
   
 - [Screwing on the PS3 controller battery pack](#screwing-on-the-ps3-controller-battery-pack) - Start of the assembly guide  
 
 - [Plugging in the Battery Connector](#plugging-in-the-battery-connector) - Hooking up the battery  
 
 - [Plugging in the 4-Pin OLED](#plugging-in-the-4-pin-oled) - Standard (power hungry) OLED  
 

## Alternate Battery:  
 
 - [Using the 110mAh LiPo Battery](#using-the-110mAh-lipo-battery-instead) - the smaller battery option (removing the OLED dramatically improves battery life)  



## Alternate Display:  
 
 - [Replacing the 4-Pin OLED with a NiceView](#replacing-the-4-pin-oled-with-a-niceview) - Best screen to use if you install the 110mAh battery  
<br/><br/>

>[!Warning]
>Important Note on LiPo Batteries  
>  
>LiPo (Lithium Polymer) batteries are considered a fire hazard due to their sensitivity
>to overcharging, punctures, or improper handling, which can lead to overheating or combustion.
>Because of strict shipping regulations, LiPo batteries cannot be included with this keyboard
>and must be purchased separately by the builder.  
>  
>Disclaimer: I am not responsible for any damage, injury, or loss resulting from the use,
>charging, or installation of LiPo batteries. Use at your own risk and follow all safety guidelines
>provided by the battery manufacturer.  
<br/><br/>  

## Batteries tested to work with the keyboard

- 1800mAh PS3 Controller Battery (LIP1359)
   
  - [Amazon Item Link](https://a.co/d/4CgXvFp)  
  - [Aliexpress Item Link](https://www.aliexpress.com/item/1005005213892382.html)  
  <br/>  

- 120mAh LiPo Battery (401230) + JST PH2.0mm - This battery is small enough to fit under the MCU
  
  - [Aliexpress Item Link](https://www.aliexpress.com/item/1005003383250806.html)  
  <br/>  
  
- 110mAh LiPo Battery (401030) + JST PH2.0mm - This battery is small enough to fit under the MCU
  
  - [Ebay Item Link](https://www.ebay.com/itm/124961007813)  
  - [Aliexpress Item Link](https://www.aliexpress.com/item/1005006161362814.html)  
  <br/>  


## Screwing on the PS3 controller battery pack  

1. Make sure this screw is already screwed into the nylon standoff on the other side.  

<img src="images/1.jpg" width="500"><br/><br/>


2. Place Bottom Plate Section and Screw in this 12mm screw first.  

<img src="images/2.jpg" width="500"><br/><br/>


3. Screw in the nylon standoff as shown below.  

<img src="images/3.jpg" width="500"><br/><br/>


4. Here is how the battery will fit in the 3D-Printed battery pack.  

<img src="images/4.jpg" width="500"><br/><br/>


5. First, put the JST PH2.0 battery connector through to the other side as shown below.  

<img src="images/5.jpg" width="500"><br/><br/>


6. Next, carefully place the battery cover over the battery.  

<img src="images/6.jpg" width="500"><br/><br/>


7. Align/Adjust the cover so the screw holes match the plate underneath.  

<img src="images/7.jpg" width="500"><br/><br/>


8. Now screw in this 5mm M2 screw as shown in the image.  

<img src="images/8.jpg" width="500"><br/><br/>


9. Next, screw in this screw.  

<img src="images/9.jpg" width="500"><br/><br/>


10. Then this 12mm screw as shown.  

<img src="images/10.jpg" width="500"><br/><br/>


11. Screw in the nylon standoff seen just under the RESET switch.  

<img src="images/11.jpg" width="500"><br/><br/>


12. Next screw back in the hex nut with the brass standoff and leave the allen key wrench in.  

<img src="images/12.jpg" width="500"><br/><br/>


13. Hold the allen key wrench in position to prevent it from spinning as you screw in from the other side as shown below.  

<img src="images/13.jpg" width="500"><br/><br/>


## Plugging in the Battery Connector  

14. Now insert the battery connector by hand, with the help of tweezers or the switch puller as shown.  

<img src="images/14.jpg" width="500"><br/><br/>


15. Make sure the jumpers are over the correct pins as shown in the image (they should be correct straight out of the box).  

<img src="images/15.jpg" width="500"><br/><br/>


16. Do the same for the right half and see if the cable colors and jumpers are the same as in the image below.  

<img src="images/16.jpg" width="500"><br/><br/>


17. Place the 3D-Printed cover over the MCU so that it is flush with the PCB.  

<img src="images/17.jpg" width="500"><br/><br/>


## Plugging in the 4-Pin OLED  

18. Insert the 4-Pin OLED into the left female pin headers as shown in the image for both sides.  

<img src="images/18.jpg" width="500"><br/><br/>


# Using the 110mAh LiPo Battery instead  

19. Remove the MCU carefully with a switch puller.  

<img src="images/19.jpg" width="500"><br/><br/>


20. Insert the connector through the hole as shown.  

<img src="images/20.jpg" width="500"><br/><br/>


21. Push the connector back out the other hole as shown.  

<img src="images/21.jpg" width="500"><br/><br/>


22. Try to avoid the pins puncturing into the wire to prevent unwanted short circuits (electrical tape can be used to cover the pins).  

<img src="images/22.jpg" width="500"><br/><br/>


23. Check that you have moved the pins to the correct positions as shown before plugging in the battery connector.  

<img src="images/23.jpg" width="500"><br/><br/>


24. Carefully push the MCU back into its place with the pins aligned correctly.  

<img src="images/24.jpg" width="500"><br/><br/>


25. Repeat the process for the right half with the jumpers placed as shown.  

<img src="images/25.jpg" width="500"><br/><br/>


# Replacing the 4-Pin OLED with a NiceView

26. You can replace the normal OLED with a super efficient screen famously known as the [Nice!View](https://nicekeyboards.com/nice-view/)

> [!Warning]  
> You will need to flash a [special version of firmware](https://github.com/Timception/zmk-config-drift-v3-nv-editor) on to both sides before inserting the Nice!View
> 
<img src="images/NiceView.jpg" width="500"><br/><br/>


> [!Note]
> If you forgot how to fork and compile your own firmware, [please refer to this guide](https://github.com/Timception/zmk-config-drift-v3-editor/tree/main/docs/change-keys)
<br/><br/>  
