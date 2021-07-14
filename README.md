# air_calculator

Writing letters with a pen on paper is very different from drawing letters in the air.

Drawing "-" minus operator and "+" operator in the air are extremely difficult so that these operators in the current system are replaced by "W" and "P" respectively.

When drawing letters with fingers in the air, letters that are difficult 
to recognize or write in the air need to be replaced with letters 
that can be accurately recognized by artificial intelligence.
For example, replace the number "1" with "L" in the air.

# How to install necessary libraries

$ pip install pytesseract

For Windows users, you should also install the latest tesseract

https://github.com/UB-Mannheim/tesseract/wiki

And add tesseract.exe of Tesseract-OCR directory PATH in .profile or .bashrc.

$ pip install mediapipe

Finally install aircalc

$ pip install aircalc

# fingermath.py is renamed as aircalc.py

# How to run aircalc

aircalc is a program for drawing a math expression 
in the air for possible calculation.

aircalc is based on two open source libraries including mediapipe and tesseract.

There are six states of five fingers recognized by mediapipe library: 
0-finger, 1-finger, 2-finger, 3-finger, 4-finger, and 5-finger respectively.
<pre>
A pen of index finger tip is used for drawing an expression 
by fingers. 

0-finger can move the pen without drawing. 
1-finger can draw lines in the air. 
2-finger can move the pen without drawing. 
3-finger can delete the last touches of drawn letters for correction.
4-finger can call tesseract for transforming the hand-writing 
images to the digital text for possible calculation. 
For several seconds, 4-finger can terminate the program 
for showing the answer of the hand-drawn expression.
5-finger can move the pen without drawing. 
</pre>

Continuous 4-finger state can terminate and exit this program.

0-finger or 5-finger is equivalent to 2-finger.

The saved picture is tranformed into digital text using the state-of-the-art 
optical character recognition.

Writing letters with a pen on paper is very different from drawing letters in the air.

Of the 0 to 9 digits, 1 is the least recognizable number.

Drawing "L" in the air represents "1".

"S" or "5" in the air represents "5".

"P" in the air represents "+" plus operator.

"W" or "-" represents "-" minus operator.

"V" in the air represents "/" division operator.

"M" in the air represents "*" multiplication operator.

"&" in the air represents "\**" exponential operator.

Drawing two letters "a" and "A" in the air represents the sqrt() function.
Therefore, the string "a13A" or "aL3A" represents sqrt(13).

$ aircalc

https://youtu.be/med_jrFTMPA
<pre>  sqrt(6)*2=?    </pre>
<img src='https://github.com/ytakefuji/air_calculator/raw/main/a6AM2.png' width=320 height=240>

<pre>         1-3=?                                 10+2=?  </pre>
[![Lw3.gif](https://github.com/ytakefuji/air_calculator/raw/main/Lw3.gif)](https://github.com/ytakefuji/air_calculator) [![10plus2.gif](https://github.com/ytakefuji/air_calculator/raw/main/10plus2.gif)](https://github.com/ytakefuji/air_calculator)

<pre>        4-5-3=?            </pre>
[![4-5-3.gif](https://github.com/ytakefuji/air_calculator/raw/main/4-5-3.gif) <img src='https://github.com/ytakefuji/air_calculator/raw/main/4-5-3.png' width=160 height=120> <img src='https://github.com/ytakefuji/air_calculator/raw/main/resize_4-5-3.png' width=120 height=90>

<pre>        2-3/5=?   </pre>
[![2-3div5.gif](https://github.com/ytakefuji/air_calculator/raw/main/2-3div5.gif)
<img src='https://github.com/ytakefuji/air_calculator/raw/main/2-3div5.png' width=160 height=120> <img src='https://github.com/ytakefuji/air_calculator/raw/main/resize_2-3div5.png' width=120 height=90>


<pre>        34*5=?     </pre>
[![34M5.gif](https://github.com/ytakefuji/air_calculator/raw/main/34M5.gif)
<img src='https://github.com/ytakefuji/air_calculator/raw/main/34M5.png' width=160 height=120> <img src='https://github.com/ytakefuji/air_calculator/raw/main/resize_34M5.png' width=120 height=90>

<pre> 2**8=?</pre>
[![2^8.gif](https://github.com/ytakefuji/air_calculator/raw/main/2^8.gif)


<pre>      2&9V3 --> 2**9/3        </pre>
[![2^9div3.gif](https://github.com/ytakefuji/air_calculator/raw/main/2^9div3.gif)
<img src='https://github.com/ytakefuji/air_calculator/raw/main/2^9div3.png' width=160 height=120> <img src='https://github.com/ytakefuji/air_calculator/raw/main/resize_2^9div3.png' width=120 height=90>

<pre>       aLLAV3=? -> sqrt(11)/3 </pre>  
[![aLLAV3.gif](https://github.com/ytakefuji/air_calculator/raw/main/aLLAV3.gif)
<img src='https://github.com/ytakefuji/air_calculator/raw/main/aLLAV3.png' width=160 height=120> <img src='https://github.com/ytakefuji/air_calculator/raw/main/resize_aLLAV3.png' width=120 height=90>
