# Pressure sensor sealing test report

## Goal
For accurate tracking of the sea turtles the information about the depth is very important. A pressure sensor will be used in the PitStop Tags to measure the depth. Sealing tests of the pressure sensor were similar to the sealing tests of the PitStop Tag enclosures. A special enclosure was made from polyoxymethylene (POM) plastics with rubber O-ring string and an O-ring gasket used for sealing. Enclosure with the pressure sensor was put under high pressure up to 10 bar, equal to the depth of 100m.

<img
src="https://github.com/IRNAS/PitStop1/blob/master/testing/pressure%20sensor/pics/IMG_20180315_110824.jpg"  width="500px" height="375px">

## Equipment
* Pressure container

<img
src="https://github.com/IRNAS/PitStop1/blob/master/testing/pressure%20sensor/pics/IMG_0981.JPG"  width="500px" height="375px">

* Circlip and pliers

<img
src="https://github.com/IRNAS/PitStop1/blob/master/testing/pressure%20sensor/pics/IMG_0983.JPG"  width="500px" height="375px">

* Air hose under pressure

<img
src="https://github.com/IRNAS/PitStop1/blob/master/testing/pressure%20sensor/pics/IMG_0984.JPG"  width="500px" height="375px">

## Tested enclosure and pressure sensor
* Special enclosure for the pressure sensor

<span><img
src="https://github.com/IRNAS/PitStop1/blob/master/testing/pressure%20sensor/pics/IMG_20180320_104601.jpg"  width="400px" height="300px">
<img
src="https://github.com/IRNAS/PitStop1/blob/master/testing/pressure%20sensor/pics/IMG_20180320_104651.jpg"  width="400px" height="300px">
<img
src="https://github.com/IRNAS/PitStop1/blob/master/testing/pressure%20sensor/pics/IMG_20180418_085850.jpg"  width="400px" height="300px"></span>

* TE Connectivity MS5837-30BA Pressure Sensor (http://www.te.com/usa-en/product-CAT-BLPS0017.html) with O-ring gasket

<img
src="https://github.com/IRNAS/PitStop1/blob/master/testing/pressure%20sensor/pics/IMG_20180320_104728.jpg"  width="400px" height="300px">

* A custom PCB, designed to attach and connect the pressure sensor

<span><img
src="https://github.com/IRNAS/PitStop1/blob/master/testing/pressure%20sensor/pics/IMG_20180418_090453.jpg"  width="400px" height="300px">
<img
src="https://github.com/IRNAS/PitStop1/blob/master/testing/pressure%20sensor/pics/IMG_20180418_090424.jpg"  width="400px" height="300px"></span>

## Testing
To test how the pressure sensor can handle the pressure in water we used a pressure container.

The container was filled half way up with water. The tested enclosure was assembled and put on the bottom of the container fully covered with water. The container was sealed with the cover and a circlip and the air hose was attached. The enclosure with the pressure sensor was tested under 10 bars of pressure for 60 min. Afterwards it was taken out and the backplate was unscrewed from the rest of the case very carefully so no water from the outside of the case would flow inside accidently.

In the first two tests we used an aluminium plate to attach the pressure sensor. We have then designed a custom PCB which will be used to attach and connect the pressure sensor in the actual PitStop Tags. In the third test we then used the PCB to attach the pressure sensor.

## Results
During the assembly the pressure sensor was damaged when inserted into the special enclosure due to the incorrect O-ring size. Because of the damage the water was able to penetrate the pressure sensor and fully flooded the case. The sealing test was unsuccessful and therefore had to be repeated with the correct O-ring size and a new pressure sensor.

<span><img
src="https://github.com/IRNAS/PitStop1/blob/master/testing/pressure%20sensor/pics/IMG_20180315_110831.jpg"  width="400px" height="300px">
<img
src="https://github.com/IRNAS/PitStop1/blob/master/testing/pressure%20sensor/pics/IMG_20180315_111131.jpg"  width="400px" height="300px"></span>

Another test with a new pressure sensor and the correct O-ring was conducted. This time the case stayed completely dry.

<span><img
src="https://github.com/IRNAS/PitStop1/blob/master/testing/pressure%20sensor/pics/IMG_20180323_124931.jpg"  width="400px" height="300px">
<img
src="https://github.com/IRNAS/PitStop1/blob/master/testing/pressure%20sensor/pics/IMG_20180323_130200.jpg"  width="400px" height="300px"></span>

In the third test we used a custom PCB which is used to attach and connect the pressure sensor. The case stayed completely dry.

<span><img
src="https://github.com/IRNAS/PitStop1/blob/master/testing/pressure%20sensor/pics/IMG_20180418_085949.jpg"  width="400px" height="300px">
<img
src="https://github.com/IRNAS/PitStop1/blob/master/testing/pressure%20sensor/pics/IMG_20180417_154520.jpg"  width="400px" height="300px"></span>

## Conclusion
The first test of the pressure sensor was unsuccessful because the sensor was damaged during the assembly. Because of the damage the water was able to penetrate the pressure sensor. The sealing test was then repeated with the correct O-ring size and a new pressure sensor. In the second test the case stayed completely dry. In the third test we used a custom PCB which will be used to attach and connect the pressure sensor in the actual PitStop Tags. We confirmed the sealing with the PCB as well.

The prescribed sealing method for the pressure sensor was confirmed, but more tests at 25 bar of pressure should be conducted to confirm the sealing under high pressure equal to the depth of 250m.
