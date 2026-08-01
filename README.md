# custom-keyboard
## a custome keyboard for the keeb project from hack club
### 0h in
I am going to participate to the keeb project from hackclub to create my custom mechanicale keyboard I have a little bit of experience in everything that I will need in this project (kiCad, CAD, coding, soldering) but by doing this project i want to do learn more.

### 0h30 in
I have start doing an idea of what I want I a 70% keyboard layout I think I am going to for linear switches and i think as addon i will add LED's and a rotary encoder but no oled screen because i don't know what to do with it and i think i am going for a black case design. Here's the layout that I make by myself in a website that i found, and i will use it as a guide here is it :
<img width="1242" height="497" alt="image" src="https://github.com/user-attachments/assets/ac84f850-609d-44d4-a885-7f2bf3603e44" />
i know it's simple but it's good and versatile and now it's time for the pcb

## 2h in
I have just started to do the schematic the keyboard had taked me some time and also the LED matrix but for the rotary encoder i didn't had enough pin for the rotary encoder so with some help of the community and some research I added it to the switch matrix and I had the idea of connecting it only to ROW0 (and not to COL0) so if the raspberry pi have only signal to the ROW0 pin it will know that it's the rotary encoder switch pin. I also added a oled screen because it's seem cool at the end and I am about to finish the schematic I just have to add some little resistor and capacitor for security and I am done
Here's some photo of my switch matrix, my addons and my raspberry pi :
<img width="1400" height="627" alt="image" src="https://github.com/user-attachments/assets/e54ee839-6211-4c6b-8fbf-f5a5fafc7028" />
<img width="1541" height="882" alt="image" src="https://github.com/user-attachments/assets/defec5d3-39f7-45e2-9e3a-67f7cca853f6" />
<img width="246" height="372" alt="image" src="https://github.com/user-attachments/assets/b84356af-00aa-40b9-b423-69f6f4b1999d" />

## 3h in 
I finished all i needed in my schematic added resistor and capacitor in the led matrix to secure it and annotated all the part and added all the footprint and my schematic was finished
here's the last picture of my schematic :
<img width="1798" height="922" alt="image" src="https://github.com/user-attachments/assets/c68c4775-ee38-42dc-90d8-b8a8964a622f" />
<img width="1542" height="967" alt="image" src="https://github.com/user-attachments/assets/e32ce1cf-321d-4223-9d47-3b81ecba9f1b" />
<img width="857" height="493" alt="image" src="https://github.com/user-attachments/assets/a725a803-235a-49e8-bcf1-7393c991ee68" />
Now i am starting the pcb part i didn't start yet but i have now to do some tricks to make it compact but also to fit all the part inside it
Here's a picture of the starting pcb :
<img width="703" height="652" alt="image" src="https://github.com/user-attachments/assets/c7bab2c5-d345-4d38-8090-fe6ab14e0d28" />

## 4h in
I started placing all the diode and switches in place but now i have to place the LED's and after it I will have to start routing the trace
here's my progress :
<img width="988" height="706" alt="image" src="https://github.com/user-attachments/assets/27fe9b27-e1c0-438a-ae6b-200f7dba2bda" />
<img width="1182" height="542" alt="image" src="https://github.com/user-attachments/assets/3103f394-17b2-4a12-a3e1-8ba85991601a" />











