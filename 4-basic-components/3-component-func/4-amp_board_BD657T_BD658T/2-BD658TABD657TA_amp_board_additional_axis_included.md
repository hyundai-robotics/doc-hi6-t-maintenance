# 4.3.4.2. BD658TA/BD657TA (AMP Board, additional axis included)

The AMP Board performs a power amplification function that allows the current to flow to individual phases of the motor according to the current command from the servo board. BD658TA and BD657TA enable simultaneous driving of 8 motors and are configured as follows.

<br><br>

Table 4-17 Configuration of BD658TA / BD657TA (AMP Board)

<table>
<thead>
  <tr>
    <th colspan="2">Components</th>
    <th>Functions</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="6">BD658TA/657TA<br>(AMP Board)</td>
    <td>Gate drive circuit</td>
    <td>Generates the IPM gate signal</td>
  </tr>
  <tr>
    <td>Gate power module</td>
    <td>Generates the gate power</td>
  </tr>
  <tr>
    <td>Current detection part</td>
    <td>Detects the current that flows through the motor</td>
  </tr>
  <tr></tr>
  <tr></tr>
  <tr></tr>
  <tr>
    <td rowspan="4">Other Parts</td>
    <td>Heat sink</td>
    <td>Releases the heat generated from power elements to the outside</td>
  </tr>
  <tr>
  <td>IPM</td>
  <td>A switching device</td>
  </tr>
</tbody>
</table>

<br><br>

■  **Configuration of the Type Number of AMP Board**

![](../../../_assets/4.3.4.2_앰프보드형번구성.PNG)
<br><br>

Table 4-18 Specification of the AMP Board

<table>
<thead>
  <tr>
    <th>Configuration</th>
    <th colspan="2">Classification</th>
    <th colspan="2">Application</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="2">Board No. For each axis
</td>
    <td>8</td>
    <td>BD658TA</td>
    <td>1~3 and 7 axes</td>
    <td rowspan="2">8 axis use </td>
  </tr>
  <tr>
    <td>7</td>
    <td>BD657TA</td>
    <td>4~6 and 8 axes</td>
  </tr>
  <tr>
    <td>Year</td>
    <td colspan="2">00 ~ 99</td>
    <td colspan="2">Production year: 2000-2099</td>
  </tr>
  <tr>
    <td>Month</td>
    <td colspan="2">01 ~ 12</td>
    <td colspan="2">Production month: January-December</td>
  </tr>
  <tr>
    <td>Serial No.</td>
    <td colspan="2">0001 ~ 999</td>
    <td colspan="2">Number of units produced monthly: 1~9999</td>
  </tr>
</tbody>
</table>

{% hint style="info" %}
The location where the amp board is fastened on the backplane board may be different, so you must check the type when replacing it.
{% endhint %}

![](../../../_assets/4.3.4.2_앰프보드_BD658TA_부품배치도.PNG)

Figure 4.20 BD658TA/657TA part layout
<br><br>


Table 4-19 BD658TA/657TA connector description

<table>
<tbody>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p><strong>Usage</strong></p></td>
<td><p><strong>Connection of<br>external devices</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>CNM4~7</strong></p></td>
<td><p>BD658TA : Motor drive output for Axis 1 to Axis 4, and Axis 7</p>
<p>BD657TA : Motor drive output for Axis 4 to Axis 6, and Axis 8</p></td>
<td><p>CMEC1</p></td>
</tr>

</tbody>
</table>

