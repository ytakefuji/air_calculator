# air_calculator

Writing letters with a pen on paper is very different from writing letters in the air.

Drawing "-" minus operator and "+" operator in the air are extremely difficult so that these operators are replaced by "W" and "P" respectively.

"1" one  is replace with "L" in the air.



# How to run fingermath.py

fingermath.py is a program for drawing an expression, for example, 4-5.
fingermath.py is based on mediapipe.
There are six states of five fingers recognized by mediapipe library: 
0-finger, 1-finger, 2-finger, 3-finger, 4-finger, and 5-finger respectively.
Drawing an expression by fingers with a pen of index finger tip. 
1-finger can draw lines in the air. 
2-finger can move the pen without drawing. 
3-finger can delete elements of the drawn picture for correction.
4-finger can transform hand-written characters to the digital text 
for calculating the expression. 
Continuous 4-finger state can terminate and exit this program.
0-finger or 5-finger is equivalent to 2-finger.
The saved picture is tranformed into digital text using the state-of-the-art 
optical character recognition.
Drawing a line by a pen on a paper is very different from drawing in the air.
From 0 to 9 digit number, 1 is the most difficult to be recognized.

"L" represents "1".

"S" or "5" represents "5".

"P" represents "+" operator.

"W" or "-" represents "-" operator.

"V" represents "/" division operator.

"M" represents "*" multiplication operator.

"&" represents "\**" exponential operator.

"a" and "A" represent sqrt() function. a13A represents sqrt(13).

$ python fingermath.py

https://youtu.be/med_jrFTMPA
<img src='a6AM2.png' width=320 height=240>

<pre>         1-3=?                                 10+2=?  </pre>
<img src='Lw3.gif' width=320 height=240> <img src='10plus2.gif' width=320 height=240>

<pre>        4-5-3=?                                2-3/5=?   </pre>
<img src='4-5-3.gif' width=320 height=240> <img src='2-3divide_by5.gif' width=320 height=240>

<pre>        34*5=?                         2**8=?</pre>
<img src='34M5.gif' width=320 height=240> <img src='2^8.gif' width=320 height=240>  

<pre> 128v3=? -> 128/3=?                    a11AV3=? -> sqrt(11)/3 </pre>            
<img src='128div3.gif' width=320 height=240> <img src='sqrt(11)div3.gif' width=320 >

