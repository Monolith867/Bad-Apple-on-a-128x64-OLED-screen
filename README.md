# Bad-Apple-on-a-128x64-OLED-screen
More of a joke project that took more effort than I imagined. I have recently ordered an OLED screen with a resolution of 128 by 64 and thought to test it by trying to play the popular [Bad Apple video](https://www.youtube.com/watch?v=FtutLA63Cp8&list=RDFtutLA63Cp8&start_radio=1) on it. 
Now, you can't play the video directly on it, as the screen can mainly display images and text, so what I did was to first convert the video resolution to 128 x 64. Then I decided I'm not gonna play the whole video for a test, so I trimmed it to only the first minute. Then I extracted all the frames in the video at a speed of 13 FPS using an online tool. After that, I converted every frame into its C++ equivalent so it can be displayed properly. Finally, I made the screen display these at a rate of 50 ms/frame using a 'for' function.

# Bill of Materials

x1 ESP32

x1 OLED 0.96” screen

Wires

#Enviroments and online tools used

Arduino IDE

Windows 10

Video to frames: https://videotoframes.com/

Video trimmer: https://online-video-cutter.com/

Video resolution modifier: https://online-video-cutter.com/resize-video

#Media 

<img width="2048" height="1376" alt="image" src="https://github.com/user-attachments/assets/61630e47-aa95-41ae-81a1-b1009baf8c77" />

<img width="1157" height="2048" alt="image" src="https://github.com/user-attachments/assets/438e2895-30e6-4b08-b44b-23ac9dcae0f7" />

Video proof: https://imgur.com/a/9r9WVLc

Disclaimer: I do not own neither the original song nor the animation, credit is due to their original owners.

