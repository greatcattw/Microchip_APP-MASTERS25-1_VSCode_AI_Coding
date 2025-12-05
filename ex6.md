# Exercise 6 : ADC with timer callback, Data Visualizer

<br>![pic](pic6/1.png)<br>
Create a new project for EVK of APP-MASTERS25-1 .<br>
Start MCC.<br>
Run [Plugins/Clock configuration] to check Main Clock.<br><br>

<br>![pic](pic6/2.png)<br>
Run [Plugins/Pin configuration] to set pins.<br><br>

<br>![pic](pic6/3.png)<br>
Set Systick as 200ms<br><br>

<br>![pic](pic6/3a.png)<br>
Form [Device Resource], add ADC, SERCOM0, STDIO to [Project Graph]<br><br>

<br>![pic](pic6/3b.png)<br>
Ok to add ADC, SERCOM0, STDIO <br><br>

<br>![pic](pic6/4.png)<br>
Set parameter of ADC.<br><br>

<br>![pic](pic6/5.png)<br>
Link SERCOM0 and STDIO.<br>
Set parameter of STDIO.<br><br>

<br>![pic](pic6/6.png)<br>
Set parameter of SERCOM0.<br>
Project Resource / [Generate] to add MCC code to project.<br>
copy-paste code  form src/ex6/main.c to main.c of project.<br>
Do work of "build" and "program devcie."<br><br>

<br>![pic](pic6/11.png)<br>
press ctrl+shift+p and select MPLAB:Data Visualizer.<br><br>

<br>![pic](pic6/12.png)<br>
press the icon to set parameter of UART.<br><br>

<br>![pic](pic6/13.png)<br>
Check Buad Rate.<br><br>

<br>![pic](pic6/14.png)<br>
press the icon to display data.<br><br>

<br>![pic](pic6/15.png)<br>
Select [Send to Terminal]<br><br>

<br>![pic](pic6/16.png)<br>
Data Visualizer display the data for MCU.<br><br>
