# How to Change your Keymap on GitHub (step by step)  

## Summary of tasks:  

  - Login to GitHub, [fork keyboard repository](#1-fork-this-repository)  
  - [Enable workflows/actions](#4-enable-workflows) (to pump out your own firmware)  
  - [Enable keymap editor](#12-click-the-keymap-editor-link) (to edit your keymap)  
  - [Save keymap changes](#24-click-save-at-the-top-to-save-your-new-keymap), download new firmware  
  - [Flash keyboard firmware](#28-plug-left-half-of-the-drift-keyboard-into-your-computer-then-double-click-the-reset-button) one side at a time, enjoy  
<br/><br/>  

## Follow the illustrated guide below if this is your first time  

### 1. Fork [This Repository](https://github.com/Timception/zmk-config-drift-v3-editor)  

<img src="images/1.png" width="600"><br/><br/><br/>  

### 2. Set Repository Name and Create Fork  

<img src="images/2.png" width="600"><br/><br/><br/>  

### 3. Go to the Actions Tab  

<img src="images/3.png" width="600"><br/><br/><br/>  

### 4. Enable Workflows  

<img src="images/4.png" width="600"><br/><br/><br/>  

### 5. Click Build your ZMK Firmware  

<img src="images/5.png" width="600"><br/><br/><br/>  

### 6. Run Workflow  

<img src="images/6.png" width="600"><br/><br/><br/>  

### 7. Wait for GitHub to Compile Firmware Files  

<img src="images/7.png" width="600"><br/><br/><br/>  

### 8. Click the Firmware Link after Build Complete  

<img src="images/8.png" width="600"><br/><br/><br/>  

### 9. Download Firmware  

<img src="images/9.png" width="600"><br/><br/><br/>  

### 10. Unzip to Find 3 Files: Firmware Files for the Left and Right Keyboard Halves and a Reset File  
This confirms that you can now make your own firmware. Next, let's try and change some keys.  

<img src="images/10.png" width="600"><br/><br/><br/>  

### 11. Go Back to the Repository Page  

<img src="images/11.png" width="600"><br/><br/><br/>  

### 12. Click the [Keymap Editor Link](https://nickcoutsos.github.io/keymap-editor/)  

<img src="images/12.png" width="600"><br/><br/><br/>  

### 13. Authenticate with GitHub  

<img src="images/13.png" width="600"><br/><br/><br/>  

### 14. Authorize Keymap Editor  

<img src="images/14.png" width="600"><br/><br/><br/>  

### 15. Add Repository  

<img src="images/15.png" width="600"><br/><br/><br/>  

### 16. Add Select Repository - Drift V3  

<img src="images/16.png" width="600"><br/><br/><br/>  

### 17. After Installation - Keymap will Appear  

<img src="images/17.png" width="600"><br/><br/><br/>  

### 18. Click the Layer Numbers to View the Keys on Each of those layers  

<img src="images/18.png" width="600"><br/><br/><br/>  

### 19. You can Access the Bluetooth Functions by Pressing and Holding "mo2"  

<img src="images/19.png" width="600"><br/><br/><br/>  

### 20. Bluetooth Functions [(more on this here)](https://github.com/Timception/zmk-config-drift-v3-editor/tree/main/docs/bluetooth)  

<img src="images/20.png" width="600"><br/><br/><br/>  

### 21. Click the "Alt" Key to bring up the Behaviour Settings for that Key  

<img src="images/21.png" width="600"><br/><br/><br/>  

### 22. Click the Current Key in the Key Code Field  

<img src="images/22.png" width="600"><br/><br/><br/>  

### 23. Find the Shift Keycode by using the Search Bar then Click "Okay"  

<img src="images/23.png" width="600"><br/><br/><br/>  

### 24. Click "Save" at the top to Save your New Keymap  

<img src="images/24.png" width="600"><br/><br/><br/>  

### 25. Note the Changes you Made (optional) and Click "Commit"  

<img src="images/25.png" width="600"><br/><br/><br/>  

### 26. Click Firmware File Link to go to the Firmware Building Page  

<img src="images/26.png" width="600"><br/><br/><br/>  

### 27. Download New Firmware after Everything is Green and Complete  

<img src="images/27.png" width="600"><br/><br/><br/>  

### 28. Plug Left Half of the Drift Keyboard into your Computer then Double-Click the RESET Button  

<img src="images/28.jpg" width="600"><br/><br/><br/>  

### 29. A New Drive Should Appear (for you to upload your firmware file)  

<img src="images/29.png" width="600"><br/><br/><br/>  

### 30. Drop the Firmware for the Left Side into that Drive and Wait for Transfer to Complete  

<img src="images/30.png" width="600"><br/><br/><br/>  

### 31. Repeat Steps for the Right Half and Drop the Appropriate Firmware File into its Drive  

<br/><br/>

### 32. Test Keys Using This [Online Key Tester](https://www.keyboardtester.com/tester.html) or Download [Switch Hitter](https://www.majorgeeks.com/files/details/switch_hitter.html)  

<br/><br/>


For more information on Behaviours and Key Codes please visit: [ZMK Behaviours](https://zmk.dev/docs/keymaps/behaviors)  


You can see more actual builds [-=HERE=-](https://www.instagram.com/majin.keyboards)  
