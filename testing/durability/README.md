# Durability test report

## Goal

The turtles clean their shells by rubbing them at rocks. Because the turtle is very heavy it would create a lot of force if it hits the spot where the case is mounted. We wanted to know if the tested cases can survive a hit with such high force. Our goal was to see which material absorbs most force at the given shape and to try and simulate a scenario of use of the case.

## Equipment

We have built a pendulum like construction. There is a 73cm long lever with its axis of rotation on a screw that is mounted on a two part holder mounted on the table. The screw is held by two bearings to help make the rotation smoother. There is a nut on the screw between the lever and the holder to keep some distance. At the other end of the lever there's a backplate mounted on the lever with two screws, with two long screws heading out in the opposite direction where the weights can be put on. On the opposite side of the lever there's a small sphere, which hits the target case. On the ground there is a holder that holds the tested case in place. It's mounted on a heavy wooden block. There is a board that shows angles (10°, 20°, 30°, 50°, 60°, 67°) mounted on the table.

<img
src="https://github.com/IRNAS/PitStop1/blob/master/testing/durability/pics/drawing.JPG"  width="500px" height="375px">
<img
src="https://github.com/IRNAS/PitStop1/blob/master/testing/durability/pics/pendulum_front.png"  width="500px" height="805.7px">
<img
src="https://github.com/IRNAS/PitStop1/blob/master/testing/durability/pics/pendulum.JPG"  width="500px" height="375px">

## Tested materials
*	Acryl (transparent) - weight: 88g
* Polyamide (black) - weight: 102g
* Oleamide (green) - weight: 83g
* PA6 (white) - weight: 83g

## Testing

To see witch material absorbs the most force we let the pendolum crash into the case with different weights from different angles.

We pulled the pendulum up to a certain angle and let it crash into the tested case. After the first crash we stopped it to prevent it from crashing again. We tried to keep the number of hits as low as possible so the case wouldn't break because of the number of hits rather than the force of the hit. We started on low angles and worked our way up. We started our testing without any weights on to get an approximation of what the cases can handle. The Acrylic case broke very fast without any weights on. After that we started putting more and more weights on the backplate of the pendulum and the cases held up more than we expected. The polyamide case finally broke with already very heavy weights on and the oleamide and PA6 cases wouldn't even break with all the weights that we could fit on the backplate.

<img
src="https://github.com/IRNAS/PitStop1/blob/master/testing/durability/pics/weights.png"  width="500px" height="375px">

#### Weights:
* weight 1 (W1): 1140g
* weight 2 (W2): 825g
* weight 3 (W3): 2075g
* weight 4 (W4): 4985g
* weight 5 (W5): 3610g
* weight 6 (W6): 10085g

#### Equipment weight:
* lever: 1715g
* backplate: 710g

## Results
#### Acryl
* no add. weights


|Angle(°)|<span style="font-weight:normal;color:gray">20</span>  |<span style="font-weight:normal;color:gray">30</span>  |<span style="font-weight:normal;color:gray">40</span>    |
|:-:|:-:|:-:|:-:|
|**Status**   | ok  |ok  |broken|


#### Polyamide
* no add. weights

|Angle(°)|<span style="font-weight:normal;color:gray">67</span>  |
|:-:|:-:|
|**Status**   | ok  |

* with W1 (1140g)

|Angle(°)|<span style="font-weight:normal;color:gray">30</span>  |<span style="font-weight:normal;color:gray">40</span>  |<span style="font-weight:normal;color:gray">50</span> |<span style="font-weight:normal;color:gray">67</span>    |
|:-:|:-:|:-:|:-:|:-:|
|**Status**   | ok  |ok  |ok |ok

* -with W1 + W2 (1965g)

|Angle(°)|<span style="font-weight:normal;color:gray">50</span>  |<span style="font-weight:normal;color:gray">67</span>
|:-:|:-:|:-:|
|**Status**   | ok  |ok

* with W2+W3 (2900g)

|Angle(°)|<span style="font-weight:normal;color:gray">50</span>  |<span style="font-weight:normal;color:gray">67</span>
|:-:|:-:|:-:|
|**Status**   | ok  |ok

* with W1+W2+W3 (4040g)

|Angle(°)|<span style="font-weight:normal;color:gray">67</span>  |
|:-:|:-:|
|**Status**   | ok  |

