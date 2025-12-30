# Exercise 4 : Blink LED1 by AI coding

First, create a project and set PA00 as LED1 with MCC. It is the same as ex3.

<br>![pic](pico/pic4a/a.png)<br>
select [Open Chat].<br><br>

<br>![pic](pico/pic4a/b.png)<br>
select [MPLAB AI CODING ASSISTANT].<br><br>

<br>![pic](pico/pic4a/c.png)<br>
Press the button indicated by the arrow.<br><br>

<br>![pic](pico/pic4a/d.png)<br>
Press the button indicated by the arrow. Relink to server.<br><br>

<br>![pic](pico/pic4a/e.png)<br>
Check the indicator is green. <br>
Select [Agent] mode.<br><br>

<br>![pic](pico/pic4a/f.png)<br>
Fill in the prompt.<br><br>
please help me coding. I need a program for blinking LED with 1Hz.<br>
MCU is PIC32CM3204GV00048.<br>
I had set MCC, GPIO of PA00 as LED1.<br>
I want to use while loop to do it.<br><br>

<br>![pic](pico/pic4a/g.png)<br>
Press button of [Accept All], AI will change the code at main.c<br><br>

Finally, build code and program device.<br>

# Ex4.2
please help me coding. <br>
I need a program for blinking LED with 500ms On and 500ms Off.<br>
I want to use systick to delay.<br>
MCU is PIC32CM3204GV00048.<br>
I had set MCC below<br>
-GPIO of PA00 as LED1.<br>
-systick 100 ms<br>
