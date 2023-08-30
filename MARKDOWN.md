## Challenges:

### 1.Web:
-  #### Simple Web:
    1.Opened the Deployment of the website.
   
    2.Clicked on inspect and headed to the Sources page and chose script.js.

   3.Scrolled down untill a list of words was found and looked promising enough to be the flag.

   4.Used Base64 in order to decode the given text.

   5.The flag was wired{m5_Dh0n1_1S_b3sT_c4Pt14N}

   6.Another way to get the flag was to figure out the Username and Password to the website. This would display a pop up which shows u the flag to be deciphered.
    
### 2.Crypto:
-  #### Crypto Layers:
    1.In order to recieve the flag, the message had to be decoded in Binary > Caesar(shift of 5) > Vignere.

    2.The Binary text was converted into Swby70Hqd3u5Jn3S00q (into Caesar).

    3.The Caesar text was converted into Nrwt70Cly3p5Ei3N00l (into Vignere) with a shift of 5.

    4.The Vignere text was converted into Cryp70Lay3r5Ar3C00l (the flag) with the key as "LAYER".

    5.The HINT really helped me to get throught and solve the challenge.
-  #### da_french_cipher:
    1.wmzsx{w3pk0a3_n0_tl3_e0ffd_0j_k1db3rw} had to be decoded using a french cipher language.

    2.It could either be Caesar or Vignere. Vignere was used to decipher the message in order to get the flag.

    3.wmzsx{w3pk0a3_n0_tl3_e0ffd_0j_k1db3rw} was converted into wired{w3lc0m3_t0_th3_w0rld_0f_c1ph3rs} with keys as the vowels (AEIOU).
   
### 3.Wireless:
-  #### w!r3d_sh4rk:
   1.This task was completed with the help of the software "Wireshark".

   2.The given file was opened in Wireshark.

   3.flag-is-wireshark-is-cool.my.canva.site was the first thing that seen after entering into the file.

   4.Replacing the '-' with '_' was the format of the flag (flag{wireshark_is_cool}). 

   5.The flag could have also been found after searching for the canva website. The flag will be displayed right in front.

-  #### what's_up_DoH:
   1.This task was completed with the help of the software "Wireshark".

   2.The given file was opened in Wireshark.

   3.Using the search bar (Ctrl+F), and seraching 'idk567', I was able to find 'idk567.my.canva.site' inside a packet.

   4.Searching for such a website reveals a image of Spongebob on the screen.

   5.The flag is wired{Spongebob_Squarepants} , which can be found in the inspect bar or by just typing out the name of the character on the screen.

### 4.Reversing:
-  #### grep it:
    1.This task wasn't completed using Linux. The file was opened in notepad.

    2.'wired' was typed into the search bar and the flag 'wired{Argentnia_cant_even_beat_Saudi_Arabia}' was found out to be the flag.

~~The flag did hurt me :(~~ 

-  #### 0R_bu7_3xCLus1ve:
    1. ---------------------------------------------------------------
   
### 5.ICS:
-  #### sh0d4n:
    1.'shodan' was used as the website to find out the flag.

    2.The text 'gas tank' was serached untill the right IP was found to be the flag (the gas tank was in Canada).

-  #### l4dd3r_l0gic:
    1.The website PLCsimulator was used.

    2.The whole diagram was reconstructed into the simulator.

    3.The different boolean values were entered and given to the differnt 'NO Relay contact', 'NC Relay contact' and 'Output coil'.

    4.The relay contacts were switched to True and False untill all the Output coils glowed green together.

    5.The values of the variables w,x,y and z were False, True, True and False (0110).

    6.Using a MD5 Hash Decoder, the flag was figured out to be '2a66acbc1c39026b5d70457bb71b142b'.

    7.The flag didn't seem to be working at first, but after a fix, the task was completed.
   ![image](https://github.com/D-0zakh/D-0zakh/assets/143344125/07ee1a8a-d201-4a3f-aac6-9d0f0912ee39)

   
   ![image](https://github.com/D-0zakh/D-0zakh/assets/143344125/cdae35a7-6e80-4dac-a58b-45660e089fab)


   
### 6.Misc:
-  #### Find Me!:
    1.Different Social Media platforms of 'Jenisha Harrison' had to be searched in order to find more about the country she was in.
   
    2.Heading onto her X(Twitter) acount 'Jenisha Harrison', we were able to find out about her instagram username.
   
    3.We were able to find 5 images uploaded onto her account. These seemed random, but one image of a socket led to the flag.
   
    4.The socket was mainly used in Italy. Thus, wired{Italy} was the flag.
   
-  #### Web Sleuth!:
    1.'Estebanlavos' was typed into the search bar of Github untill the a 'Readme.md' file was found which had a username to his X(Twitter) account.

    2.The account consisted of 5 images that seemed random at first.

    3.Looking further into the comments led to the flag.
   
-  #### da_0n3_wh3r3_u_v1su4l1s3:
    1.The original way to find the flag was to change the format of the file (.txt) to .jpg

    2.This didn't seem to work on my laptop.

    3.But downloading the same file on my phone seemed to open it in .jpg format which led to the flag.
   
 - #### MICH43L5_P4R4DIS3:
    1.In order to find the flag, the given iamge had to be reverse image serached.

    2.The bridge clearly looked like the bridge from GTA 5. The name fo the bridge 'Vespucci Bridge' was the flag.
   
-  #### Achan's Favourite:
    1.The file given was in the .wav format.
   
    2.In order to get the hidden flag, the file was different types of formats (.txt ,.jpg ,.png).

    3.The audio file was decoded using 'https://academo.org/demos/spectrum-analyzer/' in order to get the flag.

    4.The name of the person shown(Steven He) ,who created the meme was the flag.

### 7.Embedded:
-  #### D0t5 & D4sh35:
    1.The given Morse code had to decoded. The Morse code code took many attempts to fully solve and type in the flag.

    2.Morse Code was searched was figured out in order to figure out the flag.
   
    3.The flag was wired{it_is_what_it_is}.
   ![image](https://github.com/D-0zakh/D-0zakh/assets/143344125/e7767a78-fef7-4d82-b8d7-db2ce6ac9665)

   
-  #### GATE Reversing:
    1.The given task was to find the values of A, B, C and D.

    2.In order to get the values, we have to know the different logic gates (AND, OR, NOT).

    3.I did the task after trial and error. The values were 1001.

    4.The actual way to solve it was done as well.
   ![image](https://github.com/D-0zakh/D-0zakh/assets/143344125/d5462a05-5ec6-44d7-9949-b232cb787b24)


-  #### u_4r7:
  1
-  #### Ain't no sunshine!:
    1.The given circuit in the imaage had to be connected in roder to recieve the flag.

    2.A proper connection between the A0, Ground, 5V and the potentiometer made the Arduino UNO connect and display the flag in the Serial Monitor.

    3.The reset button had to be pressed to get the output (the flag).

    4.The Arduino board had to be connected to the laptop via the HDMI cable in order for the rduino IDE to detect the device.
   
-  #### 70ugh_n07_70UgH:
1
-  #### L05t_With1n_R0bots:
  1
-  #### μPython_flag:
  1
-  #### extraCt:
-  1.
-  #### ESP-ionage:
  1


### 8.Automotive:
- #### CANtroll:
    Wasn't able to to do it
