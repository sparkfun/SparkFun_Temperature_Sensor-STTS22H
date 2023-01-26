
###STTS22


The STTS22H is an ultralow-power, high-accuracy, digital temperature sensor offering high performance over the entire operating temperature range. Thanks to its factory calibration the STTS22H offers high-end accuracy performance over the entire operating temperature range, reaching as low as ±0.5 °C without requiring any further calibration at the application level. The sensor operating mode is user-configurable and allows selecting between different ODRs (down to 1 Hz) or the one-shot mode for battery saving. In one-shot mode, the sensor current consumption falls to 1.75 µA. For more information, refer to the [datasheet](https://cdn.sparkfun.com/assets/3/0/b/7/6/STTS22h-Datasheet.pdf). 


<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg .tg-v0mg{border-color:#ffffff;text-align:center;vertical-align:middle}
</style>
<table class="tg">
  <tr>
    <th class="tg-v0mg"><a href="..\assets\imgs\21262-Temperature_Sensor-STTS22H_Sensor.jpg"><img src="..\assets\imgs\21262-Temperature_Sensor-STTS22H_Sensor.jpg" alt="STTS22 Highlight"></a></th>
    <th class="tg-v0mg"><a href="..\assets\imgs\21273-Micro_Temperature_Sensor-STTS22H-Sensor.png"><img src="..\assets\imgs\21273-Micro_Temperature_Sensor-STTS22H-Sensor.png" alt="STTS22 Highlight on Micro"></a></th>
  </tr>
  <tr>
    <td class="tg-v0mg"><i>STTS22</i></td>
    <td class="tg-v0mg"><i>STTS22 on Micro</i></td>
  </tr>
</table>




###Qwiic Connectors

There are two Qwiic connectors on either side of the SparkFun Temperature Sensor - STTS22H to provide power and I<sup>2</sup>C connectivity simultaneously. The Micro version has a single Qwiic connector that again provides power and I<sup>2</sup>C connectivity. The I<sup>2</sup>C address of both boards is <b>0x3C</b> by default, but the 1x1 board has 3 other addresses the board can be configured to use, while the Micro has 1 other address available.

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg .tg-v0mg{border-color:#ffffff;text-align:center;vertical-align:middle}
</style>
<table class="tg">
  <tr>
    <th class="tg-v0mg"><a href="..\assets\imgs\21262-Temperature_Sensor-STTS22H_QwiicConnectors.jpg"><img src="..\assets\imgs\21262-Temperature_Sensor-STTS22H_QwiicConnectors.jpg" alt="Qwiic Connectors"></a></th>
    <th class="tg-v0mg"><a href="..\assets\imgs\21273-Micro_Temperature_Sensor-STTS22H-QwiicConnector.png"><img src="..\assets\imgs\21273-Micro_Temperature_Sensor-STTS22H-QwiicConnector.png" alt="Qwiic Connector on Micro"></a></th>
  </tr>
  <tr>
    <td class="tg-v0mg"><i>Qwiic Connectors</i></td>
    <td class="tg-v0mg"><i>Qwiic Connector on Micro</i></td>
  </tr>
</table>

###Power

Ideally, power will be supplied via the Qwiic connector(s). Alternatively, power can be supplied through the header along the bottom side of the board labeled `3V3` and `GND`. The input voltage range should be between <b>1.5</b>-<b>3.6V</b>. The Micro version has a single Ground Pin available. 


<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg .tg-v0mg{border-color:#ffffff;text-align:center;vertical-align:middle}
</style>
<table class="tg">
  <tr>
    <th class="tg-v0mg"><a href="..\assets\imgs\21262-Temperature_Sensor-STTS22H_PowerPins.jpg"><img src="..\assets\imgs\21262-Temperature_Sensor-STTS22H_PowerPins.jpg" alt="3.3V & GND Pins"></a></th>
    <th class="tg-v0mg"><a href="..\assets\imgs\21273-Micro_Temperature_Sensor-STTS22H-GroundPin.png"><img src="..\assets\imgs\21273-Micro_Temperature_Sensor-STTS22H-GroundPin.png" alt="GND Pin on Micro"></a></th>
  </tr>
  <tr>
    <td class="tg-v0mg"><i>3.3V & GND Pins</i></td>
    <td class="tg-v0mg"><i>GND Pin on Micro</i></td>
  </tr>
</table>

<div class="alert alert-danger" role="alert">&#x26A1; <b>Note: </b> There is no onboard voltage regulation on either of these boards. If you choose to provide power via the plated through holes, ensure that your voltage does not exceed <b>5.5V</b>. </div>

###Interrupt Pin

An interrupt pin is available to signal the application whenever the selectable high or low threshold has been exceeded.

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg .tg-v0mg{border-color:#ffffff;text-align:center;vertical-align:middle}
</style>
<table class="tg">
  <tr>
    <th class="tg-v0mg"><a href="..\assets\imgs\21262-Temperature_Sensor-STTS22H_InterruptPin.jpg"><img src="..\assets\imgs\21262-Temperature_Sensor-STTS22H_InterruptPin.jpg" alt="Interrupt Pin"></a></th>
    <th class="tg-v0mg"><a href="..\assets\imgs\21273-Micro_Temperature_Sensor-STTS22H-InterruptPin.png"><img src="..\assets\imgs\21273-Micro_Temperature_Sensor-STTS22H-InterruptPin.png" alt="Interrupt Pin on Micro"></a></th>
  </tr>
  <tr>
    <td class="tg-v0mg"><i>Interrupt Pin</i></td>
    <td class="tg-v0mg"><i>Interrupt Pin on Micro</i></td>
  </tr>
</table>



###Power LED

Hopefully this is self-explanatory, but this LED lights up when power is supplied to the board. 

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg .tg-v0mg{border-color:#ffffff;text-align:center;vertical-align:middle}
</style>
<table class="tg">
  <tr>
    <th class="tg-v0mg"><a href="..\assets\imgs\21262-Temperature_Sensor-STTS22H_PowerLED.jpg"><img src="..\assets\imgs\21262-Temperature_Sensor-STTS22H_PowerLED.jpg" alt="Power LED"></a></th>
    <th class="tg-v0mg"><a href="..\assets\imgs\21273-Micro_Temperature_Sensor-STTS22H-PowerLED.png"><img src="..\assets\imgs\21273-Micro_Temperature_Sensor-STTS22H-PowerLED.png" alt="Power LED on Micro"></a></th>
  </tr>
  <tr>
    <td class="tg-v0mg"><i>Power LED</i></td>
    <td class="tg-v0mg"><i>Power LED on Micro</i></td>
  </tr>
</table>

###Exposed Pad

There's an extra pad on the bottom side of each board that allows for the most accurate possible readings. 

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg .tg-v0mg{border-color:#ffffff;text-align:center;vertical-align:middle}
</style>
<table class="tg">
  <tr>
    <th class="tg-v0mg"><a href="..\assets\imgs\21262-Temperature_Sensor-STTS22H_BareCopperSensorPad.jpg"><img src="..\assets\imgs\21262-Temperature_Sensor-STTS22H_BareCopperSensorPad.jpg" alt="Exposed Pad"></a></th>
    <th class="tg-v0mg"><a href="..\assets\imgs\21273-Micro_Temperature_Sensor-STTS22H-BareCopperSensorPad.png"><img src="..\assets\imgs\21273-Micro_Temperature_Sensor-STTS22H-BareCopperSensorPad.png" alt="Exposed Pad on Micro"></a></th>
  </tr>
  <tr>
    <td class="tg-v0mg"><i>Exposed Pad</i></td>
    <td class="tg-v0mg"><i>Exposed Pad on Micro</i></td>
  </tr>
</table>




###Jumpers

####LED Jumper

If power consumption is an issue, cut this jumper to disable the LED on the front of the board. 

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg .tg-v0mg{border-color:#ffffff;text-align:center;vertical-align:middle}
</style>
<table class="tg">
  <tr>
    <th class="tg-v0mg"><a href="..\assets\imgs\21262-Temperature_Sensor-STTS22H_LED-Jumper.jpg"><img src="..\assets\imgs\21262-Temperature_Sensor-STTS22H_LED-Jumper.jpg" alt="Power LED Jumper"></a></th>
    <th class="tg-v0mg"><a href="..\assets\imgs\21273-Micro_Temperature_Sensor-STTS22H-LED-Jumper.png"><img src="..\assets\imgs\21273-Micro_Temperature_Sensor-STTS22H-LED-Jumper.png" alt="Power LED Jumperon Micro"></a></th>
  </tr>
  <tr>
    <td class="tg-v0mg"><i>Power LED Jumper</i></td>
    <td class="tg-v0mg"><i>Power LED Jumper on Micro</i></td>
  </tr>
</table>



####Address Jumpers

The 1x1 board has two address jumpers available. The default I<sup>2</sup>C address is <b>0x3C</b>. By cutting various trace combinations, there are three other I<sup>2</sup>C addresses available. 

<table class="tg" align="center">
  <tr>
    <th class="text-center"  colspan="2"><b>ADDR</b></th>
  </tr>
  <tr>
    <td>R8(15K)</td>
    <td>0x3C (Default)</td>
  </tr>
  <tr>
    <td>R7(56K)</td>
    <td>0x3E</td>
  </tr>
  <tr>
    <td>VDD</td>
    <td>0x38</td>
  </tr>
  <tr>
    <td>GND</td>
    <td>0x3F</td>
  </tr>
  <tr>
    <td>OPEN</td>
    <td>Undefined</td>
  </tr>
</table>

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg .tg-v0mg{border-color:#ffffff;text-align:center;vertical-align:middle}
</style>
<table class="tg">
  <tr>
    <th class="tg-v0mg"><a href="..\assets\imgs\21262-Temperature_Sensor-STTS22H_ADDR-Jumper.jpg"><img src="..\assets\imgs\21262-Temperature_Sensor-STTS22H_ADDR-Jumper.jpg" alt="Address Jumper"></a></th>
    <th class="tg-v0mg"><a href="..\assets\imgs\21262-Temperature_Sensor-STTS22H_ADDR1-Jumper.jpg"><img src="..\assets\imgs\21262-Temperature_Sensor-STTS22H_ADDR1-Jumper.jpg" alt="Address Jumper 1"></a></th>
  </tr>
  <tr>
    <td class="tg-v0mg"><i>Address Jumper</i></td>
    <td class="tg-v0mg"><i>Address Jumper 1</i></td>
  </tr>
</table>


The Micro version of this board has a single address jumper that affords the ability to change the I<sup>2</sup>C address from <b>0x3C (Default)</b> to 0x38. 

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg .tg-v0mg{border-color:#ffffff;text-align:center;vertical-align:middle}
</style>
<table class="tg">
  <tr>
    <th class="tg-v0mg"><a href="..\assets\imgs\21273-Micro_Temperature_Sensor-STTS22H-Address-Jumper.png"><img src="..\assets\imgs\21273-Micro_Temperature_Sensor-STTS22H-Address-Jumper.png" alt="Address Jumper on Micro"></a></th>
  </tr>
  <tr>
    <td class="tg-v0mg"><i>Address Jumper on Micro</i></td>
  </tr>
</table>



####I<sup>2</sup>C Jumper

These boards are both equipped with pull-up resistors. If you are daisy-chaining multiple Qwiic devices, you will want to cut this jumper; if multiple sensors are connected to the bus with the pull-up resistors enabled, the parallel equivalent resistance will create too strong of a pull-up for the bus to operate correctly. As a general rule of thumb, disable all but one pair of pull-up resistors if multiple devices are connected to the bus. To disable the pull up resistors, use an X-acto knife to cut the joint between the two jumper pads highlighted below. 

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg .tg-v0mg{border-color:#ffffff;text-align:center;vertical-align:middle}
</style>
<table class="tg">
  <tr>
    <th class="tg-v0mg"><a href="..\assets\imgs\21262-Temperature_Sensor-STTS22H_I2C-Jumper.jpg"><img src="..\assets\imgs\21262-Temperature_Sensor-STTS22H_I2C-Jumper.jpg" alt="I<sup>2</sup>C Jumper"></a></th>
    <th class="tg-v0mg"><a href="..\assets\imgs\21273-Micro_Temperature_Sensor-STTS22H-I2C-Jumper.png"><img src="..\assets\imgs\21273-Micro_Temperature_Sensor-STTS22H-I2C-Jumper.png" alt="I<sup>2</sup>C Jumper on Micro"></a></th>
  </tr>
  <tr>
    <td class="tg-v0mg"><i>I<sup>2</sup>C Jumper</i></td>
    <td class="tg-v0mg"><i>I<sup>2</sup>C Jumper on Micro</i></td>
  </tr>
</table>

###Board Outline

The standard Temperature Sensor STTS22H Breakout measures 1" x 1". 

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg .tg-v0mg{border-color:#ffffff;text-align:center;vertical-align:middle}
</style>
<table class="tg">
  <tr>
    <th class="tg-v0mg"><a href="..\assets\imgs\21262-SparkFun_Temperature_Sensor-STTS22H-BoardOutline.png"><img src="..\assets\imgs\21262-SparkFun_Temperature_Sensor-STTS22H-BoardOutline.png" alt="Address Jumper on Micro"></a></th>
  </tr>
  <tr>
    <td class="tg-v0mg"><i>Board Outline of 1" x 1"</i></td>
  </tr>
</table>


The Micro Temperature Sensor STTS22H Breakout measures 0.75" x 0.3". 

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg .tg-v0mg{border-color:#ffffff;text-align:center;vertical-align:middle}
</style>
<table class="tg">
  <tr>
    <th class="tg-v0mg"><a href="..\assets\imgs\21273-SparkFun_Micro_Temperature_Sensor-STTS22H-BoardOutline.png"><img src="..\assets\imgs\21273-SparkFun_Micro_Temperature_Sensor-STTS22H-BoardOutline.png"></a></th>
  </tr>
  <tr>
    <td class="tg-v0mg"><i>Board Outline of Micro</i></td>
  </tr>
</table>