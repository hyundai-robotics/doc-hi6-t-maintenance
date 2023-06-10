# 4.3.4.1. BD658T/BD657T (앰프 보드)

The Amp Board performs a power amplification function that allows the current to flow to the individual phases of the motor according to the current command from the servo board. BD658T and BD657T enable simultaneous driving of 6 motors and are configured as follows.

The single-phase current supplied from the power supply module is rectified through a diode module and then converted into direct current and stored in a smoothing capacitor. 

<br><br>

Table 4-14 Configuration of BD658T / BD657T (Amp Board)

<table>
<thead>
  <tr>
    <th colspan="2">Components</th>
    <th>Functions</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="6">BD658T/657T<br>(AMP Board)</td>
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
    <td rowspan="4">Other parts</td>
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

![](../../../_assets/4.3.4.1_앰프보드형번구성.PNG)
<br><br>

Table 4-15 Specification of Amp Board

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
    <td rowspan="2">Board No.
For each axis
</td>
    <td>8</td>
    <td>BD658T</td>
    <td>1~3 axes</td>
    <td rowspan="2">6 axis use</td>
  </tr>
  <tr>
    <td>7</td>
    <td>BD657T</td>
    <td>4~6 axes</td>
  </tr>
  <tr>
    <td>Year</td>
    <td colspan="2">00 ~ 99</td>
    <td colspan="2">Production year: 2000 ~ 2099</td>
  </tr>
  <tr>
    <td>Month</td>
    <td colspan="2">01 ~ 12</td>
    <td colspan="2">Production month: January~December</td>
  </tr>
  <tr>
    <td>Serial No.</td>
    <td colspan="2">0001 ~ 999</td>
    <td colspan="2">Number of units produced monthly: 1~999</td>
  </tr>
</tbody>
</table>

{% hint style="info" %}
The location where the amp board is fastened on the backplane board may be different, so you must check the type when replacing it.
{% endhint %}
<br><br>

![](../../../_assets/4.3.4.1_앰프보드_BD658T_부품배치도.PNG)

Figure 4.19 BD658T/657T part layout
<br><br>

Table 4-16 BD658T/657T connector description

<table>
<tbody>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p><strong>Usage</strong></p></td>
<td><p><strong>Connection of external devices</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>CNM4~6</strong></p></td>
<td><p>BD658T : Motor drive output for Axis 1 to Axis 3</p>
<p>BD657T : Motor drive output for Axis 4 to Axis 6</p></td>
<td><p>CMEC1</p></td>
</tr>

</tbody>
</table>

