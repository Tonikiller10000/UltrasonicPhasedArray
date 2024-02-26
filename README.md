# UltrasonicPhasedArray
An ultrasonic Phased Array made out of 8x 10mm ultrasonc transmitters.




<img src="https://github.com/Tonikiller10000/UltrasonicPhasedArray/blob/main/UltrasonicPhasedArray_Pictures/parts.png"/>
<img src="https://github.com/Tonikiller10000/UltrasonicPhasedArray/blob/main/UltrasonicPhasedArray_Pictures/pro.png"/>
<img src="https://github.com/Tonikiller10000/UltrasonicPhasedArray/blob/main/UltrasonicPhasedArray_Pictures/pcb.png"/>



## How it works:
The ultrasonic emitors generate 40KHz sinus sound waves whose phase can be controlled with the TC78H621FNG wave generator. 
By combining such type of waves, you can make interferences to increase or decrease the intensity of a wave.
If the waves have the same phase, the intensity of the wave doubles, and if the waves have oposite phases, they cancel out. 
This examples can be seen in the following picture:
<img src="https://phys.libretexts.org/@api/deki/files/43023/8.4-CD.png?revision=1&size=bestfit&width=801&height=405"/>
By combining multiple emitors, you can make a narrower sound wave like an sound LASER.
<img src="https://lh3.googleusercontent.com/proxy/OXCBphyn6LKgIOYrxJP1FDfGYbe-H5XtUl6BqG6psCCJqaPnHMZ7RECLaWCUshUFGlpMAjtqAGHEM8Q-jDJfoIuhxYw8-Ty7UtB5QqnByxMUq-mXuDWsn2eNOHlrLJLYhUSYzvxlsrTztwYtXsSbGdYZ"/>
Also, by changing the phase of the waves, you can make one or more directional waves in different points without any moving parts. 
<img src="https://github.com/Tonikiller10000/UltrasonicPhasedArray/blob/main/UltrasonicPhasedArray_Pictures/uph.png"/>
This is the way that ecographyes and 5G work. Also, if you want to find more about this subjects like doppler effect, analog phased array and waves in general, you can read more at the following links:

- [bitluni Phased arrays video + implementation](https://www.youtube.com/watch?v=z4uxC7ISd-c&t=649s)
- [bitluni Phased arrays video 2](https://www.youtube.com/watch?v=Evao3XUUAOY)
- [wikiwand](https://www.wikiwand.com/en/Phased_array)
- [Wikipedia](https://en.wikipedia.org/wiki/Phased_array)
- [MathLab Phased Arrays playlist](https://www.youtube.com/playlist?list=PLn8PRpmsu08q9U0y7_63Dfz5cawEnicxi)


## Links:
- schematic: https://github.com/Tonikiller10000/UltrasonicPhasedArray/blob/main/UltrasonicPhasedArray_Pictures/sch.png
- TC78H621FNG(Wave Generator): https://pdf1.alldatasheet.com/datasheet-pdf/view/1465439/TOSHIBA/TC78H621FNG.html
- TCT40-10TR1(Ultrasonic transmitter): https://www.mantech.co.za/datasheets/products/tct40-10tr1.pdf