* with W1+W2+W3+W4 (9025g)

|Angle(°)|<span style="font-weight:normal;color:gray">50</span>  |<span style="font-weight:normal;color:gray">67</span>  |<span style="font-weight:normal;color:gray">67</span>  |
|:-:|:-:|:-:|:-:|
|**Status**   | ok  | ok  | ok

<img
src="https://github.com/IRNAS/PitStop1/blob/master/testing/durability/pics/polyamide.JPG"  width="500px" height="375px">

#### Oleamide

* with W1+W2+W3+W5 (7650g)

|Angle(°)|<span style="font-weight:normal;color:gray">67</span>  |
|:-:|:-:|
|**Status**   | ok  |

* with W1+W2+W3+W4 (9025g)

|Angle(°)|<span style="font-weight:normal;color:gray">67</span>  |
|:-:|:-:|
|**Status**   | ok  |

* withW1+W2+W3+W4+W5 (12635g)

|Angle(°)|<span style="font-weight:normal;color:gray">67</span>  |
|:-:|:-:|
|**Status**   | ok  |

* withW1+W2+W3+W4+W6 (19110g)

|Angle(°)|<span style="font-weight:normal;color:gray">67</span>  |
|:-:|:-:|
|**Status**   | ok  |

<img
src="https://github.com/IRNAS/PitStop1/blob/master/testing/durability/pics/oleamide.jpg"  width="500px" height="375px">

#### PA6

* W1+W2+W3+W4+W6 (19110g)

|Angle(°)|<span style="font-weight:normal;color:gray">67</span>  |
|:-:|:-:|
|**Status**   | ok  |

<img
src="https://github.com/IRNAS/PitStop1/blob/master/testing/durability/pics/PA6.jpg"  width="500px" height="375px">

## Calculation of momentum

* m<span style ="font-size:x-small">L</span> (lever weight) = 1715g
* m<span style ="font-size:x-small">B</span> (backplate weight) = 710g
* l (lever lenght) = 0.7m
* x (distance from center of mass of the backplate and weights to rotation axis) = 0.65m
* h (height from the lowest point of the pendulum)
* v (speed just before collision)

#### Acryl<br>
a) With no weights at 30° (try before break)<br>
h = 0.09m<br>
v = 1.76 m/s

**L =** m<span style ="font-size:x-small">L</span> &times; (l/2) &times; v + m<span style ="font-size:x-small">B</span> &times; x &times; v = **1.87 kgm²/s**

b)With no waights at 40° (try of break)<br>
h = 0.16m<br>
v = 1.77 m/s

**L =** m<span style ="font-size:x-small">L</span> &times; (l/2) &times; v + m<span style ="font-size:x-small">B</span> &times; x &times; v = **1.88 kgm²/s**

#### Polyamide
a) Weights: W1,W2,W3,W4 (9025g) at 67° (try of break)<br>
h = 0.42m<br>
v = 2.9 m/s


**L =** m<span style ="font-size:x-small">L</span> &times; (l/2) &times; v + (m<span style ="font-size:x-small">B</span> + W1 + W2 + W3 + W4) &times; x &times; v = **20.09 kgm²/s**

#### Oleamide & PA6
a) Weights: W1,W2,W3,W4,W6 (19110g) at 60° (try of break)<br>
h = 0.35m<br>
v = 2.6 m/s


**L =** m<span style ="font-size:x-small">L</span> &times; (l/2) &times; v + (m<span style ="font-size:x-small">B</span> + W1 + W2 + W3 + W4 + W6) &times; x &times; v = **33.35 kgm²/s**

## Conclusion
At the beginning we increased the angles and weights very slowly. After the acrylic case broke so quickly we were even more careful because we thought the other cases would break shortly after the acrylic one, but we were surprised. The polyamide case exceeded our expectations and just wouldn't break. We started increasing the weights more drastically and finally it gave in at an already very high load. After that we tried the same load on the remaining two cases and they both survived the crash. After that we wanted to see how far we can go and put on all the weights we could fit on the backplate to hit the PA6 case and the oleamide case but still none of them would break at a load of almost 20kg.

Looking at the results it's clear that acryl isn't fit for our purpose because it already broke without any weights put on the pendulum. Polyamide was already surprisingly strong and exceeded our expectations. We couldn't break the oleamide and PA6 cases.
