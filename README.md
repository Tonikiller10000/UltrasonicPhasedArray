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
Also, by changing the phase of the waves, you can make one or more directional waves in different points without any moving parts. 

<table>
  <tr>
    <td><img src="https://lh3.googleusercontent.com/proxy/OXCBphyn6LKgIOYrxJP1FDfGYbe-H5XtUl6BqG6psCCJqaPnHMZ7RECLaWCUshUFGlpMAjtqAGHEM8Q-jDJfoIuhxYw8-Ty7UtB5QqnByxMUq-mXuDWsn2eNOHlrLJLYhUSYzvxlsrTztwYtXsSbGdYZ"/> <td>
    <td><img src="https://github.com/Tonikiller10000/UltrasonicPhasedArray/blob/main/UltrasonicPhasedArray_Pictures/uph.png"/></td>
  </tr>
</table>

This is the way that ecographyes and 5G work. 
Also, if you want to find more about this subjects like doppler effect, analog phased array and waves in general, you can read more at the following links:
- [Bitluni Phased arrays video + implementation](https://www.youtube.com/watch?v=z4uxC7ISd-c&t=649s)
- [Bitluni Phased arrays video 2](https://www.youtube.com/watch?v=Evao3XUUAOY)
- [wikiwand](https://www.wikiwand.com/en/Phased_array)
- [Wikipedia/ Phased Arrays](https://en.wikipedia.org/wiki/Phased_array)
- [Wikipedia/ Beam forming](https://en.wikipedia.org/wiki/Beamforming)
- [MathLab Phased Arrays playlist](https://www.youtube.com/playlist?list=PLn8PRpmsu08q9U0y7_63Dfz5cawEnicxi)
- [diy beamformer](https://www.youtube.com/watch?v=2QXKuEYR4Bw)
- [Beam forming](https://www.youtube.com/watch?v=HKpQP8H4JRc&t=1125s)
- [Phased arrays lecture](https://www.youtube.com/watch?v=LYyGkKP4Obg)
- [Hackaday phased arrays talk](https://www.youtube.com/watch?v=ytBmoL2wZLw&t=1472s)
- [Phased arryas paper](https://www.mdpi.com/2076-3417/8/9/1544)
- [Phased array signal processing](https://hackaday.io/page/13711-phased-array-signal-processing)


## Datasheets:
- schematic: https://github.com/Tonikiller10000/UltrasonicPhasedArray/blob/main/UltrasonicPhasedArray_Pictures/sch.png
- TC78H621FNG(Wave Generator): https://pdf1.alldatasheet.com/datasheet-pdf/view/1465439/TOSHIBA/TC78H621FNG.html
- TCT40-10TR1(Ultrasonic transmitter): https://www.mantech.co.za/datasheets/products/tct40-10tr1.pdf

