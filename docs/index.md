<p align="center">
  <a href="https://github.com/sparkfun/SparkFun_Temperature_Sensor-STTS22H/issues" alt="Issues">
    <img src="https://img.shields.io/github/issues/sparkfun/SparkFun_Temperature_Sensor-STTS22H.svg" /></a>
  <a href="https://github.com/sparkfun/SparkFun_Temperature_Sensor-STTS22H/actions" alt="Actions">
    <img src="https://github.com/sparkfun/SparkFun_Temperature_Sensor-STTS22H/actions/workflows/mkdocs.yml/badge.svg" /></a>
  <a href="https://github.com/sparkfun/SparkFun_Temperature_Sensor-STTS22H/blob/main/LICENSE.md" alt="License">
    <img src="https://img.shields.io/badge/license-CC%20BY--SA%204.0-blue.svg"/></a>
  <a href="https://twitter.com/intent/follow?screen_name=sparkfun">
    <img src="https://img.shields.io/twitter/follow/sparkfun.svg?style=social&logo=twitter" alt="follow on Twitter"></a>
</p>




The [SparkFun Temperature Sensor - STTS22H (Qwiic)](https://www.sparkfun.com/products/21262) and the [SparkFun Micro Temperature Sensor - STTS22H (Qwiic)](https://www.sparkfun.com/products/21273) are Qwiic enabled breakout boards based on the ultralow-power, high-accuracy, digital temperature sensor STTS22H from ST Microelectronics. Thanks to its factory calibration the STTS22H offers high-end accuracy performance over the entire operating temperature range, reaching as low as ±0.5 °C without requiring any further calibration at the application level. 


<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg .tg-v0mg{border-color:#ffffff;text-align:center;vertical-align:middle}
</style>
<table class="tg">
  <tr>
    <th class="tg-v0mg"><a href="https://cdn.sparkfun.com/assets/parts/2/1/0/3/8/STTS22-_01.jpg"><img src="https://cdn.sparkfun.com/assets/parts/2/1/0/3/8/STTS22-_01.jpg" alt="SparkFun Temperature Sensor - STTS22H (Qwiic)"></a></th>
    <th class="tg-v0mg"><a href="https://cdn.sparkfun.com/assets/parts/2/1/0/5/1/STTS22Micro-_01.jpg"><img src="https://cdn.sparkfun.com/assets/parts/2/1/0/5/1/STTS22Micro-_01.jpg" alt="SparkFun Micro Temperature Sensor - STTS22H (Qwiic)"></a></th>
  </tr>
  <tr>
    <td class="tg-v0mg"><i>SparkFun Temperature Sensor - STTS22H (Qwiic)</i></td>
    <td class="tg-v0mg"><i>SparkFun Micro Temperature Sensor - STTS22H (Qwiic)</i></td>
  </tr>
</table>


<center><iframe width="560" height="315" src="https://www.youtube.com/embed/ffbvpoyrDyg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></center>

### Required Materials

To follow along with this tutorial, you will need the following materials. You may not need everything though depending on what you have. Add it to your cart, read through the guide, and adjust the cart as necessary.

<div>
<table style="border-style:none">
    <tr>
        <td width="140">
            <a href="https://www.sparkfun.com/products/21262">
              <div style="text-align: center"><img src="https://cdn.sparkfun.com/assets/parts/2/1/0/3/8/STTS22-_01.jpg" alt="SparkFun Temperature Sensor - STTS22H (Qwiic)" height="140"></div>
              <h3 style="text-align: left">SparkFun Temperature Sensor - STTS22H (Qwiic)</h3>
            </a>
            <span>SEN-21262</span>
        </td>
        <td width="140">
            <a href="https://www.sparkfun.com/products/21273">
              <div style="text-align: center"><img src="https://cdn.sparkfun.com/assets/parts/2/1/0/5/1/STTS22Micro-_01.jpg" alt="SparkFun Micro Temperature Sensor - STTS22H (Qwiic)" height="140"></div>
              <h3 style="text-align: left">SparkFun Micro Temperature Sensor - STTS22H (Qwiic)</h3>
            </a>
            <span>SEN-21273</span>
        </td>
        <td width="140">
            <a href="https://www.sparkfun.com/products/15123">
              <div style="text-align: center"><img src="https://cdn.sparkfun.com//assets/parts/1/3/4/9/2/15123-SparkFun_RedBoard_Qwiic-01a.jpg" alt="SparkFun RedBoard Qwiic" height="140"></div>
              <h3 style="text-align: left">SparkFun RedBoard Qwiic</h3>
            </a>
            <span>DEV-15123</span>
        </td>
    </tr>
    <tr>
      <td width="140">
          <a href="https://www.sparkfun.com/products/10215">
            <div style="text-align: center"><img src="https://cdn.sparkfun.com//assets/parts/4/5/5/8/10215-01.jpg" alt="USB micro-B Cable - 6 Foot" height="140"></div>
            <h3 style="text-align: left">USB micro-B Cable - 6 Foot</h3>
          </a>
          <span>CAB-10215</span>
      </td>
        <td width="140">
            <a href="https://www.sparkfun.com/products/14426">
              <div style="text-align: center"><img src="https://cdn.sparkfun.com//assets/parts/1/2/4/5/2/14426-Qwiic_Cable_-_50mm-01.jpg" alt="Qwiic Cable - 50mm" height="140"></div>
              <h3 style="text-align: left">Qwiic Cable - 50mm</h3>
            </a>
            <span>PRT-14426</span>
        </td>
    </tr>
</table>
</div>



### Suggested Reading

If you aren't familiar with the Qwiic system, we recommend reading [here for an overview](https://www.sparkfun.com/qwiic).

<div style="text-align: center">
<table style="border-style:none">
  <tr>
   <td>
   <div style="text-align: center"><a href="https://www.sparkfun.com/qwiic"><img src="assets/imgs/Qwiic-registered-updated.png" alt="Qwiic Connect System" title="Click to learn more about the Qwiic Connect System!"></a></td></div>
  </tr>
  <tr>
    <td><div style="text-align: center"><i><a href="https://www.sparkfun.com/qwiic">Qwiic Connect System</a></i></div></td>
  </tr>
</table>
</div>

If you aren’t familiar with the following concepts, we also recommend checking out a few of these tutorials before continuing.

<table style="border-style:none">
    <tr>
        <td style="vertical-align: text-top;" width="264px">
            <a href="https://learn.sparkfun.com/tutorials/i2c">
            <div style="text-align: center"><img src="https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/8/2/I2C-Block-Diagram.jpg" style="width:264px; height:148px; object-fit:contain;"></div>
            <h3 style="text-align: left">I2C
            </h3></a>
        </td>
        <td style="vertical-align: text-top;" width="264px">
            <a href="https://learn.sparkfun.com/tutorials/serial-basic-hookup-guide">
            <div style="text-align: center"><img src="https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/5/9/7/14050-01.jpg" style="width:264px; height:148px; object-fit:contain;"></div>
            <h3 style="text-align: left">Serial Basic Hookup Guide
            </h3></a>
        </td>
        <td style="vertical-align: text-top;" width="264px">
            <a href="https://learn.sparkfun.com/tutorials/redboard-plus-hookup-guide">
            <div style="text-align: center"><img src="https://cdn.sparkfun.com/c/264-148/assets/learn_tutorials/1/7/5/8/18158-SparkFun_RedBoard_Plus-01.jpg" style="width:264px; height:148px; object-fit:contain;"></div>
            <h3 style="text-align: left">RedBoard Hookup Guide
            </h3></a>
        </td>
    <tr>
</table>
